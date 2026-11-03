<img src="https://feascript.github.io/FEAScript-website/assets/feascript-logo.png" width="80" alt="FEAScript Logo">

# FEAScript-Scribbler-examples

This repository showcases a collection of finite-element analysis (FEA) examples built with [FEAScript](https://feascript.com/) and designed to run on [Scribbler](https://scribbler.live/), an interactive JavaScript notebook environment with pre-loaded scientific libraries.

You can also explore and run these examples live on [Scribbler Hub](https://hub.scribbler.live/portfolio/#!nikoscham/FEAScript-Scribbler-examples).

## Examples

### Creeping Flow (creepingFlowScript)

- **Lid-Driven Cavity Creeping Flow**: 2D steady Stokes (incompressible creeping flow) simulation in a rectangular cavity with no-slip walls and a moving top lid, solved with Taylor-Hood mixed finite elements (Q2/Q1).

### Front Propagation (frontPropagationScript)

- **Solidification Front Propagation in a 2D Domain**: 2D steady-state eikonal equation problem modeling the movement of a solidification interface (e.g., in metal cooling or crystal growth), with constant-value boundary conditions on three sides and zero-gradient on the remaining boundary.

### General Form PDE (generalFormPDEScript)

- **Advection-Diffusion with a Gaussian Source Term**: 1D advection-diffusion problem with a source term, demonstrating the use of constant value and zero-gradient boundary conditions.

### Heat Transfer (heatConductionScript)

- **Heat Conduction Through a Wall**: 1D heat transfer with convection and constant temperature boundary conditions.
- **Heat Conduction in a 2D Fin**: 2D heat transfer in a cooling fin with symmetry, convection, and constant-temperature boundaries.

Read the full Scribbler blog post regarding the heat transfer examples: [Heat Transfer Finite Element Simulations in JavaScript using FEAScript](https://scribbler.live/2025/08/25/Heat-Transfer-Finite-Element-Simulations-in-JavaScript-using-FEAScript.html).

## License

The examples in this repository are released under the [MIT license](LICENSE). Note that the core library of FEAScript is distributed under the terms of the [MIT license](https://github.com/FEAScript/FEAScript-core/blob/main/LICENSE).
