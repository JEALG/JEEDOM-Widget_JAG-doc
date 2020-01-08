---
layout: default
title: JEEDOM-Fenetre--mobile
description: explication widget Fenêtre (numérique)
---
[back](./)
# Widget "Fenêtre (mobile) (numérique)"

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info numérique</b>
<p><img src="../img/RESULTAT_JEEDOM_Fenetre.png" alt="Resultat" /></p>
<blockquote>
Le widget inclus plusieurs icônes. Il est possible d'ajouter ses propres icônes.
</blockquote>
<p><img src="../img/VISUEL_JEEDOM_Fenetre.png" alt="Visuels" /></p>

# A savoir
<blockquote>
<b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est necessaire d'avoir le widget "Multi_action-Defaut"</b>
    <a href="JEEDOM_Multi_action_Defaut">Widget Dashboard : <b>Multi-action</b></a>
</blockquote>

# Paramétrage
## Choix de l'icône
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
    <ul>
        <li><b>logo_<b>x</b></b> : Permet de choisir l'image pour la valeur <b>x</b></li>
        <li><b>logo_<b>x</b>_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo_<b>x</b></i> (par exemple: 'gif', 'jpg', etc.....)<i> (valeur par défaut : png)</i></li>
        <li><b>x</b> : Remplacer <b>x</b> par le numéro de la valeur correspondante (valeur possible de 0 à 8)</li>
    </ul>
</blockquote>
<blockquote>
    <ul>
        <li><b>logo_<b>0</b></b> : <i>valeur par défaut : ou_baie2_wh_db_off</i></li>
        <li><b>logo_<b>1</b></b> : <i>valeur par défaut : ou_baie2_wh_lf_on</i></li>
        <li><b>logo_<b>2</b></b> : <i>valeur par défaut : ou_baie2_wh_rg_on</i></li>
        <li><b>logo_<b>3</b></b> : <i>valeur par défaut : ou_baie2_wh_db_on</i></li>
        <li><b>logo_<b>4</b></b> : <i>valeur par défaut : ou_baie2_wh_db_on</i></li>
        <li><b>logo_<b>5</b></b> : <i>valeur par défaut : ou_baie2_wh_db_on</i></li>
        <li><b>logo_<b>6</b></b> : <i>valeur par défaut : ou_baie2_wh_db_on</i></li>
        <li><b>logo_<b>7</b></b> : <i>valeur par défaut : ou_baie2_wh_db_on</i></li>
        <li><b>logo_<b>8</b></b> : <i>valeur par défaut : ou_baie2_wh_db_on</i></li>
    </ul>
</blockquote>
            
## Choix de la valeur
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
    <ul>
        <li><b>Pourcentage-M</b> : Permet de choisir la taille en "px" ou "%" <i>(valeur par défaut : NO donc "px")</i></li>
        <li><b>valeur_<b>x</b></b> : Permet de choisir l'image pour la valeur <b>x</b></li>
        <li><b>x</b> : Remplacer <b>x</b> par le numéro de la valeur correspondante (valeur possible de 0 à 5)</li>
    </ul>
</blockquote>
<blockquote>
    <ul>
        <li><b>valeur_<b>0</b></b> : <i>valeur par défaut : 0</i></li>
        <li><b>valeur_<b>1</b></b> : <i>valeur par défaut : 1</i></li>
        <li><b>valeur_<b>2</b></b> : <i>valeur par défaut : 2</i></li>
        <li><b>valeur_<b>3</b></b> : <i>valeur par défaut : 3</i></li>
        <li><b>valeur_<b>4</b></b> : <i>valeur par défaut : 4</i></li>
        <li><b>valeur_<b>5</b></b> : <i>valeur par défaut : 5</i></li>
        <li><b>valeur_<b>6</b></b> : <i>valeur par défaut : 6</i></li>
        <li><b>valeur_<b>7</b></b> : <i>valeur par défaut : 7</i></li>
        <li><b>valeur_<b>8</b></b> : <i>valeur par défaut : 8</i></li>
    </ul>
</blockquote>      


## Taille des images ou des icônes
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
    <ul>
        <li><b>sizeh-M</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 80)</i></li>
        <li><b>sizew-M</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 80)</i></li>
    </ul>
</blockquote>

## Autres paramétrages possible et Aide
<blockquote>
        <ul>
            <li><a href="JEEDOM_AIDE_CONFIG_INFOS.html">Aide ajout Des paramétres pour un widget Info</a></li>
            <li><a href="JEEDOM_AIDE_Error.html">Paramétrage image de défaut</a></li>
            <li><a href="JEEDOM_AIDE_STATS_TEMPS.html">Affichage des informations de durée sur les widgets info (binaire, numérique)</a></li>
            <li><a href="JEEDOM_AIDE_PARA.html">Ajouter les paramétres sur un widget</a></li>
        </ul>
</blockquote>

# >Exemples de paramétrage
<li><a href="JEEDOM_AIDE_PARA_FENETRES.html">Exemple de paramétrages</a></li>

<hr />
# Télécharger les sources
 <a href="https://github.com/JEALG/JEEDOM-Fenetre--mobile/tree/masterv4">Télécharger les sources pour la V4</a><br/>
 
# Changelog
<a href="https://github.com/JEALG/JEEDOM-Fenetre--mobile/commits/masterv4">Changelog WIDGET pour le Core V4</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Fenetre--mobile/commits/master">Changelog WIDGET pour le Core V3</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)