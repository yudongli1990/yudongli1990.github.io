---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Metallurgical Materials Engineering, The University of Alabama, 2019
* M.S. in Metallurgical Engineering, Northeastern University(CN), 2014
* B.S. in Metallurgical Engineering, Northeastern University(CN), 2012

Skills
======

| Materials/Chemical Processing                                 | Materials characterization                      | Modelling/Programming                           |
|:--------------------------------------------------------------|:------------------------------------------------|:------------------------------------------------|
| Multiphase Reaction Kinetics Analysis                         | XRD (Rietveld Analysis)                         | ANSYS Fluent(UDF/UDS) / ICEM-CFD / Workbench    |
| Reactor Design/construction                                   | SEM / EDS / EBSD                                | OpenFOAM / LIGGGHTS / CFDEM / LAMMPS / ParaView |
| Polymer/ceramic coating/brazing                               | DSC / TGA / FTIR / RAMAN                        | SolidWorks / Salome / MeshLab                   |
| Heat transfer / Electrochemical / reaction kinetics modelling | Electrochemical Testing (CV / CA / EIS / Tafel) | C / C++ / Python / Matlab                       |


Work experience
======

* Fall 2018: Student Assistant , The University of Alabama High Performance Computing
  * Supercomputer system administration/troubleshooting at the University of Alabama High Performance Computing (UAHPC) group
  * Studied GPU computing performance with CUDA using Matlab and LAMMPS.
  * Provided user support on software (ANSYS Fluent, OpenFOAM, LAMMPS).
  
* Summer 2018: Apprentice Intern-Material Science Engineer, Kennametal
  * Lead a R&D project to develop polymer-ceramics composite for low temperature wear-resistant coating. The coating developed is 3~4 time better than competitors.
  * Studied effect of epoxy formulation, bonding between epoxy and different ceramics (carbides, oxides), and filler addition (carbide and oxide powders/fibers) on coating performance
  * Tested coating performance (abrasion/erosion/corrosion). Microstructure of coating was analyzed using KEYENCE 3D microscope
  * Lead a Process Hazard Analysis (PHA) committee. Developed procedures in handling hazardous chemicals.

Research experience
======


  
* Research Assistant, The University of Alabama (Aug. 2014 - May 2018)

  _Dissertation: Experimental and numerical study of the reduction of silica in a thermal plasma reactor_
  * Constructed and improved an in-house thermal plasma reactor system (Phoenix Solutions Corp. PT-50C) for direct methane reduction of oxides (SiO2, Fe2O3) to produce ultra-fine carbides and composites.
  * Designed/conducted experiments to establish a correlation between the reactor temperature profile with operating parameters (plasma power and gas flow).
  * Quantified products (addressing amorphous SiO2) using advanced XRD quantitative phase analysis.
  * Developed a new heterogeneous reaction kinetic rate expression to model CH4–SiO2 (gas-solid) reaction kinetics in the reactor. Designed/conducted experiments to parameterize the kinetic rate equation.
  * Developed and validated a multi-physics CFD model to study the transport phenomena in the reactor.
  * Developed customized algorithms to implement heterogeneous chemical reaction kinetics for particle-gas interaction and plasma nozzle boundary condition using UDFs and DPM-UDS.
  * Optimized particle combustion kinetics parameters for product prediction by implementing a custom algorithm to integrate Matlab with ANSYS Fluent.

  _Class Projects:_
  * Reaction kinetics study of SiO2 reduction by carbon using TGA/DSC. A solid-solid reaction model was proposed.
  * Developed aluminum alloy strip casting CFD model using ANSYS Fluent for a twin-roller caster. Pull speed influence on the temperature distribution was studied.
  * Developed FEA model for an impact deformation/failure process in cold spray using Abaqus.
  
  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
