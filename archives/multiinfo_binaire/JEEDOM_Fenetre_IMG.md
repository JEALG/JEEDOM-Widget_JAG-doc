---
layout: default
title: JEEDOM-Fenetre-IMG
description: explication widget Fenêtre-IMG
---
[back](../JEEDOM_Archive_info_binaire.html)
# Widget "Fenêtre-IMG" 

<h4 id="A Savoir">A savoir</h4>
<blockquote>
    <b>Afin de simplifier la gestion des images et la migration du widget en Core V4, depuis le 10/09/2019, ce widget est remplacé par le widget <a href="./JEEDOM_Multi_info_Binaire.html">Widget Mobile : <b>Multi info - Binaire</b></a></b>
    <ul>
        <li><b>Pour avoir les images </b><a href="../../JEEDOM_Multi_action_Defaut">Widget Dashboard : <b>Multi-action</b></a></li>
        <li><b>Pour avoir le paramétrage par défaut du widget Fenetre-IMG, il faudra ajouter pour avoir le logo par défaut de ce widget </b> :</li>
        <ul>
            <li><b>dossier</b> avec la valeur : <i>fenetre</i></li>
            <li><b>logoON</b> avec la valeur : <i>ou_baie2_wh_db_off</i></li>
            <li><b>logoOFF</b> avec la valeur : <i>ou_baie2_wh_rg_on</i></li>
            <li><b>Les autres variables sont identiques</b></li>
        </ul>
    </ul>
</blockquote>

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info binaire</b>
<p><img src="../../img/RESULTAT_JEEDOM_Fenetre_IMG.png" alt="Resultat" /></p>
<blockquote>

<h4 id="A Savoir">A savoir</h4>
<blockquote>
<b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est necessaire d'avoir le widget "Multi_action-Defaut"</b>
</blockquote>

<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Choix de l'icône</h4>
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>logoClose</b> : Permet de choisir l'image pour la fenêtre fermée <i>(valeur par défaut : ou_baie2_wh_db_off)</i></li>
            <li><b>logoClose_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoClose</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
            <li><b>logoOpen</b> : Permet de choisir l'image pour la fenêtre fermée <i>(valeur par défaut : ou_baie2_wh_rg_on)</i></li>
            <li><b>logoOpen_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoOpen</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
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
    <a href="https://github.com/JEALG/JEEDOM-Fenetre-IMG/commits/master">Changelog WIDGET</a><br/>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>
</dl>
<hr />
[back](../JEEDOM_Archive_info_binaire.html)