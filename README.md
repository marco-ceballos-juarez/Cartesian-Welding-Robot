# Cartesian Welding Robot

<p align="center">
  <img src="mechanical/07_Media/ASM_000_CARTESIAN_ROBOT_ISO" alt="Cartesian Welding Robot" width="85%">
</p>

<p align="center">
  <strong>Open-source development of a Cartesian robotic platform for MIG/MAG wire welding applications.</strong>
</p>

<p align="center">
  Based on the <a href="https://wiki.printnc.info/en/home">PrintNC open-source CNC project</a>, adapted and extended for robotic welding applications.
</p>

<p align="center">
  <a href="README.es.md">🇲🇽 Español</a>
  <a href="README.md">🇬🇧 English</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Open%20Source-green" alt="Open Source">
  <img src="https://img.shields.io/badge/Platform-Cartesian%20Robot-blue" alt="Cartesian Robot">
  <img src="https://img.shields.io/badge/Application-MIG%2FMAG%20Welding-orange" alt="MIG/MAG Welding">
  <img src="https://img.shields.io/badge/Status-Under%20Development-yellow" alt="Under Development">
</p>

---

## Overview

The **Cartesian Welding Robot** is an open-source project focused on the design, development, and integration of a Cartesian robotic platform for **MIG/MAG welding using a continuously fed wire electrode (wire welding)**.

The mechanical architecture is based on the [PrintNC project](https://github.com/PrintNC/PrintNC), an open-source CNC machine design. Its original structure has been adapted and extended to meet the requirements of robotic welding, incorporating modifications to the mechanical system, welding torch mounting, electronics, control software, and motion planning.

The project aims to provide an accessible and modular robotic platform that can be reproduced, modified, and further developed by researchers, students, and robotics enthusiasts.

## Project Features

- **Open-source architecture:** Based on an existing open-source CNC platform.
- **Cartesian configuration:** Three linear axes (X, Y, and Z) for positioning and a fourth rotational degree of freedom for torch orientation.
- **MIG/MAG welding:** Designed to accommodate a welding torch with continuously fed wire.
- **Modular mechanical design:** Adaptable structure using standardized and custom-manufactured components.
- **Motion planning:** Cartesian trajectory generation and coordinated axis movement.
- **Simulation:** Robot description and simulation models for development and testing.
- **Custom software:** Tools for robot operation, command interpretation, and graphical interaction.

## Repository Structure

The repository is organized into the following directories:

| Directory | Description |
|:---|:---|
| [`docs/`](docs/) | Technical documentation, project guides, diagrams, and reference material. |
| [`mechanical/`](mechanical/) | CAD models, mechanical assemblies, engineering drawings, and bill of materials. |
| [`electronics/`](electronics/) | Electrical schematics, wiring diagrams, component specifications, and hardware documentation. |
| [`software/`](software/) | Robot control software, motion planning algorithms, command interpreter, and graphical user interface. |
| [`simulation/`](simulation/) | URDF robot description, simulation environments, and simulation-related resources. |
| [`experiments/`](experiments/) | Experimental procedures, test configurations, raw measurements, and processed results. |
| [`thesis/`](thesis/) | Thesis source files, technical appendices, and supporting academic material. |

### Directory Details

<details>
<summary><strong>docs/ — Documentation</strong></summary>

Contains the technical documentation associated with the project, including:

- General project documentation and development notes.
- System architecture and subsystem descriptions.
- Installation and configuration guides.
- User and operation manuals.
- Technical references and supporting material.

Documentation is maintained in both English and Spanish whenever applicable.

</details>

<details>
<summary><strong>mechanical/ — Mechanical Design</strong></summary>

Contains the complete mechanical design and CAD documentation of the robotic platform:

- Full mechanical assemblies.
- Custom-designed components and parts.
- Commercial component models and specifications.
- Engineering drawings and manufacturing documentation.
- Bill of materials (BOM).
- Design configurations, exports, and mechanical analysis.
- Visual references, renders, and assembly documentation.

The mechanical design is primarily developed using SolidWorks.

</details>

<details>
<summary><strong>electronics/ — Electronics and Electrical Systems</strong></summary>

Contains the electrical and electronic documentation required for the robot:

- Electrical schematics.
- Wiring diagrams and connection layouts.
- Electronic component specifications.
- Motor drivers, power supplies, and control hardware.
- Electrical interfaces and subsystem documentation.

</details>

<details>
<summary><strong>software/ — Software and Control</strong></summary>

Contains the software developed for robot operation and control:

- Robot control and communication modules.
- Motion planning and trajectory generation.
- Command interpreter and robot instruction handling.
- Graphical user interface (GUI).
- Hardware communication and integration tools.
- Installation requirements and software documentation.

</details>

<details>
<summary><strong>simulation/ — Robot Modeling and Simulation</strong></summary>

Contains the digital representation of the robotic platform and its simulation resources:

- URDF robot description files.
- Robot kinematic model.
- Simulation project files and environments.
- Robot configurations and simulation assets.
- Trajectory testing and visualization resources.

</details>

<details>
<summary><strong>experiments/ — Experimental Validation</strong></summary>

Contains the documentation and data generated during experimental testing:

- Experimental procedures and test protocols.
- Test configurations and operating parameters.
- Raw experimental data.
- Processed data and analysis.
- Graphs, measurements, and validation results.
- Photographic and video evidence of experiments.

</details>

<details>
<summary><strong>thesis/ — Academic Documentation</strong></summary>

Contains the academic documentation associated with the development of the project:

- Thesis source files.
- Technical chapters and appendices.
- Supporting figures, tables, and references.
- Supplementary technical documentation.
- Final thesis documents and related material.

</details>

## Project Development

The development of the platform involves several interconnected areas:

1. **Mechanical Design:** Adaptation of the PrintNC architecture and development of the welding torch mounting system.
2. **Electronics Integration:** Selection and integration of motors, drivers, power supplies, and control hardware.
3. **Robot Modeling:** Development of the robot kinematic model and URDF description.
4. **Software Development:** Implementation of motion planning, command interpretation, and user interaction.
5. **Simulation and Testing:** Evaluation of robot movements and system behavior in a simulated environment.
6. **Experimental Validation:** Physical testing and evaluation of the robotic platform.

## Media

Project images, CAD renders, simulation videos, and experimental demonstrations will be added as development progresses.

<p align="center">
  <img src="docs/media/robot_isometric.png" alt="Robot CAD Isometric View" width="75%">
</p>

<p align="center">
  <em>Cartesian Welding Robot — CAD model.</em>
</p>

## Acknowledgments

This project builds upon the open-source mechanical design of [PrintNC](https://github.com/PrintNC/PrintNC). We acknowledge the original developers and contributors for making their work available to the community.

## License

License information and usage conditions will be specified here.

## Contact and Contributions

Contributions, suggestions, and technical discussions are welcome.

For questions, bug reports, or proposals, please use the repository's [Issues](../../issues) section.

---

<p align="center">
  <strong>Cartesian Welding Robot</strong><br>
  Open-source robotics development for welding applications.
</p>
