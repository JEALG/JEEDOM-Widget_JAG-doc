---
layout: default
title: JEEDOM-Multi_info-Binaire
description: Explication widget Multi-info-Binaire
---
[back](./)
# Widget "Multi-info-Binaire"

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info binaire</b>

<p><img src="../img/exemple/d/multi_binaire.png" alt="Resultat" /></p>

# A savoir
<ul>
<li><b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est nécessaire d'avoir le </b><a href="WIDGET_d_Multi_action_Defaut">Widget Dashboard : <b>Multi-action</b></a></li>
<li><b>Ce widget remplace ces widgets </b><a href="Archive_WIDGET_d_Multiinfo">Archive Widget Info Binaire</a></li>
</ul>

# Paramétrage
## Choix de l'icône
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
Dans le cas de l'utilisation avec le nom de l'image normalisé
<blockquote>
    <ul>
        <li><b>logo</b> : Permet de choisir l'image pour la valeur ON ou OFF <i>(pas de valeur par défaut)</i></li>
        <li><b>logo_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        <li>Le nommage des images normalisées doit respecter le format suivant :</li>
        <ul>
            <li><b>Image pour la valeur ON</b> : type_on</li>
            <li><b>Image pour la valeur OFF</b> : type_off</li>
            <li><i>Remplacer <b>type</b> par le nom de l'image</i></li>
            <li><i>à renseigner dans la variable logo <b>type</b></i></li>
        </ul>
            <li><b>l'utilisation de cette méthode désactive les variables <i>logoON</i> et <i>logoOFF</i></b> </li>
        </ul>
</blockquote>
Dans le cas de l'utilisation avec le nom de l'image non normalisé
<blockquote>
    <ul>
        <li><b>logoON</b> : Permet de choisir l'image pour la valeur ON <i>(valeur par défaut : fi_wh_off")</i></li>
        <li><b>logoON_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
        <li><b>logoOFF</b> : Permet de choisir l'image pour la valeur OFF <i>(valeur par défaut : fi_bu_on)</i></li>
        <li><b>logoOFF_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoOFF</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
    </ul>
</blockquote>

## Sous dossier
Il possible d'ajouter de mettre les images dans des sous dossiers, (la variable est valable pour l'ensemble des valeurs)
<blockquote>
    <ul>
        <li><b>dossier</b> : Nom du dossier (Par défaut : fibarooeil)</li>
        <li><a href="List_img.html">Listes des images par dossiers</a></li>
    </ul>
</blockquote>

## Taille des images ou des icônes
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
    <ul>
        <li><b>Pourcentage</b> : Permet de choisir la taille en "px" ou "%" <i>(valeur par défaut : NO donc "px")</i></li>
        <ul>
            <li><i>Pourcentage = NO</i> la taille sera en "px"</li>
            <li><i>Pourcentage = YES</i> la taille sera en "%"</li>
        </ul>
        <li><b>sizeh</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 80)</i></li>
        <li><b>sizew</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 80)</i></li>
    </ul>
</blockquote>

## Autres paramétrages possible et Aide
<blockquote>
    <ul>
        <li><a href="HELP_config_info.html">Aide pour le paramétrage des widgets de type infos</a></li>
        <li><a href="HELP_stats.html">Afficher les statistiques</a></li>
        <li><a href="HELP_stats_temps.html">Affichage des informations de durée sur les widgets info (binaire, numérique, actions)</a></li>
        <li><a href="HELP_para.html">Ajouter les paramètres sur un widget</a></li>
    </ul>
</blockquote>

## Exemple de paramétrage
>* <a href="HELP_config_info.html">Aide pour le paramétrage des widgets de type info (binaire, numérique, actions)</a>

# Télécharger les sources
><a href="HELP_Install_Manu.html">Aide pour l'installation manuelle des widgets</a>
<br/>

<li><a href="https://github.com/JEALG/JEEDOM-Multi_info-Binaire/tree/masterv4">Télécharger les sources du Widget pour le Core V4</a></li>
<li><a href="https://github.com/JEALG/JEEDOM-Multi_info-Binaire/tree/master">Télécharger les sources du Widget pour le Core V3</a></li>

<hr />
# Changelog
<a href="https://github.com/JEALG/JEEDOM-Multi_info-Binaire/commits/masterv4">Changelog WIDGET pour le Core V4</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Multi_info-Binaire/commits/master">Changelog WIDGET pour le Core V3</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)