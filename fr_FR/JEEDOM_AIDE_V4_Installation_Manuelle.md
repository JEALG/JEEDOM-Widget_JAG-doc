---
layout: default
title: JEEDOM-AIDE Installation Manuelle des widgets V4
description: Installation Manuelle des widgets pour le core V4
---
[back](../)
# Info
<blockquote>
Comme vous le savez le plugin widget va disparaitre avec la version du Core V4. Si vous voulez continuer à utiliser mes widgets et avoir les mises à jour. 
    Voici une méthode vous permetant d'installer et de faire les mises à jour.
</blockquote>

# A Savoir
<blockquote>
Pour l'ensemble de mes widgets, il est nécessaire d'avoir le widget <b><i>JEEDOM-Multi_action-Defaut</i></b>
</blockquote>

# Récupérer les sources
Les sources sont disponible sur mon github 
<a href="https://github.com/JEALG">Mon Github</a>
Choisir le widget voulu
voici un exemple pour récupèrer les sources
<a href="https://github.com/JEALG/JEEDOM-Multi_action-Defaut">JEEDOM-Multi_action-Defaut</a>
<p><img src="AIDE_V4_Github_branche_1.png" alt="Choix Branche" /></p>
Sélectionner la branche voulu :
<blockquote>
    <ul>
        <li>Beta : Version en test</li>
        <li>Master : Version Stable pour le Core <b>V3</b></li>
        <li>MasterV4 : Version Stable pour le core <b>V4</b></li>
    </ul>
</blockquote>
Cliquer sur <i>Clone or download</i> ensuite cliquer sur <i>Download ZIP</i>
<p><img src="AIDE_V4_Github_branche_2.png" alt="Download" /></p>

# Plugin nécessaire
Il faut installer le plugin Jeexplorer
    Attention : Comme tout explorateur de fichiers, celui-ci vous permet d'accéder et d'éditer tous les fichiers présent dans le répertoire racine de Jeedom.
    Attention donc aux mauvaises manipulations qui pourraient rendre votre Jeedom complètement inopérant !
<ul>
    <li><a href="https://www.jeedom.com/market/index.php?v=d&p=market&type=plugin&categorie=programming&&name=JeeXplorer">Lien Market vers le plugin</a></li>
    <li><a href="https://kiboost.github.io/jeedom_docs/plugins/jeexplorer/fr_FR/">Lien vers la doc du plugin</a></li>   
</ul>

# Installation ou Mise à jour
Dézipper le fichier télécharger.
Se rendre dans Jeedom et ouvrir le plugin <i>Organisation/Jeexplorer</i>
Se rendre dans le dossier correspondant au type de widget
<ul>
  <b>l'ensemble des fichiers sont à copier dans les dossiers suivant :</b>
    <blockquote>
        <ul>
            <li>data/customTemplates/dashboard/</li>
            <li>data/customTemplates/mobile/ <i>Le nom des reposites de mes widgets mobile se termine par "--mobile"</i></li>
        </ul>
    </blockquote>
</ul>
<p><img src="AIDE_V4_ADD_Widget_1.png" alt="ADD" /></p>
Cliquer sur 
<p><img src="AIDE_V4_ADD_Widget_1.png" alt="ADD" /></p>
Cliquer ensuite sur <i>Sélectionner les fichiers à envoyer</i> ou pour envoyer l'ensemble des dossiers, cliquer sur <i>Choisir le dossier</i>
<p><img src="AIDE_V4_ADD_Widget_3.png" alt="ADD" /></p>
<hr />
# Télécharger les sources

# Chancelog
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](../)
