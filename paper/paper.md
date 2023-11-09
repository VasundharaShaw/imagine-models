---
title: 'The IMAGINE Model library'
tags:
- C++
- Python
- astronomy
- Galactic magnetic field
- Milky Way
authors:
- name: Sebastian Hutschenreuter
  orcid: 0000-0002-6952-9688
  affiliation: "1, 2"

affiliations:
- name: Institute for Astronomy (IfA), University of Vienna, T\"urkenschanzstrasse 17, A-1180 Vienna
  index: 1
- name: Department of Astrophysics/IMAPP, Radboud University, P.O. Box 9010,6500 GL Nijmegen, The Netherlands
  index: 2
date: x x 2023
bibliography: paper.bib
---

# Statement of need

The Galactic magnetic field (GMF) is an important component of the Milky Way, 
both for its dynamical evolution 
It is furthermore connected 

Foreground, Axions  

Constraining the GMF is a delicate task as all available tracers are convolved with other components of the Milky Way, e.g. with the thermal electrons in the case of Faraday rotation, relativistic electrons in case of synchrotron radiation or dust properties in the case of (optical and infrared) stellar polarisation.

Over the decades, the community has produced several models of the large scale GMF constrained by different tracers. 
Additionally, more local measurements have allowed to constrain the GMF close to the sun, specifically. 

These models vary considerably between each other, highlighting the need of a holistic framework to 
To constrain the Galactic magnetic fields, 
[@Boulanger2018] IMAGINE have proposed 

The aim of the IMAGINE model interface is to 

# Features of the library

The library provides a simple interface to access the magnetic field vector at each position in Galacto-centric cartesian coordinates. 
It furthermore provides convenience functionality to evaluate the models on regular and irregular grids, as well as point clouds.  
Optionally (and requiring the installation of additional packages), the library gives the 
Also 

The library is written in C++ and interfaced to Python using [@pybind112017]. 
Some features are directly implemented on the pytthn side, and hence not 

Why: unified interface, bridges to hammurabi, CRPRopa, nifty8, imagine 




# Acknowledgements

We acknowledge ... 
Cite pybind11, autodiff, fftw

# References