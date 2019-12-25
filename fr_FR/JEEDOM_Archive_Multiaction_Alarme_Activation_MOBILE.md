---
layout: default
title: JEEDOM-Alarme-Activation--Mobile
description: Explication widget Alarme-Activation (mobile)
---
[back](../JEEDOM_Archive_action_mobile.html)
# Widget "Alarme-Activation (mobile)" 

# A savoir
<blockquote>
<b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est necessaire d'avoir le widget "Multi_action-Defaut"</b>
</blockquote>

# Nouveau paramétrage
## Remplacer par le widget
Ce widget est remplacé par :

## Paramétrage


<h4 id="A Savoir">A savoir</h4>
<blockquote>
    <b>Afin de simplifier la gestion des images et la migration du widget en Core V4, depuis le 10/09/2019, ce widget est remplacé par le widget <a href="../../JEEDOM_Multi_action_Defaut_mobile">Widget Dashboard : <b>Multi-action (mobile)</b></a></b>
    <ul>
        <li><b>Pour avoir les images </b><a href="../../JEEDOM_Multi_action_Defaut">Widget Dashboard : <b>Multi-action</b></a></li>
        <li><b>Pour avoir le paramétrage par défaut du widget Alarme-Activation (mobile), il faudra ajouter pour avoir le logo par défaut de ce widget </b> :</li>
        <ul>
            <li><b>dossier</b> avec la valeur : <i>alarme</i></li>
            <li><b>logoON-M</b> avec la valeur : <i>al_type1_on</i></li>
            <li><b>logoOFF-M</b> avec la valeur : <i>al_type1_off</i></li>
            <li><b>Les autres variables sont identiques</b></li>
        </ul>
    </ul>
</blockquote>

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>action ON/OFF</b>
<p><img src="img/RESULTAT_JEEDOM_Alarme_Activation_Mobile.png" alt="Resultat" /></p>
<blockquote>
Le widget inclus plusieurs icônes. Il est possible d'ajouter ses propres icônes.
</blockquote>
<p><img src="img/VISUEL_JEEDOM_Alarme.png" alt="Visuels" /></p>

<h4 id="A Savoir">A savoir</h4>
<blockquote>
<b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est necessaire d'avoir la version dashboard du widget</b>
</blockquote>

<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Choix de l'icône</h4>
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>logoON-M</b> : Permet de choisir l'image pour la valeur ON <i>(valeur par défaut : al_type1_on)</i></li>
            <li><b>logoON_type-M</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON-M</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
            <li><b>logoOFF-M</b> : Permet de choisir l'image pour la valeur OFF <i>(valeur par défaut : al_type1_off)</i></li>
            <li><b>logoOFF_type-M</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoOFF-M</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>

<h4 id="Taille">Taille des images ou des icônes</h4>
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>sizeh-M</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 40)</i></li>
            <li><b>sizew-M</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 40)</i></li>
        </ul>
</blockquote>
 
<hr />
# Changelog
<a href="https://github.com/JEALG/JEEDOM-Alarme-Activation--Mobile/commits/master">Changelog WIDGET</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](../JEEDOM_Archive_action_mobile.html)
