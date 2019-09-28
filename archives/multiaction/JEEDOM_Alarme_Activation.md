---
layout: default
title: JEEDOM-Alarme-Activation
description: Explication widget Alarme Activation
---
[back](../JEEDOM_Archive_action.html)
# Widget "Alarme-Activation" 

<h4 id="A Savoir">A savoir</h4>
<blockquote>
    <b>Afin de simplifier la gestion des images et la migration du widget en Core V4, depuis le 10/09/2019, ce widget est remplacé par le widget <a href="../../JEEDOM_Multi_action_Defaut">Widget Dashboard : <b>Multi-action</b></a></b>
    <ul>
        <li><b>Pour le paramétrage, il faudra ajouter pour avoir le logo par défaut de ce widget </b> :</li>
        <ul>
            <li><b>dossier</b> avec la valeur : <i>alarme</i></li>
            <li><b>logoON-M</b> avec la valeur : <i>al_type1_on</i></li>
            <li><b>logoOFF-M</b> avec la valeur : <i>al_type1_off</i></li>
            <li><b>Les autres variables sont identiques</b></li>
        </ul>
    </ul>
</blockquote>

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>action ON/OFF</b>
<p><img src="../../img/RESULTAT_JEEDOM_Alarme_Activation.png" alt="Resultat" /></p>
<blockquote>
Le widget inclus plusieurs icônes. Il est possible d'ajouter ses propres icônes.
</blockquote>
<p><img src="../../img/VISUEL_JEEDOM_Alarme.png" alt="Visuels" /></p>

<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Choix de l'icône</h4>
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>logoON</b> : Permet de choisir l'image pour la valeur ON <i>(valeur par défaut : al_type1_on)</i></li>
            <li><b>logoON_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
            <li><b>logoOFF</b> : Permet de choisir l'image pour la valeur OFF <i>(valeur par défaut : al_type1_off)</i></li>
            <li><b>logoOFF_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoOFF</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>

<h4 id="Taille">Taille des images ou des icônes</h4>
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>sizeh</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 80)</i></li>
            <li><b>sizew</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 80)</i></li>
        </ul>
</blockquote>

<hr />
<dl>
    <a href="https://github.com/JEALG/JEEDOM-Alarme-Activation/commits/master">Changelog WIDGET</a><br/>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>
</dl>
<hr />
[back](../JEEDOM_Archive_action.html)