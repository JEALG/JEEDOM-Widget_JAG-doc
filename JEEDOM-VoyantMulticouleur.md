---
layout: default
title: JEEDOM-VoyantMulticouleur
description: explication Bouton en forme de voyant Multi couleur
---
[back](./)
# Widget "VoyantMulticouleur : Bouton en forme de voyant Multi couleur" 

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info binaire</b>
<p><img src="Img/RESULTAT%20-%20JEEDOM-VoyantMulticouleur.png" alt="Resultat" /></p>
<blockquote>
Le widget inclus d'office 14 types d'icônes.
</blockquote>

<p><img src="Img/VISUEL%20-%20JEEDOM-VoyantMulticouleur.png" alt="Visuels" /></p>

<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Choix de la couleur</h4>
Pour choisir la couleur, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>CouleurON</b> : Permet de choisir la couleur du voyant pour la valeur ON<i>(valeur par défaut : GN)</i></li>
            <li><b>CouleurOFF</b> : Permet de choisir la couleur du voyant pour la valeur OFF<i>(valeur par défaut : RD)</i></li>
            <li><b>Les valeurs possibles </b> : BK, BU, GN, OR, RD, WH, YE</li>
        </ul>
</blockquote>

<h4 id="Logo">Choix de la forme</h4>
Pour choisir la forme, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>FormeON</b> : Permet de choisir la forme du voyant pour la valeur ON<i>(valeur par défaut : ROND)</i></li>
            <li><b>FormeOFF</b> : Permet de choisir la forme du voyant pour la valeur OFF<i>(valeur par défaut : ROND)</i></li>
            <li><b>Les valeurs possibles </b> : ROND, CARRE</li>
        </ul>
</blockquote>

<h4 id="Logo">Choix de l'extension'</h4>
Pour choisir le type d'extension de l'image
<blockquote>
        <ul>
            <li><b>logoON_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i>(par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
            <li><b>logoOFF_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i>(par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
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

<h4 id="Aide">Autres paramétrages possible et Aide</h4>
<blockquote>
        <ul>
            <li><a href="JEEDOM-AIDE-CONFIG-INFO.html">Aide ajout Des paramétres pour un widget Info</a></li>
            <li><a href="JEEDOM-AIDE-PARA.html">Ajouter les paramétres sur un widget</a></li>
        </ul>
</blockquote>

<hr />
<h4 id="Add img">Ajout d'image</h1>
<hr />
<blockquote>
        Il est possible d'inclure d'autres icônes dans le widget.<br/>
        Le nommage des images est normalisé et doit respecter le format suivant :
        <ul>
            <li><b>Image pour la valeur pour le niveau</b> : FORME_COULEUR</li>
            <li><i>Remplacer <b>FORME</b> par la valeur ROND ou CARRE ou Autres</i></li>
            <li><i>Remplacer <b>COULEUR</b> par la valeur BK, BU, GN, OR, RD, WH, YE</i></li>
        </ul>
        <ul>
            <li><a href="./JEEDOM-AIDE-ADD_IMG.html">Ajouter des images dans un widget</a></li>
        </ul>   
</blockquote>

<hr />
<dl>
    <dt>Mise à jour JAG - 20190714<br/>
    <a href="https://github.com/JEALG/JEEDOM-VoyantMulticouleur/commits/master">Changelog WIDGET</a><br/>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a></dt>
</dl>
<hr />
[back](./)