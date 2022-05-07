<p align="center">
  <a href="https://sport.silvain.eu/">
    <img alt="Statutis" src="https://github.com/Statutis/.github/raw/main/mark/favicon.png" height="100"/>
  </a>
</p>

<h1 align="center">Statutis</br>Les statuts de vos services</h1>
<p align="center">
  <a href="https://statutis.silvain.eu/">Site WEB</a>
  |
  <a href="https://api.statutis.silvain.eu/swagger/">API Rest</a>
</p>
<p align="center">
    <a href="https://github.com/statutis/frontend/actions">
        <img src="https://github.com/Statutis/frontend/actions/workflows/deploy.yml/badge.svg">
    </a>
    <a href="https://github.com/statutis/api/actions">
        <img src="https://github.com/Statutis/api/actions/workflows/deploy.yml/badge.svg">
    </a>
</p>

<p align="center">
  L'appplication Statutis a pour objectif de vérifier la disponibilité de vos services (exemple : Site web), ainsi que ce dernier fonctionne correctement. Pour cela, ce logiciel se base su différent mode de vérification comme des requêtes HTTP ou DNS, et vous permez d'en controller le résultat (dans une certaine mesure). Ce projet à été développé par <a href="https://github.com/Miithrandiir">Simon HEBAN</a> & <a href="https://github.com/silvainlud">Ludwig SILVAIN</a> dans le cadre du module d'initiation au WebService lors de la première année de master WedSci de l'Université du Littoral Cote d'opale.
</p>

## Projets

| Dêpots | Descripition |
| --- | --- |
| Frontent | l'interface web pour l'application |
| API | API Rest et tâches cron de notre logiciel |
| docker-compose | instruction de deploiement en production |

**[Consulter le WIKI](https://github.com/Statutis/.github/wiki)**

<br/>
<hr/>

# Réponses aux consignes


##  Créerez des services web REST en utilisant les verbes utilisés en cours (GET, POST, PUT, DELETE) [3 x Controller minimum].


| Controlleur | GET | POST | PUT | DELETE |
| --- | --- | --- | --- | --- | 
| AuthenticateController |  | 3 | | |
| GroupController | 3 | 1 | 2 | 1 |
| HistoryController | 2 | | | |
| ServiceController | 8 | 4 | 4 | 1 |
| ServiceTypeController | 2 | | | |
| TeamController | 3 | 1 | 2 | 1 |
| UserController | 5 | 0 | 3 | 0 |

## Consommerez des services web REST (Ceux que vous avez crées, via un front web , un bot discord, une app mobile...)

Réalisation d'un site Frontend avec le framework React : [lien vers le dépôt](https://github.com/Statutis/frontend)

##  Consommerez des services web externes (Twitter, Facebook, Google, Twitch, toute autre api externe...)

Utilisation du webservice de [statuspage.io](https://www.atlassian.com/software/statuspage) de Atlassian pour vérifier les status de certains service comme [Github](https://www.githubstatus.com/api) ou encore [DigitalOceans](https://status.digitalocean.com/api).

## Langage

- Fontend : Javascript avec le framework React
- API : C# avec ASP .Net Core 6

