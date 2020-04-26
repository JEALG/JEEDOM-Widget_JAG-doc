---
layout: default
title: JEEDOM-Multi_info-Binaire
description: Explication widget Multi-info-Binaire-mobile
---
[back](./)
# Widget "Multi-info-Binaire (mobile)"

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info binaire</b>

<p><img src="../img/exemple/m/multi_binaire.png" alt="Resultat" /></p>

# A savoir
<ul>
<li><b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est nécessaire d'avoir le </b><a href="WIDGET_d_Multi_action_Defaut">Widget Dashboard : <b>Multi-action</b></a></li>
<li><b>Ce widget remplace ces widgets </b><a href="Archive_WIDGET_m_Multiinfo">Archive Widget Info Binaire</a></li>
</ul>

# Paramétrage
## Choix de l'icône
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
Il est possible de récupérer le même réglage que le dashboard

Cas Image identique avec le Dashboard avec la variable <b>Dashboard-M = <i>YES</i></b>
<blockquote>
    <ul>
        <li><b>Dashboard-M</b> : Image identique au Dashboard <i> (valeur par défaut : YES)</i></li>
        <li><b>logoON</b> : Permet de choisir l'image pour la valeur ON<i> (valeur par défaut : di_day)</i></li>
        <li><b>logoON_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
        <li><b>logoOFF</b> : Permet de choisir l'image pour la valeur OFF<i> (valeur par défaut : di_night)</i></li>
        <li><b>logoOFF_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoOFF</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
    </ul>
</blockquote>

Cas Image différente avec le Dashboard avec la variable <b>Dashboard-M = <i>NO</i></b>
<blockquote>
    <ul>
        <li><b>Dashboard-M</b> : Image identique au Dashboard <i> (valeur par défaut : YES)</i></li>
        <li><b>logoON-M</b> : Permet de choisir l'image pour la valeur ON<i> (valeur par défaut : di_day)</i></li>
        <li><b>logoON_type-M</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
        <li><b>logoOFF-M</b> : Permet de choisir l'image pour la valeur OFF<i> (valeur par défaut : di_night)</i></li>
        <li><b>logoOFF_type-M</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoOFF</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
    </ul>
</blockquote>


## Sous dossier
Il possible d'ajouter de mettre les images dans des sous dossiers, (la variable est valable pour l'ensemble des valeurs)

Cas Image identique avec le Dashboard avec la variable <b>Dashboard-M = <i>YES</i></b>
<blockquote>
    <ul>
        <li><b>dossier</b> : Nom du dossier (Par défaut : fibarooeil)</li>
        <li><a href="List_img.html">Listes des images par dossiers</a></li>
    </ul>
</blockquote>

Cas Image différente avec le Dashboard avec la variable <b>Dashboard-M = <i>NO</i></b>
<blockquote>
    <ul>
        <li><b>dossier-M</b> : Nom du dossier (Par défaut : fibarooeil)</li>
    </ul>
</blockquote>

## Taille des images ou des icônes
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
    <ul>
        <li><b>Pourcentage-M</b> : Permet de choisir la taille en "px" ou "%" <i>(valeur par défaut : NO donc "px")</i></li>
        <ul>
            <li><i>Pourcentage-M = NO</i> la taille sera en "px"</li>
            <li><i>Pourcentage-M = YES</i> la taille sera en "%"</li>
        </ul>
        <li><b>sizeh-M</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 40)</i></li>
        <li><b>sizew-M</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 40)</i></li>
    </ul>
</blockquote>

## Autres paramétrages possible et Aide
<blockquote>
    <ul>
        <li><a href="HELP_CONFIG_INFOS.html">Aide pour le paramétrage des widgets de type infos</a></li>
        <li><a href="HELP_STATS.html">Afficher les statistiques</a></li>
        <li><a href="HELP_STATS_TEMPS.html">Affichage des informations de durée sur les widgets info (binaire, numérique)</a></li>
        <li><a href="HELP_PARA.html">Ajouter les paramétres sur un widget</a></li>
    </ul>
</blockquote>


# Télécharger les sources
<li><a href="https://github.com/JEALG/JEEDOM-Multi_info-Binaire--mobile/tree/masterv4">Télécharger les sources pour la V4</a></li>
<li><a href="https://github.com/JEALG/JEEDOM-Multi_info-Binaire--mobile/tree/master">Télécharger les sources pour la V3</a></li>

<hr />
# Changelog
<a href="https://github.com/JEALG/JEEDOM-Multi_info-Binaire--mobile/commits/masterv4">Changelog WIDGET pour le Core V4</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Multi_info-Binaire--mobile/commits/master">Changelog WIDGET pour le Core V3</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)