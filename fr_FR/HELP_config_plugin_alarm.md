---
layout: default
title: JEEDOM-AIDE-CONFIG-INFO
description: explication Aide pour le paramétrage des widgets de type info (binaire, numérique) et action pour le plugin Alarme
---
[back](./)
# Aide pour le paramétrage des widgets de type info (binaire, numérique) et de de type action avec l'utilisation du plugin Alarmw

<p><img src="../img/help/config_alarm_1.png" alt="Aide 1" /></p>

Ici l'exemple d'un équipement fait avec le plugin Alarme, Pour paramétrer les infos, il faut sur ce plugin cliquer sur "Configuration Avancée"
<p><img src="../img/help/config_alarm_2.png" alt="Aide 2" /></p>

Le paramétrage va se faire en plusieurs étapes
<p><img src="../img/help/config_alarm_3.png" alt="Aide 3" /></p>
* Paramétrage des actions
* Paramétrage des infos


# Paramétrage des actions

## Pour la commande "Activer"

<p><img src="../img/help/config_alarm_4.png" alt="Aide 4" /></p>
* Cliquer sur la roue crantée en face de la commande <b> Fléche en rouge </b>
* Ensuite dans l'onglet paramétrer les infos suivantes dans l'onglet <b><i>"Affichage"</i></b><br/>
<p><img src="../img/help/config_alarm_5.png" alt="Aide 4" /></p><br/>

* Ajouter les variables ci-dessous en cliquant sur le bouton <b><i>"Ajouter"</i></b><br/>

<CENTER>
    <TABLE width="60%">
        <TR>
            <TD width="50%">Nom</TD>
            <TD width="50%">Valeur</TD>
        </TR>
        <TR>
            <TD width="50%">logoON</TD>
            <TD width="50%">al_type1_on</TD>
        </TR>
        <TR>
            <TD width="50%">logoOFF</TD>
            <TD width="50%">al_type1_off</TD>
        </TR>
        <TR>
            <TD width="50%">dossier</TD>
            <TD width="50%">alarme</TD>
        </TR>
    </TABLE>
</CENTER>




* <b>En Rouge</b> : Sous types
	* Type : info
	* Sous-Type : Binaire

* <b>En vert</b> : Options
    * Afficher : Cocher cette case
    * Historiser : Permet d'historiser l'équipement (En option suivant les besoins)

* <b>En bleue</b> : Options
    * roue cranté permet de choisir le type de widget et les options

## Exemple de paramétrage
Voici l'exemple voulu
<p><img src="../img/exemple/d/multi_binaire.png" alt="Résultat" /></p>

## Les commandes d'action
voir l'exemple dans la doc <a href="HELP_config_action.html">Aide pour le paramétrage des widgets de type action</a>

# Choix du widget
Cliquer sur la roue crantée (voir image ci-dessous),
<p><img src="../img/AIDE_CONFIG_INFO_4.png" alt="Aide 4" /></p>

Cliquer sur affichage, sélectionner ensuite le widget voulu dans la partie bleu (grâce à la liste déroulante)
<p><img src="../img/AIDE_CONFIG_INFO_2.png" alt="Aide 2" /></p>

# Ajout des paramètres
Cliquer sur le bouton <i>Ajouter</i> pour ajouter les différents paramètres du widget, ensuite se référer sur chacun des widgets pour avoir les variables
<p><img src="../img/AIDE_CONFIG_INFO_3.png" alt="Aide 3" /></p>

<hr />
# Changelog
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)