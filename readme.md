<div align="center">

<img width="1774" height="887" alt="Awesome Physical Engineering AI" src="https://github.com/user-attachments/assets/ff0be2cf-51ed-46e7-8847-e1f592275554" />

<br>

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Last Audit](https://img.shields.io/badge/Last_Audit-October_22_2026-blue.svg)](docs/audits/2026-10-22.md)

**A curated, high-signal list of AI systems for engineers working with the physical world — CAD, CAE, manufacturing, inspection, materials, robotics, and engineering agents.**

[Submit a Tool](#contributing) · [Report Broken Link](https://github.com/010zx00x1/Awesome-Physical-Engineering-AI/issues/new) · [Suggest Category](https://github.com/010zx00x1/Awesome-Physical-Engineering-AI/issues/new)

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
| ✅      | Code under a declared open-source license                           |
| 🟡     | Source-available / mixed code and model terms |
| 🔒     | Proprietary / commercial                          |
| ⚪     | Public code; reuse license not verified             |

### Maturity

| Label            | Meaning                                                     |
| ---------------- | ----------------------------------------------------------- |
| **Production**   | Available and documented for real engineering workflows     |
| **Preview**      | Public or vendor-supported preview; capabilities may change |
| **Active**       | Maintained project with usable code and documentation       |
| **Experimental** | Working project that still requires careful validation      |
| **Research**     | Research model, method, or implementation                   |
| **Announced**    | Publicly announced but not yet generally available          |

Vendor claims are not independent benchmarks. **Production** describes documented availability, not certification or independently measured reliability. **Preview** includes beta and limited customer rollouts.

Code, model weights, and datasets can have different licenses. A public repository alone does not establish permission to reuse its code. Availability and maturity were reviewed on **October 22, 2026**; see the [audit notes and unresolved checks](docs/audits/2026-10-22.md).

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
| [sim-cli](https://github.com/svd-ai-lab/sim-cli) | CAE file context for agents | ✅ | **Experimental** |
| [Foam-Agent](https://github.com/csml-rpi/Foam-Agent)                               | Autonomous CFD                  |       ✅      | **Research**     |
| [AutoCFD](https://github.com/YYgroup/AutoCFD)                                          | LLM-driven OpenFOAM             |       ✅      | **Research**     |
| [NVIDIA PhysicsNeMo](https://github.com/NVIDIA/physicsnemo)                            | Physics ML                      |       ✅      | **Active**       |
| [Anomalib](https://github.com/open-edge-platform/anomalib)                             | Industrial anomaly detection    |       ✅      | **Active**       |
| [Obico](https://github.com/TheSpaghettiDetective/obico-server)                         | 3D-print failure detection      |       ✅      | **Active**       |
| [predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) | Condition monitoring            |       ✅      | **Active**       |
| [MatterGen](https://github.com/microsoft/mattergen)                                    | Materials generation            |       ✅      | **Research**     |
| [MatterSim](https://github.com/microsoft/mattersim)                                    | Atomistic ML                    |       ✅      | **Research**     |
| [LeRobot](https://github.com/huggingface/lerobot)                                      | Robot learning                  |       ✅      | **Active**       |
| [OpenVLA](https://github.com/openvla/openvla)                                          | Vision-language-action robotics |       🟡      | **Research**     |
| [OpenPI](https://github.com/Physical-Intelligence/openpi)                              | Robot foundation models         |      🟡      | **Research**     |
| [Isaac GR00T N1.7](https://github.com/NVIDIA/Isaac-GR00T)                                   | Robot foundation models         |       ✅      | **Active**     |
| [Octo](https://github.com/octo-models/octo)                                            | Generalist robot policies       |       ✅      | **Research**     |

> [!TIP]
> **Open source is not a separate quality tier.**
>
> Open and proprietary systems are judged by the same criteria: engineering capability, validation, reproducibility, maturity, maintenance, and usefulness.

---

## Contents

* [🎨 AI CAD & Engineering Design](#ai-cad-engineering-design)
* [🔍 Engineering Review, Drawings & Knowledge](#engineering-review-drawings-knowledge)
* [🧪 AI for CAE & Simulation](#ai-cae-simulation)
* [⚙️ AI CAM & Manufacturing](#ai-cam-manufacturing)
* [👁️ Inspection & Machine Vision](#inspection-machine-vision)
* [🔮 Predictive Maintenance & Industrial AI](#predictive-maintenance-industrial-ai)
* [🧱 Materials AI](#materials-ai)
* [🤖 Robotics & Physical AI](#robotics-physical-ai)
* [⚡ Electronics, PCB & EDA AI](#electronics-pcb-eda-ai)
* [🔌 MCP Servers, Connectors & Agent Skills](#mcp-connectors-agent-skills)
* [📄 Research Models & Methods](#research-models-methods)
* [📊 Benchmarks & Reality Checks](#benchmarks-reality-checks)
* [🧰 Engineering Foundations](#engineering-foundations)
* [🧪 Experimental / Early Projects](#experimental-early-projects)
* [🪦 Removed / Reclassified](#removed--reclassified)
* [📚 Learning Resources](#learning-resources)

---

<a id="ai-cad-engineering-design"></a>

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
| [Prompt2CAD](https://prompt2cad.com/) | Generate and refine dimensioned CAD from text or reference inputs | Agent-driven CAD planning, modeling, and inspection | Editable geometry, STEP/DXF/STL exports, and preliminary parts lists | 🔒 | **Production** |
| [SOLIDWORKS AI / LEO](https://www.solidworks.com/product/solidworks-design/ai-overview) | Assist modeling, assembly, and documentation workflows | Product-specific AI and virtual companions | Native CAD actions and engineering content; features depend on release | 🔒 | **Production** |
| [Ansys GeomAI](https://ansys.synopsys.com/products/ai/geomai) | Explore geometry concepts learned from reference designs | Learned geometry representation | New geometry concepts for design exploration | 🔒 | **Production** |
| [Spectral Labs SGS-1](https://www.spectrallabs.ai/research/SGS-1) | Image / mesh → structured CAD reconstruction      | Generative B-Rep / CAD reconstruction                     | STEP / B-Rep geometry                                       |      🔒      | **Research**   |

---

<a id="engineering-review-drawings-knowledge"></a>

## 🔍 Engineering Review, Drawings & Knowledge

AI that reviews engineering artifacts, generates technical documentation, retrieves engineering knowledge, or checks drawings and CAD against engineering context.

| Tool                                               | Engineering task                             | AI mechanism                                            | Output / action                                           | Availability | Maturity       |
| -------------------------------------------------- | -------------------------------------------- | ------------------------------------------------------- | --------------------------------------------------------- | :----------: | -------------- |
| [CoLab AutoReview](https://www.colabsoftware.com/product/autoreview) | Review drawings and CAD against engineering requirements | AI drawing review plus deterministic 3D checks | Annotated findings for dimensions, standards, BOM, and DFM | 🔒 | **Preview** |
| [bananaz](https://www.bananaz.ai/)                 | CAD, drawing, BOM, and DFX review            | Engineering-focused document/CAD agents                 | Review findings, standards checks and change analysis     |      🔒      | **Production** |
| [DraftAid](https://draftaid.io/)                   | Generate fabrication drawings from 3D CAD    | AI-assisted drawing automation                          | 2D engineering drawings and exports                       |      🔒      | **Production** |
| [Leo AI](https://www.getleo.ai/)                   | Search and reason over engineering knowledge | Retrieval and reasoning over PLM/PDM/CAD/technical data | Part search, calculations and sourced engineering answers |      🔒      | **Production** |

> [!NOTE]
> This category is currently much more commercially concentrated than CAD generation or Physics ML. Weak OSS projects are not added merely to create artificial balance.

---

<a id="ai-cae-simulation"></a>

## 🧪 AI for CAE & Simulation

This section separates **simulation agents** from **learned physics and surrogate models**.

Traditional solvers remain in [Engineering Foundations](#engineering-foundations). Agent-facing file readers and solver connectors are listed under [MCP Servers, Connectors & Agent Skills](#mcp-connectors-agent-skills).

### Open source

| Tool                                                        | Engineering task                                          | AI mechanism                                                | Output / action                            | Availability | Maturity     |
| ----------------------------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------ | :----------: | ------------ |
| [Foam-Agent](https://github.com/csml-rpi/Foam-Agent)    | Automate OpenFOAM CFD workflows                           | Multi-agent planning and execution                          | OpenFOAM cases, runs and results           |       ✅      | **Research** |
| [AutoCFD](https://github.com/YYgroup/AutoCFD)               | Natural language → CFD configuration                      | Fine-tuned LLM + multi-agent execution/error correction     | Executable OpenFOAM cases                  |       ✅      | **Research** |
| [AgentFEM + MCP](https://github.com/haoming-luo/agentfem) | Build and inspect finite-element studies through an AI assistant | External agent uses Python, CLI, or MCP over a deterministic FEM engine | Reproducible studies, solver results, and verification records | ✅ | **Active** |
| [NVIDIA PhysicsNeMo](https://github.com/NVIDIA/physicsnemo) | Physics-informed and data-driven surrogate modeling       | Neural operators, GNNs, transformers and related Physics ML | Trainable surrogate / Physics-ML models    |       ✅      | **Active**   |

### Proprietary

| Tool                                                 | Engineering task                                                   | AI mechanism                         | Output / action                                         | Availability | Maturity       |
| ---------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------ | ------------------------------------------------------- | :----------: | -------------- |
| [Ansys SimAI](https://ansys.synopsys.com/products/ai/simai) | Predict physics from geometry and previous simulation data | Geometry-aware ML surrogate models | Predicted physical fields; desktop Pro and cloud Premium options | 🔒 | **Production** |
| [SimScale Engineering AI](https://www.simscale.com/product/engineering-ai/) | Set up, run, and report on simulations from engineering intent | Agent operates CAD, meshing, solvers, and post-processing tools | Simulation projects, results, and reports | 🔒 | **Production** |
| [Neural Concept](https://www.neuralconcept.com/)     | Predict physical behavior from 3D geometry                         | Geometric deep learning              | Aero, thermal and structural predictions                |      🔒      | **Production** |
| [Monolith](https://www.monolithai.com/)              | Learn from test and simulation data                                | ML over engineering datasets         | Predictions, anomaly detection and test recommendations |      🔒      | **Production** |
| [Cosmon Argus](https://www.cosmon.com/) | Coordinate CAD, simulation, and PLM tasks | Engineering agent operating native tool integrations | CAD edits, simulation setup, drawings, and workflow results | 🔒 | **Production** |

### Physics-ML tooling

[PhysicsNeMo-CFD](https://github.com/NVIDIA/physicsnemo-cfd) · [DeepXDE](https://github.com/lululxvi/deepxde) · [neuraloperator](https://github.com/neuraloperator/neuraloperator) · [PhiFlow](https://github.com/tum-pbs/PhiFlow)

---

<a id="ai-cam-manufacturing"></a>

## ⚙️ AI CAM & Manufacturing

AI that materially generates machining strategies, CNC operations, manufacturing plans, toolpaths, setup recommendations, or cost/time estimates.

| Tool                                                           | Engineering task                  | AI mechanism                                                             | Output / action                                                 | Availability | Maturity       |
| -------------------------------------------------------------- | --------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------------- | :----------: | -------------- |
| [CloudNC CAM Assist](https://www.cloudnc.com/)                 | Automate CNC programming          | Automated / learned machining strategy generation plus machining physics | 3-axis and 3+2 CAM strategies and toolpaths                     |      🔒      | **Production** |
| [Lambda Function](https://www.lambdafunction.ai/)              | CNC programming assistance        | AI over CAM and machining context                                        | Operation/setup recommendations and CAM assistance              |      🔒      | **Production** |
| [Toolpath](https://toolpath.com/)                              | DFM, estimating, and CAM planning | Feature recognition and automated machining/cost reasoning               | Manufacturing plans, tooling, cycle estimates and CAM workflows |      🔒      | **Production** |
| [Mastercam Copilot](https://www.mastercam.com/solutions/add-ons/mastercam-copilot/) | Assist Mastercam programming | Natural-language help and command execution | Machine groups, operations, and feed/speed edits | 🔒 | **Production** |
| [NX X Manufacturing Chat Copilot](https://blogs.sw.siemens.com/nx-manufacturing/when-ai-becomes-your-cam-programming-partner/) | Answer NX CAM workflow and programming questions | Domain-specific conversational assistance | In-product guidance and documentation links | 🔒 | **Production** |

> [!WARNING]
> **This is currently one of the most commercially concentrated areas of engineering AI.**
>
> Ordinary open-source CAM software is not included merely to make the table look balanced.
>
> AI-generated machining strategies still require simulation, collision checking, tooling verification, workholding validation, and machinist approval.

---

<a id="inspection-machine-vision"></a>

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
| [LandingLens](https://support.landing.ai/docs/models-page)          | Train and deploy inspection models | Computer vision                        | Production inspection inference                        |      🔒      | **Production** |

---

<a id="predictive-maintenance-industrial-ai"></a>

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

The predictive-maintenance-mcp code is MIT-licensed; its bundled example vibration data has separate noncommercial terms. See the [project license](https://github.com/LGDiMaggio/predictive-maintenance-mcp/blob/main/LICENSE).

---

<a id="materials-ai"></a>

## 🧱 Materials AI

AI used to predict material behavior, discover candidate materials, or learn process-property relationships.

| Tool                                                | Engineering task                       | AI mechanism                           | Output / action                                                      | Availability | Maturity       |
| --------------------------------------------------- | -------------------------------------- | -------------------------------------- | -------------------------------------------------------------------- | :----------: | -------------- |
| [MatterGen](https://github.com/microsoft/mattergen) | Generate inorganic material candidates | Generative crystal/material model      | Candidate crystal structures conditioned on target properties        |       ✅      | **Research**   |
| [MatterSim](https://github.com/microsoft/mattersim) | Atomistic materials simulation         | Learned interatomic / foundation model | Energies, forces and material-behavior predictions                   |       ✅      | **Research**   |
| [Citrine Informatics](https://citrine.io/)          | Materials/process-property modeling    | Materials-specific ML                  | Property predictions, virtual experiments and candidate formulations |      🔒      | **Production** |

Materials databases and conventional analysis libraries such as Materials Project and pymatgen belong in Foundations rather than being labeled AI.

---

<a id="robotics-physical-ai"></a>

## 🤖 Robotics & Physical AI

AI that **perceives and acts through physical machines**.

Traditional robotics middleware and physics simulators remain in Foundations.

| Project                                                   | Engineering task                              | AI mechanism                                   | Output / action                                  | Availability | Maturity     |
| --------------------------------------------------------- | --------------------------------------------- | ---------------------------------------------- | ------------------------------------------------ | :----------: | ------------ |
| [LeRobot](https://github.com/huggingface/lerobot)         | Train and deploy learning-based robot control | Imitation learning, RL and pretrained policies | Robot policies, datasets and actions             |       ✅      | **Active**   |
| [OpenVLA](https://github.com/openvla/openvla)             | Language-conditioned robot manipulation       | Vision-Language-Action model                   | Robot actions / fine-tuned manipulation policies |       🟡      | **Research** |
| [OpenPI](https://github.com/Physical-Intelligence/openpi) | General-purpose learned robot control         | Vision-language-action / flow-based policies   | Robot action policies                            |      🟡      | **Research** |
| [Isaac GR00T N1.7](https://github.com/NVIDIA/Isaac-GR00T)      | Generalized robot and humanoid skills         | Vision-Language-Action foundation model        | Robot action trajectories and policies           |       ✅      | **Active** |
| [Octo](https://github.com/octo-models/octo)               | Generalist manipulation policies              | Transformer / diffusion robot policy           | Fine-tunable robot-control policies              |       ✅      | **Research** |

> [!NOTE]
> ROS 2, MoveIt, MuJoCo, Drake, PyBullet and classical controls remain crucial infrastructure, but are **not AI systems by themselves**.

OpenVLA uses MIT-licensed code with Llama-derived model terms. GR00T N1.7 provides a maintained GA stack, while deployment on a particular robot still requires evaluation. OpenVLA and Octo remain listed as research baselines; their latest repository pushes were March 2025 and July 2024 respectively.

---

<a id="electronics-pcb-eda-ai"></a>

## ⚡ Electronics, PCB & EDA AI

EDA is in scope when AI performs engineering design, verification, implementation, or sign-off work.

| Tool                                                                                                                               | Engineering task                       | AI mechanism                                    | Output / action                                                       | Availability | Maturity       |
| ---------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- | ----------------------------------------------- | --------------------------------------------------------------------- | :----------: | -------------- |
| [Siemens Fuse EDA AI Agent](https://www.siemens.com/en-us/products/fuse-eda-ai-system/agent/)                                             | Semiconductor, 3D-IC and PCB workflows | Domain-scoped agent architecture                | Design, verification and sign-off workflow orchestration              |      🔒      | **Production** |
| [Synopsys AgentEngineer / Autopilot](https://www.synopsys.com/ai/agentic-ai.html) | Orchestrate verification, implementation, and related engineering workflows | Domain agents coordinated through the Autopilot platform | RTL, testbench, implementation, and analysis workflows | 🔒 | **Announced** |
| [Cadence AuraStack AI Super Agent](https://www.cadence.com/en_US/home/tools/pcb-design-and-analysis/aurastack-ai-super-agent.html) | PCB and advanced-package engineering   | Super-agent coordinating specialized EDA agents | Planning, constraints, implementation, DFM and multiphysics workflows |      🔒      | **Announced**  |

Community KiCad agent integrations are listed under [MCP Servers, Connectors & Agent Skills](#mcp-connectors-agent-skills).

Synopsys announced end-of-2026 availability for its expanded AgentEngineer / Autopilot offering; existing customer engagements do not imply general availability. See the [dated announcement](https://news.synopsys.com/2026-09-28-Synopsys-Powers-Autonomous-Engineering-with-a-Broad-Portfolio-of-Long-Horizon-Agents-and-Autopilot-Platform).

---

<a id="mcp-connectors-agent-skills"></a>

## 🔌 MCP Servers, Connectors & Agent Skills

**MCP is a protocol, not a quality badge.**

Official vendor integrations, mature OSS systems, and small proof-of-concepts should not be presented as equivalent.

### Official / first-party

| Connector                                                                                               | Target                 | What it exposes                                       | Availability | Maturity       |
| ------------------------------------------------------------------------------------------------------- | ---------------------- | ----------------------------------------------------- | :----------: | -------------- |
| [Autodesk Fusion MCP Server](https://help.autodesk.com/view/ADSKMCP/ENU/?guid=ADSKMCP_FusionDesktopMcp_autodesk_fusion_mcp_server_html) | Fusion desktop | Modeling and commands in a running local Fusion session | 🔒 | **Production** |
| [Autodesk Fusion Data MCP](https://help.autodesk.com/view/fusion360/ENU/?guid=FMCP-OVERVIEW) | Fusion cloud data | Hubs, projects, folders, items, and access management | 🔒 | **Production** |
| [Autodesk Revit MCP Server](https://help.autodesk.com/view/ADSKMCP/ENU/?guid=ADSKMCP_RevitMcp_revit_mcp_server_html) | Revit 2027.2 | Read, write, and experimental model tools in technical preview | 🔒 | **Preview** |
| [Autodesk Product Help MCP](https://help.autodesk.com/view/ADSKMCP/ENU/) | Autodesk documentation | Search and retrieve product documentation | 🔒 | **Production** |
| [Autodesk AutoCAD and Civil 3D MCP](https://help.autodesk.com/view/ADSKMCP/ENU/) | AutoCAD / Civil 3D | Query and modify drawings; inspect templates and styles | 🔒 | **Preview** |
| [Autodesk Fusion Compute MCP](https://www.autodesk.com/products/fusion-360/blog/fusion-compute-mcp/) | Fusion in the cloud | Headless modeling, assemblies, CAM, and exports | 🔒 | **Preview** |
| [Blender Lab MCP Server](https://www.blender.org/lab/mcp-server/) | Blender 5.1+ | Python API, scene inspection, and documentation access | ✅ | **Experimental** |
| [SketchUp Connector for Claude](https://help.sketchup.com/en/sketchup-claude-connector) | SketchUp | Generate new `.skp` files; cannot import and edit an existing `.skp` | 🔒 | **Production** |

> [!NOTE]
> **Open protocol ≠ universal vendor support.**
>
> A connector using MCP does not guarantee that every MCP client is officially supported.

### Community engineering integrations

| Project                                                  | Target          | What it does                                                           | Availability | Maturity         |
| -------------------------------------------------------- | --------------- | ---------------------------------------------------------------------- | :----------: | ---------------- |
| [CAD Skills](https://github.com/earthtojake/text-to-cad) | CAD / CAE / CAM | Specialized skills for generating and validating engineering artifacts |       ✅      | **Active**       |
| [freecad-mcp](https://github.com/neka-nat/freecad-mcp)   | FreeCAD         | Model creation, inspection, Python execution and FEM-related workflows |       ✅      | **Active**       |
| [MCP for Blender](https://github.com/ahujasid/mcp-for-blender)    | Blender         | Community scene/object/material manipulation through MCP               |       ✅      | **Active**       |
| [PartCAD agent skills / MCP](https://github.com/partcad/partcad) | Parametric parts and assemblies | Agent-authored CAD, rendering, inspection, and validation through PartCAD tools | ✅ | **Active** |
| [Onshape MCP](https://github.com/hedless/onshape-mcp)    | Onshape         | Programmatic CAD modeling through the Onshape API                      |       ✅      | **Experimental** |
| [KiCad MCP](https://github.com/lamaalrajih/kicad-mcp)    | KiCad           | PCB/electronics access through MCP                                     |       ✅      | **Experimental** |
| [STK-MCP](https://github.com/alti3/stk-mcp) | Ansys / AGI STK | Scenario and mission-analysis tools; reuse license not verified | ⚪ | **Experimental** |
| [sim-cli](https://github.com/svd-ai-lab/sim-cli) | CAE files and solver plugins | Extract structured model context; optional plugins expose solver execution | ✅ | **Experimental** |

The `sim-cli` project currently labels itself **alpha**. STK-MCP exposes public source, but its root files, README, and package metadata did not declare a reuse license during this review. KiCad MCP remains experimental; its last repository push was October 17, 2025.

### Safety for engineering agents

Agents that can modify CAD, simulation inputs, BOMs, CAM data, or machine instructions should be used with copies or version history, explicit human approval for destructive changes, deterministic geometry and solver checks, manufacturing simulation where available, and inspection of generated scripts, toolpaths, and machine parameters before execution.

---

<a id="research-models-methods"></a>

## 📄 Research Models & Methods

### CAD generation and reconstruction

| Work                                              | Year / venue           | Contribution                                                                    |
| ------------------------------------------------- | ---------------------- | ------------------------------------------------------------------------------- |
| [Cadrille](https://arxiv.org/abs/2505.22914)      | ICLR 2026 Oral         | Multimodal CAD reconstruction from point clouds, images and text with online RL |
| [ToolCAD](https://arxiv.org/abs/2604.07960)       | 2026                   | Tool-using LLM agents for text-to-CAD                                           |
| [CAD-Llama](https://arxiv.org/abs/2505.04481)     | CVPR 2025              | LLM framework for parametric CAD command generation                             |
| [Text2CAD](https://arxiv.org/abs/2409.17106)      | NeurIPS 2024 Spotlight | Sequential parametric CAD generation from natural language                      |
| [BrepGen](https://arxiv.org/abs/2401.15563)       | 2024                   | Diffusion-based B-Rep generation                                                |
| [DeepCAD](https://github.com/rundiwu/DeepCAD) | ICCV 2021              | Historical CAD command-sequence generation baseline                             |
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

<a id="benchmarks-reality-checks"></a>

## 📊 Benchmarks & Reality Checks

Engineering AI should be evaluated on **engineering correctness**, not only visual similarity.

| Benchmark                                          | What it tests                                               | Why it matters                                                          |
| -------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------------------- |
| [CADBench](https://arxiv.org/abs/2605.10873) | Multimodal CAD program generation across five input modalities | Measures geometry, executability, and program compactness |
| [BenchCAD](https://arxiv.org/abs/2605.10865)       | Execution-verified industrial-style CAD programs            | Tests whether generated CAD executes and preserves parametric structure |
| [Text2CAD-Bench](https://arxiv.org/abs/2605.18430) | Text-to-CAD from simple to complex topology                 | Separates primitive success from robust feature generation              |
| [MUSE](https://arxiv.org/abs/2605.28579) | Multi-component B-Rep assemblies and interface geometry | Tests execution, geometry, assembly structure, and functional consistency |
| [CFDLLMBench / FoamBench](https://arxiv.org/abs/2509.20374) | CFD knowledge, numerical reasoning, and executable workflows | Measures solution accuracy and convergence as well as code execution |

> [!CAUTION]
> **Text-to-CAD is not solved.**
>
> Current systems are useful for simple geometry, repetitive operations, design exploration, and agent-assisted workflows.
>
> Complex feature history, constraints, assemblies, design intent, and manufacturing-ready CAD remain significantly harder than producing a visually plausible 3D shape.

---

<a id="engineering-foundations"></a>

## 🧰 Engineering Foundations

These are important building blocks for engineering AI systems, but **they are not presented as AI products**.

<details>
<summary><b>CAD kernels, modelers, and programmatic CAD</b></summary>

* [FreeCAD](https://www.freecad.org/)
* [CadQuery](https://github.com/CadQuery/cadquery)
* [build123d](https://github.com/gumyr/build123d)
* [OpenCASCADE / OCCT](https://occt3d.com/open-cascade-technology/index.html)
* [OpenSCAD](https://openscad.org/)
* [KCL](https://zoo.dev/)
* [PartCAD](https://github.com/partcad/partcad)

</details>

<details>
<summary><b>CAE solvers, meshing, and visualization</b></summary>

* [OpenFOAM](https://www.openfoam.com/)
* [CalculiX](https://www.calculix.de/)
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
* [Pyslvs](https://github.com/KmolYuan/Pyslvs-UI) — legacy UI reference; last repository push in July 2022

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
* [NVIDIA DeepStream](https://github.com/NVIDIA/DeepStream)

</details>

<details>
<summary><b>Additive manufacturing infrastructure</b></summary>

* [PrusaSlicer](https://github.com/prusa3d/PrusaSlicer)
* [CuraEngine](https://github.com/Ultimaker/CuraEngine)
* [OctoPrint](https://github.com/OctoPrint/OctoPrint)
* [Materialise Magics](https://www.materialise.com/en/industrial/software/magics-data-build-preparation)

</details>

<details>
<summary><b>Digital twin and engineering-data infrastructure</b></summary>

* [Eclipse Ditto](https://github.com/eclipse-ditto/ditto)
* [Azure Digital Twins](https://azure.microsoft.com/en-us/products/digital-twins)
* [AWS IoT TwinMaker](https://aws.amazon.com/iot-twinmaker/)
* [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/)
* [OpenBOM](https://www.openbom.com/)
* [Aras Innovator](https://aras.com/en)

</details>

<details>
<summary><b>Materials data and analysis</b></summary>

* [Materials Project](https://materialsproject.org/)
* [pymatgen](https://github.com/materialsproject/pymatgen)
* [MatWeb](https://www.matweb.com/)
* [chemicals](https://github.com/CalebBell/chemicals)

</details>

---

<a id="experimental-early-projects"></a>

## 🧪 Experimental / Early Projects

Projects worth watching, but not yet presented at the same maturity level as production or established open projects.

| Project                                                                       | Target     | Why it is here                              |
| ----------------------------------------------------------------------------- | ---------- | ------------------------------------------- |
| [SolidworksMCP-TS](https://github.com/vespo92/SolidworksMCP-TS)               | SolidWorks | Community COM/MCP bridge                    |
| [mcp-server-solidworks](https://github.com/eyfel/mcp-server-solidworks)       | SolidWorks | Alternative community SolidWorks MCP        |
| [Jarvis Onshape MCP](https://github.com/ReshefElisha/jarvis-onshape-mcp)      | Onshape    | Agentic FeatureScript-oriented layer        |
| [openfoam-mcp-server](https://github.com/webworn/openfoam-mcp-server)         | OpenFOAM   | LLM/MCP interface with educational focus    |

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
| [cadquery-mcp-server](https://github.com/rishigundakaram/cadquery-mcp-server) / [mcp-cadquery](https://github.com/bertvanbrakel/mcp-cadquery) | **Historical experiments** | Last repository pushes June / April 2025; current maintenance and reuse licenses unverified |
| Autodesk Model Data Explorer MCP | **Current availability unverified** | Announced in 2025; absent from the current documented MCP catalog. Do not label Production without current evidence |
| Small abandoned demos                                       | **Removed / Experimental**                    | Repository existence alone is not sufficient evidence                     |

</details>

---

<a id="learning-resources"></a>

## 📚 Learning Resources

| Resource                                                                                       | Focus                                       |
| ---------------------------------------------------------------------------------------------- | ------------------------------------------- |
| [Flocode Newsletter](https://flocode.dev/)                                                 | Python for civil and structural engineers   |
| [Structural Python](https://www.structuralpython.com/)                                         | Automated structural-engineering toolkits   |
| [Python Libraries for Engineers](https://github.com/joreilly86/Python-Libraries-for-Engineers) | Python resources for engineers              |
| [MIT OCW: Mechanical Engineering](https://ocw.mit.edu/search/?d=Mechanical%20Engineering&s=department_course_numbers.sort_coursenum)         | Free mechanical-engineering courses         |
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
