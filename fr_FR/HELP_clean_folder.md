---
layout: default
title: Nettoyage des dossiers
description: Nettoyage des dossiers
---
[back](./)
# Infos
## Rappel
<blockquote>
Avant d'effectuer cette manipulation, il est conseillé de faire une sauvegarde de la Jeedom
Tous mes widgets nécessitent d'avoir le widget <b><i>dashboard Multi-action</i></b> pour avoir les images.
Je vous propose de faire un nettoyage des dossiers

</blockquote>

# Plugin nécessaire
<blockquote>
Il faut installer le plugin Jeexplorer
    Attention : Comme tout explorateur de fichiers, celui-ci vous permet d'accéder et d'éditer tous les fichiers présents dans le répertoire racine de Jeedom.
    Attention donc aux mauvaises manipulations qui pourraient rendre votre Jeedom complètement inopérant !
</blockquote>

* <a href="https://www.jeedom.com/market/index.php?v=d&p=market&type=plugin&categorie=programming&&name=JeeXplorer">Lien Market vers le plugin</a>
* <a href="https://kiboost.github.io/jeedom_docs/plugins/jeexplorer/fr_FR/">Lien vers la doc du plugin</a>

## Opération préalable

<blockquote>
    <ul>
        <li>Faire une sauvegarde de Jeedom</li>
        <li>Vérifier que vous avez les dernières versions des widgets</li>
    </ul>
</blockquote>

# Nettoyage des dossiers
## Dossiers à nettoyer
<CENTER>
    <TABLE width="100%">
        <TR>
            <th scope="col" width="26%">Type de Représentation</th>
            <th scope="col" width="37%">Pour le Core V4</th>
            <th scope="col" width="37%">Pour le Core V3</th>
        </TR>
        <TR>
            <TD width="26%">Dashboard</TD>
            <TD width="37%">data/customTemplates/dashboard/</TD>
            <TD width="37%">plugins/widget/core/template/dashboard/</TD>
        </TR>
        <TR>
            <TD width="26%">Mobile</TD>
            <TD width="37%">data/customTemplates/mobile/</TD>
            <TD width="37%">plugins/widget/core/template/mobile/</TD>
        </TR>
    </TABLE>
</CENTER>

## Nettoyage
<ul>
    <li>Ouvrir le plugin <b>JeeXplorer</b></li>
    <ul>
        <li>se rendre dans le dossier </li>
        <li>Supprimer ou exporter les dossiers suivants :</li>
        <blockquote>
            <ul>
                <li>cmd.info.numeric.Barometre</li>
                <li>cmd.info.numeric.Biroute_vent</li>
                <li>cmd.info.numeric.Fenetre</li>
                <li>cmd.info.numeric.Fenetre</li>
                <li>cmd.info.numeric.Humidite-Goutte_eau</li>
                <li>cmd.info.string.Icon_Mode</li>
                <li>cmd.info.numeric.Luminosite-IMG-Mini</li>
                <li>cmd.info.binary.Multi info - Binaire</li>
                <li>cmd.info.numeric.pointrosee</li>
                <li>cmd.info.string.Season</li>
                <li>cmd.info.numeric.Store-banne</li>
                <li>cmd.info.numeric.Tendance-Baro</li>
                <li>cmd.info.numeric.Temperature_thermometre</li>
            </ul>
        </blockquote>
    </ul>
</ul>

<hr />
[back](./)