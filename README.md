GMIS-mfrtm

GMIS-mfrtm is a graphical user interface (GUI) designed for numerical simulations of reactive solute transport in groundwater, developed to support research in groundwater hydrology, hydrochemistry, and environmental geochemistry. This platform integrates a comprehensive simulation workflow with a focus on interactivity, modularity, and advanced visualization, enabling users to easily build and analyze complex groundwater models.

Features

Interactive Workflow: GMIS-mfrtm allows users to seamlessly go from model setup to simulation output through a four-stage workflow: parameter configuration → input generation → parallel computation → 3D post-processing.

Intuitive GUI: Built on Python-Qt with PyVista/VTK for 3D visualization, GMIS-mfrtm features a user-friendly interface that supports dynamic interaction with model grids, permeability, reaction kinetics, and boundary conditions.

Multi-Physics Integration: The platform supports coupling of flow, solute transport, chemical reactions, providing a unified view of multi-field behavior.

Customizable Models: Users can define models layer-by-layer, from grid design to material properties, boundary conditions, and chemical reactions. All settings are stored in a unified data model for traceability.

Parallel Computing: GMIS-mfrtm provides fast, parallel computation for large-scale models. The platform supports seamless integration with WSL-MPI for cross-platform simulation execution.

Advanced 3D Visualization: GMIS-mfrtm uses PyVista and VTK for advanced 3D visualization, allowing users to visualize concentration fields, flow patterns, contour surfaces, and time-series data interactively.

Cross-Platform Support: GMIS-mfrtm is compatible with Windows, macOS, and Linux, ensuring flexibility across various environments.

Key Features

User-Friendly Interface: Easy-to-use interface for model configuration, solving, and visualization.

Dynamic Visualization: Real-time display of grid structures, flow fields, concentration profiles, and more.

Comprehensive Model Configuration: Support for detailed simulation of groundwater flow, reactive transport, and environmental geochemical processes.

Parallelized Solver Integration: High-performance solver with MPI parallelization for large-scale simulations.

Data Export and Post-Processing: Supports data export in HDF5 and VTK formats for further analysis.

Installation

Clone this repository:

git clone https://github.com/your-username/gmis-mfrtm.git
cd gmis-mfrtm

Follow the instructions in the Software Environment Setup for configuring PFLOTRAN and MPI.

Usage

Model Setup: Use the graphical interface to define grid configurations, material properties, chemical reactions, boundary conditions, and other model parameters.

Run Simulation: Generate the necessary input files and launch simulations .

Visualize Results: View the output in 3D, with real-time concentration and flow field visualization.

Documentation

Detailed user instructions and technical documentation are available in the software's User Manual, which includes:

Software framework and architecture

Step-by-step usage guide

Example configurations

Advanced simulation techniques

Contributing

We welcome contributions to improve GMIS-mfrtm! To contribute, please fork the repository, make your changes, and submit a pull request.

This README provides an overview of the software’s purpose, features, installation, and usage, highlighting its strengths in simulation, interactivity, and visualization.
