---
layout: default
title: JEEDOM-Icon_Mode--Mobile
description: explication widget Icon_Mode (Mobile)
---
[back](./)
# Widget "Icon_Mode (Mobile)" 

Widget pour Jeedom permettant d'afficher une icône pour une valeur <b>info texte</b>
<p><img src="Img/RESULTAT%20-%20JEEDOM-Icon_Mode.png" alt="Resultat" /></p>
<blockquote>
Le widget inclus plusieurs icônes. Il est possible d'ajouter ses propres icônes.
</blockquote>

<h1 id="Merci">Merci</h1>
<blockquote>
        <ul>
            <li>Merci @Salviaf pour l'affichage de la durée</li>
            <li>Merci @Nicoraptor pour le code pour récupérer valeur Mode</li>
            <li>Merci @Antoinekl1 pour l'info et le code suite à la modif du plugin "Mode"</li>
        </ul>
</blockquote>

<h4 id="A Savoir">A savoir</h4>
<blockquote>
<b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est necessaire d'avoir le widget "Multi_action-Defaut"</b>
</blockquote>

<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Valeur du mode</h4>
Pour que le widget fonctionne, il faut indiquer la valeur du mode dans les variables
<blockquote>
        <ul>
            <li><b>modex</b> : Valeur du mode</li>
            <li><b>x</b> : Remplacer <b>x</b> par le numéro de mode (valeur possible de 0 à 10)</li>
        </ul>
</blockquote>
Pour que le widget fonctionne dans le cas où les noms des commandes sont remplacés par des icônes, il faut indiquer le nom de l'icône dans les variables
<blockquote>
        <ul>
            <li><b>modex</b> : Nom de l'icône</li>
            <li><b>x</b> : Remplacer <b>x</b> par le numéro de mode (valeur possible de 0 à 10)</li>
        </ul>
</blockquote>

<h4 id="Logo">Choix de l'icône</h4>
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels si le nom du mode ne correspond pas au nom de l'image :
<blockquote>
        <ul>
            <li><b>logox</b> : Permet de choisir l'image pour la valeur pour le mode <i>(valeur par défaut : <b>Nom_MODE</b>)</i></li>
            <li><b>logo_typex</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
            <li><b>x</b> : Remplacer <b>x</b> par le numéro de mode (valeur possible de 0 à 10)</li>
            <li><b>Nom_MODE</b> : correspond au nom exact de l'image</li>
        </ul>
</blockquote>


<h4 id="Dossier">Sous dossier</h4>
Il possible d'ajouter de mettre les images dans des sous dossiers, (la variable est valable pour l'ensemble des valeurs)
<blockquote>
        <ul>
            <li><b>dossier</b> : Nom du dossier (Par défaut : Chauffage)</li>
            <li><a href="./JEEDOM-Liste_images_dossiers.html">Listes des images par dossiers</a></li>
        </ul>
</blockquote>

<h4 id="Taille">Taille des images ou des icônes</h4>
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant : (en px ou %)
<blockquote>
        <ul>
            <li><b>Pourcentage-M = <i>NO</i></b> : Permet de choisir la taille en "px" <i>(valeur par défaut : NO)</i></li>
            <li><b>Pourcentage-M = <i>YES</i></b> : Permet de choisir la taille en "%"</li>
            <li><b>sizeh-M</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 40)</i></li>
            <li><b>sizew-M</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 40)</i></li>
        </ul>
</blockquote>
 
<h4 id="Error">Autres paramétrages possible</h4>
<blockquote>
        <ul>
            <li><a href="JEEDOM-AIDE-CONFIG-INFO.html">Aide ajout Des paramétres pour un widget Info</a></li>
            <li><a href="JEEDOM-AIDE-Error.html">Paramétrage image de défaut</a></li>
            <li><a href="JEEDOM-AIDE-STATS.html">Afficher les statistiques</a></li>
            <li><a href="JEEDOM-AIDE-STATS TEMPS.html">Affichage des informations de durée sur les widgets info (binaire, numérique)</a></li>
            <li><a href="JEEDOM-AIDE-PARA.html">Ajouter les paramétres sur un widget</a></li>
        </ul>
</blockquote>

<h1 id="Aide">Exemple Paramétrage d'un mode</h1>
<p><img src="Img/ JEEDOM-Icon_Mode - Para mode.png" alt="exemple Para" /></p>
<hr />
<h4 id="Logo">Exemple</h4>
Un Premier exemple avec le mode0 = CONFORT et le nom de l'image est "CONFORT.PNG"
<blockquote>
        <ul>
            <li><b>mode0</b> : renseigner la valeur <b>CONFORT</b></li>
            <li><b>logo0</b> : Il n'est pas necessaire de le renseigner vu que le nom du mode est identique au nom de l'image</li>
            <li><b>logo_type0</b> : Il n'est pas necessaire de le renseigner vu que l'extension de l'image est <i>png</i></li>
        </ul>
</blockquote>
Un deuxieme exemple avec le mode5 = PURGE et le nom de l'image est "puitsvide.PNG"
<blockquote>
        <ul>
            <li><b>mode5</b> : renseigner la valeur <b>PURGE</b></li>
            <li><b>logo5</b> : renseigner la valeur <b>puitsvide</b></li>
            <li><b>logo_type5</b> : Il n'est pas necessaire de le renseigner vu que l'extension de l'image est <i>png</i></li>
        </ul>
</blockquote>

<hr />
<dl>
    <a href="https://github.com/JEALG/JEEDOM-Icon_Mode/commits/master">Changelog WIDGET</a><br/>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>
</dl>
<hr />
[back](./)