# my-typical-rest-api
All in all, when I want it just with a git clone


* modèle no.1 : https://www.codementor.io/olatundegaruba/nodejs-restful-apis-in-10-minutes-q0sgsfhbd, mais avec un docker-compose, les oéprations standards de dev, un conteneur mongo, un conteneur qui publie la documentation OpenAPI de l'API, et mongoose comme framework ORM
* évolution no 1 : pareil avec mongoose, mais refondu en typescript, et toujours avec express.js
* évolution no. 2 : avec mongoose, typescript côté serveur, et RxJS pour appeler mongoose



# Outils gestion de documentation REST API

* https://github.com/lord/slate ==>> _beautiful static doc for your API_ (très beau celui-là, et à nourrir avec du gatsby / netlify. Netlify sert à gatsby toutes les descriptions de tous les endpoints, pour toutes les versions de l'API. (celui là à faire de POC) (oui, netlify est nativement doué pour prendre git comme source de données, donc netlify va me servir les releases une à une à Gatsby, pour générer tout très très beau, donc j'aurai un point de customisation excellent avec le gatsby generator que je versionne, pour versionner.. je le version dans le pipeline de documentation.
* et j'ai un candidat excellent et amélioré de slate :  https://github.com/Mermade/shins  (exemple : https://mermade.github.io/shins ) je veux voir si je peux intégrer ça à la chaîne gatsby netlify 
* https://github.com/swagger-api/swagger-ui
* https://github.com/sourcey/spectacle
* http://dapperdox.io/docs/proxy-configure (sympa ils proposent un petit servie de reverses-proxy, en gros tu tapes sur ton dapper, et derrière, ça fait le rouiting vers le serveur de l'API voulue, avec la doc, ça deviendrait presque une API Gateway

Une étude à faire sur la gestion du cycle de vie de la documentation, intégrée aux pipelines
Une étude à faire sur la gestion du cycle de vie d'une API, intégrée aux pipelines
