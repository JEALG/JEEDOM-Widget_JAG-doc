---
layout: default
title: JEEDOM-AIDE Error
description: explication Image défaut widget
---
[back](./)
# Paramétrage image défaut Widget 

## Choix de l'icône en cas d'erreur pour un widget "Dashboard"
En cas de défaut de valeur sur un widget de type info (binaire - Numérique), le widget affichage un icône d'erreur, il est possible de paramétrer celui-ci
<blockquote>
        <ul>
            <li><b>logoER</b> : Permet de choisir l'image pour la valeur ETAT en cas de problème <i>(valeur par défaut en général : oups)</i></li>
            <li><b>logoER_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoER</i>(par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>

## Choix de l'icône en cas d'erreur pour un widget "Mobile"
En cas de défaut de valeur sur un widget de type info (binaire - Numérique), le widget affichage un icône d'erreur, il est possible de paramétrer celui-ci
<blockquote>
        <ul>
            <li><b>logoER-M</b> : Permet de choisir l'image pour la valeur ETAT en cas de problème <i>(valeur par défaut en général : er_oups1)</i></li>
            <li><b>logoER_type-M</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoER-M</i>(par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>

<p><img src="../img/VISUEL_JEEDOM_Error.png" alt="Error" /></p>

# Cas Particulier
Pour les widgets suivants, il est possible d'indiquer le dossier de l'image d'erreur
<ul>
    <li><a href="JEEDOM_Icon_Mode.html">Widget Dashboard : <b>Icon_Mode</b></a></li>
    <li><a href="JEEDOM_Icon_Mode_Mobile.html">Widget Mobile : <b>Icon_Mode (mobile)</b></a></li>
    <li><a href="JEEDOM_Multi_info_Binaire.html">Widget Dashboard : <b>Multi info - Binaire</b></a></li>
    <li><a href="JEEDOM-Multi_info_Binaire_mobile.html">Widget Mobile : <b>Multi info - Binaire (mobile)</b></a></li>
</ul>
<blockquote>
        <ul>
            <li><b>dossierER</b> : Permet de choisir le dossier pour l'image "Erreur" pour la version dashboard <i>(valeur par défaut : error)</i></li>
            <li><b>dossierER-M</b> : Permet de choisir le dossier pour l'image "Erreur" pour la version dashboard <i>(valeur par défaut : error)</i></li>
        </ul>
</blockquote>

# Cas Particulier pour les widgets Multi_info-Binaire
<ul>
    <li><a href="JEEDOM_Multi_info_Binaire.html">Widget Dashboard : <b>Multi info - Binaire</b></a></li>
    <li><a href="JEEDOM_Multi_info_Binaire_mobile.html">Widget Mobile : <b>Multi info - Binaire (mobile)</b></a></li>
</ul>
<blockquote>
    Petit rappel : la variable ci-dessous permet de récupèrer ou pas les même infos que le Dashboard
        <ul>
            <li><b>Dashboard-M</b> = <i>YES (valeur par défaut)</i> : Image identique au Dashboard</li>
            <li><b>Dashboard-M</b> = <i>NO</i>  : Image différente au Dashboard</li>
        </ul>
</blockquote>
<blockquote>
    Paramétrage image Erreur : Il est possible d'appliquer la même image que pour la valeur ON ou OFF
        <ul>
            <li><b>para_ER</b> = <i>logoON</i> : l'image d'erreur sera identique que pour la valeur ON</li>
            <li><b>para_ER-M</b> = <i>logoON</i> : l'image d'erreur sera identique que pour la valeur ON</li>
            <li><b>para_ER</b> = <i>logoOFF</i> : l'image d'erreur sera identique que pour la valeur OFF</li>
            <li><b>para_ER-M</b> = <i>logoOFF</i> : l'image d'erreur sera identique que pour la valeur OFF</li>
            <li><b>para_ER</b> = <i> </i> (valeur vide) : l'image d'erreur sera identique que pour la valeur logoER <i>(valeur par défaut)</i></li>
            <li><b>para_ER-M</b> = <i></i> (valeur vide) : l'image d'erreur sera identique que pour la valeur logoER <i>(valeur par défaut)</i></li>
        </ul>
</blockquote>
<hr />
# Télécharger les sources

# Changelog
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)