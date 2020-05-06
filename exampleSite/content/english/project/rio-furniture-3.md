---
title: 'Notre mission '
description: 'Présentation et définition '
image: "/images/mission.png"
bg_image: "/images/space_earth.jpg"
category: Général
information:
- label: Date de début
  info: septembre 2017
- label: Fin de phase A
  info: Mai 2018
- label: Fin de phase B
  info: mai 2020

---
## Notre mission

Le domaine spatial, à l’origine porté par des motivations essentiellement politiques et militaires, a trouvé depuis une dizaine d’années un nouveau souffle avec l’émergence du “NewSpace”, une démocratisation du milieu qui s’illustre, entre autres, par la présence de nombreux projets de satellites développés par des équipes étudiantes. Citons par exemple le projet X-CubeSat développé à l’École polytechnique et lancé en 2017. Notre projet s’inscrit dans sa continuité.

**IonSat est un projet du Centre spatial étudiant (CSEP) de l’École polytechnique**, en partenariat avec le CNES, visant à concevoir, placer et maintenir en orbite basse (jusqu’à une orbite circulaire à 250km d’altitude) un CubeSat équipé d’un moteur à propulsion ionique à l’iode développé par la start-up ThrustMe.

Ce projet ambitieux (nous comptons être un des premiers satellites étudiants à propulsion ionique mis en orbite) comporte une importante valeur ajoutée technologique et scientifique, qui suit une tendance récente dans le secteur spatial se manifestant par un intérêt croissant porté aux orbites très basses (VLEO = Very Low Earth Orbit). Les avantages potentiels de ces orbites sont nombreux (temps de latence des communications réduit, meilleure résolution, coûts de lancement moindres, etc.) mais ces altitudes sont pour l’instant peu explorées en raisons de nombreuses inconnues (importance de la traînée, comportement des propulseurs ioniques dans l’atmosphère,...). Le motivation première d’IonSat est donc de défier la traînée atmosphérique à une altitude peu connue, réalisant ainsi une démonstration technologique.

En outre, nous souhaitons renforcer l’intérêt scientifique de la mission en intégrant une charge utile scientifique. Un partenariat avec le laboratoire belge VKI est à l’étude et permettrait à notre satellite d’étudier les conséquences de la corrosion de la structure par dépôt d’iode, liée à l’utilisation du moteur. L’ajout d’autres expériences embarquées est en cours d’étude.

Le projet a démarré en 2017 dans le cadre du PSC (Projet scientifique collectif) proposé aux étudiants de 2e année. Deux promotions successives (X2016 et X2017) ont apporté leur contribution, dont la définition de mission, l’étude de faisabilité et le design préliminaire pour le satellite. L’objectif de notre équipe, constitué d’élèves de la promotion X2018, est d’effectuer un design détaillé à partir du travail de nos prédécesseurs, et de commencer la construction de certaines parties du satellite avant de passer le relais à la promotion suivante. Sur le long terme, nous visons un lancement entre 2021 et 2023.

## Caractère innovant du projet

La plupart des CubeSats ont une orbite déterminée par leur lanceur et sur laquelle ils ne peuvent influer. Aujourd’hui, les rares CubeSats propulsés appartiennent aux agences gouvernementales de taille conséquente (comme la NASA) ; et la commercialisation de solutions comme celle testée sur IonSat permettrait à de nombreuses entreprises d’effectuer des missions jusque-là réservées aux plus gros satellites.

En outre, le **choix de la VLEO** (Very Low Earth Orbit), au cœur de la mission IonSat, constitue sa spécificité majeure. Cet aspect a été évoqué plus haut : les très basses orbites sont actuellement peu explorées et exploitées, mais font l’objet depuis quelque temps d’une attention renouvelée. Le projet serait donc à la pointe d’une nouvelle tendance dans le domaine spatial.

Un des intérêts principaux des CubeSats est la normalisation de leur format, qui permet d’acheter des composants «sur étagère», sans avoir à les réaliser en interne ou à financer de développements dédiés, ce qui permet d’accélérer le développement tout en diminuant les coûts et les risques. La problématique devient alors de choisir les composants adaptés parmi l’offre disponible sur le marché et de les intégrer correctement à la structure du nanosatellite.

L’utilisation d’un **moteur ionique à l’iode** contribue également au caractère innovant du projet. Les moteurs conventionnels (à propulsion chimique) fournissent, en peu de temps, une accélération importante, mais utilisent pour cela de grandes quantités de carburant. A l’inverse, la poussée fournie par un moteur électrique est très faible mais possède un rendement (impulsion spécifique) bien plus élevé que les moteurs chimiques. Ce type de **propulsion est par conséquent idéal** pour effectuer des corrections d'orientation ou de trajectoire de satellites en orbite, permettant un gain substantiel de poids et de durabilité.

Adaptable pour des CubeSats, cette technologie prend deux formes principales : les moteurs ioniques à grille et les propulseurs à effet Hall. Le moteur NPT30i de ThrustMe, dont IonSat sera équipé, appartient à la première catégorie et possède la particularité de ne pas fonctionner au Xénon (comme il est d’usage pour ce type de moteurs) mais au diiode solide. L’analyse de la mission IonSat pourra donc fournir des résultats utiles concernant cette nouvelle technologie de propulsion.

Concernant la définition de la mission, les deux plus grands défis techniques qui se posent sont :

\-La puissance électrique : consommation en pic supérieure 50 W. Le standard pour les CubeSats est d’environ 1W pour 1U, alors qu’IonSat possède un rapport proche de 10W/U, ce qui est relativement inédit. Les conséquences sont critiques pour le dimensionnement du satellite : besoin de collecter et de stocker beaucoup d’énergie (panneaux solaires et batteries de grandes dimensions), fortes contraintes thermiques et électromagnétiques,...

\-Le contrôle d’orbite : la mission a pour objectif de défier la traînée atmosphérique, à des altitudes bien plus basses que la plupart des missions usuelles. A 250 km d’altitude, l’espérance de vie du satellite est de l’ordre de la journée si le moteur est éteint. Il y a donc un fort besoin d’automatisation ou de réactivité, qui intervient de manière critique dans le design (notamment sur le choix en télécommunications ou sur la conception du mode survie du satellite).

A ceci vient s’ajouter un aspect déterminant, concernant la gestion du projet : **le temps de développement doit être aussi court que possible** (pour satisfaire le critère de démonstration technologique), et le coût relativement peu élevé ; alors que l’équipe sera majoritairement constituée d’étudiants peu formés, et pour le moment attachés au projet pour un an uniquement. Cela a un impact sur la solution technique retenue (composants achetés sur étagère) et sur l’organisation générale du développement (lien entre les promotions : tuteur, importance de la passation, de la documentation,...).