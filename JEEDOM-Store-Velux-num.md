---
layout: default
title: JEEDOM-Store-Velux-num
description: explication widget Store-VELUX (numérique)
---
[back](./)
# Widget "Store-VELUX (numérique)" 

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info numérique</b>
<p><img src="Img/RESULTAT%20-%20JEEDOM-Store-Velux-num.png" alt="Resultat" /></p>


<p><img src="Img/VISUEL%20-%20JEEDOM-Store-Velux-num.png" alt="Visuels" /></p>

<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Choix de l'icône</h4>
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>logo</b> : Permet de choisir l'image<i>(valeur par défaut : Store-)</i></li>
            <li><b>logo_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo</i>(par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>

<h4 id="Taille">Taille des images ou des icônes</h4>
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>sizeh</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 90)</i></li>
            <li><b>sizew</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 90)</i></li>
        </ul>
</blockquote>

<h4 id="Niveau">Paramétrage des Niveau</h4>
Il est possible de personnaliser les niveaux :
<blockquote>
        <ul>
            <li><b>level_0</b> : Niveau 0 <i>(valeur par défaut : 0) </i></li>
            <li><b>level_1</b> : Niveau 1 <i>(valeur par défaut : 17)</i></li>
            <li><b>level_2</b> : Niveau 2 <i>(valeur par défaut : 35)</i></li>
            <li><b>level_3</b> : Niveau 3 <i>(valeur par défaut : 45)</i></li>
            <li><b>level_4</b> : Niveau 4 <i>(valeur par défaut : 55)</i></li>
            <li><b>level_5</b> : Niveau 5 <i>(valeur par défaut : 63)</i></li>
            <li><b>level_6</b> : Niveau 6 <i>(valeur par défaut : 73)</i></li>
            <li><b>level_7</b> : Niveau 7 <i>(valeur par défaut : 84)</i></li>
            <li><b>level_8</b> : Niveau 8 <i>(valeur par défaut : 92)</i></li>
            <li><b>level_9</b> : Niveau 9 <i>(valeur par défaut : 95)</i></li>
            <li><b>level_10</b> : Niveau 10 <i>(valeur par défaut : 100)</i></li>
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
        Le nommage des images est normalisé et doit respecter le format suivant :
        <ul>
            <li><b>Image</b> : type-x</li>
            <li><i>Remplacer <b>type</b> par le nom de l'image</i></li>
            <li><i>Remplacer <b>x</b> par le niveau (Valeur possible : 0, 1, 10, 20, 30, 40, 50, 60, 70, 80, 99)</i></li>
        </ul>
        Les images en fonction des niveaux
        <ul>
            <li><b>Niveau = level_0</b> : Store-0</li>
            <li><b>Niveau > level_0 et Niveau ≤ Level_1</b> : Store-1</li>
            <li><b>Niveau > level_1 et Niveau ≤ Level_2</b> : Store-10</li>
            <li><b>Niveau > level_2 et Niveau ≤ Level_3</b> : Store-20</li>
            <li><b>Niveau > level_3 et Niveau ≤ Level_4</b> : Store-30</li>
            <li><b>Niveau > level_4 et Niveau ≤ Level_5</b> : Store-40</li>
            <li><b>Niveau > level_5 et Niveau ≤ Level_6</b> : Store-50</li>
            <li><b>Niveau > level_6 et Niveau ≤ Level_7</b> : Store-60</li>
            <li><b>Niveau > level_7 et Niveau ≤ Level_8</b> : Store-70</li>
            <li><b>Niveau > level_8 et Niveau ≤ Level_9</b> : Store-80</li>
            <li><b>Niveau > level_9 et Niveau ≤ Level_10</b> : Store-99</li>
        </ul>  
    <li><a href="./JEEDOM-AIDE-ADD_IMG.html">Ajouter des images dans un widget</a></li>
</blockquote>

<hr />
<dl>
    <dt>Mise à jour JAG - 20190610<br/>
    <a href="https://github.com/JEALG/JEEDOM-Store-Velux-num/commits/master">Changelog WIDGET</a><br/>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a></dt>
</dl>
<hr />
[back](./)