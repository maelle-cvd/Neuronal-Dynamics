# Grid Cell Continuous Attractor Network (CAN) Simulation

## Overview

This project explores how animals perform **path integration**, a process in which self-motion cues are continuously integrated to estimate position over time. A key neural substrate for spatial navigation is the **entorhinal cortex**, where **grid cells** exhibit highly regular firing patterns that form a hexagonal lattice across an environment (Hafting et al., 2005). This discovery was recognized with the 2014 Nobel Prize in Physiology or Medicine.

One prominent theoretical framework for explaining this phenomenon is the **Continuous Attractor Network (CAN)** model. These models describe how neural circuits can sustain and smoothly update localized activity “bumps” that encode spatial variables. In this project, we implement and explore a CAN-based model following the approach of Burak and Fiete (2009).

## Project Goals

The model is built incrementally to demonstrate how grid-like representations and path integration can emerge from recurrent neural dynamics:

- Construct a **1D ring attractor** supporting stable, periodic activity patterns  
- Use it to build a **1D velocity integration system**  
- Extend the architecture to a **2D neural sheet** producing multiple stable activity bumps  
- Introduce **2D velocity inputs** to simulate movement in continuous space  
- Study the impact of boundary conditions and reduce edge artifacts using biologically inspired solutions

## Implementation Notes

The project is implemented in Python. 
