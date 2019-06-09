---
layout: default
title: JEEDOM-Icon_Mode
description: explication widget Icon_Mode
---
[back](./)
# Widget "Icon_Mode" 

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info binaire</b>
<p><img src="Img/RESULTAT - JEEDOM-Lampe-Binaire-Resultat.png" alt="Resultat" /></p>
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
            <li><b>logo_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo</i>(par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>

<h4 id="Taille">Taille des images ou des icônes</h4>
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>sizeh</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 80)</i></li>
            <li><b>sizew</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 80)</i></li>
        </ul>
</blockquote>
 
<h4 id="Error">Autres paramétrages possible</h4>
<blockquote>
        <ul>
            <li><a href="JEEDOM-AIDE-CONFIG-INFO.html">Aide ajout Des paramétres pour un widget Info</a></li>
            <li><a href="JEEDOM-AIDE-Error.html">Paramétrage image de défaut</a></li>
            <li><a href="JEEDOM-AIDE-STATS.html">Afficher les statistiques</a></li>
            <li><a href="JEEDOM-AIDE-STATS TEMPS.html">Affichage des informations de durée sur les widgets info (binaire, numérique)</a></li>
        </ul>
</blockquote>

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
    <a href="https://github.com/JEALG/JEEDOM-Lampe-Binaire/commits/master">Changelog WIDGET</a><br/>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a></dt>
</dl>
<hr />
[back](./)