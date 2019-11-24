---
layout: default
title: JEEDOM-AIDE Nettoyage des dossiers
description: Nettoyage des dossiers
---
[back](../)
# Rappel 
<blockquote>
Avant d'effectuer cette manipulation, il est conseillé de faire une sauvegarde de la Jeedon
Depuis quelques temps, je suis en train de migrer toutes les images vers le widget <i>dashboard Multi-action</i> les dossiers avec les anciennes versions restent sur la jeedom et prenne de la place.
Je vous propose de faire un nettoyage des dossiers

</blockquote>

# Plugin necessaire
<blockquote>
Il faut installer le plugin Jeexplorer
    Attention : Comme tout explorateur de fichiers, celui-ci vous permet d'accéder et d'éditer tous les fichiers présent dans le répertoire racine de Jeedom. Attention donc aux mauvaises manipulations qui pourraient rendre votre Jeedom complètement inopérant !
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
<ul>
    <li>Ouvrir le plugin <b>JeeXplorer</b></li>
    <ul>
        <li>se rendre dans le dossier <i>plugins/widget/core/template/dashboard/</i></li>
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
    <li>Faire la même chose pour les dossier suivant :</li>
    <blockquote>
        <ul>
            <li>plugins/widget/core/template/mobile</li>
        </ul>
    </blockquote>
    
    
    
  <li><b>Pour la version core V4, les widgets sont copiés dans les dossiers suivant :</b></li>
    <blockquote>
        <ul>
            <li>data/customTemplates/dashboard/</li>
            <li>data/customTemplates/mobile/</li>
        </ul>
    </blockquote>
</ul>

<hr />
<dl>
    <a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>
</dl>
<hr />
[back](../)