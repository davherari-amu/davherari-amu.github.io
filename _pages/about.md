---
permalink: /
title: ""
seo_title: "David Hernández-Aristizábal – Computational Scientist, Mechanics & Biology"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /en/
---

{% include base_path %}

## Profile
I am a computational scientist with five years' experience in the
mathematical modelling of biological and mechanical systems.
I specialise in **finite element and multiphysics simulation**, from the
mathematical model to validated open-source code, and in the
**statistical design of simulation studies**.
I have published seven peer-reviewed articles (six as first author), and
I am used to working on interdisciplinary projects end to end and
communicating complex results.

I am based in **Nice, France**, and I am looking for **industrial R&D
roles** in numerical simulation, computational biology or scientific
software.

<p>
  <a href="{{ base_path }}/files/cv_david_HA.pdf" class="btn btn--primary">Download my CV (PDF)</a>
  <a href="mailto:{{ site.author.email }}" class="btn btn--info">Contact me</a>
</p>

## What I do
- **Finite element and multiphysics simulation**: nonlinear and
  moving-boundary problems, custom elements and solvers (FEniCSx,
  Code_Aster, Abaqus UEL, Gmsh).
- **Mechanobiology**: models of cell migration and cancer invasion that
  couple mechanics and biochemistry on evolving geometries.
- **Bio-inspired design**: generative design of contact interfaces based
  on the growth rules of synovial joints.
- **Design of experiments**: response-surface metamodels that show which
  parameters drive a simulated outcome.
- **Scientific computing**: simulation campaigns on computing clusters
  (Slurm, MPI), profiling and optimisation of Python code.

## Current work
I am a postdoctoral researcher at **Université Côte d'Azur**, in the
Laboratoire Jean Alexandre Dieudonné, working with Rachele Allena and
Frédéric Luton, in collaboration with Anotida Madzvamuse and Francesca
Ballatore.

I study how **tumour cells** interact with the **basement membrane**, a
thin yet stiff extracellular matrix that plays a central role in tissue
organisation and cancer invasion, and how cells squeeze through
**narrow constrictions**.
Both problems couple mechanics and biochemistry within highly
deformable, evolving domains, which I model with geometric surface
partial differential equations solved in FEniCSx.
This work has led to two first-author articles in 2026, in the
*Journal of the Royal Society Interface* and *PLOS Computational
Biology*, and to two articles in preparation.
The code for the published work is open source:
[FilopodiaToPores](https://github.com/davherari-amu/FilopodiaToPores)
and
[ConfinedCellMigration](https://github.com/davherari-amu/ConfinedCellMigration).

## How I use models
A model is a simplified description of reality, and the biological
measurements needed to fit its parameters vary strongly from one case to
another or are simply not available.
So rather than reproducing one experiment quantitatively, I use
**mathematical modelling as a comparative tool**: I explore the parameter
space systematically and define **objective metrics** to identify which
mechanisms drive the behaviour of the system.

Simulation videos are on the [Portfolio](/portfolio/) page, articles on
the [Publications](/publications/) page, and the full [CV](/cv/) is
online and [in PDF]({{ base_path }}/files/cv_david_HA.pdf).
