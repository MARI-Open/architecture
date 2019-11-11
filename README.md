POC @service.nom.toUpperCase() Solution - Version 2019-10-27
==============================================
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/ms-solution.svg)

![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-pac.svg)
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-ws.svg)
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-cycle.svg)
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-design.svg)
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-build.svg)
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-run.svg)

#@service.nom.toUpperCase()
-----------
@service.nom.toUpperCase() @service.texte.
 

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
POC @service.nom..toUpperCase() Solution - Version 2019-10-27
2
==============================================
3
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/ms-solution.svg)
4
​
5
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-pac.svg)
6
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-ws.svg)
7
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-cycle.svg)
8
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-design.svg)
9
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-build.svg)
10
![](https://e9wtofe7li.execute-api.eu-west-1.amazonaws.com/Prod/images/etat-run.svg)
11
​
12
#@service.nom.toUpperCase()
13
@service.nom.toUpperCase() assume la gestion des logiciels de cache et leur configuration.
14
 
15
​
16
Contenu
17
-----------
18
​
19
Micro service & dépendances:
20
​
21
* app.js - ce fichier est le point d'entrée applicatif du micro service
22
* index.js - ce fichier est l'enveloppe du microservice en fonction de son contexte
23
* metier/ - ce repertoire contient les entités primaires et secondaires ansi que les modules de gestion des données (Référentiel, Qualité, Cycle...)
24
* fonctionnel/ - ce repertoire contient les régles spécifiques d'orchestration, de transformation et de routage
25
* technique/ - ce repertoire contient les enveloppes pour la gestion des ressources techniques
26
* tests/ - ce repertoire contient les tests unitaires, d'intégration et de non-régression du micro service
27
​
28
​
29
Commandes
30
------------------
31
```
32
$ git clone service.url
33
$ cd service.nom.toLowerCase()
34
$ npm install
35
$ pip install --upgrade awscli
36
$ npm test
37
$ aws cloudformation package --template template.yml --s3-bucket $S3_BUCKET --output-template template-export.yml
38
$ sed -i.bak 's/\$PARTITION\$/'${PARTITION}'/g;s/\$AWS_REGION\$/'${AWS_REGION}'/g;s/\$ACCOUNT_ID\$/'${ACCOUNT_ID}'/g;s/\$PROJECT_ID\$/'${PROJECT_ID}'/g' template-configuration.json
39
​
40
```
41
​
42
Pour en savoir plus...
43
-------------------------
44
​
45
Que devons-nous faire pour optimiser notre démarche agile?
46
https://#
47

Pour en savoir plus...
-------------------------

Que devons-nous faire pour optimiser notre démarche agile?
https://#

Que devons-nous faire avant de mettre un micro service en production?
------------------

Bonnes partiques: 
https://#


