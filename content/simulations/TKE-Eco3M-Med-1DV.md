---
section: Simulations
nav_order: 4
title: TKE-ECO3M-1DV
---


# TKE/Eco3M-Med 1DV

People involved: Melika Baklouti (MIO), Yutong Zhang (MIO), Camille Mazoyer (MIO)

The 1DV TKE/Eco3M-Med model is a coupled physical-biogeochemical tool forced by air-sea flows. It provides a sufficiently realistic 1DV structure and seasonality of the water column to be used for a variety of applications.  Typically, this tool can be used to develop or improve the biogeochemical model, to test new formulations or parameterisations, or to study biogeochemical processes and their interaction with vertical physics. The very reasonable calculation times (1 year simulated in less than 3 minutes) also make it possible to envisage ensemble simulations. Finally, one of the versions implemented by default reproduces the DyFaMed station in the North-West Mediterranean (Ligurian Sea), and can therefore be used for validation purposes, given the large dataset available at this station in the MOOSE network.

The most recently published version of Eco3M-MED is described in [Baklouti et al (2021)](https://doi.org/10.1016/j.pocean.2021.102634). However, a publication presenting the most recent version, which has benefited from an overhaul of the parameterisation strategy to make the whole even more coherent, is currently being written.

The vertical spatial resolution is the same as that of the NEMOMED12 model, based on z-coordinate, with cell thickness increasing with depth (from 1 m near the surface to 300 m deep).

The new parametrisation strategy is designed to deduce as many parameters as possible from each other, so that only a much smaller set of independent parameters need be set. It should be noted that this strategy is facilitated by the use of a representation of organisms in terms of abundance (in addition to biomass), which makes it possible to use different conservation laws, allometry, etc. It will be described in an article in preparation.

Before the 1DV configurations of TKE-ECO3M-1DV are published on a specific repository, you can learn more on ECO3M [here](https://github.com/Eco3M).
