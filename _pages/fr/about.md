---
permalink: /fr/
title: ""
seo_title: "David Hernández-Aristizábal – Simulation numérique, mécanique et biologie"
description: "Docteur en simulation numérique à Nice : éléments finis et multiphysique, mécanobiologie, plans d'expériences. Post-doctorant à l'Université Côte d'Azur, à la recherche d'un poste de R&D en entreprise."
author_profile: true
---

{% include base_path %}

## Profil
Docteur avec cinq ans d'expérience dans la modélisation mathématique de
systèmes biologiques et mécaniques, je suis spécialiste de la
**simulation par éléments finis et multiphysique**, du modèle
mathématique jusqu'au code open source validé, et de la
**conception statistique d'études de simulation**.
Auteur de sept publications dans des revues à comité de lecture (dont
six en premier auteur), j'ai l'habitude de mener des projets
interdisciplinaires de bout en bout et de communiquer des résultats
complexes.

Je suis basé à **Nice** et je recherche un **poste de R&D en
entreprise** en simulation numérique, biologie computationnelle ou
logiciel scientifique.

<p>
  <a href="{{ base_path }}/files/cv_david_HA_fr.pdf" class="btn btn--primary">Télécharger mon CV (PDF)</a>
  <a href="mailto:{{ site.author.email }}" class="btn btn--info">Me contacter</a>
</p>

## Ce que je fais
- **Simulation par éléments finis et multiphysique** : problèmes non
  linéaires et à frontière mobile, éléments et solveurs sur mesure
  (FEniCSx, Code_Aster, Abaqus UEL, Gmsh).
- **Mécanobiologie** : modèles de migration cellulaire et d'invasion
  tumorale qui couplent mécanique et biochimie sur des géométries
  évolutives.
- **Conception bio-inspirée** : conception générative d'interfaces de
  contact à partir des règles de croissance des articulations
  synoviales.
- **Plans d'expériences** : métamodèles de surface de réponse qui
  montrent quels paramètres déterminent un résultat simulé.
- **Calcul scientifique** : campagnes de simulation sur clusters de
  calcul (Slurm, MPI), profilage et optimisation de code Python.

## Travaux actuels
Je suis post-doctorant à l'**Université Côte d'Azur**, au Laboratoire
Jean Alexandre Dieudonné, où je travaille avec Rachele Allena et
Frédéric Luton, en collaboration avec Anotida Madzvamuse et Francesca
Ballatore.

J'étudie comment les **cellules tumorales** interagissent avec la
**lame basale**, une matrice extracellulaire fine mais rigide qui joue
un rôle central dans l'organisation des tissus et dans l'invasion
tumorale, et comment les cellules se faufilent à travers des
**constrictions étroites**.
Ces deux problèmes couplent mécanique et biochimie dans des domaines
très déformables et évolutifs, que je modélise par des équations aux
dérivées partielles sur surfaces géométriques résolues avec FEniCSx.
Ces travaux ont donné lieu à deux articles en premier auteur en 2026,
dans le *Journal of the Royal Society Interface* et dans *PLOS
Computational Biology*, et à deux articles en préparation.
Le code des travaux publiés est open source :
[FilopodiaToPores](https://github.com/davherari-amu/FilopodiaToPores)
et
[ConfinedCellMigration](https://github.com/davherari-amu/ConfinedCellMigration).

## Ma façon d'utiliser les modèles
Un modèle est une description simplifiée de la réalité, et les mesures
biologiques nécessaires pour en ajuster les paramètres varient
fortement d'un cas à l'autre, quand elles existent.
Plutôt que de reproduire quantitativement une expérience, j'utilise
donc la **modélisation mathématique comme outil comparatif** :
j'explore systématiquement l'espace des paramètres et je définis des
**métriques objectives** pour identifier les mécanismes qui pilotent le
comportement du système.

Les vidéos de simulation sont sur la page [Portfolio](/fr/portfolio/),
les articles sur la page [Publications](/fr/publications/), et le
[CV](/fr/cv/) complet est en ligne et
[en PDF]({{ base_path }}/files/cv_david_HA_fr.pdf).
