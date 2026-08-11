<div align="center">

<img width="1774" height="887" alt="Awesome Physical Engineering AI" src="https://github.com/user-attachments/assets/ff0be2cf-51ed-46e7-8847-e1f592275554" />

<br>

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Last Audit](https://img.shields.io/badge/Last_Audit-August_11_2026-blue.svg)](#)

**A curated, high-signal list of AI systems for engineers working with the physical world — CAD, CAE, manufacturing, inspection, materials, robotics, and engineering agents.**

[Submit a Tool](#contributing) · [Report Broken Link](../../issues/new) · [Suggest Category](../../issues/new)

</div>

---

> [!NOTE]
> **Generative design is not automatically generative AI.**
>
> Classical topology optimization, numerical search, parametric automation, solvers, CAD kernels, slicers, robotics middleware, and digital-twin infrastructure remain valuable — but they are not labeled AI here unless a learned or agentic component is central to the listed capability.

---

## 🗺️ Physical Engineering AI Stack

Engineering AI sits on top of conventional engineering software, geometry kernels, numerical solvers, robotics frameworks, manufacturing systems, and scientific computing.

Agents, MCP servers, and specialized skills increasingly provide the interface between foundation models and those deterministic engineering systems.

<div align="center">

<img width="1672" height="941" alt="Physical Engineering AI Stack" src="https://github.com/user-attachments/assets/80436950-23c1-418f-951d-8db6e9c86562" />

</div>

---

## Availability & maturity

### Availability

| Symbol | Meaning                                           |
| ------ | ------------------------------------------------- |
| ✅      | Open source / open code                           |
| 🟡     | Mixed licensing, source-available, or open models |
| 🔒     | Proprietary / commercial                          |

### Maturity

| Label            | Meaning                                                     |
| ---------------- | ----------------------------------------------------------- |
| **Production**   | Available and documented for real engineering workflows     |
| **Preview**      | Public or vendor-supported preview; capabilities may change |
| **Active**       | Maintained project with usable code and documentation       |
| **Experimental** | Working project that still requires careful validation      |
| **Research**     | Research model, method, or implementation                   |
| **Announced**    | Publicly announced but not yet generally available          |

Vendor claims are not independent benchmarks.

Descriptions below focus on **what the system actually does to an engineering artifact or workflow**, rather than marketing language.

---

## 🌱 Open-Source Highlights

A substantial part of the most interesting engineering-AI work is open.

| Project                                                                                | Domain                          | Availability | Maturity         |
| -------------------------------------------------------------------------------------- | ------------------------------- | :----------: | ---------------- |
| [CADAM](https://github.com/Adam-CAD/CADAM)                                             | Parametric CAD generation       |       ✅      | **Active**       |
| [AgentSCAD](https://github.com/Kevoyuan/AgentSCAD)                                     | CAD generation + validation     |       ✅      | **Active**       |
| [CAD Skills](https://github.com/earthtojake/text-to-cad)                               | CAD / CAE / CAM agent skills    |       ✅      | **Active**       |
| [FreeCAD AI](https://github.com/ghbalf/freecad-ai)                                     | Conversational FreeCAD          |       ✅      | **Experimental** |
| [freecad-mcp](https://github.com/neka-nat/freecad-mcp)                                 | FreeCAD agent control           |       ✅      | **Active**       |
| [sim-cli](https://github.com/svd-ai-lab/sim-cli)                                       | Agentic simulation              |       ✅      | **Active**       |
| [Foam-Agent](https://github.com/KasperHonore/Foam-Agent)                               | Autonomous CFD                  |       ✅      | **Research**     |
| [AutoCFD](https://github.com/YYgroup/AutoCFD)                                          | LLM-driven OpenFOAM             |       ✅      | **Research**     |
| [NVIDIA PhysicsNeMo](https://github.com/NVIDIA/physicsnemo)                            | Physics ML                      |       ✅      | **Active**       |
| [Anomalib](https://github.com/open-edge-platform/anomalib)                             | Industrial anomaly detection    |       ✅      | **Active**       |
| [Obico](https://github.com/TheSpaghettiDetective/obico-server)                         | 3D-print failure detection      |       ✅      | **Active**       |
| [predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) | Condition monitoring            |       ✅      | **Active**       |
| [MatterGen](https://github.com/microsoft/mattergen)                                    | Materials generation            |       ✅      | **Research**     |
| [MatterSim](https://github.com/microsoft/mattersim)                                    | Atomistic ML                    |       ✅      | **Research**     |
| [LeRobot](https://github.com/huggingface/lerobot)                                      | Robot learning                  |       ✅      | **Active**       |
| [OpenVLA](https://github.com/openvla/openvla)                                          | Vision-language-action robotics |       ✅      | **Research**     |
| [OpenPI](https://github.com/Physical-Intelligence/openpi)                              | Robot foundation models         |      🟡      | **Research**     |
| [Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T)                                   | Robot foundation models         |       ✅      | **Research**     |
| [Octo](https://github.com/octo-models/octo)                                            | Generalist robot policies       |       ✅      | **Research**     |

> [!TIP]
> **Open source is not a separate quality tier.**
>
> Open and proprietary systems are judged by the same criteria: engineering capability, validation, reproducibility, maturity, maintenance, and usefulness.

---

## Contents

* [🎨 AI CAD & Engineering Design](#-ai-cad--engineering-design)
* [🔍 Engineering Review, Drawings & Knowledge](#-engineering-review-drawings--knowledge)
* [🧪 AI for CAE & Simulation](#-ai-for-cae--simulation)
* [⚙️ AI CAM & Manufacturing](#️-ai-cam--manufacturing)
* [👁️ Inspection & Machine Vision](#️-inspection--machine-vision)
* [🔮 Predictive Maintenance & Industrial AI](#-predictive-maintenance--industrial-ai)
* [🧱 Materials AI](#-materials-ai)
* [🤖 Robotics & Physical AI](#-robotics--physical-ai)
* [⚡ Electronics, PCB & EDA AI](#-electronics-pcb--eda-ai)
* [🔌 MCP Servers, Connectors & Agent Skills](#-mcp-servers-connectors--agent-skills)
* [📄 Research Models & Methods](#-research-models--methods)
* [📊 Benchmarks & Reality Checks](#-benchmarks--reality-checks)
* [🧰 Engineering Foundations](#-engineering-foundations)
* [🧪 Experimental / Early Projects](#-experimental--early-projects)
* [🪦 Removed / Reclassified](#-removed--reclassified)
* [📚 Learning Resources](#-learning-resources)

---

## 🎨 AI CAD & Engineering Design

Systems where AI materially creates, modifies, interprets, reconstructs, or validates engineering geometry.

**Mesh-only visual 3D generation is not treated as engineering CAD.**

### Open source

| Tool                                                     | Engineering task                                              | AI mechanism                                                     | Output / action                           | Availability | Maturity         |
| -------------------------------------------------------- | ------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------------------------------- | :----------: | ---------------- |
| [CADAM](https://github.com/Adam-CAD/CADAM)               | Natural language / image → parametric CAD                     | LLM-generated OpenSCAD plus editable parameter extraction        | SCAD, STL, DXF                            |       ✅      | **Active**       |
| [AgentSCAD](https://github.com/Kevoyuan/AgentSCAD)       | Generate and repair parametric CAD                            | LLM generation + deterministic geometry/manufacturing validation | SCAD, STL, validation artifacts           |       ✅      | **Active**       |
| [CAD Skills](https://github.com/earthtojake/text-to-cad) | Generate, inspect, modify, and validate engineering artifacts | Coding-agent skills backed by deterministic CAD tooling          | STEP, STL, 3MF, DXF and related artifacts |       ✅      | **Active**       |
| [FreeCAD AI](https://github.com/ghbalf/freecad-ai)       | Conversational modeling inside FreeCAD                        | LLM-generated FreeCAD Python                                     | Native FreeCAD geometry                   |       ✅      | **Experimental** |

### Proprietary / hosted

| Tool                                                              | Engineering task                                  | AI mechanism                                              | Output / action                                             | Availability | Maturity       |
| ----------------------------------------------------------------- | ------------------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------- | :----------: | -------------- |
| [Zoo Design Studio + Zookeeper](https://zoo.dev/)                 | Parametric creation, modification, and inspection | LLM agent operating through KCL and Zoo geometry services | Editable parametric CAD                                     |      🔒      | **Production** |
| [Adam](https://adam.new/)                                         | CAD copilot workflows                             | Agentic reasoning plus native CAD integrations            | Feature-aware CAD edits and automation                      |      🔒      | **Production** |
| [SOLIDWORKS AI / LEO](https://www.solidworks.com/)                | Assembly analysis and assisted CAD workflows      | Product-specific AI / LLM automation                      | Native SOLIDWORKS actions and generated engineering content |      🔒      | **Production** |
| [Ansys GeomAI](https://www.ansys.com/)                            | Generate geometry concepts from reference designs | Learned geometry representation                           | New geometry concepts                                       |      🔒      | **Production** |
| [Spectral Labs SGS-1](https://www.spectrallabs.ai/research/SGS-1) | Image / mesh → structured CAD reconstruction      | Generative B-Rep / CAD reconstruction                     | STEP / B-Rep geometry                                       |      🔒      | **Research**   |

---

## 🔍 Engineering Review, Drawings & Knowledge

AI that reviews engineering artifacts, generates technical documentation, retrieves engineering knowledge, or checks drawings and CAD against engineering context.

| Tool                                               | Engineering task                             | AI mechanism                                            | Output / action                                           | Availability | Maturity       |
| -------------------------------------------------- | -------------------------------------------- | ------------------------------------------------------- | --------------------------------------------------------- | :----------: | -------------- |
| [CoLab AutoReview](https://www.colabsoftware.com/) | Automated CAD and drawing review             | Specialized review agents + deterministic checks        | Dimensions, tolerances, standards, BOM and DFM findings   |      🔒      | **Production** |
| [bananaz](https://www.bananaz.ai/)                 | CAD, drawing, BOM, and DFX review            | Engineering-focused document/CAD agents                 | Review findings, standards checks and change analysis     |      🔒      | **Production** |
| [DraftAid](https://draftaid.io/)                   | Generate fabrication drawings from 3D CAD    | AI-assisted drawing automation                          | 2D engineering drawings and exports                       |      🔒      | **Production** |
| [Leo AI](https://www.getleo.ai/)                   | Search and reason over engineering knowledge | Retrieval and reasoning over PLM/PDM/CAD/technical data | Part search, calculations and sourced engineering answers |      🔒      | **Production** |

> [!NOTE]
> This category is currently much more commercially concentrated than CAD generation or Physics ML. Weak OSS projects are not added merely to create artificial balance.

---

## 🧪 AI for CAE & Simulation

This section separates **simulation agents** from **learned physics and surrogate models**.

Traditional solvers remain in [Engineering Foundations](#-engineering-foundations).

### Open source

| Tool                                                        | Engineering task                                          | AI mechanism                                                | Output / action                            | Availability | Maturity     |
| ----------------------------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------ | :----------: | ------------ |
| [sim-cli](https://github.com/svd-ai-lab/sim-cli)            | Let coding agents operate engineering simulation software | Agent runtime + solver-specific skills + bounded execution  | Replayable simulation projects and results |       ✅      | **Active**   |
| [Foam-Agent](https://github.com/KasperHonore/Foam-Agent)    | Automate OpenFOAM CFD workflows                           | Multi-agent planning and execution                          | OpenFOAM cases, runs and results           |       ✅      | **Research** |
| [AutoCFD](https://github.com/YYgroup/AutoCFD)               | Natural language → CFD configuration                      | Fine-tuned LLM + multi-agent execution/error correction     | Executable OpenFOAM cases                  |       ✅      | **Research** |
| [NVIDIA PhysicsNeMo](https://github.com/NVIDIA/physicsnemo) | Physics-informed and data-driven surrogate modeling       | Neural operators, GNNs, transformers and related Physics ML | Trainable surrogate / Physics-ML models    |       ✅      | **Active**   |

### Proprietary

| Tool                                                 | Engineering task                                                   | AI mechanism                         | Output / action                                         | Availability | Maturity       |
| ---------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------ | ------------------------------------------------------- | :----------: | -------------- |
| [Ansys SimAI](https://www.ansys.com/products/simai)  | Predict physics on new geometries from previous simulation data    | Geometry-aware ML surrogate models   | Predicted physical fields                               |      🔒      | **Production** |
| [SimScale Engineering AI](https://www.simscale.com/) | Configure and execute simulation workflows from engineering intent | Agentic simulation workflow planning | CFD / FEA / thermal workflows and reports               |      🔒      | **Preview**    |
| [Neural Concept](https://www.neuralconcept.com/)     | Predict physical behavior from 3D geometry                         | Geometric deep learning              | Aero, thermal and structural predictions                |      🔒      | **Production** |
| [Monolith](https://www.monolithai.com/)              | Learn from test and simulation data                                | ML over engineering datasets         | Predictions, anomaly detection and test recommendations |      🔒      | **Production** |

### Physics-ML tooling

[PhysicsNeMo-CFD](https://github.com/NVIDIA/physicsnemo-cfd) · [DeepXDE](https://github.com/lululxvi/deepxde) · [neuraloperator](https://github.com/neuraloperator/neuraloperator) · [PhiFlow](https://github.com/tum-pbs/PhiFlow)

---

## ⚙️ AI CAM & Manufacturing

AI that materially generates machining strategies, CNC operations, manufacturing plans, toolpaths, setup recommendations, or cost/time estimates.

| Tool                                                           | Engineering task                  | AI mechanism                                                             | Output / action                                                 | Availability | Maturity       |
| -------------------------------------------------------------- | --------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------- | :----------: | -------------- |
| [CloudNC CAM Assist](https://www.cloudnc.com/)                 | Automate CNC programming          | Automated / learned machining strategy generation plus machining physics | 3-axis and 3+2 CAM strategies and toolpaths                     |      🔒      | **Production** |
| [Lambda Function](https://www.lambdafunction.ai/)              | CNC programming assistance        | AI over CAM and machining context                                        | Operation/setup recommendations and CAM assistance              |      🔒      | **Production** |
| [Toolpath](https://toolpath.com/)                              | DFM, estimating, and CAM planning | Feature recognition and automated machining/cost reasoning               | Manufacturing plans, tooling, cycle estimates and CAM workflows |      🔒      | **Production** |
| [Mastercam Copilot](https://www.mastercam.com/)                | Assist Mastercam programming      | Natural-language assistant tied to CAM commands and context              | Workflow guidance and command execution                         |      🔒      | **Production** |
| [Siemens NX CAM Copilot](https://plm.sw.siemens.com/en-US/nx/) | Machining strategy assistance     | Domain-specific manufacturing copilot                                    | Guided NX CAM actions and machining recommendations             |      🔒      | **Production** |

> [!WARNING]
> **This is currently one of the most commercially concentrated areas of engineering AI.**
>
> Ordinary open-source CAM software is not included merely to make the table look balanced.
>
> AI-generated machining strategies still require simulation, collision checking, tooling verification, workholding validation, and machinist approval.

---

## 👁️ Inspection & Machine Vision

Manufacturing-specific visual AI stays in Core.

Generic CV infrastructure remains in Foundations.

### Open source

| Tool                                                           | Engineering task                              | AI mechanism                           | Output / action                               | Availability | Maturity   |
| -------------------------------------------------------------- | --------------------------------------------- | -------------------------------------- | --------------------------------------------- | :----------: | ---------- |
| [Anomalib](https://github.com/open-edge-platform/anomalib)     | Industrial anomaly detection and localization | Deep-learning anomaly-detection models | Anomaly scores, localization and segmentation |       ✅      | **Active** |
| [Obico](https://github.com/TheSpaghettiDetective/obico-server) | Detect failed FDM prints                      | Deep-learning visual failure detection | Print-failure alerts and monitoring           |       ✅      | **Active** |

### Proprietary

| Tool                                        | Engineering task                   | AI mechanism                           | Output / action                                        | Availability | Maturity       |
| ------------------------------------------- | ---------------------------------- | -------------------------------------- | ------------------------------------------------------ | :----------: | -------------- |
| [Cognex AI Vision](https://www.cognex.com/) | Industrial visual inspection       | Edge learning and deep-learning vision | Pass/fail, localization, OCR and defect classification |      🔒      | **Production** |
| [Overview](https://www.overview.ai/)        | Manufacturing defect inspection    | Production vision models               | Defect detection and classification                    |      🔒      | **Production** |
| [LandingLens](https://landing.ai/)          | Train and deploy inspection models | Computer vision                        | Production inspection inference                        |      🔒      | **Production** |

---

## 🔮 Predictive Maintenance & Industrial AI

AI that learns from sensor or machine-condition data to identify faults, degradation, or future maintenance needs.

### Open source

| Tool                                                                                   | Engineering task                                 | AI mechanism                                                  | Output / action                                   | Availability | Maturity         |
| -------------------------------------------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------------------- | ------------------------------------------------- | :----------: | ---------------- |
| [predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) | Vibration and bearing diagnostics through agents | LLM tool use + signal processing + anomaly detection          | Fault diagnostics, vibration analysis and reports |       ✅      | **Active**       |
| [Machina](https://github.com/LGDiMaggio/machina)                                       | Build maintenance-oriented AI agents             | Agent framework integrating industrial maintenance tools/data | Industrial maintenance agents                     |       ✅      | **Experimental** |

### Proprietary

| Tool                                             | Engineering task                        | AI mechanism                                         | Output / action                              | Availability | Maturity       |
| ------------------------------------------------ | --------------------------------------- | ---------------------------------------------------- | -------------------------------------------- | :----------: | -------------- |
| [Augury Machine Health](https://www.augury.com/) | Machine-health diagnostics              | ML over vibration and condition data                 | Fault alerts and maintenance recommendations |      🔒      | **Production** |
| [Nanoprecise](https://nanoprecise.io/)           | Rotating-equipment condition monitoring | ML over vibration, acoustic, RPM and thermal signals | Condition and fault alerts                   |      🔒      | **Production** |

---

## 🧱 Materials AI

AI used to predict material behavior, discover candidate materials, or learn process-property relationships.

| Tool                                                | Engineering task                       | AI mechanism                           | Output / action                                                      | Availability | Maturity       |
| --------------------------------------------------- | -------------------------------------- | -------------------------------------- | -------------------------------------------------------------------- | :----------: | -------------- |
| [MatterGen](https://github.com/microsoft/mattergen) | Generate inorganic material candidates | Generative crystal/material model      | Candidate crystal structures conditioned on target properties        |       ✅      | **Research**   |
| [MatterSim](https://github.com/microsoft/mattersim) | Atomistic materials simulation         | Learned interatomic / foundation model | Energies, forces and material-behavior predictions                   |       ✅      | **Research**   |
| [Citrine Informatics](https://citrine.io/)          | Materials/process-property modeling    | Materials-specific ML                  | Property predictions, virtual experiments and candidate formulations |      🔒      | **Production** |

Materials databases and conventional analysis libraries such as Materials Project and pymatgen belong in Foundations rather than being labeled AI.

---

## 🤖 Robotics & Physical AI

AI that **perceives and acts through physical machines**.

Traditional robotics middleware and physics simulators remain in Foundations.

| Project                                                   | Engineering task                              | AI mechanism                                   | Output / action                                  | Availability | Maturity     |
| --------------------------------------------------------- | --------------------------------------------- | ---------------------------------------------- | ------------------------------------------------ | :----------: | ------------ |
| [LeRobot](https://github.com/huggingface/lerobot)         | Train and deploy learning-based robot control | Imitation learning, RL and pretrained policies | Robot policies, datasets and actions             |       ✅      | **Active**   |
| [OpenVLA](https://github.com/openvla/openvla)             | Language-conditioned robot manipulation       | Vision-Language-Action model                   | Robot actions / fine-tuned manipulation policies |       ✅      | **Research** |
| [OpenPI](https://github.com/Physical-Intelligence/openpi) | General-purpose learned robot control         | Vision-language-action / flow-based policies   | Robot action policies                            |      🟡      | **Research** |
| [Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T)      | Generalized robot and humanoid skills         | Vision-Language-Action foundation model        | Robot action trajectories and policies           |       ✅      | **Research** |
| [Octo](https://github.com/octo-models/octo)               | Generalist manipulation policies              | Transformer / diffusion robot policy           | Fine-tunable robot-control policies              |       ✅      | **Research** |

> [!NOTE]
> ROS 2, MoveIt, MuJoCo, Drake, PyBullet and classical controls remain crucial infrastructure, but are **not AI systems by themselves**.

---

## ⚡ Electronics, PCB & EDA AI

EDA is in scope when AI performs engineering design, verification, implementation, or sign-off work.

| Tool                                                                                                                               | Engineering task                       | AI mechanism                                    | Output / action                                                       | Availability | Maturity       |
| ---------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- | ----------------------------------------------- | --------------------------------------------------------------------- | :----------: | -------------- |
| [Siemens Fuse EDA AI Agent](https://news.siemens.com/en-us/siemens-fuse-eda-ai-agent/)                                             | Semiconductor, 3D-IC and PCB workflows | Domain-scoped agent architecture                | Design, verification and sign-off workflow orchestration              |      🔒      | **Production** |
| [Synopsys AgentEngineer](https://www.synopsys.com/)                                                                                | Semiconductor design and verification  | Multi-agent engineering system                  | RTL, lint, testbench and verification workflows                       |      🔒      | **Production** |
| [Cadence AuraStack AI Super Agent](https://www.cadence.com/en_US/home/tools/pcb-design-and-analysis/aurastack-ai-super-agent.html) | PCB and advanced-package engineering   | Super-agent coordinating specialized EDA agents | Planning, constraints, implementation, DFM and multiphysics workflows |      🔒      | **Announced**  |

Community KiCad agent integrations are listed under [Experimental / Early Projects](#-experimental--early-projects).

---

## 🔌 MCP Servers, Connectors & Agent Skills

**MCP is a protocol, not a quality badge.**

Official vendor integrations, mature OSS systems, and small proof-of-concepts should not be presented as equivalent.

### Official / first-party

| Connector                                                                                               | Target                 | What it exposes                                       | Availability | Maturity       |
| ------------------------------------------------------------------------------------------------------- | ---------------------- | ----------------------------------------------------- | :----------: | -------------- |
| [Autodesk Fusion MCP Server](https://www.autodesk.com/solutions/autodesk-ai/autodesk-mcp-servers)       | Fusion                 | Design context and supported feature/modeling actions |      🔒      | **Preview**    |
| [Autodesk Fusion Data MCP](https://www.autodesk.com/solutions/autodesk-ai/autodesk-mcp-servers)         | Fusion cloud data      | Project, item and design-data access                  |      🔒      | **Production** |
| [Autodesk Revit MCP Server](https://www.autodesk.com/solutions/autodesk-ai/autodesk-mcp-servers)        | Revit                  | Structured Revit model querying and inspection        |      🔒      | **Preview**    |
| [Autodesk Product Help MCP](https://www.autodesk.com/solutions/autodesk-ai/autodesk-mcp-servers)        | Autodesk documentation | Current Autodesk product documentation                |      🔒      | **Production** |
| [Autodesk Model Data Explorer MCP](https://www.autodesk.com/solutions/autodesk-ai/autodesk-mcp-servers) | AEC/model data         | Structured model-data exploration                     |      🔒      | **Production** |
| [Autodesk Fusion Automation MCP](https://www.autodesk.com/solutions/autodesk-ai/autodesk-mcp-servers)   | Fusion automation      | Planned cloud Fusion automation                       |      🔒      | **Announced**  |
| [Blender Lab MCP Server](https://www.blender.org/lab/mcp-server/)                                       | Blender                | Blender Python API and scene operations               |       ✅      | **Active**     |
| [SketchUp Connector for Claude](https://help.sketchup.com/en/sketchup-claude-connector)                 | SketchUp               | Conversational `.skp` generation                      |      🔒      | **Production** |

> [!NOTE]
> **Open protocol ≠ universal vendor support.**
>
> A connector using MCP does not guarantee that every MCP client is officially supported.

### Open-source engineering integrations

| Project                                                  | Target          | What it does                                                           | Availability | Maturity         |
| -------------------------------------------------------- | --------------- | ---------------------------------------------------------------------- | :----------: | ---------------- |
| [CAD Skills](https://github.com/earthtojake/text-to-cad) | CAD / CAE / CAM | Specialized skills for generating and validating engineering artifacts |       ✅      | **Active**       |
| [freecad-mcp](https://github.com/neka-nat/freecad-mcp)   | FreeCAD         | Model creation, inspection, Python execution and FEM-related workflows |       ✅      | **Active**       |
| [BlenderMCP](https://github.com/ahujasid/blender-mcp)    | Blender         | Community scene/object/material manipulation through MCP               |       ✅      | **Active**       |
| [Onshape MCP](https://github.com/hedless/onshape-mcp)    | Onshape         | Programmatic CAD modeling through the Onshape API                      |       ✅      | **Experimental** |
| [KiCad MCP](https://github.com/lamaalrajih/kicad-mcp)    | KiCad           | PCB/electronics access through MCP                                     |       ✅      | **Experimental** |
| [STK-MCP](https://github.com/alti3/stk-mcp)              | Ansys / AGI STK | Digital mission-engineering workflows                                  |       ✅      | **Experimental** |

### Safety for engineering agents

Agents that can modify CAD, simulation inputs, BOMs, CAM data, or machine instructions should be used with copies or version history, explicit human approval for destructive changes, deterministic geometry and solver checks, manufacturing simulation where available, and inspection of generated scripts, toolpaths, and machine parameters before execution.

---

## 📄 Research Models & Methods

### CAD generation and reconstruction

| Work                                              | Year / venue           | Contribution                                                                    |
| ------------------------------------------------- | ---------------------- | ------------------------------------------------------------------------------- |
| [Cadrille](https://arxiv.org/abs/2505.22914)      | ICLR 2026 Oral         | Multimodal CAD reconstruction from point clouds, images and text with online RL |
| [ToolCAD](https://arxiv.org/abs/2604.07960)       | 2026                   | Tool-using LLM agents for text-to-CAD                                           |
| [CAD-Llama](https://arxiv.org/abs/2505.04481)     | CVPR 2025              | LLM framework for parametric CAD command generation                             |
| [Text2CAD](https://arxiv.org/abs/2409.17106)      | NeurIPS 2024 Spotlight | Sequential parametric CAD generation from natural language                      |
| [BrepGen](https://arxiv.org/abs/2401.15563)       | 2024                   | Diffusion-based B-Rep generation                                                |
| [DeepCAD](https://github.com/ChrisWu1997/DeepCAD) | ICCV 2021              | Historical CAD command-sequence generation baseline                             |
| [ASSEMCAD](https://arxiv.org/abs/2607.05123)      | 2026                   | Assembly-oriented CAD generation with connection/mating structure               |

### Physics-aware and agentic simulation

| Work                                               | Year | Contribution                             |
| -------------------------------------------------- | ---- | ---------------------------------------- |
| [MetaOpenFOAM](https://arxiv.org/abs/2407.21320)   | 2024 | Early multi-agent framework for OpenFOAM |
| [OpenFOAMGPT](https://arxiv.org/abs/2501.06327)    | 2025 | RAG-augmented OpenFOAM assistant         |
| [Foam-Agent 2.0](https://arxiv.org/abs/2509.18178) | 2025 | Composable multi-agent OpenFOAM workflow |
| [ChatCFD](https://arxiv.org/abs/2506.02019)        | 2025 | End-to-end CFD agent                     |
| [CFDagent](https://arxiv.org/abs/2507.23693)       | 2025 | Autonomous multi-agent CFD workflow      |

---

## 📊 Benchmarks & Reality Checks

Engineering AI should be evaluated on **engineering correctness**, not only visual similarity.

| Benchmark                                          | What it tests                                               | Why it matters                                                          |
| -------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------------------- |
| [CADBench](https://arxiv.org/abs/2605.10873)       | Large-scale CAD reconstruction across increasing complexity | Shows degradation as parametric and geometric complexity increases      |
| [BenchCAD](https://arxiv.org/abs/2605.10865)       | Execution-verified industrial-style CAD programs            | Tests whether generated CAD executes and preserves parametric structure |
| [Text2CAD-Bench](https://arxiv.org/abs/2605.18430) | Text-to-CAD from simple to complex topology                 | Separates primitive success from robust feature generation              |
| [MUSE](https://arxiv.org/abs/2605.28579)           | Manufacturability, functionality and assemblability         | Evaluates engineering usefulness rather than appearance alone           |

> [!CAUTION]
> **Text-to-CAD is not solved.**
>
> Current systems are useful for simple geometry, repetitive operations, design exploration, and agent-assisted workflows.
>
> Complex feature history, constraints, assemblies, design intent, and manufacturing-ready CAD remain significantly harder than producing a visually plausible 3D shape.

---

## 🧰 Engineering Foundations

These are important building blocks for engineering AI systems, but **they are not presented as AI products**.

<details>
<summary><b>CAD kernels, modelers, and programmatic CAD</b></summary>

* [FreeCAD](https://www.freecad.org/)
* [CadQuery](https://github.com/CadQuery/cadquery)
* [build123d](https://github.com/gumyr/build123d)
* [OpenCASCADE / OCCT](https://dev.opencascade.org/)
* [OpenSCAD](https://openscad.org/)
* [KCL](https://zoo.dev/)
* [PartCAD](https://github.com/openvmp/partcad)

</details>

<details>
<summary><b>CAE solvers, meshing, and visualization</b></summary>

* [OpenFOAM](https://www.openfoam.com/)
* [CalculiX](http://www.calculix.de/)
* [Elmer](https://www.elmerfem.org/)
* [FEniCS](https://fenicsproject.org/)
* [SU2](https://su2code.github.io/)
* [MFEM](https://mfem.org/)
* [Gmsh](https://gmsh.info/)
* [ParaView](https://www.paraview.org/)
* [PyVista](https://docs.pyvista.org/)
* [VTK](https://vtk.org/)

</details>

<details>
<summary><b>Robotics, dynamics, and controls</b></summary>

* [ROS 2](https://docs.ros.org/)
* [MoveIt](https://moveit.ai/)
* [Drake](https://drake.mit.edu/)
* [MuJoCo](https://mujoco.org/)
* [PyBullet](https://pybullet.org/)
* [python-control](https://python-control.readthedocs.io/)
* [Pyslvs](https://github.com/KmolYuan/Pyslvs-UI)

</details>

<details>
<summary><b>Scientific and engineering Python</b></summary>

* [NumPy](https://numpy.org/)
* [SciPy](https://scipy.org/)
* [SymPy](https://www.sympy.org/)
* [pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [pint](https://github.com/hgrecco/pint)
* [CoolProp](https://github.com/CoolProp/CoolProp)
* [fluids](https://github.com/CalebBell/fluids)
* [thermo](https://github.com/CalebBell/thermo)
* [handcalcs](https://github.com/connorferster/handcalcs)
* [sectionproperties](https://github.com/robbievanleeuwen/section-properties)
* [structuralcodes](https://github.com/fib-international/structuralcodes)
* [PyNite](https://github.com/JWock82/PyNite)

</details>

<details>
<summary><b>Computer vision infrastructure</b></summary>

* [OpenCV](https://github.com/opencv/opencv)
* [Ultralytics YOLO](https://github.com/ultralytics/ultralytics)
* [Roboflow Inference](https://github.com/roboflow/inference)
* [Roboflow Supervision](https://github.com/roboflow/supervision)
* [NVIDIA DeepStream](https://developer.nvidia.com/deepstream-sdk)

</details>

<details>
<summary><b>Additive manufacturing infrastructure</b></summary>

* [PrusaSlicer](https://github.com/prusa3d/PrusaSlicer)
* [CuraEngine](https://github.com/Ultimaker/CuraEngine)
* [OctoPrint](https://github.com/OctoPrint/OctoPrint)
* [Materialise Magics](https://www.materialise.com/en/industrial/software/magics)

</details>

<details>
<summary><b>Digital twin and engineering-data infrastructure</b></summary>

* [Eclipse Ditto](https://github.com/eclipse-ditto/ditto)
* [Azure Digital Twins](https://azure.microsoft.com/en-us/products/digital-twins)
* [AWS IoT TwinMaker](https://aws.amazon.com/iot-twinmaker/)
* [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/)
* [OpenBOM](https://www.openbom.com/)
* [Aras Innovator](https://www.aras.com/)

</details>

<details>
<summary><b>Materials data and analysis</b></summary>

* [Materials Project](https://materialsproject.org/)
* [pymatgen](https://github.com/materialsproject/pymatgen)
* [MatWeb](https://www.matweb.com/)
* [chemicals](https://github.com/CalebBell/chemicals)

</details>

---

## 🧪 Experimental / Early Projects

Projects worth watching, but not yet presented at the same maturity level as production or established open projects.

| Project                                                                       | Target     | Why it is here                              |
| ----------------------------------------------------------------------------- | ---------- | ------------------------------------------- |
| [SolidworksMCP-TS](https://github.com/vespo92/SolidworksMCP-TS)               | SolidWorks | Community COM/MCP bridge                    |
| [mcp-server-solidworks](https://github.com/eyfel/mcp-server-solidworks)       | SolidWorks | Alternative community SolidWorks MCP        |
| [Jarvis Onshape MCP](https://github.com/ReshefElisha/jarvis-onshape-mcp)      | Onshape    | Agentic FeatureScript-oriented layer        |
| [openfoam-mcp-server](https://github.com/webworn/openfoam-mcp-server)         | OpenFOAM   | LLM/MCP interface with educational focus    |
| [cadquery-mcp-server](https://github.com/rishigundakaram/cadquery-mcp-server) | CadQuery   | Natural-language parametric CAD experiments |
| [mcp-cadquery](https://github.com/bertvanbrakel/mcp-cadquery)                 | CadQuery   | Script execution and part-library workflows |

> Inclusion here means **worth watching**, not production endorsement.

---

<a id="removed--reclassified"></a>

<details>
<summary><b>🪦 Removed / Reclassified</b> — click to expand</summary>

<br>

This is the project's curation history: entries that were removed, moved to Foundations, superseded, or reclassified so they do not silently return in future updates.

| Entry / class                                               | Decision                                      | Reason                                                                    |
| ----------------------------------------------------------- | --------------------------------------------- | ------------------------------------------------------------------------- |
| Classical topology optimization / generic generative design | **Reclassified**                              | Numerical optimization is not automatically AI                            |
| Rules-only DFM systems                                      | **Reclassified**                              | Deterministic engineering automation is useful but not automatically AI   |
| Generic instant quoting                                     | **Removed unless AI mechanism is documented** | Automatic CAD analysis and pricing alone do not establish AI              |
| ROS 2 / MoveIt / MuJoCo / Drake / PyBullet                  | **Foundations**                               | Robotics infrastructure rather than AI systems                            |
| FreeCAD / CadQuery / build123d / OCCT / OpenSCAD            | **Foundations**                               | CAD substrates used by engineering agents                                 |
| OpenFOAM / CalculiX / FEniCS / Gmsh / ParaView              | **Foundations**                               | Simulation infrastructure                                                 |
| pint / CoolProp / fluids / handcalcs                        | **Foundations**                               | Engineering calculation libraries                                         |
| PrusaSlicer / CuraEngine / OctoPrint                        | **Foundations**                               | Additive manufacturing infrastructure                                     |
| Azure Digital Twins / Eclipse Ditto / TwinMaker             | **Foundations**                               | Digital-twin infrastructure is not inherently AI                          |
| Tripo / Meshy / Point-E                                     | **Removed from CAD Core**                     | Primarily visual / mesh generation rather than parametric engineering CAD |
| Generic LangChain / CrewAI / AutoGen entries                | **Not Core**                                  | General agent frameworks require a concrete engineering application       |
| Small abandoned demos                                       | **Removed / Experimental**                    | Repository existence alone is not sufficient evidence                     |

</details>

---

## 📚 Learning Resources

| Resource                                                                                       | Focus                                       |
| ---------------------------------------------------------------------------------------------- | ------------------------------------------- |
| [Flocode Newsletter](https://www.flocode.dev/)                                                 | Python for civil and structural engineers   |
| [Structural Python](https://www.structuralpython.com/)                                         | Automated structural-engineering toolkits   |
| [Python Libraries for Engineers](https://github.com/joreilly86/Python-Libraries-for-Engineers) | Python resources for engineers              |
| [MIT OCW: Mechanical Engineering](https://ocw.mit.edu/courses/mechanical-engineering/)         | Free mechanical-engineering courses         |
| [awesome-mecheng](https://github.com/m2n037/awesome-mecheng)                                   | General mechanical-engineering awesome list |
| [awesome-digital-twins](https://github.com/edt-community/awesome-digital-twins)                | Digital-twin resources                      |
| [Roboflow Universe](https://universe.roboflow.com/)                                            | Computer-vision datasets                    |

---

<div align="center">

## Contributing

</div>

Contributions are welcome.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

<div align="center">

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

**If this list saved you research time, star it ⭐ and share it with an engineer.**

</div>
