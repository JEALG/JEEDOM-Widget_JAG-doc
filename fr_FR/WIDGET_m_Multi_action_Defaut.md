---
layout: default
title: JEEDOM-Multi_action-Defaut
description: Explication widget Multi-action--mobile
---
[back](./)
# Widget "Multi-action (mobile)"

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>action ON/OFF</b>
<blockquote>
    Ce widget regroupe l'ensemble des différentes images de mes widgets
</blockquote>

<p><img src="../img/exemple/m/multi_action.png" alt="Resultat" /></p>
<blockquote>
    Le widget inclus plusieurs icônes dans des sous dossiers
</blockquote>

# A savoir

> <b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est necessaire d'avoir le </b><a href="WIDGET_d_Multi_action_Defaut">Widget Dashboard : <b>Multi-action</b></a>
> <b>Ce widget remplace ces widgets </b><a href="Archive_WIDGET_m_Multiaction">Archive Widget Multi action</a>


# Paramétrage
## Choix de l'icône
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
Il est possible de récupérer le même réglage que le dashboard
<blockquote>
    Cas Image identique avec le Dashboard avec la variable <b>"Dashboard-M = <i>YES</i></b>
        <ul>
            <li><b>Dashboard-M</b> : Image identique au Dashboard <i> (valeur par défaut : YES)</i></li>
            <li><b>logoON</b> : Permet de choisir l'image pour la valeur ON<i> (valeur par défaut : di_day)</i></li>
            <li><b>logoON_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
            <li><b>logoOFF</b> : Permet de choisir l'image pour la valeur OFF<i> (valeur par défaut : di_night)</i></li>
            <li><b>logoOFF_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoOFF</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
        </ul>
</blockquote>
<blockquote>
    Cas Image différente avec le Dashboard avec la variable <b>"Dashboard-M = <i>NO</i></b>
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
<blockquote>
    Cas Image identique avec le Dashboard avec la variable <b>"Dashboard-M = <i>YES</i></b>
        <ul>
            <li><b>dossier</b> : Nom du dossier (Par défaut : divers)</li>
            <li><a href="JEEDOM_Liste_images_dossiers.html">Listes des images par dossiers</a></li>
        </ul>
</blockquote>
<blockquote>
    Cas Image différente avec le Dashboard avec la variable <b>"Dashboard-M = <i>NO</i></b>
        <ul>
            <li><b>dossier-M</b> : Nom du dossier (Par défaut : divers)</li>
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
            <li><a href="JEEDOM_AIDE_CONFIG_ACTION">Aide pour le paramétrage des widgets de type action</a></li>
            <li><a href="JEEDOM_AIDE_STATS">Afficher les statistiques</a></li>
            <li><a href="JEEDOM_AIDE_STATS_TEMPS.html">Affichage des informations de durée sur les widgets info (binaire, numérique, actions)</a></li>
            <li><a href="JEEDOM_AIDE_PARA">Ajouter les paramétres sur un widget</a></li>
        </ul>
</blockquote>

### Ajout d'image
<hr />
<blockquote>
        Il est possible d'inclure d'autres icônes dans le widget.<br/>
        Le nommage des images n'est pas normalisé sur ce widget
        <ul>
            <li><a href=".JEEDOM_AIDE_ADD_IMG.html">Ajouter des images dans un widget</a></li>
        </ul>
</blockquote>

<hr />
# Télécharger les sources
<li><a href="https://github.com/JEALG/JEEDOM-Multi_action-Defaut--mobile/tree/masterv4">Télécharger les sources pour la V4</a></li>
<li><a href="https://github.com/JEALG/JEEDOM-Multi_action-Defaut--mobile/tree/master">Télécharger les sources pour la V3</a></li>

# Changelog
<a href="https://github.com/JEALG/JEEDOM-Multi_action-Defaut--mobile/commits/masterv4">Changelog WIDGET pour le Core V4</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Multi_action-Defaut--mobile/commits/master">Changelog WIDGET pour le Core V3</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)