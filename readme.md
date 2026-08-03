Apres avoir recuperer le projet
cmd -> mvn clean install
cmd pour lancer l'importation du csv ->  java -jar target/projet-0.0.1-SNAPSHOT.jar src/main/resources/adresses-79-2026-06-22.csv
Si lancé avec intellij -> mettre en argument le chemin du csv exemple : src/main/resources/adresses-79-2026-06-22.csv
!!! Attention le projet se comporte différemment selon la base utilisée dans veuillez à modifier le paramétrage dans l'application.properties dans le dossier resources !!!
Si vous utilisez Postgres, veuillez à bien créer la base avant

Bon run!!!
