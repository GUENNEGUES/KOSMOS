# Editer cette documentation

## I/ Introduction
Cette documentation est mise en page par ReadTheDocs.org et [lisible à l'adresse ci attaché](https://kosmos30.readthedocs.io). En aucun cas, cette adresse permet d'éditer la documentation. 

Afin de pouvoir contribuer à cette documentation, vous pouvez contribuer directement au [repository GitHub](https://github.com/KonkArLab/KOSMOS). C'est sur GitHub que sont déposés les fichiers sources. On y retrouve l'arborescence suivante : 

 - **docs :** Est le dossier qui contient les documents qui pourront être affichés sur le read the doc. Dans ce dossier sont entreposés :

   - A la racine les fichiers marckdown qui sont les textes de la documentation. Pour chaque onglet sur read the doc nous ajouterons un fichier séparé avec un titre en Anglais sans espaces terminé par "_fr" pour la version française ou "_en" pour la version anglaise. L'extention sera toujours ".md".
   - Le dossier "Pictures" : contient plusieurs dossiers dont chacun porte un nom en rapport avec le fichier marckdown auquel il se rapporte. Ainsi pour un fichier de documentation "test1_fr.md" on prendra le soin d'entreposer les images dans un dossier "/docs/pictures/test1.md".

 - **Hardware :** c'est le dossier qui contient les fichiers d'impressions 3D, de découpe laser et ainsi de suite...  

Avant de faire une proposition de contribution, il est bienvenu d'éditer le repository depuis votre compte en effectuant un forke de la présente documentation. Une fois que vous aurez une version prête à être publiée il suffira de faire une pull request au main projet soit celui du konkarlab/KOSMOS.
C'est un administrateur KOSMOS qui étudiera votre proposition pour en intégrer tout ou partie sur le projet. 


## II/ Edition

### 1. Ecriture en Marckdown
Le Marckdown est un language de mise en forme de texte très simplifié. On peut éditer un fichier ".md" directement via gitHub ou en local de son ordinateur avec n'importe quel éditeur de texte. Cependant nous recommandons [Ghostwriter](https://wereturtle.github.io/ghostwriter/) qui présente l'avantage proposer une vue en direct du rendu.

[Pour ce qui est de la synthaxe, consulter ce guide](https://www.markdownguide.org/basic-syntax/)


### 2. Ajout et mise à jour d'une image

#### 2.1 Ajout
Les images que l'on souhaite faire apparaître dans la documentation ne doivent pas être collées dans le document. 

   - Créer un nouveau dossier du même nom que la documentation dans "/docs/pictures/" en créant un fichier vide que l'on suprimera par la suite.
   - Dans le dossier "pictures", cliquer sur "add file" et dans l'espace pour nommer le fichier entrer "nom_du_dossier/nom_fichier.md"
   - Ajouter les images désirées que l'on aura préalablement réduit en taille chacune en dessous de 200Ko et renommées de manière à être facilement identifiable.
   - On pourra par la suite supprimer le fichier md vide qui nous aura servi à créer le dossier.  
   - Dans le fichier de documentation correspondant à la ligne où l'on souhaite faire apparaître l'image, ajouter la ligne suivante : 
 ```![Legende_Image](pictures/nom_du_dossier/nom_image.JPG)``` 


#### 2.2 Mise à jour 
Pour mettre à jour une image, il suffit de supprimer du git l'image en question et d'uploader la nouvelle image en prenant soin de renommer cette nouvelle avec le nom exact de l'ancienne. 

