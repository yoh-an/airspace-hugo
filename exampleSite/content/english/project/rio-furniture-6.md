---
title: Contrôle d'altitude
description: Comment va t-on stabiliser le satellite ?
image: "/images/altitude.png"
bg_image: "/images/altitude.png"
category: Trajectoire
information:
- label: Référent
  info: Robin Courson
- label: Mi-temps
  info: Brice Douet
- label: Mi-temps
  info: Florian Girault

---
## Contrôle d'altitude

Ce pôle possède **deux rôles fondamentaux**:

\-estimer l'altitude à partir des données fournies par les capteurs.

\-Suivre une consigne d'altitude de manière précise en agissant sur les actuateurs.

Notre problématique est posée par des **moments perturbateurs qui vont représenter un défi pendant le vol**. Cela peut être le déclenchement d'une phase de poussée du moteur ou encore la trainée en orbite basse. Les roues à réaction doivent être capables de compenser ces moments lorsque les magnéto-coupleurs sont inopérants.

Voici le plan de connexion des différents composants concernant ce pôle.

![](/images/controle_altitude.png)

Nous avons choisi une solution sur étagère de Cubespace: **CUBEADCS 3-AXIS**