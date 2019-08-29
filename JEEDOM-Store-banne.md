---
layout: default
title: JEEDOM-Store-banne
description: explication Store-banne
---
[back](./)
# Widget "Store-banne" 

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info numérique</b>
<p><img src="Img/RESULTAT%20-%20JEEDOM-Store-banne.png" alt="Resultat" /></p>


<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Choix de l'icône</h4>
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>logo</b> : Permet de choisir l'image pour la valeur <i>(valeur par défaut : battery_)</i></li>
            <li><b>logo_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
        </ul>
</blockquote>

<h4 id="Taille">Taille de l'image</h4>
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>sizeh</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 65)</i></li>
            <li><b>sizew</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 30)</i></li>
        </ul>
</blockquote>

<h4 id="Masque">Masquer la valeur</h4>
Il est possible de masquer la valeur de l'ouverture :
<blockquote>
        <ul>
            <li><b>masque_valeur</b> : Permet de masquer la valeur <i>(valeur par défaut :NO)</i></li>
            <li>variable avec la valeur <b>NO</b> ne masque pas la valeur <i>(valeur par défaut)</i></li>
            <li>variable avec la valeur <b>YES</b> masque la valeur</li>
        </ul>
</blockquote>

<h4 id="Niveau">Inversion sens image</h4>
Si l'équipement a la valeur 0 pour l'ouverture, il est possible d'inverser le sens 
<blockquote>
        <ul>
            <li><b>levelINV = 0</b>Ouverture = 100% <i>(valeur par défaut : 0)</i></li>
            <li><b>levelINV = 1</b>Ouverture = 0%  <i></i></li>
        </ul>
</blockquote>


<h4 id="Aide">Autres paramétrages possible et Aide</h4>
<blockquote>
        <ul>
            <li><a href="JEEDOM-AIDE-CONFIG-INFO.html">Aide ajout Des paramétres pour un widget Info</a></li>
            <li><a href="JEEDOM-AIDE-Error.html">Paramétrage image de défaut</a></li>
            <li><a href="JEEDOM-AIDE-STATS.html">Afficher les statistiques</a></li>
            <li><a href="JEEDOM-AIDE-STATS TEMPS.html">Affichage des informations de durée sur les widgets info (binaire, numérique)</a></li>
            <li><a href="JEEDOM-AIDE-PARA.html">Ajouter les paramétres sur un widget</a></li>
        </ul>
</blockquote>

<hr />
<h3 id="Add img">Ajout d'image</h3>
<hr />
<blockquote>
        Il est possible d'inclure d'autres icônes dans le widget.<br/>
        Le nommage des images n'est pas normalisé sur ce widget
        <ul>
            <li><a href="./JEEDOM-AIDE-ADD_IMG.html">Ajouter des images dans un widget</a></li>
        </ul>
</blockquote>

<hr />
<dl>
    <dt>Mise à jour JAG - 20190714<br/>
    <a href="https://github.com/JEALG/JEEDOM-Store-banne/commits/master">Changelog WIDGET</a><br/>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a></dt>
</dl>
<hr />
[back](./)