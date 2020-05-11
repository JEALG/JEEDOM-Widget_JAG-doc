# Description

Ce plugin permet d'obtenir le point de rosée pour savoir si l'herbe sera mouillée le matin, ou bien en hiver savoir s'il va falloir gratter le pare-brise.
Pour fonctionner, on doit indiquer un équipement température et un équipement humidité (extérieures, bien-sûr…).

# Configuration

Le plugin ne comporte pas de configuration générale, il faut ajouter :

> - Equipement "Température"
> - Equipement "Humidité Relative"

En option
> - Equipement "Pression Atmosphérique" : Pression atmosphérique réelle sur le site. 1013.25 hPa par défaut si non renseignée.
> - Seuil (°C) : Seuil de déclenchement de l'alerte rosée, 2°C par défaut (dépression du point de rosée T°-Tr°) A ajuster en fonction des observations locales.
> - Seuil d'hunidité absolue : Seuil humidité absolue en dessous duquel il est peu probable qu'il givre, 2.8 par défaut.

# Exemple de configuration

Voici un exemple de configuration

![exemple](../images/equipement.png)
![exemple](../images/commandes.png)

# Alerte Givre
Le plugin calcule 4 niveaux d'alerte
- Cas N°0 :
    >- Calcul : Aucun cas ci-dessous couvert
    >- Alerte Givre : 0
    >- Alerte Rosée : Automatique
    >- Message numérique Givre : 0
    >- Message d'info : Aucun risque de Givrage
- Cas N°1 :
    >- Calcul : (Température <=1 et Point de Givrage <= 0) et (Humidité absolue en (gr/m3) < Seuil d'humidité absolue)
    >- Alerte Givre : 1
    >- Alerte Rosée : forcé à 0
    >- Message numérique Givre : 1
    >- Message d'info : Givre peu probable malgré la température
- Cas N°2 :
    >- Calcul : (Température <=4 et Point de Givrage <= 0.5)
    >- Alerte Givre : 1
    >- Alerte Rosée : forcé à 0
    >- Message numérique Givre : 2
    >- Message d'info : Risque de givre
- Cas N°3 :
    >- Calcul : (Température <=1 et Point de Givrage <= 0) et (Humidité absolue en (gr/m3) > Seuil d'humidité absolue)
    >- Alerte Givre : 1
    >- Alerte Rosée : forcé à 0
    >- Message numérique Givre : 3
    >- Message d'info : Givre, Présence de givre

# FAQ

-   Est-ce que le plugin s'appuie sur des API tiers ?

>Non, le plugin fait le calcul en interne par rapport à la température et l’humidité extérieure.

-   C’est quoi le point de rosée ?

>Le point de rosée ou température de rosée est la température la plus basse à laquelle une masse d'air peut être soumise, à pression et humidité données, sans qu'il se produise une formation d'eau liquide par saturation.
>
>La notion de point de rosée est une notion de base importante dans le fonctionnement des sécheurs frigorifiques d'air comprimé et de la condensation atmosphérique créant les hydrométéores. Il est une donnée déterminante dans l'isolation thermique du bâtiment qui permettra de savoir s'il y a un risque que l'humidité ambiante d'une pièce se condense en traversant les couches successives d'un mur extérieur, dans lequel chaque couche affiche un gradient de température particulier, dégressif vers l'extérieur. Le cas échéant, l'humidité qui se condense peut provoquer la détérioration de la couche dans laquelle le phénomène se produit.
(Source Wikipédia)

-   Et le point de givrage ?

>Le point de givrage, connu également comme la température du point givrage ou le point de gelée, est une donnée météorologique calculée à partir de l'humidité, la pression et la température. Le point de givrage de l'air est la température à laquelle, tout en gardant inchangées les conditions barométriques courantes, l'air devient saturé de vapeur d'eau par rapport à la glace. Le point de givrage est donc l'équivalent du point de rosée pour la condensation de la vapeur d'eau directement en cristaux de glace et non en micro-gouttelettes. C'est le phénomène de déposition, qui survient lorsque le point de givre est atteint, qui créé la gelée blanche.
>
>Le point de givrage n'est donc défini que sous le point de congélation. Il coexiste avec le point de rosée à ces températures mais comme la pression de vapeur saturante par rapport à la glace est plus faible, le point de givrage est atteint plus rapidement. La capacité hygrométrique détermine les phénomènes de saturation, plus il fait froid, moins l'air peut contenir d'humidité (humidité absolue) et les deux se rejoignent à zéro degré Celsius.
(Source Wikipédia)

# Troubleshotting

- Je n'ai pas d'informations qui remontent

>Il faut bien indiquer un équipement température et un équipement humidité pour que le calcul du point de rosée puisse se faire.
>
>On peut rechercher les équipements grace au bouton de recherche de l’équipement.

- Le point de givrage est égal à la température

>La température dépasse 10°C donc le point de givrage n'est plus calculé.
>