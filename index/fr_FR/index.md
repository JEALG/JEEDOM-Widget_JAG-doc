---
layout: default
title: Liste des plugins
lang: fr_FR
---

Protocole
========

EIB / KNX (eibd)
----------------

Ce plugin permet de communiquer entre Jeedom et votre installation KNX.
Jeedom deviendra donc un équipement de votre installation.
Des fonctions d'auto-configuration (auto-include, parser ETS5) ont été implémentées pour permettre une mise en place rapide.

- [Documentation]({{site.baseurl}}/eibd/{{page.lang}})
- [Changelog]({{site.baseurl}}/eibd/{{page.lang}}/changelog)

Global Cache (globalcache)
--------------------------

Ce plugin a pour objet de connecter Jeedom à vos équipements __global cache__.

- [Documentation]({{site.baseurl}}/globalcache/{{page.lang}})
- [Changelog]({{site.baseurl}}/globalcache/{{page.lang}}/changelog)

Mochad - X10 (mochad)
--------------------

Ce plugin permet de gerer vos equipements x10 grace a votre CM15 ou CM19

- [Documentation]({{site.baseurl}}/mochad/{{page.lang}})
- [Changelog]({{site.baseurl}}/mochad/{{page.lang}}/changelog)

Automatisation
==============

Arrosage automatique (arrosageAuto)
-----------------------------------
Ce plugin a pour objet de gérer facilement et automatiquement votre arrosage automatique.

- [Documentation]({{site.baseurl}}/arrosageAuto/{{page.lang}})
- [Changelog]({{site.baseurl}}/arrosageAuto/{{page.lang}}/changelog)

Gestion du Chauffe Eau (ChauffeEau)
----------------------------------

Ce plugin permet de gérer votre chauffe-eau.
Il va estimer le temps nécessaire pour une chauffe complète de votre ballon.
Si votre installation est équipée d'une sonde de température, le plugin arrêtera la chauffe dès qu'il atteindra sa température désirée.
Après l'heure programmée, le plugin arrêtera la chauffe et attendra le prochain créneau, reduit du temps de chauffage calculé.

Le plugin embarque une régulation configurable par hystérésis.

- [Documentation]({{site.baseurl}}/ChauffeEau/{{page.lang}})
- [Changelog]({{site.baseurl}}/ChauffeEau/{{page.lang}}/changelog)

Volet proportionel (voletProp)
------------------------------

Ce plugin a pour but de permetre de gerer ses volets de maniere proportionnel

- [Documentation]({{site.baseurl}}/voletProp/{{page.lang}})
- [Changelog]({{site.baseurl}}/voletProp/{{page.lang}}/changelog)

Gestion de Volets (Volets)
--------------------------

Ce plugin a pour objectif de gérer facilement et automatiquement vos volets.

- [Documentation]({{site.baseurl}}/Volets/{{page.lang}})
- [Changelog]({{site.baseurl}}/Volets/{{page.lang}}/changelog)

Communication
============

Client SIP (clientSIP)
----------------------
Ce plugin a pour but de conneter jeedom a notre reseau Sip

- [Documentation]({{site.baseurl}}/clientSIP/{{page.lang}})
- [Changelog]({{site.baseurl}}/clientSIP/{{page.lang}}/changelog)

Free SMS (FreeSms)
------------------

Ce plugin vous permet d'envoyer des sms à votre portable Free via le service de notification proposé par Free.

- [Documentation]({{site.baseurl}}/FreeSms/{{page.lang}})
- [Changelog]({{site.baseurl}}/FreeSms/{{page.lang}}/changelog)

Energie
=======

Production Energie (prosommateur)
---------------------------------

L’autoconsommation est le bute dans la production d’énergie. Ce plugin est la pour vous y aidé en contrôlant les activations.

- [Documentation]({{site.baseurl}}/prosommateur/{{page.lang}})
- [Changelog]({{site.baseurl}}/prosommateur/{{page.lang}}/changelog)

Santée
======

Withings / Nokia (withings)
---------------------------

Plugin pour appareils Withings / Nokia, il permet de récupérer les informations des balances withings (poids, masse graisseuse mais pas le CO2) et des bracelets (distance, nombre de pas, heures de sommeil profond, heures de sommeil léger...)

- [Documentation]({{site.baseurl}}/withings/{{page.lang}})
- [Changelog]({{site.baseurl}}/withings/{{page.lang}}/changelog)

Monitoring
==========

Freebox Crystal (freeCrystal)
-----------------------------

Ce plugin permet de récupérer les informations de votre Freebox Crystal.
Certains éléments sont rendus actifs par Jeedom (Redémarrage des Freebox, présence DHCP) mais nécessitent une installation supplémentaire sur votre serveur.

- [Documentation]({{site.baseurl}}/freeCrystal/{{page.lang}})
- [Changelog]({{site.baseurl}}/freeCrystal/{{page.lang}}/changelog)

Freebox OS (Freebox_OS)
-----------------------

Ce plugin permet de récupérer les informations de votre freeboxOS (Serveur Freebox Révolution ou 4K ou DELTA).

- [Documentation]({{site.baseurl}}/Freebox_OS/{{page.lang}})
- [Changelog]({{site.baseurl}}/Freebox_OS/{{page.lang}}/changelog)

LibreNMS (libreNMS)
-------------------

LibreNMS est une AutoDiscovery PHP/MySQL/SNMP réseau de surveillance qui comprend la prise en charge d'une large gamme de matériel réseau et les systèmes d'exploitation, y compris Cisco, Linux, FreeBSD, Juniper, Brocade, Foundry, HP et beaucoup plus.

- [Documentation]({{site.baseurl}}/libreNMS/{{page.lang}})
- [Changelog]({{site.baseurl}}/libreNMS/{{page.lang}}/changelog)

Multimedia
=========

Télécommande Freebox mini4K (FreeboxMini4k)
------------------------------------------

Contrôler votre Freebox mini4K

- [Documentation]({{site.baseurl}}/FreeboxMini4k/{{page.lang}})
- [Changelog]({{site.baseurl}}/FreeboxMini4k/{{page.lang}}/changelog)

Freebox Révolution (telecfree)
------------------------------

Plugin pour commander le Freebox Player de la Freebox Révolution

- [Documentation]({{site.baseurl}}/telecfree/{{page.lang}})
- [Changelog]({{site.baseurl}}/telecfree/{{page.lang}}/changelog)

Plex (plex)
-----------

Contrôler vos clients plex grâce a votre domotique.
Créer des réveil, musical grâce a l'association de plex et de jeedom.

- [Documentation]({{site.baseurl}}/plex/{{page.lang}})
- [Changelog]({{site.baseurl}}/plex/{{page.lang}}/changelog)

Organisiation
=============

Réveil (reveil)
---------------
Ce plugin permet de créer des réveils.

- [Documentation]({{site.baseurl}}/reveil/{{page.lang}})
- [Changelog]({{site.baseurl}}/reveil/{{page.lang}}/changelog)

Cave à Vin (CaveVin)
--------------------

Et si on domotisait notre cave à vin !
Ce plugin Jeedom nous permet de créer virtuellement notre cave, si on veut on peut domotiser la présence de la bouteille.

- [Documentation]({{site.baseurl}}/CaveVin/{{page.lang}})
- [Changelog]({{site.baseurl}}/CaveVin/{{page.lang}}/changelog)

Confort
=======

SPA Balboa (balboa) 
-------------------
Ce plugin a pour objet de connecter Jeedom à vos Sap __balboa__.

- [Documentation]({{site.baseurl}}/balboa/{{page.lang}})
- [Changelog]({{site.baseurl}}/balboa/{{page.lang}}/changelog)

Luminothérapie (luminotherapie)
-------------------------------

Ce plugin permet de créer des ambiances lumineuse

- [Documentation]({{site.baseurl}}/luminotherapie/{{page.lang}})
- [Changelog]({{site.baseurl}}/luminotherapie/{{page.lang}}/changelog)

Sécurité
========

Face detection (facedetection) 
------------------------------

Ce plugin utilise OpenCv pour détecter les visages sur vos camera.

- [Documentation]({{site.baseurl}}/facedetection/{{page.lang}})
- [Changelog]({{site.baseurl}}/facedetection/{{page.lang}}/changelog)

Reconnaissance facial (facerecognition)
---------------------------------------

Ce plugin utilise OpenCv pour détecter et reconnaitre votre visage. Attention, toute de même aux permissions que vous accordez au plugin car on peut le tromper avec des photos … ou son jumeau

- [Documentation]({{site.baseurl}}/facerecognition/{{page.lang}})
- [Changelog]({{site.baseurl}}/facerecognition/{{page.lang}}/changelog)

Reconnaissance de chute (falldetector)
--------------------------------------

Ce plugin utilise OpenCv pour détecter et reconnaitre les situations de chute.an 9

- [Documentation]({{site.baseurl}}/falldetector/{{page.lang}})
- [Changelog]({{site.baseurl}}/falldetector/{{page.lang}}/changelog)

Motion (motion)
---------------

Motion est un logiciel de détection vidéo et qui permet de diffuser un flux vidéo via internet par le protocole HTTP. C’est une solution simple pour diffuser le flux de sa webcam en ligne ou pour détecter des mouvements dans le champ d’une caméra par exemple.
Dans ce plugin motion sera utilisé pour ces capacité de detection de mouvement

- [Documentation]({{site.baseurl}}/motion/{{page.lang}})
- [Changelog]({{site.baseurl}}/motion/{{page.lang}}/changelog)

OpenALPR (openalpr)
-------------------

Plugin permanent de faire de la reconnaissance de plaque d’immatriculation avec nos camera

> Attention avec l'usage de ce plugin
Seules les autorités publiques (les mairies notamment) peuvent filmer la voie publique.
Les particuliers ne peuvent filmer que l’intérieur de leur propriété.
Ils ne peuvent pas filmer la voie publique, y compris pour assurer la sécurité de leur véhicule garé devant leur domicile.

- [Documentation]({{site.baseurl}}/openalpr/{{page.lang}})
- [Changelog]({{site.baseurl}}/openalpr/{{page.lang}}/changelog)

Acces par QR code (QRacces)
---------------------------

Ce plugin permet de gerer une acces par QRcode.
Un Qr code est envoyé par mail a l'utilisateur autorisé

- [Documentation]({{site.baseurl}}/QRacces/{{page.lang}})
- [Changelog]({{site.baseurl}}/QRacces/{{page.lang}}/changelog)
