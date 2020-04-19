---
layout: default
title: JEEDOM-AIDE Script
description: Script
---
[back](./)
# Prérequis
<blockquote>
Pour utiliser ce script, il faut d'abord installer en ssh
</blockquote>
<pre><code>
    sudo pip3 install git+git://github.com/HR/github-clone#egg=ghclone
</code></pre>

# Script Pour le core V3
## Script Update dossier Image

Ce script va copier les images dans le bon dossier du plugin Widget

> * Script update image Widget Master Core V3 JAG
> * Mise à jour du script : 20200419

<pre><code>
    cd /var/www/html/plugins/widget/core/template/dashboard/
    sudo ghclone https://github.com/JEALG/JEEDOM-Multi_action-Defaut/tree/master/cmd.action.other.Multi-action-Defaut
    sudo chown -R www-data:www-data /var/www/html/plugins/widget/core/template/
    sudo chmod 740 /var/www/html/plugins/widget/core/template/
</code></pre>

## Script pour récupérer les widgets
Ce script va copier l'ensemble de mes widgets
### Les widgets pour le Dashboard
> * Script update code Widget Master Core V3 JAG
> * Mise à jour du script : 20200419
<pre><code>
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Barometre/master/cmd.info.numeric.Barometre.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Barometre.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Batterie-EeDomus/master/cmd.info.numeric.Batterie-EeDomus.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Batterie-EeDomus.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Batterie-telldusBattery/master/cmd.info.numeric.Batterie-telldusBattery.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Batterie-telldusBattery.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Biroute_vent/master/cmd.info.numeric.Biroute_vent.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Biroute_vent.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Fenetre/master/cmd.info.numeric.Fenetre.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Fenetre.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Humidite-Goutte_eau/master/cmd.info.numeric.Humidite-Goutte_eau.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Humidite-Goutte_eau.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Icon_Mode/master/cmd.info.string.Icon_Mode.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.string.Icon_Mode.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Luminosite-IMG-Mini/master/cmd.info.numeric.Luminosite-IMG-Mini.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Luminosite-IMG-Mini.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Multi_action-Defaut/master/cmd.action.other.Multi-action-Defaut.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.action.other.Multi-action-Defaut.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Multi_info-Binaire/master/cmd.info.binary.Multiinfo-Binaire.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.binary.Multiinfo-Binaire.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Point-rosee/master/cmd.info.numeric.pointrosee.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.pointrosee.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Store-banne/master/cmd.info.numeric.Store-banne.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Store-banne.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Store-Velux-num/master/cmd.info.numeric.Store-VELUX.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Store-VELUX.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Tendance-Baro/master/cmd.info.numeric.Tendance-Baro.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Tendance-Baro.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-Thermometre/master/cmd.info.numeric.Temperature_thermometre.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.info.numeric.Temperature_thermometre.html
    wget https://raw.githubusercontent.com/JEALG/JEEDOM-VoyantMulticouleur/master/cmd.action.other.VoyantMulticouleur.html -O /var/www/html/plugins/widget/core/template/dashboard/cmd.action.other.VoyantMulticouleur.html
    cd /var/www/html/plugins/widget/core/template/dashboard/
    sudo chown -R www-data:www-data /var/www/html/plugins/widget/core/template/
    sudo chmod 740 /var/www/html/plugins/widget/core/template/
</code></pre>

# Script Pour le core V4
## Script Update dossier Image

Ce script va copier les images dans le bon dossier du plugin Widget

> * Script update image Widget Master Core V4 JAG
> * Mise à jour du script : 20200419

<pre><code>
    cd /var/www/html/data/customTemplates/dashboard/
    sudo ghclone https://github.com/JEALG/JEEDOM-Multi_action-Defaut/tree/masterv4/cmd.action.other.Multi-action-Defaut
    sudo chown -R www-data:www-data /var/www/html/data/customTemplates/dashboard/
    sudo chmod 740 /var/www/html/data/customTemplates/dashboard/
</code></pre>


<hr />
# Changelog
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)