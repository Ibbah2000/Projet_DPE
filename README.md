Ce dashboard a été fait dans le cadre du [open data university challenge](https://latitudes.notion.site/Saison-4-Espace-tudiants-et-tudiantes-Open-Data-University-242ff5903e5a806c969fe369fd105aa2https://latitudes.notion.site/Saison-4-Espace-tudiants-et-tudiantes-Open-Data-University-242ff5903e5a806c969fe369fd105aa2) les bases de données proviennent de [Defis.data.gouv](https://defis.data.gouv.fr/defis/diagnostics-de-performance-energetique)

En tant qu'apprentis économistes, ce dashboard R/Flexdashboard est notre réponse concrète au défi de la performance énergétique.
Nous avons structuré cet outil pour transformer des données brutes DPE en une feuille de route claire pour la rénovation.

Le dashboard commence par un diagnostic technique précis de la répartition des classes DPE dans l'échantillon analysé.
Notre analyse quantifie rigoureusement la consommation réelle (kWh) par classe énergétique et selon le type de chauffage.

L'innovation clé réside dans la cartographie interactive, permettant de cibler les départements ayant la consommation la plus élevée.Nous avons également modélisé, via une heatmap, les gains énergétiques potentiels d'une rénovation.

Cette quantification des économies (kWh/an) par changement de classe DPE est notre outil d'aide à la décision majeur.

Tout ce que présente ce dashboard est le fruit d'un traitement de données rigoureux en plusieurs étapes :

**Préparation**: Nettoyage des données brutes, conversion des unités (MWh en kWh), et normalisation des étiquettes DPE.

**Calcul d'Indicateurs**: Création des indicateurs clés (consommation/m², statistiques descriptives) et calcul stratégique des gains potentiels de rénovation (heatmap).

**Spatialisation** : Agrégation des consommations par département et jointure des données pour la cartographie.
