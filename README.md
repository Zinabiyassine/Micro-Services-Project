# Architecture MicroServices 
![imagemicro](https://user-images.githubusercontent.com/34307997/37597626-3faf530a-2b80-11e8-9a10-b834c537c279.png)

## Utilisation
* Dans le cas d'un changement dans les services un script **mvn.sh** est proposé pour la generation des nouveaux jars.
* le docker compose est executé grace à la commande **docker-compose up**.

## La liste des URL des services:

Nom Service | Url Service
------------ | -------------
EUREKA-SERVICE | http://localhost:8761/
DIPLOME-SERVICE | http://localhost:3333/
ENSEIGNANT-SERVICE | http://localhost:2222/
SERVICES-SERVICE | http://localhost:1111/
PROXY-SERVICE | http://localhost:9999/



## Affichage avec Swagger des mappings disponibles

* PROXY-SERVICE: http://localhost:9999/swagger-ui.html
