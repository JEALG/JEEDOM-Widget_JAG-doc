---
layout: default
lang: fr_FR
title: Jeedom | Plugin Rosee Changelog
---

# Info
## Description
Ce plugin permet d'obtenir le point de rosée pour savoir si l'herbe sera mouillée le matin, ou bien en hiver desavoir s'il va falloir gratter le pare-brise. Pour fonctionner, on doit indiquer sélectionner un équipement de température, d'humidité et de pression (extérieures, bien-sûr…)

[Documentation](https://jealg.github.io/plugin-rosee/#language#/)

## Info sur les mises à jour
>*Important : en cas de mise à jour disponible pour laquelle il n’y a pas d’information dans cette section, c’est qu’elle n’intègre aucune nouveauté majeure. Cela peut être un ajout de documentation, une correction de documentation, des traductions ou bien de la correction de bugs mineurs.*

# Version 20200430
- Correction ajout widget core par défaut sur les nouveaux équipements

# Version 20200418
- Ajout calcul "Tendance Météo"
- Nettoyage log
- Corrections bugs
- Corrections bug sur le choix d'équipement obligatoire
- Ajout Cron 10/15/Heures
- Remplacement Cron5 par Cron30 (les calculs se feront par défaut toutes les 30 minutes)
>**Info : Penser à vérifier que le cron 30 est actif si non il faut l'activer**
- Ajout widget core pour les commandes (uniquement pour les nouveaux équipements)
- Ajout widget pour la tendance (uniquement pour le Core V4 et les nouveaux équipements)

# Version 20200409
- Séparation des calculs
- Nettoyage des infos dans les logs
- Ajout bouton pour recréer les commandes
- Résolution Bug Liste déroulante choix calcul vide
- Masquage des paramètres non nécessaire suivant le mode de calcul
- Modification création des commandes cela tient compte désormais du mode de calcul
- Suppression de certains calculs intermédiaires
- Affectation valeur Min et Max sur le "Message numérique"

>*Info : Penser à sauvegarder chaque équipement

# Version 20200226
- Le point de givre est égal à 5 si la température dépasse 5°
- Possibilité de sélectionner uniquement une partie du calcul (Rosée et givre, Humidité absolue, Givre, Point de rosée)
- Ajout offset sur la température (valeur par défaut : 0)

# Version 20200210
- Le point de givre est égal à la température quand la température est supérieure à 10°C

# Version 20200209

>*Info : Changement de l'auteur du plugin, merci @claude.metzger*

- Ajout de log supplémentaire en mode DEBUG
- Nettoyage du code
- Nouveau calcul pour la gestion de l'alerte givre
- Ajout d'un message pour le type de givre ainsi que d'une valeur numérique suivant le code <a href="https://pon.fr/dzvents-alerte-givre-et-calcul-humidite-absolue/">https://pon.fr/dzvents-alerte-givre-et-calcul-humidite-absolue</a>
    >- CAS N°0 : Message =  *Aucun risque de Givre*, Alerte givre = *0*, Message numérique = *0*
    >- CAS N°1 : Message =  *Givre peu probable malgré la température*, Alerte givre = *1*, Message numérique = *1*
    >- CAS N°2 : Message =  *Risque de givre*, Alerte givre = *1*, Message numérique = *2*
    >- CAS N°3 : Message =  *Givre, Présence de givre*, Alerte givre = *1*, Message numérique = *3*
- Changement du logo du plugin merci @mich0111
- Correction type de générique
- Posibilité d'enregistrer l'équipement sans les champs obligatoires si l'équipement n'est pas actif
- Modification affichage des commandes
    >- Ajout la posibilité d'inverser les commandes binaires
    >- Suppression de l'historique sur les commandes messages
- Ajout des nouvelles commandes en automatique sans recréer les commandes (Merci à Kiboost et à Mips)
- Modification du type de données pour les seuils => Uniquement numérique
- Ajout d'un seuil d'humidité absolue pour le calcul de l'alerte de givre
- Pas de calcul des infos de givres si la température est supérieure à 10°C

    >*Remarque : Il est obligatoire de sauvegarder chaque équipement pour avoir les nouvelles commandes*

# Version 3.3.2
- Ajout de log supplémentaire en mode DEBUG
- Suppression visibilité pour le calcul du point de rosée et du point de givrage

# Version 3.3.1
- Correction Documentation

# Version 3.3
- Correction Bug

# Version 3.2
- Ajout d’un cron 30 (Merci à kiboost)
- Amélioration de l'affichage pour le Core V4 (Merci à kiboost)
- Possibilité de renommer les commandes (Merci à kiboost)
- Correction des historiques (Merci à kiboost)
- Commande Refresh (sur la tuile, scénario etc) (Merci à kiboost)
- Amélioration des logs
- Correction type de generic
- Correction Bug : l'actualisation des données ne se fait plus si l'équipement est désactivé
- Les alertes sont visible par défaut (plus de masquage si l'alerte est à 0)
- Nettoyage des dossiers (Merci à kiboost)
- Mise à jour de la documentation

>*Remarque : Il est conseillé de supprimer le plugin et ensuite le réinstaller*

# Version 3.1
- La recherche des cmd pour mise à jour ne se fait plus par getConfiguration('data') mais par leur logicalId. Les cmd perdent leur data de configuration. (merci à  jpty)

# Version 3.0
- Support de PHP 7.3
- Migration vers font-awesome 5
- Migration affichage au format core V4

# Version 2.1
- Correction affichage point de rosée et givre defaillants

# Version 2.0
- Mise à jour pour compatibilité V3 Jeedom

# Version 1.5.2
- Correction de bug dans rosee.class.php dans l'appel de la fonction cron15() (merci à mika-nt28 et Mika)

# Version 1.5.1
- Correction de bug dans la prise en compte du seuil d’alerte rosée

# Version 1.5
- Gestion des alertes rosée et givre par changement d’état (merci Toregreb)

# Version 1.4
- Seuil d’alerte du point de rosée configurable dans Informations. Valeur par défaut 2°C

# Version 1.3.1
- Réglage du seuil d’alerte du point de rosée et du point de givrage à 2°C (dépression du point de rosée)

# Version 1.3

- Ajout d’une alerte point de rosée et d’une alerte point de givrage

# Version 1.2
- Selection de la temperature et de l’humidité (possibles par un bouton de recherche) (merci Lunarok)

# Version 1.1
- Ajout du point de givre

# Version 1.0
- Création du plugin
