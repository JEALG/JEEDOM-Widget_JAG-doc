---
layout: default
title: JEEDOM-VoyantMulticouleur- Mobile
description: explication Bouton en forme de voyant Multi couleur (mobile)
---
[back](./)
# Widget "VoyantMulticouleur : Bouton en forme de voyant Multi couleur (mobile)"

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info binaire</b>
<p><img src="../img/exemple/m/voyant_multicouleur.png" alt="Resultat" /></p>
<blockquote>
Les visu à utiliser sont :
</blockquote>

<p><img src="../img/VISUEL_JEEDOM_Voyant.png" alt="Visuels" /></p>

# A savoir

> <b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est nécessaire d'avoir le </b><a href="WIDGET_d_Multi_action_Defaut">Widget Dashboard : <b>Multi-action</b></a>


# Paramétrage
## Choix de la couleur
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
Il est possible de récupérer le même réglage que le dashboard

Cas Image identique avec le Dashboard avec la variable <b>Dashboard-M = <i>YES</i></b>
<blockquote>
    <ul>
        <li><b>Dashboard-M</b> : Image identique au Dashboard <i> (valeur par défaut : YES)</i></li>
        <li><b>CouleurON</b> : Permet de choisir la couleur du voyant pour la valeur ON <i>(valeur par défaut : gn)</i></li>
        <li><b>CouleurOFF</b> : Permet de choisir la couleur du voyant pour la valeur OFF <i>(valeur par défaut : rd)</i></li>
        <li><b>Les valeurs possibles </b> : bk, bu, gn, or, rd, wh, ye</li>
        </ul>
</blockquote>

Cas Image différente avec le Dashboard avec la variable <b>Dashboard-M = <i>NO</i></b>
<blockquote>
    <ul>
        <li><b>Dashboard-M</b> : Image identique au Dashboard <i> (valeur par défaut : YES)</i></li>
        <li><b>CouleurON-M</b> : Permet de choisir la couleur du voyant pour la valeur ON <i>(valeur par défaut : gn)</i></li>
        <li><b>CouleurOFF-M</b> : Permet de choisir la couleur du voyant pour la valeur OFF <i>(valeur par défaut : rd)</i></li>
        <li><b>Les valeurs possibles </b> : bk, bu, gn, or, rd, wh, ye</li>
    </ul>
</blockquote>

## Choix de la forme
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
Il est possible de récupérer le même réglage que le dashboard

Cas Image identique avec le Dashboard avec la variable <b>Dashboard-M = <i>YES</i></b>
<blockquote>
    <ul>
        <li><b>Dashboard-M</b> : Image identique au Dashboard <i> (valeur par défaut : YES)</i></li>
        <li><b>FormeON</b> : Permet de choisir la forme du voyant pour la valeur ON <i>(valeur par défaut : rond)</i></li>
        <li><b>FormeOFF</b> : Permet de choisir la forme du voyant pour la valeur OFF <i>(valeur par défaut : rond)</i></li>
        <li><b>Les valeurs possibles</b> : rond, carre</li>
    </ul>
</blockquote>


Cas Image différente avec le Dashboard avec la variable <b>Dashboard-M = <i>NO</i></b>
<blockquote>
    <ul>
        <li><b>Dashboard-M</b> : Image identique au Dashboard <i> (valeur par défaut : YES)</i></li>
        <li><b>FormeON-M</b> : Permet de choisir la forme du voyant pour la valeur ON <i>(valeur par défaut : rond)</i></li>
        <li><b>FormeOFF-M</b> : Permet de choisir la forme du voyant pour la valeur OFF <i>(valeur par défaut : rond)</i></li>
        <li><b>Les valeurs possibles</b> : rond, carre</li>
    </ul>
</blockquote>

## Choix de l'extension
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
Il est possible de récupérer le même réglage que le dashboard

Cas Image identique avec le Dashboard avec la variable <b>"Dashboard-M = <i>YES</i></b>
<blockquote>
    <ul>
        <li><b>Dashboard-M</b> : Image identique au Dashboard <i> (valeur par défaut : YES)</i></li>
        <li><b>logoON_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
        <li><b>logoOFF_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
    </ul>
</blockquote>

Cas Image différente avec le Dashboard avec la variable <b>"Dashboard-M = <i>NO</i></b>
<blockquote>
    <ul>
        <li><b>Dashboard-M</b> : Image identique au Dashboard <i> (valeur par défaut : YES)</i></li>
        <li><b>logoON-M_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
        <li><b>logoOFF-M_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
    </ul>
</blockquote>

## Autres paramétrages possible et Aide
<blockquote>
    <ul>
        <li><a href="JEEDOM_AIDE_CONFIG_INFOS.html">Aide ajout Des paramétres pour un widget Info</a></li>
        <li><a href="JEEDOM_AIDE_PARA.html">Ajouter les paramétres sur un widget</a></li>
    </ul>
</blockquote>

<hr />
# Télécharger les sources
<li><a href="https://github.com/JEALG/JEEDOM-VoyantMulticouleur--mobile/tree/masterv4">Télécharger les sources pour la V4</a></li>
<li><a href="https://github.com/JEALG/JEEDOM-VoyantMulticouleur--mobile/tree/master">Télécharger les sources pour la V3</a></li>

# Changelog
<a href="https://github.com/JEALG/JEEDOM-VoyantMulticouleur--mobile/commits/masterv4">Changelog WIDGET pour le Core V4</a><br/>
<a href="https://github.com/JEALG/JEEDOM-VoyantMulticouleur--mobile/commits/master">Changelog WIDGET pour le Core V3</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)