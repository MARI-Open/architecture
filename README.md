POC @service.nom..toUpperCase() Solution - Version 2019-10-27
==============================================
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/ms-solution.svg)

![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-pac.svg)
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-ws.svg)
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-cycle.svg)
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-design.svg)
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-build.svg)
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-run.svg)

#@service.nom.toUpperCase()
@service.nom.toUpperCase() assume la gestion des logiciels de cache et leur configuration.
 

Contenu
-----------

Micro service & dépendances:

* app.js - ce fichier est le point d'entrée applicatif du micro service
* index.js - ce fichier est l'enveloppe du microservice en fonction de son contexte
* metier/ - ce repertoire contient les entités primaires et secondaires ansi que les modules de gestion des données (Référentiel, Qualité, Cycle...)
* fonctionnel/ - ce repertoire contient les régles spécifiques d'orchestration, de transformation et de routage
* technique/ - ce repertoire contient les enveloppes pour la gestion des ressources techniques
* tests/ - ce repertoire contient les tests unitaires, d'intégration et de non-régression du micro service


Commandes
------------------
```
$ git clone service.url
$ cd service.nom.toLowerCase()
$ npm install
$ pip install --upgrade awscli
$ npm test
$ aws cloudformation package --template template.yml --s3-bucket $S3_BUCKET --output-template template-export.yml
$ sed -i.bak 's/\$PARTITION\$/'${PARTITION}'/g;s/\$AWS_REGION\$/'${AWS_REGION}'/g;s/\$ACCOUNT_ID\$/'${ACCOUNT_ID}'/g;s/\$PROJECT_ID\$/'${PROJECT_ID}'/g' template-configuration.json

```

Pour en savoir plus...
-------------------------

Que devons-nous faire pour optimiser notre démarche agile?
https://#

Que devons-nous faire avant de mettre un micro service en production?
------------------

Bonnes partiques: 
https://#


