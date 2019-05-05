# JEEDOM-Lampe

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>action ON/OFF</b>

Le widget inclus d'office 8 types de lampes (4xON et 4xOFF). Il est possible d'ajouter ses propres icônes.

<img src="Lampe-Visuel.png" alt="visuels"/>

Pour choisir le type de visuel à afficher, il faut ajouter un paramètre optionnel<br/>
* '**<b>logo</b>**' : Permet de choisir l'image pour la valeur ON ou OFF <i>(valeur par défaut : Lampe)<br/></i>
* '**<b>logo_type</b>**' : Permet de choisir l'extension pour l'image pour la valeur ON ou OFF <i>(valeur par défaut : png)<br/></i>

Pour choisir la dimension de l'image il faut ajouter un paramètre optionnel<br/>
* '**<b>sizeh</b>**' : Permet de choisir l'hauteur de l'image <i>(valeur par défaut : 80)<br/></i>
* '**<b>sizew</b>**' : Permet de choisir la largeur de l'image <i>(valeur par défaut : 80)<br/></i>
  
Vous avez la possibilité d'inclure vos propres icônes dans le widget. Le nommage des images est normalisé et doit respecter le format suivant:<br/>
* **<b>Image pour la valeur ON </b>** : type-ON<br/>
* **<b>Image pour la valeur OFF </b>** : type-OFF<br/>
(remplacer "type" par le nom de votre image)<br/>
Pour ajouter vos icônes, sur la page du Widget, cliquer sur le bouton "Fichiers" tout en haut puis "choisir un fichier" et ajouter vos images une par une.<br/>

<b>Pour le paramétrage dans l'équipement</b><br/>
Cliquez sur la roue crantée à gauche de la commande ON et/ou OFF<br/>
<img src="Lampe-Acces.png" alt="Access"/><br/>
<b>Choisir le widget et ajouter les parametres voulus</b><br/>
<img src="Lampe-Configuration.png" alt="Configuration"/><br/>
