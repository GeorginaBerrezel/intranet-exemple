# INTRANET - Example

1 - Installer sass
    Une fois installé : 
        $ node -v
        $ npm -v
        $ npm -g install sass
        $ npm init (puis entrée jusqu'à "it's ok ? (yes))

    Dans {}package.json :
        >Debug
        "scripts": {
            "sass":"sass --watch .sass/main.scss:./css/style.css"
        }

2 - A chaque ouverture du projet, lancer la commande :
        npm run sass
    pour que la compilation des fichiers se fasse automatiquement grâce aux fichiers .scss
