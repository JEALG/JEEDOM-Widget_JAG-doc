---
layout: default
title: JEEDOM-Luminosite-IMG-Mini
description: explication widget Luminosité-IMG-Mini
---
[back](./)
# Widget "Luminosité-IMG-Mini" 

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info numérique</b>
<p><img src="Img/RESULTAT%20-%20JEEDOM-Lum_IMG.png" alt="Resultat" /></p>

<h4 id="Taille">Taille des images ou des icônes</h4>
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>Pourcentage</b> : Permet de choisir la taille en "px" ou "%" <i>(valeur par défaut : NO donc "px")</i></li>
            <li><b>sizeh</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 65)</i></li>
            <li><b>sizew</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 70)</i></li>
        </ul>
</blockquote>

<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Choix de l'icône</h4>
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>logo_level1</b> : Permet de choisir l'image pour la valeur  pour le niveau 1 <i>(valeur par défaut : moon)</i></li>
            <li><b>logo_level1_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo_level1</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
            <li><b>logo_level2</b> : Permet de choisir l'image pour la valeur  pour le niveau 2 <i>(valeur par défaut : cloud)</i></li>
            <li><b>logo_level2_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo_level2</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
            <li><b>logo_level3</b> : Permet de choisir l'image pour la valeur  pour le niveau 3 <i>(valeur par défaut : sun)</i></li>
            <li><b>logo_level3_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo_level3</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>

<h4 id="Level">Niveau</h4>
Il est possible de modifier les niveaux
<blockquote>
        <ul>
            <li><b>level_1</b> : Niveau Bas (nuit) <i>(valeur par défaut : 20)</i></li>
            <li><b>level_2</b> : Niveau Haut (jour) <i>(valeur par défaut : 100.0)</i></li>
        </ul>
</blockquote>
<h4 id="Pos">Position Légende</h4>
Il est possible de déplacer la légende
<blockquote>
        <ul>
            <li><b>leg_pos</b> = low <i>(valeur par défaut)</i></li>
            <p><img src="Img/RESULTAT - JEEDOM-Lum_IMG.png" alt="Resultat - Bas" /></p>
        </ul>
</blockquote>
<blockquote>
        <ul>
            <li><b>leg_pos</b> = right <i></i></li>
            <p><img src="Img/RESULTAT - JEEDOM-Lum_IMG - Droite.png" alt="Resultat - Droite" /></p>
        </ul>
</blockquote>
<blockquote>
        <ul>
            <li><b>leg_pos</b> = left</li>
            <p><img src="Img/RESULTAT - JEEDOM-Lum_IMG - Gauche.png" alt="Resultat - Gauche" /></p>
        </ul>
</blockquote>
<blockquote>
        <ul>
            <li><b>leg_pos</b> = top</li>
            <p><img src="Img/RESULTAT - JEEDOM-Lum_IMG - Haut.png" alt="Resultat - Haut" /></p>
        </ul>
</blockquote>
<h4 id="Aide">Autres paramétrages possible et Aide</h4>
<blockquote>
        <ul>
            <li><a href="JEEDOM-AIDE-CONFIG-INFO.html">Aide ajout Des paramétres pour un widget Info</a></li>
            <li><a href="JEEDOM-AIDE-Error.html">Paramétrage image de défaut</a></li>
            <li><a href="JEEDOM-AIDE-STATS.html">Afficher les statistiques</a></li>
            <li><a href="JEEDOM-AIDE-PARA.html">Ajouter les paramétres sur un widget</a></li>
        </ul>
</blockquote>

<hr />
<dl>
    <dt>Mise à jour JAG - 20190926<br/>
    <a href="https://github.com/JEALG/JEEDOM-Luminosite-IMG-Mini/commits/master">Changelog WIDGET</a><br/>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a></dt>
</dl>
<hr />
[back](./)