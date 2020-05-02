---
layout: default
title: JEEDOM-AIDE-CONFIG-INFO
description: explication Aide pour le paramétrage des widgets de type info (binaire, numérique) et action pour le plugin Alarme
---
[back](./)

# Aide pour le paramétrage des widgets de type info (binaire, numérique) et de de type action avec l'utilisation du plugin Alarme
Ici l'exemple d'un équipement fait avec le plugin Alarme
<p><img src="../img/help/config_alarm_1.png" alt="Aide 1" width="200"/></p>

Pour paramétrer les infos des widgets, il faut sur ce plugin cliquer sur <b><i>Configuration Avancée</i></b>
<p><img src="../img/help/config_alarm_2.png" alt="Aide 2" width="700"/></p>

Le paramétrage va se faire en plusieurs étapes
* <b>En rouge </b>: Le paramétrage des actions
* <b>En bleu </b>: Le paramétrage des infos
<p><img src="../img/help/config_alarm_3.png" alt="Aide 3" width="700" /></p>

# Paramétrage des actions

* Cliquer sur la roue crantée en face de la commande <b>Activer</b>  (flèche en jaune)

<p><img src="../img/help/config_alarm_4.png" alt="Aide 4" /></p>

* Ensuite sélectionner l'onglet <b><i>Affichage</i></b> (flèche en violet)<br/>
<p><img src="../img/help/config_alarm_5.png" alt="Aide 5" width="700" /></p><br/>

* Ajouter les variables ci-dessous en cliquant sur le bouton <b><i>Ajouter</i></b> (flèche en orange)<br/>
<CENTER>
    <TABLE width="60%">
        <TR>
            <th scope="col" width="50%">Nom</th>
            <th scope="col" width="50%">Valeur</th>
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

* Répéter la même opération en cliquant sur la roue crantée en face de la commande <b>Désactiver</b>  (flèche en rose)

# Paramétrage des infos

* Cliquer sur la roue crantée en face de la commande <b>Immédiat</b>  (flèche en jaune)

<p><img src="../img/help/config_alarm_6.png" alt="Aide 6" /></p>

* Ensuite sélectionner l'onglet <b><i>Affichage</i></b> (flèche en violet)<br/>
<p><img src="../img/help/config_alarm_7.png" alt="Aide 7" width="700"/></p><br/>

* Ajouter les variables ci-dessous en cliquant sur le bouton <b><i>Ajouter</i></b> (flèche en orange)<br/>
<CENTER>
    <TABLE width="60%">
        <TR>
            <th scope="col" width="50%">Nom</th>
            <th scope="col" width="50%">Valeur</th>
        </TR>
        <TR>
            <TD width="50%">logoON</TD>
            <TD width="50%">al_type0_off</TD>
        </TR>
        <TR>
            <TD width="50%">logoOFF</TD>
            <TD width="50%">al_type0_on</TD>
        </TR>
        <TR>
            <TD width="50%">dossier</TD>
            <TD width="50%">alarme</TD>
        </TR>
    </TABLE>
</CENTER>

* Répéter la même opération en cliquant sur la roue crantée en face de la commande <b>Statut</b>  (flèche en rose)

<hr />
# Changelog
<a href="https://github.com/JEALG/JEEDOM-Widget_JAG-doc/commits/master">Changelog DOC</a>

<hr />
[back](./)