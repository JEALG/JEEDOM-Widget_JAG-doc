---
layout: default
title: JEEDOM-AIDE Nettoyage des dossiers
description: Nettoyage des dossiers
---
[back](./)
# Nettoyage des dossiers
# Rappel
<blockquote>
Avant d'effectuer cette manipulation, il est conseillé de faire une sauvegarde de la Jeedom
Tous mes widgets necessitent d'avoir le widget <b><i>dashboard Multi-action</i></b> pour avoir les images.
Je vous propose de faire un nettoyage des dossiers

</blockquote>

# Plugin nécessaire
<blockquote>
Il faut installer le plugin Jeexplorer
    Attention : Comme tout explorateur de fichiers, celui-ci vous permet d'accéder et d'éditer tous les fichiers présent dans le répertoire racine de Jeedom.
    Attention donc aux mauvaises manipulations qui pourraient rendre votre Jeedom complètement inopérant !
</blockquote>
<ul>
    <li><a href="https://www.jeedom.com/market/index.php?v=d&p=market&type=plugin&categorie=programming&&name=JeeXplorer">Lien Market vers le plugin</a></li>
    <li><a href="https://kiboost.github.io/jeedom_docs/plugins/jeexplorer/fr_FR/">Lien vers la doc du plugin</a></li>
</ul>

# Opération préalable
<blockquote>
    <ul>
        <li>Faire une sauvegade de la jeedom</li>
        <li>Vérifier que vous avez les dernières versions des widgets</li>
    </ul>
</blockquote>

# Nettoyage des dossiers
## Dossiers à nettoyer
### Pour le Core V3
> * Dashboard : plugins/widget/core/template/dashboard/
> * Mobile : plugins/widget/core/template/mobile/

### Pour le Core V4
> * Dashboard : data/customTemplates/dashboard/
> * Mobile : data/customTemplates/mobile/

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