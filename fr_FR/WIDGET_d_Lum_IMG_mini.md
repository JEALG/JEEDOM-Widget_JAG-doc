---
layout: default
title: JEEDOM-Luminosite-IMG-Mini
description: explication widget Luminosité-IMG-Mini
---
[back](./)
# Widget "Luminosité-IMG-Mini"

Widget pour Jeedom permettant d'afficher une icône pour une fonction de type <b>info numérique</b>
<p><img src="../img/exemple/d/lumi.png" alt="Resultat" /></p>

# A savoir
<blockquote>
<b>Afin de simplifier la gestion des images, depuis le 10/09/2019, il est nécessaire d'avoir le </b><a href="WIDGET_d_Multi_action_Defaut">Widget Dashboard : <b>Multi-action</b></a>
<b>Ce widget remplace ces widgets </b><a href="Archive_WIDGET_d_Luminosite">Archive Widget Luminosité-IMG-Mini</a>
</blockquote>

# Paramétrage
## Taille des images ou des icônes
Il est possible de spécifier la hauteur et la largeur des icônes ou images par l'ajout des paramètres optionnels suivant :
<blockquote>
    <ul>
        <li><b>Pourcentage</b> : Permet de choisir la taille en "px" ou "%" <i>(valeur par défaut : NO donc "px")</i></li>
        <ul>
            <li><i>Pourcentage = NO</i> la taille sera en "px"</li>
            <li><i>Pourcentage = YES</i> la taille sera en "%"</li>
        </ul>
        <li><b>sizeh</b> : Permet de choisir la hauteur de l'image <i>(valeur par défaut : 65)</i></li>
        <li><b>sizew</b> : Permet de choisir la largeur de l'image <i>(valeur par défaut : 70)</i></li>
    </ul>
</blockquote>

## Choix de l'icône
Pour choisir le type de visuel à afficher, il faut ajouter les paramètres optionnels suivant :
<blockquote>
    <ul>
        <li><b>logo_level1</b> : Permet de choisir l'image pour la valeur  pour le niveau 1 <i>(valeur par défaut : moon)</i></li>
        <li><b>logo_level1_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo_level1</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        <li><b>logo_level2</b> : Permet de choisir l'image pour la valeur  pour le niveau 2 <i>(valeur par défaut : cloud)</i></li>
        <li><b>logo_level2_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo_level2</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
        <li><b>logo_level3</b> : Permet de choisir l'image pour la valeur  pour le niveau 3 <i>(valeur par défaut : sun)</i></li>
        <li><b>logo_level3_type</b> : Permet de choisir <i>l'extension</i> pour l'icône/image <i>logo_level3</i> (par exemple: 'gif', 'jpg', etc.....)<i>(valeur par défaut : png)</i></li>
    </ul>
</blockquote>

## Niveau
Il est possible de modifier les niveaux
<blockquote>
    <ul>
        <li><b>level_1</b> : Niveau Bas (nuit) <i>(valeur par défaut : 20)</i></li>
        <li><b>level_2</b> : Niveau Haut (jour) <i>(valeur par défaut : 100.0)</i></li>
    </ul>
</blockquote>
## Position Légende
Il est possible de déplacer la légende
<blockquote>
    <ul>
        <li><b>leg_pos</b> = low <i>(valeur par défaut)</i></li>
        <p><img src="../img/exemple/d/lumi.png" alt="Resultat - Bas" /></p>
    </ul>
</blockquote>
<blockquote>
    <ul>
        <li><b>leg_pos</b> = right <i></i></li>
        <p><img src="../img/exemple/d/lumi_r.png" alt="Resultat - Droite" /></p>
    </ul>
</blockquote>
<blockquote>
    <ul>
        <li><b>leg_pos</b> = left</li>
        <p><img src="../img/exemple/d/lumi_l.png" alt="Resultat - Gauche" /></p>
        </ul>
</blockquote>
<blockquote>
    <ul>
        <li><b>leg_pos</b> = top</li>
        <p><img src="../img/exemple/d/lumi_t.png" alt="Resultat - Haut" /></p>
    </ul>
</blockquote>

## Autres paramétrages possible et Aide
<blockquote>
    <ul>
        <li><a href="HELP_CONFIG_INFOS.html">Aide ajout des paramètres pour un widget Info</a></li>
        <li><a href="HELP_Error.html">Paramétrage image de défaut</a></li>
        <li><a href="HELP_STATS.html">Afficher les statistiques</a></li>
        <li><a href="HELP_PARA.html">Ajouter les paramètres sur un widget</a></li>
    </ul>
</blockquote>

# Télécharger les sources
><a href="HELP_Install_Manu.html">Aide pour l'installation manuelle des widgets</a>
<br/>

<li><a href="https://github.com/JEALG/JEEDOM-Luminosite-IMG-Mini/tree/masterv4">Télécharger les sources du Widget pour le Core V4</a></li>
<li><a href="https://github.com/JEALG/JEEDOM-Luminosite-IMG-Mini/tree/master">Télécharger les sources du Widget pour le Core V3</a></li>

<hr />
# Changelog
<a href="https://github.com/JEALG/JEEDOM-Luminosite-IMG-Mini/commits/masterv4">Changelog WIDGET pour le Core V4</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Luminosite-IMG-Mini/commits/master">Changelog WIDGET pour le Core V3</a><br/>
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)