Commande � lancer dans chaque microservice si il ne d�marre pas :

./mvnw package -Pprod verify jib:dockerBuild

Lancement classique : docker-compose up -d (-d = une ligne par microservice pour l'affichage dans le terminal)

Probleme de Port li� � docker : 
Restart docker est la m�thode la plus simple.