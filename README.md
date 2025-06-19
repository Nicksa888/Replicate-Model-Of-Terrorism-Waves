Spatial Replicate INLA Models of Terrorism

This repository contains R code and model outputs for analyzing the spatial behavior of terrorist groups using Integrated Nested Laplace Approximation (INLA). The models apply INLA's replicate feature to compare the spatial patterns of attacks by terrorist groups across Rapoport’s Third (New Left) and Fourth (Religious) Waves.

Key Features
Replicate INLA models for comparing spatial random effects across ideological waves.

Travel time to nearest city and distance to international borders used as structural spatial covariates.

Robust statistical framework for isolating ideological differences in spatial attack strategies while controlling for structural constraints.

Focus on Middle East and North Africa (MENA) region using geolocated terrorism data.

Research Question
Do terrorist groups from different ideological waves operate under similar structural constraints (e.g., urban proximity, border access) but produce different spatial patterns of violence?

Requirements
R

INLA package (INLA::inla)

Tidyverse (for data wrangling and visualization)
