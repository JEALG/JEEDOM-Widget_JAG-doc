---
layout: default
title: JEEDOM-Lampe
description: explication widget Lampe-Binaire
---

# Widget "Lampe-Binaire" 

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info binaire</b>
<blockquote>
Le widget inclus d'office 12 types de lampes (6xON et 6xOFF). Il est possible d'ajouter ses propres icônes.
</blockquote>

<p><img src="Img/JEEDOM-Lampe-Binaire-Visuel.png" alt="Visuels" /></p>


<h4 id="Logo">Paramétrage de l'image</h4>
Pour choisir le type de visuel à afficher, il faut ajouter un paramètre optionnel<br/>
<blockquote>
    <ul>
        <li><b>logo</b> : Permet de choisir l'image pour la valeur ON ou OFF <i>(valeur par défaut : Lampe)</i></li>
        <li><b>logo_type</b> : Permet de choisir l'extension pour l'image pour la valeur ON ou OFF <i>(valeur par défaut : png)</i></li>
</ul>
</blockquote>


<h4 id="TaIlle">Taille de l'image</h4>
Pour choisir la dimension de l'image il faut ajouter un paramètre optionnel<br/>
<blockquote>
    <ul>
        <li><b>sizeh</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 80)</i></li>
        <li><b>sizew</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 80)</i></li>
</ul>
</blockquote>

<h3 id="Aide Paramétrage">Aide pour le paramétrage du widget</h3>
<hr />
<h5 id="header-5">Paramétrage de l'équipement</h5>
<dl>
<dd>Cliquez sur la roue crantée à gauche de la commande ON et/ou OFF<br/>
    <img src="Img/JEEDOM-Lampe-Binaire-Acces.png" alt="Access"/>
</dd>
</dl>
<h5 id="header-5">Choix du widget et ajout des paramètres</h5>
<dl>
<dd>Choisir le widget et ajouter les parametres voulus<br/>
    <img src="Img/JEEDOM-Lampe-Binaire-Configuration.png" alt="Configuration"/>
</dd>
</dl>
<dd>Pour afficher les valeurs de temps<br/>
    <blockquote>
        <br/>Il est possible d'afficher les informations de temps depuis le dernier allumage/extinction. il suffit d'ajouter un paramètre optionnel "<br/>
    Merci à @Salvialf pour le code
    </blockquote>
    <img src="Img/JEEDOM-Lampe-Binaire-Configuration.png" alt="Configuration"/>
</dd>
</dl>

<h3 id="Add img">Ajout d'image</h3>
<hr />
<blockquote>
Il est possible d'inclure d'autres icônes dans le widget.<br/>
Le nommage des images est normalisé et doit respecter le format suivant :
    <ul>
        <li><b>Image pour la valeur ON</b> : type-ON <i>(valeur par défaut : 80)</i></li>
        <li><b>Image pour la valeur OFF</b> : type-OFF</li>
        <li> <i>(remplacer <b>type</b> par le nom de votre image)</i></li>
    </ul> 
</blockquote>
<hr />
<dl>
<dt>Mise à jour JAG - 20190608</dt>
</dl>
<hr />
[back](./)

# JEEDOM-Lampe-Binaire


  
Vous avez la possibilité d'inclure vos propres icônes dans le widget. Le nommage des images est normalisé et doit respecter le format suivant:
* **<b>Image pour la valeur ON </b>** : type-ON<br/>
* **<b>Image pour la valeur OFF </b>** : type-OFF<br/>
(remplacer "type" par le nom de votre image)<br/>
Pour ajouter vos icônes, sur la page du Widget, cliquer sur le bouton "Fichiers" tout en haut puis "choisir un fichier" et ajouter vos images une par une.<br/>

<br/>Pour afficher les informations de temps depuis le dernier allumage/extinction, il suffit d'ajouter un paramètre optionnel "<i><b>logoTime</b></i>" avec la valeur suivante au choix:<br/>
    Merci à @Salvialf pour le code
* '**duree**' : affiche la durée depuis le dernier allumage/extinction.  
* '**heure**' : affiche l'heure de dernier allumage extinction.  
* '**date**'  : affiche la date et l'heure de dernier allumage/extinction.  

<b>Pour le paramétrage dans l'équipement</b><br/>
Cliquez sur la roue crantée à gauche de la commande ETAT, ne pas oublier que l'etat doit être de type 'binaire'<br/>
<img src="Lampe-Acces-binaire.png" alt="Access"/><br/>
<b>Choisir le widget et ajouter les parametres voulus</b><br/>
<img src="Lampe-Configuration-binaire.png" alt="Configuration"/><br/>


Pour choisir le type de visuel à afficher en cas de problème, il est possible de paramètrer l'image
* '**<b>logoER</b>**': Permet de choisir l'image pour la valeur ETAT en cas de problème<i>(valeur par défaut : oups)<br/></i>
* '**<b>logoER_type</b>**': Permet de choisir l'extension pour l'image pour la valeur ETAT en cas de problème<i>(valeur par défaut : png)<br/></i>
<img src="Image-Error.png" alt="Image Error"/>
