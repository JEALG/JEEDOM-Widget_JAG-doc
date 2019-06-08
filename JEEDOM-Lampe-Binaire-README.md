---
layout: default
title: JEEDOM-Lampe-Binaire
description: explication widget Lampe-Binaire
---

# Widget "Lampe-Binaire" 

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info binaire</b>
<p><img src="Img/JEEDOM-Lampe-Binaire-Resultat.png" alt="Resultat" /></p>
<blockquote>
Le widget inclus d'office 12 types de lampes (6xON et 6xOFF). Il est possible d'ajouter ses propres icônes.
</blockquote>

<p><img src="Img/JEEDOM-Lampe-Visuel.png" alt="Visuels" /></p>

<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Choix de l'icône</h4>
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>logo</b> : Permet de choisir l'image pour la valeur ON ou OFF <i>(valeur par défaut : Lampe)</i></li>
            <li><b>logo_type</b> : Permet de choisir l'extension pour l'image pour la valeur ON ou OFF <i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>

<h4 id="Taille">Taille de l'image</h4>
Pour choisir la dimension de l'image il faut ajouter un paramètre optionnel<br/>
<blockquote>
        <ul>
            <li><b>sizeh</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 80)</i></li>
            <li><b>sizew</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 80)</i></li>
        </ul>
</blockquote>

<h4 id="TEMPS">Pour afficher les valeurs de temps</h4>
Il est possible d'afficher les informations de temps depuis le dernier allumage/extinction. il suffit d'ajouter un paramètre optionnel <I>Merci à @Salvialf pour le code</I>
<blockquote>
        <ul>
            <li><b>logoTime</b></li>
                <dd><b>logoTime = <i>duree</i></b> : affiche la durée depuis le dernier allumage/extinction.<br/>
                    <b>logoTime = <i>heure</i></b> : affiche l'heure de dernier allumage extinction.<br/>
                    <b>logoTime = <i>date</i></b> : affiche la date et l'heure de dernier allumage/extinction.
                </dd>
        </ul>
</blockquote>
 
<h4 id="Error">Choix de l'icône en cas d'erreur</h4>
En cas de défaut d'erreur, le widget affichage un icône d'erreur, il est possible de paramétrer cette image
<blockquote>
        <ul>
            <li><b>logoER</b> : Permet de choisir l'image pour la valeur ETAT en cas de problème <i>(valeur par défaut : oups)</i></li>
            <li><b>logoER_type</b> : Permet de choisir l'extension pour l'image pour la valeur ETAT en cas de problème <i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>
<p><img src="Img/Image-Error.png" alt="Error" /></p>


<h1 id="Aide Paramétrage">Aide pour le paramétrage du widget</h1>
<hr />
<h5 id="header-5">Paramétrage de l'équipement</h5>
<dl>
    <dd>Cliquez sur la roue crantée à gauche de la commande ON et/ou OFF</dd>
    <img src="Img/JEEDOM-Lampe-Binaire-Acces.png" alt="Access"/>
</dl>

<h5 id="header-5">Choix du widget et ajout des paramètres</h5>
<dl>
    <dd>Choisir le widget et ajouter les parametres voulus</dd>
    <img src="Img/JEEDOM-Lampe-Binaire-Configuration.png" alt="Configuration"/>
</dl>

<hr />
<h3 id="Add img">Ajout d'image</h3>
<hr />
<blockquote>
        Il est possible d'inclure d'autres icônes dans le widget.<br/>
        Le nommage des images est normalisé et doit respecter le format suivant :
        <ul>
            <li><b>Image pour la valeur ON</b> : type-ON</li>
            <li><b>Image pour la valeur OFF</b> : type-OFF</li>
            <li><i>Remplacer <b>type</b> par le nom de l'image</i></li>
        </ul> 
</blockquote>

<hr />
<dl>
    <dt>Mise à jour JAG - 20190608<br/>
    <a href="https://github.com/JEALG/JEEDOM-Lampe-Binaire/commits/master">Chancelog WIDGET</a>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Chancelog DOC</a></dt>
</dl>
<hr />
[back](./)