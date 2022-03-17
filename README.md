

## Groupomania - Réseau social d'entreprise


### - Technologies utilisées :
NodeJs - VueJs - MySQL - Bootstrap - Sass

### Prérequis :


<ul>
  <li> Git </li>
  <li> Node.js </li>
  <li> MySql</li>
</ul>


## MySQL
Complétez dans le fichier groupomania/backend/.env , le mot de passe d'accès à votre base de donnée et votre nom d'utilisateur si (root par défaut)
```
DB_USER=root
DB_PASS=
```
Ouvrir MySql command Line client puis effectuer ces deux lignes de commandes :
```
CREATE DATABASE groupomania;
USE groupomania;
```
Importer le fichier groupomania.sql (qui ce trouve a la racine du projet) : 
```
source (chemin vers le fichier groupomania.sql);
```
Attention a indiquer le chemin avec des "/" et non des "\ ".

## BACK END
Ouvrir un terminal dans le dossier backend puis effectuer les lignes de commandes suivantes :
```
npm install
node server
```
## FRONT END
Ouvrir un autre terminal dans le dossier frontend puis effectuer les lignes de commandes suivantes :
```
npm install
npm run serve
```

Ouvrir le navigateur a l'adresse http://localhost:8080/

les codes d'accès admin :
```
admin@admin.com
Admin.31
```





