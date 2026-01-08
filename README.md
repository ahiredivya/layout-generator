# layout-generator

## Overview : 
This project automatically generates multiple building layouts on a
200m × 140m rectangular site while respecting a set of geometric rules.

## Site Setup
- Site size: 200m × 140m
- Tower A: 30m × 20m
- Tower B: 20m × 20m

## Placement Rules Implemented
1. Buildings remain fully inside the site
2. Minimum 15m distance between buildings
3. Minimum 10m distance from site boundary
4. Each Tower A has at least one Tower B within 60m
5. Central 40m × 40m plaza with no overlap


## Approach
A random search–based approach is used to explore multiple layout
configurations. Invalid layouts are rejected based on rule checks.
Valid layouts are visualized using Matplotlib.
