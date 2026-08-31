# HepGPU Results

Simulation results and visualizations generated with **HepGPU** for the numerical modeling of hepatitis B virus (HBV) infection and immune response in the liver.

### 1D simulations

The one-dimensional model provides a simplified representation of the spatial evolution of the infection and immune response.

#### Infection dynamics

![1D simulation](caso_1D/simulacion_1D.gif)


### 2D simulations

Two-dimensional simulations are used to investigate the influence of spatial heterogeneity and transport restrictions on infection dynamics.

#### Unobstructed domain

Simulation of the infection and immune response in a domain without internal transport barriers.

<table>
<tr>
<td align="center" width="50%">
<b>Without barrier</b>
</td>
<td align="center" width="50%">
<b>With barrier</b>
</td>
</tr>

<tr>
<td align="center">
<img src="caso_2D/simulacion_sin_barrera_negro.gif" width="100%">
</td>
<td align="center">
<img src="caso_2D/simulacion_barrera_negro.gif" width="100%">
</td>
</tr>
</table>

#### Maze-like barriers

Simulation including internal barriers that restrict transport and modify the spatial propagation of the different populations.

![2D simulation maze](caso_2D/simulacion_laberinto.gif)

### 3D simulations

Three-dimensional simulations extend the model to more complex geometries and allow the effect of heterogeneous transport and internal barriers to be investigated.

#### Elimination infection with transport barriers

![3D simulation elimination](caso_3D/eliminacion_final.gif)

#### Chronic infection

![3D simulation chronic](caso_3D/cronificacion_final.gif)

## HepGPU

The simulations presented in this repository were generated using **HepGPU**, a Python package developed for the numerical simulation of virus spread and immune response in the liver.

HepGPU source code and installation instructions are available in the main HepGPU repository.

## Authors

This repository contains results generated as part of the development and validation of HepGPU.
