Commande à lancer dans chaque microservice si il ne démarre pas :

./mvnw package -Pprod verify jib:dockerBuild

Lancement classique : docker-compose up -d (-d = une ligne par microservice pour l'affichage dans le terminal)

Probleme de Port lié à docker : 
Restart docker est la méthode la plus simple.