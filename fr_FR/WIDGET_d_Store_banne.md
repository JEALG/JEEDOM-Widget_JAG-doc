---
layout: default
title: JEEDOM-Store-banne
description: explication Store-banne
---
[back](./)
# Widget "Store-banne"

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info numérique</b>
<p><img src="../img/exemple/d/store_banne.png" alt="Resultat" /></p>

# A savoir
<blockquote>
<b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est nécessaire d'avoir le </b><a href="WIDGET_d_Multi_action_Defaut">Widget Dashboard : <b>Multi-action</b></a>
</blockquote>


# Paramétrage
## Choix de l'icône
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
    <ul>
        <li><b>logo</b> : Permet de choisir l'image pour la valeur <i>(valeur par défaut : st_banne_pos)</i></li>
        <li><b>logo_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
    </ul>
</blockquote>

## Taille de l'image
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
    <ul>
        <li><b>sizeh</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 65)</i></li>
        <li><b>sizew</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 30)</i></li>
    </ul>
</blockquote>

## Masquer la valeur
Il est possible de masquer la valeur de l'ouverture :
<blockquote>
    <ul>
        <li><b>masque_valeur</b> : Permet de masquer la valeur <i>(valeur par défaut :NO)</i></li>
        <li>variable avec la valeur <b>NO</b> ne masque pas la valeur <i>(valeur par défaut)</i></li>
        <li>variable avec la valeur <b>YES</b> masque la valeur</li>
    </ul>
</blockquote>

## Inversion sens image
Si l'équipement a la valeur 0 pour l'ouverture, il est possible d'inverser le sens
<blockquote>
    <ul>
        <li><b>levelINV = 0</b> Ouverture = 100% <i>(valeur par défaut : 0)</i></li>
        <li><b>levelINV = 1</b> Ouverture = 0%  <i></i></li>
    </ul>
</blockquote>


## Autres paramétrages possible et Aide
<blockquote>
    <ul>
        <li><a href="HELP_config_infos.html">Aide ajout des paramètres pour un widget Info</a></li>
        <li><a href="HELP_Error.html">Paramétrage image de défaut</a></li>
        <li><a href="HELP_STATS.html">Afficher les statistiques</a></li>
        <li><a href="HELP_STATS_TEMPS.html">Affichage des informations de durée sur les widgets info (binaire, numérique)</a></li>
        <li><a href="HELP_PARA.html">Ajouter les paramètres sur un widget</a></li>
    </ul>
</blockquote>


### Ajout d'image
Il est possible d'inclure d'autres icônes dans le widget.<br/>
Le nommage des images est normalisé et doit respecter le format suivant :
<blockquote>
    <ul>
        <li><b>Image</b> : typex</li>
        <li><i>Remplacer <b>type</b> par le nom de l'image</i></li>
        <li><i>Remplacer <b>x</b> par le niveau (Valeur possible : 0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100)</i></li>
    </ul>
    <ul>
        <li><a href="HELP_ADD_IMG.html">Ajouter des images dans un widget</a></li>
    </ul>
</blockquote>

# Télécharger les sources
><a href="HELP_Install_Manu.html">Aide pour l'installation manuelle des widgets</a>
<br/>

<li><a href="https://github.com/JEALG/JEEDOM-Store-banne/tree/masterv4">Télécharger les sources du Widget pour le Core V4</a></li>
<li><a href="https://github.com/JEALG/JEEDOM-Store-banne/tree/master">Télécharger les sources du Widget pour le Core V3</a></li>

<hr />
# Changelog
<a href="https://github.com/JEALG/JEEDOM-Store-banne/commits/masterv4">Changelog WIDGET pour le Core V4</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Store-banne/commits/master">Changelog WIDGET pour le Core V3</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)