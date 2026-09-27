---
title: "Conception automatique de structures lacunaires fractales"
collection: publications
category: thesis
permalink: /publication/2025-11-07-Conception-automatique-de-structures-lacunaires-fractales
date: 2025-11-07
venue: 'PhD thesis, Université Bourgogne Europe'
citation: ' Boris Bordeaux, "Conception automatique de structures lacunaires fractales." PhD thesis, Université Bourgogne Europe, 2025'
excerpt: "This is my PhD manuscript (in french) on automatic design of lacunar fractal structures.<br/>[Read thesis here](https://doi.org/10.70675/2439b786z7e3ez4e09z9751za698e35ee55f){:target='_blank'}"
pdf: "/files/2025-phd.pdf"
---
**Abstract:** In nature, there exist complex forms exhibiting multi-scale characteristics.
Their geometry is associated with fractals, which display similar features.
Additive manufacturing enables the development of new approaches for designing complex bio-inspired structures.
In this thesis, we aim to model fractal lacunar structures.
This raises questions regarding their representation, manipulation, and control.
To address this challenge, we employ the BC-IFS (Boundary Controlled Iterated Function System) model, which allows encoding the topology of fractals.
It is based on a subdivision process represented by an automaton and on incidence and adjacency constraints.
However, the manipulation and exploration of fractals remain a challenge.
Their design consists in imagining a self-similar shape and identifying its subdivision process in order to encode it with the BC-IFS model.
Thus, it involves imagining a form from itself, which requires both skill and experience.
Once the form is imagined, its subdivision process must be identified and translated using the BC-IFS model.
This final step demands rigor and precision depending on the number of topological constraints.

We propose two approaches for the automatic design of fractal faces (in 2D), with a view to future extension into 3D.
The first approach defines a generic subdivision process which, from input parameters, generates a family of multi-scale lacunar topologies.
This process is based on defining a fractal face from its boundary, composed of fractal edges that we classify according to their topology.
The second approach automatically defines a subdivision process from a crystallographic polyhedral circle packing.
These packings, constructed geometrically from polyhedra, define another family of topologies.
We identify a subdivision process from the initial polyhedron.
In addition, we propose algorithms that translate the subdivision processes from these two approaches into topological representations using the BC-IFS model.

We exploit these two compatible approaches to design fractal structures by assembling faces.
The BC-IFS model formalizes adjacency constraints at the assembly level, ensuring the topological consistency of the structures.
We propose design rules within a topological editor accessible to non-specialist users of fractals.

We then introduce a measure of the topological complexity of a fractal face, based on the evolution of the number of lacunae and sub-faces across iterations.
This measure converges to a limit on the attractor, which can be computed directly from the BC-IFS automaton.
Finally, we propose a generalization of crystallographic polyhedral packings.
The inversions used in their geometric construction correspond to a subdivision of the initial polyhedron.
We explored other polyhedral subdivisions to facilitate extension to 3D in future work.

[Read thesis here](https://doi.org/10.70675/2439b786z7e3ez4e09z9751za698e35ee55f){:target="_blank"}