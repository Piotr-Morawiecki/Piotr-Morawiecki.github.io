---
layout: archive
title: "Benchmarking of flood estimation methods"
permalink: /flood/
author_profile: true
---


This page is dedicated to my research project on assessment of fundamental differences between flood estimation methods and their consequences. It is run together with Philippe H. Trinh (University of Bath) in collaboration
with the UK's Environment Agency, and formed the basis of my PhD thesis.


Problem overview
---

<img align="right" src="/images/flood2.jpg" width="400px"/>

*Image description: Burton Fleming floods at Christmas time. (<a href="https://creativecommons.org/licenses/by-sa/2.0/" rel="license" target="_blank">CC BY-SA 2.0</a>) by Phillip Andrew Carl Taylor*

One of the key problems in flood estimation is to predict the flow in the river after an intensive rainfall. Hydrologists use a variety of methods for such predictions, ranging from physical (PDE) to conceptual to statistical models. These models are often based on different assumptions; such assumptions may be subtle and hidden, and perhaps contradictory.

The main goal of the project is to develop a rigorous mathematical framework in order to better understand the relations between different classes of models. We develop simple benchmark scenarios for coupled surface-subsurface flows. Extensive data analysis of UK catchments allowed us to estimate key non-dimensional quantities affecting the flow. The subsequent study of these models using asymptotic analysis allows us to compare their behaviours in certain limiting scenarios and extract key factors affecting the formation of peak river flows.

This intercomparison of asymptotic behaviour of different classes of models can be used as a complementary tool to computational methods for assessing flood model accuracy, and can be used to better understand their applicability limits.

Publications
---

The main part of PhD is summarised in three-part article "On the development and analysis of coupled surface-subsurface models of catchments" currently available on Arxiv, which is the first study, in which coupled surface-subsurface catchment model was solved for a benchmark scenario analytically. Links are provided below.

In **Part 1** we estimated typical size of physical catchment parameters characterising UK catchments. In **Part 2** we formulated a simple 3D catchment benchmark model and used estimates from Part 1 to show that
the model can be reduced to a 2D form. Finally, in **Part 3** we showed that in the case of overland-dominated catchments the 2D model can be further reduced to 1D form and found its approximated solution. The analytic hydrograph obtained this was can be used in future studies to understand limitations of other rainfall-runoff models.

* Part 1. Parameter estimation and sensitivity analysis of catchment properties (<a href="https://arxiv.org/abs/2211.00964">Arxiv</a>) 
* Part 2. A three-dimensional benchmark model and its properties (<a href="https://arxiv.org/abs/2211.01440">Arxiv</a>)
* Part 3. Analytical solutions and scaling laws (<a href="https://arxiv.org/abs/2211.00972">Arxiv</a>)

These three papers are reviewed by the Journal of Fluid Mechanics. We are currently preparing three more papers to demonstrate example applications of this framework in assessment of 1) Probability Distributed Model (PDM), 2) distributed Grid-to-Grid model, and 3) FEH Flood Estimation Method.

Additional materials
---

* Talk prepared for BAMC 2022

<video width="870" controls>
  <source src="/files/BAMC2022_video.mp4" type="video/mp4">
  Your browser does not support HTML video.
</video>

* Poster prepared for BAMC 2021

<object data="/files/poster.pdf" width="870" height="1200" type='application/pdf'></object>