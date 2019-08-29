---
layout: default
title: JEEDOM-Multi_action-Defaut
description: Explication widget Multi-action
---
[back](./)
# Widget "Multi-action" 

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>action ON/OFF</b>
<blockquote>
    Ce widget regroupe l'ensemble des différentes images de mes widgets
</blockquote>

<p><img src="Img/RESULTAT - JEEDOM-Chaudiere-Activation.png" alt="Resultat" /></p>
<blockquote>
    Le widget inclus plusieurs icônes dans des sous dossiers
</blockquote>

<h1 id="Type de paramètre">Type de paramètre</h1>
<hr />
<h4 id="Logo">Choix de l'icône</h4>
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
        <ul>
            <li><b>logoON</b> : Permet de choisir l'image pour la valeur ON<i>(valeur par défaut : day)</i></li>
            <li><b>logoON_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoON</i>(par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
            <li><b>logoOFF</b> : Permet de choisir l'image pour la valeur OFF<i>(valeur par défaut : night)</i></li>
            <li><b>logoOFF_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logoOFF</i>(par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        </ul>
</blockquote>

<h4 id="Dossier">Sous dossier</h4>
Il possible d'ajouter de mettre les images dans des sous dossiers, (la variable est valable pour l'ensemble des valeurs)
<blockquote>
        <ul>
            <li><b>dossier</b> : Nom du dossier (Par défaut : Divers)</li>
        </ul>
        <ul>
            Liste des dossiers
        <li>Alarme</li>
        <p><img src="Img/VISUEL%20-%20JEEDOM-Multi-Alarme.png" alt="Visuels" /></p>
        <li>Chauffage</li>
        <p><img src="Img/VISUEL%20-%20JEEDOM-Multi-Chauffage.png" alt="Visuels" /></p>
        <li>Divers</li>
        <p><img src="Img/VISUEL%20-%20JEEDOM-Multi-Divers.png" alt="Visuels" /></p>
        <li>Eau</li>
        <p><img src="Img/VISUEL%20-%20JEEDOM-Multi-Eau.png" alt="Visuels" /></p>
        <li>FibaroOeil</li>
        <p><img src="Img/VISUEL%20-%20JEEDOM-Multi-FibaroOeil.png" alt="Visuels" /></p>
        <li>Lampe</li>
        <p><img src="Img/VISUEL%20-%20JEEDOM-Multi-Lampe.png" alt="Visuels" /></p>
        <li>Prise</li>
        <p><img src="Img/VISUEL%20-%20JEEDOM-Multi-Prise.png" alt="Visuels" /></p>
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

<h4 id="Aider">Autres paramétrages possible et Aide</h4>
<blockquote>
        <ul>
            <li><a href="./JEEDOM-AIDE-CONFIG-ACTION.html">Aide pour le paramétrage des widgets de type action</a></li>
            <li><a href="JEEDOM-AIDE-STATS.html">Afficher les statistiques</a></li>
            <li><a href="JEEDOM-AIDE-PARA.html">Ajouter les paramétres sur un widget</a></li>
        </ul>
</blockquote>
    
<h1 id="Add img">Ajout d'image</h1>
<hr />
<blockquote>
        Il est possible d'inclure d'autres icônes dans le widget.<br/>
        Le nommage des images n'est pas normalisé sur ce widget
        <ul>
            <li><a href="./JEEDOM-AIDE-ADD_IMG.html">Ajouter des images dans un widget</a></li>
        </ul>
</blockquote>

<hr />
<dl>
    <dt>Mise à jour JAG - 20190829<br/>
    <a href="https://github.com/JEALG/JEEDOM-Multi_action-Defaut/commits/master">Changelog WIDGET</a><br/>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a></dt>
</dl>
<hr />
[back](./)