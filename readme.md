<div align="center">

# 🔧 Awesome Physical Engineering AI 🔧

<img width="460" height="232" alt="image" src="https://github.com/user-attachments/assets/59b75d8f-be40-461d-a701-3865d0b71f1f"/>

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Last Update](https://img.shields.io/badge/Last_Update-April_2026-blue.svg)](#)

**A curated list of AI tools for engineers who work with the physical world — CAD, CAE, CFD, CAM, manufacturing, inspection, materials, and digital twins.**

[Submit a Tool](#contributing) · [Report Broken Link](../../issues/new) · [Suggest Category](../../issues/new)

</div>

---

> [!TIP]
> **What changed in this cleaned 2026 version:** suspicious or mismatched links were removed or corrected; generic AI frameworks were moved out of the core app lists; visual text-to-3D tools are labeled as concept/mesh tools instead of engineering CAD; and research prototypes are separated from production tools.
>
> Major fixes: **Spectral Labs SGS-1** now points to `spectrallabs.ai`, **CADscribe** now points to `cadscribelabs.com`, **Lambda Function** now points to `lambdafunction.ai`, **Productive Machines / SenseNC** now points to `productivemachines.co.uk`, **Onshape MCP** now points to a real GitHub MCP server, and **Kapow** was removed because it is not an engineering quoting/manufacturing tool.

---

## 🗺️ The Physical Engineering AI Stack

> **Design → Validate → Price → Make → Inspect → Operate**, with AI agents, MCP servers, and open-source foundations cutting across every stage.

<img width="2816" height="1536" alt="AwesomeengineeringAI" src="https://github.com/user-attachments/assets/712d83d7-3b8d-47cd-86a1-3c5ac5f1e327" />

> [!NOTE]
> **How to read this:** the main flow is the physical product lifecycle. The bottom layer is the cross-cutting infrastructure that orchestrates each stage. Before adding a tool, ask: **which stage does it actually improve, and is it engineering-specific?**

---

## Contents

- [🎨 CAD AI & Generative Geometry](#-cad-ai--generative-geometry)
- [⚡ Generative & Topology Optimization](#-generative--topology-optimization)
- [🧪 AI-Powered Simulation](#-ai-powered-simulation)
- [🏭 Design for Manufacturing (DFM)](#-design-for-manufacturing-dfm)
- [💰 Cost Estimation & Instant Quoting](#-cost-estimation--instant-quoting)
- [⚙️ CAM & CNC AI](#️-cam--cnc-ai)
- [👁️ Quality Inspection & Computer Vision](#️-quality-inspection--computer-vision)
- [🔮 Digital Twins & Predictive Maintenance](#-digital-twins--predictive-maintenance)
- [🔢 Engineering Calculations & Computation](#-engineering-calculations--computation)
- [🧱 Materials & Material Selection](#-materials--material-selection)
- [🔌 MCP Servers for Engineering](#-mcp-servers-for-engineering)
- [🧠 AI Agents for Engineering](#-ai-agents-for-engineering)
- [🤖 Robotics & Controls](#-robotics--controls)
- [🖨️ 3D Printing & Additive Manufacturing](#️-3d-printing--additive-manufacturing)
- [📦 PLM, PDM & Knowledge Management](#-plm-pdm--knowledge-management)
- [🧰 Open-Source CAD & CAE Foundations](#-open-source-cad--cae-foundations)
- [📄 AI Research Papers, Models & Datasets](#-ai-research-papers-models--datasets)
- [🐍 Python Libraries for Engineers](#-python-libraries-for-engineers)
- [📚 Learning Resources](#-learning-resources)
- [🧹 Removed / Not Included](#-removed--not-included)

---

## 🎨 CAD AI & Generative Geometry

> Tools that use AI to **create, edit, understand, or document** CAD models from text, sketches, scans, or existing 3D geometry.

### Engineering CAD tools

| Tool | Type | What it does | Open Source |
|------|------|-------------|:-----------:|
| [Adam CAD](https://adam.new) | Platform | AI-native CAD with text-to-3D and parametric editing workflows | ❌ |
| [Zoo Design Studio + Zookeeper](https://zoo.dev) | Platform / language | Conversational CAD workflows built around KCL; produces editable engineering geometry | Partial |
| [Spectral Labs SGS-1](https://www.spectrallabs.ai/research/SGS-1) | Research preview | Image/mesh → structured parametric CAD/B-Rep STEP geometry | ❌ |
| [CADscribe](https://cadscribelabs.com/) | Web app | Text prompts → CAD-style models in browser | ❌ |
| [DraftAid](https://draftaid.io/) | CAD drawing automation | Generates 2D fabrication drawings from 3D CAD models; supports SolidWorks and Inventor workflows | ❌ |
| [CADAM](https://github.com/Adam-CAD/CADAM) | Web app | Text-to-CAD using Claude API + OpenSCAD + WebAssembly; exports STL/SCAD | ✅ |
| [CQAsk](https://github.com/OpenOrion/CQAsk) | CLI/Web | LLM-powered CAD generation using CadQuery; exports STL/STEP | ✅ |
| [SolidWorks AI / AURA](https://www.solidworks.com) | Built-in / plugin | AI-assisted modeling and 3DEXPERIENCE workflows | ❌ |
| [Autodesk Fusion AI](https://www.autodesk.com/products/fusion-360) | Built-in | AI-assisted sketching, manufacturing, drawings, and CAM workflows | ❌ |
| [Siemens NX AI](https://plm.sw.siemens.com/en-US/nx/) | Built-in | AI-assisted modeling, feature recognition, and automation inside NX | ❌ |
| [PTC Creo AI](https://www.ptc.com/en/products/creo) | Built-in | AI-assisted design, generative design, and simulation-connected workflows | ❌ |

### Concept / visual 3D tools

> These are useful for ideation, visualization, game/AR assets, and early concept work. They should **not** be presented as parametric engineering CAD unless they export editable CAD/B-Rep workflows.

| Tool | Type | What it does | Open Source |
|------|------|-------------|:-----------:|
| [Tripo](https://tripo3d.ai) | Platform | Text/image/sketch → 3D mesh assets; exports common asset formats | Partial |
| [Meshy](https://meshy.ai) | Platform | Text/image → 3D mesh assets with textures | ❌ |
| [Point-E](https://github.com/openai/point-e) | Model | Text/image → 3D point clouds; research-oriented | ✅ |

---

## ⚡ Generative & Topology Optimization

> AI-driven tools that **generate or optimize geometry** for weight, strength, cost, thermal behavior, manufacturability, or design exploration.

| Tool | Key Strength | Best For | Open Source |
|------|-------------|----------|:-----------:|
| [Autodesk Fusion Generative Design](https://www.autodesk.com/solutions/generative-design-ai-software) | Multi-method optimization for additive, milling, and casting | Comparing manufacturing methods | ❌ |
| [nTop](https://www.ntop.com) | Implicit modeling, field-driven lattices, gyroids | Aerospace, medical, lightweighting | ❌ |
| [Siemens NX Generative Engineering](https://plm.sw.siemens.com/en-US/nx/) | Convergent modeling: mesh + B-Rep in one workflow | Siemens enterprise users | ❌ |
| [MSC Apex Generative Design](https://hexagon.com/products/product-groups/computer-aided-engineering-software) | Optimization with production-oriented geometry workflows | CAE-heavy teams | ❌ |
| [PTC Creo Generative Design](https://www.ptc.com/en/products/creo/generative-design) | Cloud optimization and native Creo output | Creo-native workflows | ❌ |
| [Altair HyperWorks](https://altair.com/hyperworks) | Optimization, design exploration, surrogate models, and CAE automation | High-throughput simulation teams | ❌ |
| [Monolith](https://www.monolithai.com) | No-code AI models from test and simulation data | Teams without dedicated ML teams | ❌ |

---

## 🧪 AI-Powered Simulation

> AI that **accelerates, assists, or approximates** traditional FEA/CFD/multiphysics workflows.

| Tool | Approach | Typical use | Open Source |
|------|----------|-------------|:-----------:|
| [Ansys SimAI](https://www.ansys.com/products/simai) | Simulation surrogate models trained from historical data | Fast design exploration | ❌ |
| [Ansys Engineering Copilot](https://www.ansys.com) | Natural-language assistant for Ansys workflows | Setup and interpretation assistance | ❌ |
| [Altair HyperWorks](https://altair.com/hyperworks) | CAE automation, PhysicsAI, ROMs, and optimization workflows | Enterprise CAE automation | ❌ |
| [Neural Concept](https://www.neuralconcept.com) | Deep learning from 3D geometry for aero/thermal/mechanical prediction | Real-time simulation surrogates | ❌ |
| [SimScale](https://www.simscale.com) | Cloud-native CFD/FEA/thermal simulation with AI-assisted workflows | Browser-based simulation teams | ❌ |
| [NVIDIA PhysicsNeMo](https://github.com/NVIDIA/physicsnemo) | Physics-ML framework; neural operators, GNNs, transformers, PINNs | GPU-accelerated physics ML | ✅ |
| [PhysicsNeMo-CFD](https://github.com/NVIDIA/physicsnemo-cfd) | CFD-focused models and workflows built around PhysicsNeMo | CFD surrogates and examples | ✅ |
| [FEATool Multiphysics](https://www.featool.com) | Multiphysics GUI with MATLAB/Python/OpenFOAM/FEniCS/SU2 workflows | Teaching, prototyping, multiphysics | Partial |
| [PhiFlow](https://github.com/tum-pbs/PhiFlow) | Differentiable PDE solving with PyTorch/TensorFlow/JAX | Physics ML research | ✅ |
| [DeepXDE](https://github.com/lululxvi/deepxde) | PINNs and deep operator networks | Scientific ML and PDE learning | ✅ |
| [neuraloperator](https://github.com/neuraloperator/neuraloperator) | Fourier neural operators and operator learning | PDE surrogate modeling | ✅ |
| [FourCastNet](https://github.com/NVlabs/FourCastNet) | Fourier neural operators for weather prediction | Physics ML reference model | ✅ |

---

## 🏭 Design for Manufacturing (DFM)

> AI and automation tools for catching manufacturability issues **before they become expensive**.

| Tool | What it checks | Integrations / workflow | Open Source |
|------|---------------|-------------------------|:-----------:|
| [bananaz](https://www.bananaz.ai) | DFM, GD&T, tolerance analysis, drawing review, 3D assembly comparison | SolidWorks, Creo | ❌ |
| [CoLab AutoReview](https://www.colabsoftware.com) | Multi-step design review: title blocks, callouts, DFM, cross-view consistency | Native CAD files | ❌ |
| [Leo AI](https://www.getleo.ai) | Engineering Q&A, part search, calculations, validation from PLM + external sources | CAD/PLM workflows | ❌ |
| [Autodesk Fusion DFM](https://www.autodesk.com/products/fusion-360/design-for-manufacturing) | Injection molding, toolpath, and manufacturability workflows | Fusion ecosystem | ❌ |
| [DFMPro](https://dfmpro.com/) | Rules-based checks for machining, molding, casting, sheet metal | SolidWorks, Creo, NX, CATIA | ❌ |
| [Xometry Instant Quoting](https://www.xometry.com) | Instant quotes with manufacturability feedback | Upload STEP/STL | ❌ |
| [Protolabs Network / Hubs](https://www.hubs.com) | Instant DFM analysis and quoting for CNC, 3D printing, and injection molding | Upload STEP/STL | ❌ |
| [Fictiv](https://www.fictiv.com/) | Quoting, supplier network, DFM, and manufacturing support | Upload CAD files | ❌ |

---

## 💰 Cost Estimation & Instant Quoting

> Tools that turn CAD files into **cost estimates, cycle times, manufacturability checks, and ready-to-send quotes**.

| Tool | What it does | Best For | Open Source |
|------|-------------|----------|:-----------:|
| [aPriori](https://www.apriori.com) | Digital manufacturing simulation for cost, manufacturability, sustainability, and regional cost modeling | Enterprise OEMs and should-cost teams | ❌ |
| [CloudNC Cycle Time Estimator](https://www.cloudnc.com) | Estimates cycle times and machining strategies for CNC quoting | Shops using CAM Assist / CNC quoting workflows | ❌ |
| [Toolpath Estimating](https://toolpath.com/platform/estimating) | Generates machining plans and time estimates using Autodesk Fusion tool libraries and cutting parameters | Fusion-native CNC shops | ❌ |
| [Machine Research](https://machineresearch.com) | CAD-driven time and cost estimation for programming, setup, and production | Small-to-mid CNC job shops | ❌ |
| [DigiFabster](https://digifabster.com) | Instant quoting for CNC, additive, sheet metal, waterjet, and turning | Shops needing customer-facing quoting portals | ❌ |
| [Phasio](https://www.phas.io/) | CAD upload, manufacturability checks, material suggestions, quoting, and production workflow management | Contract manufacturers and job shops | ❌ |
| [MakerVerse](https://www.makerverse.com/) | AI-driven instant quotes, built-in DFM, and industrial part sourcing | Industrial on-demand manufacturing | ❌ |
| [Dashnode](https://www.dashnode.ai/) | CAD-to-cost CNC quoting with feature-based pricing and shop-specific cost logic | CNC manufacturers, especially India-based pricing workflows | ❌ |
| [AutoCut](https://autocut.app/) | AI-powered quoting for laser, waterjet, plasma, and router operations | Sheet/plate fabrication shops | ❌ |
| [Spanflug MAKE](https://spanflug.de/en/make/) | Automatic part analysis for turning/milling, stock, tooling, and machining steps | European machine shops | ❌ |
| [Costimator](https://www.costimator.com) | Shop-floor-based cost estimating with built-in cost models | Job shops preferring rules-based estimating | ❌ |

> [!TIP]
> **Common quoting stack:** Upload STEP → DFM flags issues → quoting extracts features and cost drivers → CAM creates programs → quote goes out in minutes instead of days.

---

## ⚙️ CAM & CNC AI

> AI tools that **automate CNC programming**, optimize toolpaths, and capture machinist knowledge.

| Tool | What it does | Integrations / workflow | Open Source |
|------|-------------|-------------------------|:-----------:|
| [CloudNC CAM Assist](https://www.cloudnc.com) | AI toolpath generation for 3-axis and 3+2-axis machining; physics-based feeds and speeds | Mastercam, Fusion, GibbsCAM, SolidCAM, NX | ❌ |
| [Lambda Function](https://www.lambdafunction.ai/) | AI-assisted CNC programming, toolpath optimization, monitoring, and shop-floor feedback | CAM and CNC workflows; Siemens ecosystem support | ❌ |
| [LimitlessCNC](https://limitlesscnc.ai/) | AI CAM agent trained on shop data; recommends operations inside NX-CAM | NX-CAM | ❌ |
| [Toolpath](https://toolpath.com) | AI CAM, DFM, estimating, and Fusion-connected machining workflows | Autodesk Fusion | ❌ |
| [Productive Machines SenseNC](https://productivemachines.co.uk/) | Milling optimization for chatter avoidance, feeds/speeds, cycle time, and tool life | Siemens NX, Mastercam | ❌ |
| [Mastercam Copilot](https://www.mastercam.com) | AI assistant for Mastercam programming workflows | Mastercam | ❌ |
| [Siemens NX Manufacturing Copilot](https://plm.sw.siemens.com/en-US/nx/) | AI-guided programming and automation for NX manufacturing workflows | NX CAM | ❌ |

---

## 👁️ Quality Inspection & Computer Vision

> AI-powered **visual inspection, defect detection**, and quality control for manufacturing.

| Tool | What it does | Open Source |
|------|-------------|:-----------:|
| [Roboflow](https://roboflow.com) | End-to-end CV platform: annotate, train, deploy; edge and cloud | Partial |
| [Roboflow Inference](https://github.com/roboflow/inference) | Production-ready inference server for CV models | ✅ |
| [Roboflow Supervision](https://github.com/roboflow/supervision) | Reusable CV tools for annotation, tracking, counting, and visualization | ✅ |
| [Landing AI / LandingLens](https://landing.ai) | No-code visual inspection and defect detection for manufacturing | ❌ |
| [Lincode LIVIS](https://lincode.ai) | AI visual inspection with manufacturing-focused models | ❌ |
| [Overview.ai](https://www.overview.ai) | Fast defect detection and browser-based deployment workflows | ❌ |
| [Tritva / Ombrulla](https://ombrulla.com) | Visual inspection with monitoring and drift detection | ❌ |
| [NVIDIA DeepStream](https://developer.nvidia.com/deepstream-sdk) | Streaming analytics SDK for multi-sensor edge processing | Partial |
| [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) | Object detection and segmentation models widely used in inspection | ✅ |
| [OpenCV](https://github.com/opencv/opencv) | Foundational open-source computer vision library | ✅ |

> [!TIP]
> [Roboflow Universe](https://universe.roboflow.com) hosts many manufacturing-relevant datasets for PPE detection, defects, assembly verification, and inspection experiments.

---

## 🔮 Digital Twins & Predictive Maintenance

> AI for **virtual representations of physical systems**, condition monitoring, and failure prediction.

| Tool | What it does | Open Source |
|------|-------------|:-----------:|
| [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/) | USD-based platform for physically accurate digital twins and simulation workflows | Partial |
| [Eclipse Ditto](https://github.com/eclipse-ditto/ditto) | Framework for IoT digital twins, device state, messaging, and access control | ✅ |
| [Azure Digital Twins](https://azure.microsoft.com/en-us/products/digital-twins) | Cloud platform for modeling physical environments and relationships | ❌ |
| [AWS IoT TwinMaker](https://aws.amazon.com/iot-twinmaker/) | Build digital twins from IoT data, video, and 3D assets | ❌ |
| [predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) | MCP server for vibration analysis, bearing fault detection, and ISO-style reporting | ✅ |
| [Open Source Digital Twin](https://github.com/Open-Source-Digital-Twin) | Motion-control playground and controller for digital twin research | ✅ |
| [awesome-digital-twins](https://github.com/edt-community/awesome-digital-twins) | Curated list of digital twin resources, papers, and frameworks | ✅ |

---

## 🔢 Engineering Calculations & Computation

> Libraries for **unit-aware calculations, automated reporting**, and engineering math.

| Library | What it solves | Language | Open Source |
|---------|---------------|----------|:-----------:|
| [handcalcs](https://github.com/connorferster/handcalcs) | Renders calculations as handwritten LaTeX from code | Python | ✅ |
| [forallpeople](https://github.com/connorferster/forallpeople) | SI units in engineer-friendly notation | Python | ✅ |
| [MechLab](https://pypi.org/project/mechlab/) | Statics, dynamics, thermo, fluids, control systems | Python | ✅ |
| [DynPy](https://github.com/bogumilchilinski/dynpy) | Dynamic mechanical and electrical system simulation | Python | ✅ |
| [PyNite](https://github.com/JWock82/PyNite) | 3D structural finite element analysis | Python | ✅ |
| [sectionproperties](https://github.com/robbievanleeuwen/section-properties) | Cross-section analysis: elastic, plastic, warping | Python | ✅ |
| [structuralcodes](https://github.com/fib-international/structuralcodes) | Structural calculations per international codes | Python | ✅ |
| [fluids](https://github.com/CalebBell/fluids) | Pipe flow, compressible flow, open channel, two-phase | Python | ✅ |
| [CoolProp](https://github.com/CoolProp/CoolProp) | Thermophysical properties for many fluids | C++/Python | ✅ |
| [pint](https://github.com/hgrecco/pint) | Physical quantities and unit conversion | Python | ✅ |
| [Engineering Equation Solver](https://fchartsoftware.com/ees/) | Coupled nonlinear equations with thermo property functions | Proprietary | ❌ |

---

## 🧱 Materials & Material Selection

> AI and data tools for **finding, comparing, and optimizing** material choices.

| Tool | Type | Description | Open Source |
|------|------|-------------|:-----------:|
| [Granta MI / Ansys Materials](https://www.ansys.com/products/materials) | Enterprise | Material information management and simulation-connected material selection | ❌ |
| [Citrine Informatics](https://citrine.io) | Platform | AI for materials R&D, property prediction, and formulation optimization | ❌ |
| [MatWeb](https://www.matweb.com) | Database | Searchable material property database for metals, plastics, ceramics, and composites | ❌ |
| [Materials Project](https://materialsproject.org) | Database/API | Materials data, crystal structures, phase diagrams, and computed properties | Partial |
| [thermo](https://github.com/CalebBell/thermo) | Library | Thermodynamics and phase equilibrium calculations | ✅ |
| [chemicals](https://github.com/CalebBell/chemicals) | Library | Chemical properties database and estimation methods | ✅ |
| [pymatgen](https://github.com/materialsproject/pymatgen) | Library | Materials analysis, crystal structures, phase diagrams, electronic properties | ✅ |

---

## 🔌 MCP Servers for Engineering

> [Model Context Protocol](https://modelcontextprotocol.io) servers that let AI agents control or query engineering tools.

> [!TIP]
> MCP servers are most useful when paired with strong guardrails: dry-run mode, explicit human approval, file backups, and version control.

| Server | Target | Features | Note |
|--------|--------|----------|:----:|
| [freecad-mcp](https://github.com/neka-nat/freecad-mcp) by neka-nat | FreeCAD | Documents, primitives, booleans, export, remote control | Mature option |
| [freecad-mcp](https://github.com/contextform/freecad-mcp) by contextform | FreeCAD | PartDesign and Part operations with npm setup | Easy setup |
| [freecad_mcp](https://github.com/bonninr/freecad_mcp) by bonninr | FreeCAD | Script execution and scene inspection | Experimental |
| [SolidworksMCP-TS](https://github.com/vespo92/SolidworksMCP-TS) | SolidWorks | Node.js COM bridge and SolidWorks automation tools | Active OSS |
| [mcp-server-solidworks](https://github.com/eyfel/mcp-server-solidworks) | SolidWorks | Python/C# adapter, COM bridge, context streaming | Active OSS |
| [Onshape MCP](https://github.com/hedless/onshape-mcp) | Onshape | Programmatic CAD modeling and Onshape API workflows | Active OSS |
| [Blender MCP](https://github.com/ahujasid/blender-mcp) | Blender | Scene manipulation, asset workflows, and 3D operations | Popular OSS |
| [KiCad MCP](https://github.com/lamaalrajih/kicad-mcp) | KiCad | Netlist, BOM, DRC, PCB visualization | Electronics |
| [cadquery-mcp-server](https://github.com/rishigundakaram/cadquery-mcp-server) | CadQuery | Natural-language-to-parametric-CAD experiments | Experimental |
| [mcp-cadquery](https://github.com/bertvanbrakel/mcp-cadquery) | CadQuery | Script execution, SVG export, part library workflows | Experimental |
| [CAD-MCP](https://github.com/daobataotie/CAD-MCP) | AutoCAD / compatible CAD | Controls CAD tools through natural language | Experimental |
| [predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) | PdM | Vibration analysis, bearing fault detection, anomaly detection, ISO reports | Unique |
| [Foam-Agent MCP](https://github.com/csml-rpi/Foam-Agent) | OpenFOAM | MCP/agentic workflows for OpenFOAM case setup and execution | Research/OSS |

---

## 🧠 AI Agents for Engineering

> Autonomous or semi-autonomous agents that plan and execute multi-step workflows across CAD, CAE, CAM, EDA, simulation, and manufacturing.

| Tool | Autonomy level | What it does | Open Source |
|------|---------------|-------------|:-----------:|
| [Aibuild OS](https://ai-build.com/os/) | Autonomous | Plain-language prompt → CAD/CAE/CAM workflows and manufacturing-ready outputs | ❌ |
| [Ansys Engineering Copilot](https://www.ansys.com) | Copilot | Natural-language assistant embedded in engineering simulation workflows | ❌ |
| [SimScale Engineering AI](https://www.simscale.com) | Copilot / agentic | AI-assisted cloud simulation workflows across CFD/FEA/thermal | ❌ |
| [Synopsys AgentEngineer](https://www.synopsys.com) | Multi-agent | Agentic workflows for semiconductor and systems design | ❌ |
| [Siemens Fuse EDA AI Agent](https://news.siemens.com/en-us/siemens-fuse-eda-ai-agent/) | Autonomous / domain-scoped | Orchestrates workflows across semiconductor, 3D IC, and PCB design through manufacturing sign-off | ❌ |
| [CoLab AutoReview](https://www.colabsoftware.com) | Agentic | Multi-step design review across drawings, CAD, and review history | ❌ |
| [Leo AI](https://www.getleo.ai) | Copilot | Engineering Q&A and validation grounded in PLM and supplier/technical sources | ❌ |
| [Foam-Agent](https://github.com/csml-rpi/Foam-Agent) | Research agent | Multi-agent OpenFOAM workflow automation from natural language | ✅ |
| [SimuAgent](https://arxiv.org/abs/2601.05187) | Research agent | LLM-based Simulink modeling assistant with reinforcement learning | ✅ / Research |
| [NVIDIA NeMo Agent Toolkit](https://github.com/NVIDIA/NeMo-Agent-Toolkit) | Framework | Framework for enterprise agent workflows with MCP/A2A support | ✅ |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Framework | Stateful multi-agent and workflow orchestration | ✅ |

> [!IMPORTANT]
> General frameworks such as LangChain, LangGraph, CrewAI, AutoGen, and NeMo Agent Toolkit are useful building blocks, but they should only be listed here when tied to an engineering workflow. Keep generic AI tooling out of the core engineering app lists.

---

## 🤖 Robotics & Controls

> AI tools for **mechanism design, control systems**, robotics simulation, and motion planning.

| Tool | Domain | Open Source |
|------|--------|:-----------:|
| [ROS 2 + MoveIt](https://moveit.ai) | Motion planning and robotic manipulation | ✅ |
| [NVIDIA Isaac](https://developer.nvidia.com/isaac) | Robotics simulation and synthetic data generation | Partial |
| [MuJoCo](https://mujoco.org) | Physics engine for RL and model-based optimization | ✅ |
| [PyBullet](https://pybullet.org) | Physics simulation for robotics and ML | ✅ |
| [python-control](https://python-control.readthedocs.io) | Transfer functions, state space, frequency response | ✅ |
| [Pyslvs](https://github.com/KmolYuan/Pyslvs-UI) | Planar linkage mechanism simulation and synthesis | ✅ |
| [Drake](https://drake.mit.edu) | Model-based design, control, multibody dynamics, optimization | ✅ |
| [SimuAgent](https://arxiv.org/abs/2601.05187) | Simulink modeling agent for controls and dynamic systems | Research |

---

## 🖨️ 3D Printing & Additive Manufacturing

> AI and automation tools for **optimizing additive manufacturing** workflows.

| Tool | What it does | Open Source |
|------|-------------|:-----------:|
| [nTop Lattice Optimization](https://www.ntop.com) | Lattice generation and field-driven density workflows | ❌ |
| [Materialise Magics](https://www.materialise.com/en/industrial/software/magics) | AM data prep, build orientation, support generation | ❌ |
| [Autodesk Netfabb](https://www.autodesk.com/products/netfabb) | Build process simulation and distortion prediction | ❌ |
| [Aibuild](https://ai-build.com) | AI-assisted large-format additive manufacturing workflows | ❌ |
| [PrusaSlicer](https://github.com/prusa3d/PrusaSlicer) | Adaptive layers, supports, and open slicing workflows | ✅ |
| [CuraEngine](https://github.com/Ultimaker/CuraEngine) | Extensible slicing engine | ✅ |
| [OctoPrint](https://github.com/OctoPrint/OctoPrint) | Printer management, plugins, monitoring | ✅ |
| [Obico](https://github.com/TheSpaghettiDetective/obico-server) | AI-powered 3D print failure detection via webcam | ✅ |

---

## 📦 PLM, PDM & Knowledge Management

> AI for **engineering knowledge**, design history, review capture, BOMs, and product lifecycle management.

| Tool | Key capability | Open Source |
|------|---------------|:-----------:|
| [CoLab](https://www.colabsoftware.com) | AI-assisted design reviews and engineering knowledge capture | ❌ |
| [Leo AI](https://www.getleo.ai) | Engineering Q&A grounded in PLM data and technical sources | ❌ |
| [OpenBOM](https://www.openbom.com) | Cloud BOM and inventory management for engineering teams | ❌ |
| [Aras Innovator](https://www.aras.com) | Enterprise PLM with open architecture and deep customization | Partial / source-visible |
| [GrabCAD](https://grabcad.com) | CAD model library and GrabCAD Print for additive workflows | ❌ |
| [PartCAD](https://github.com/openvmp/partcad) | Open-source package manager / digital thread for CAD parts and assemblies | ✅ |

---

## 🧰 Open-Source CAD & CAE Foundations

> Base tools that engineering AI systems are often built on top of.

<details>
<summary><b>CAD kernels, modelers, and programmatic CAD</b></summary>

| Tool | Description |
|------|-------------|
| [FreeCAD](https://www.freecad.org) | Parametric 3D modeler with Python API; foundation for many AI-CAD integrations |
| [CadQuery](https://github.com/CadQuery/cadquery) | Python scripting CAD on OCCT; outputs STEP/STL/DXF |
| [build123d](https://github.com/gumyr/build123d) | Modern Python CAD API on OCCT; successor-style workflow to CadQuery builders |
| [OpenCASCADE / OCCT](https://dev.opencascade.org) | Open-source geometry kernel used by FreeCAD, CadQuery, and other OSS CAD tools |
| [OpenSCAD](https://openscad.org) | Script-based CSG solid modeler; common target for generated CAD code |
| [ImplicitCAD](https://github.com/Haskell-Things/ImplicitCAD) | Programmatic CAD with implicit functions and smooth operations |
| [PartCAD](https://github.com/openvmp/partcad) | Package manager and digital thread for reproducible CAD components |

</details>

<details>
<summary><b>Simulation solvers</b></summary>

| Tool | Domain |
|------|--------|
| [OpenFOAM](https://www.openfoam.com) | CFD toolbox widely used in industry and research |
| [CalculiX](http://www.calculix.de) | FEA: structural, thermal, multiphysics; ABAQUS-like input style |
| [Elmer](https://www.elmerfem.org) | Multiphysics FEM: fluid, structure, thermal, electromagnetics |
| [FEniCS](https://fenicsproject.org) | PDE computing platform using finite elements |
| [SfePy](https://sfepy.org) | Simple Finite Elements in Python |
| [SU2](https://su2code.github.io) | CFD and multiphysics optimization, common in aerospace |
| [MFEM](https://mfem.org) | Scalable high-order finite element library with GPU support |

</details>

<details>
<summary><b>Meshing and visualization</b></summary>

| Tool | Purpose |
|------|---------|
| [Gmsh](https://gmsh.info) | 3D finite element mesh generator with CAD engine |
| [ParaView](https://www.paraview.org) | Data analysis and visualization for simulation results |
| [Salome](https://www.salome-platform.org) | Pre/post-processing for numerical simulations |
| [PyVista](https://docs.pyvista.org) | 3D mesh visualization and analysis in Python |
| [VTK](https://vtk.org) | Visualization toolkit; foundation for ParaView and PyVista |

</details>

---

## 📄 AI Research Papers, Models & Datasets

> Academic work pushing the boundaries of AI in CAD, simulation, design automation, and engineering agents.

<details open>
<summary><b>CAD generation and reconstruction</b></summary>

| Paper / model | Venue / year | Contribution |
|---------------|--------------|-------------|
| [Cadrille](https://arxiv.org/abs/2505.22914) | ICLR 2026 Oral | Multi-modal CAD reconstruction from point clouds, images, and text with online RL |
| [Seek-CAD](https://arxiv.org/abs/2505.17702) | ICLR 2026 | Self-refined generative CAD using local DeepSeek-R1 inference, RAG, visual feedback, and CoT |
| [ToolCAD](https://arxiv.org/abs/2604.07960) | 2026 preprint | Tool-using LLM agents for text-to-CAD with curriculum online RL and CAD-CoT |
| [CAD-Llama](https://arxiv.org/abs/2505.04481) | CVPR 2025 | LLM framework for generating CAD parametric sequences in SPCC format |
| [Text2CAD](https://arxiv.org/abs/2409.17106) | NeurIPS 2024 Spotlight | Sequential parametric CAD generation from beginner-to-expert text prompts |
| [GenCAD-3D](https://arxiv.org/abs/2509.15246) | 2025 | CAD program generation from point clouds/meshes using multimodal latent alignment |
| [HistCAD](https://arxiv.org/abs/2602.19171) | 2026 | Constraint-aware history-based CAD dataset with sequences, STEP B-Reps, native files, images, and annotations |
| [DeepCAD](https://github.com/ChrisWu1997/DeepCAD) | ICCV 2021 | Deep generative network for CAD command sequences |
| [BrepGen](https://arxiv.org/abs/2401.15563) | 2024 | B-Rep model generation via diffusion |
| [HNC for CAD](https://github.com/3dlg-hcvc/s2cad) | ICML 2023 | Hierarchical neural coding for controllable CAD generation |
| [Point-E](https://github.com/openai/point-e) | 2023 | Point cloud generation from text/image prompts |

</details>

<details>
<summary><b>Physics ML and simulation agents</b></summary>

| Paper / model | Venue / year | Contribution |
|---------------|--------------|-------------|
| [PINNs](https://github.com/maziarraissi/PINNs) | JCP 2019 | Physics-informed neural networks for PDE solving |
| [Fourier Neural Operator](https://github.com/neuraloperator/neuraloperator) | ICLR 2021 | Learning mappings between function spaces |
| [MeshGraphNets](https://arxiv.org/abs/2010.03409) | ICML 2021 | Mesh-based simulation using graph neural networks |
| [Modulus Sym](https://github.com/NVIDIA/modulus-sym) | NVIDIA 2023 | Symbolic PINNs and multiphysics framework |
| [MetaOpenFOAM](https://arxiv.org/abs/2407.21320) | 2024 | LLM-based multi-agent framework for OpenFOAM CFD workflows |
| [OpenFOAMGPT](https://arxiv.org/abs/2501.06327) | 2025 | RAG-augmented LLM agent for OpenFOAM-based CFD |
| [Foam-Agent](https://arxiv.org/abs/2505.04997) | 2025 | Multi-agent OpenFOAM workflow automation with error correction |
| [ChatCFD](https://arxiv.org/abs/2506.02019) | 2025 | End-to-end CFD agent with domain-specific structured thinking |
| [CFDagent](https://arxiv.org/abs/2507.23693) | 2025 | Zero-shot multi-agent system for autonomous CFD simulation |
| [SimuAgent](https://arxiv.org/abs/2601.05187) | 2026 | LLM-based Simulink modeling assistant with RL |

</details>

<details>
<summary><b>3D reconstruction and perception</b></summary>

| Paper / model | Venue / year | Contribution |
|---------------|--------------|-------------|
| [3D Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) | SIGGRAPH 2023 | Real-time radiance field rendering; useful for scan-to-scene workflows |
| [PointFlow](https://github.com/stevenygd/PointFlow) | ICCV 2019 | 3D point cloud generation with continuous normalizing flows |
| [NeRF](https://www.matthewtancik.com/nerf) | ECCV 2020 | Neural radiance fields for 3D scene representation |

</details>

---

## 🐍 Python Libraries for Engineers

> Scientific Python stack commonly used in engineering AI workflows.

<details>
<summary><b>Core scientific stack</b></summary>

[NumPy](https://numpy.org) · [SciPy](https://scipy.org) · [SymPy](https://www.sympy.org) · [Matplotlib](https://matplotlib.org) · [pandas](https://pandas.pydata.org)

</details>

<details>
<summary><b>3D and mesh processing</b></summary>

[PyVista](https://docs.pyvista.org) · [trimesh](https://trimesh.org/) · [meshio](https://github.com/nschloe/meshio) · [pygmsh](https://github.com/nschloe/pygmsh) · [Open3D](http://www.open3d.org)

</details>

<details>
<summary><b>Simulation interfaces</b></summary>

[PyFoam](https://pypi.org/project/PyFoam/) · [pyNastran](https://github.com/SteveDoyle2/pyNastran) · [OpenAeroStruct](https://github.com/mdolab/OpenAeroStruct) · [OpenMDAO](https://openmdao.org)

</details>

<details>
<summary><b>Computer vision for manufacturing</b></summary>

[OpenCV](https://opencv.org) · [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) · [Roboflow Supervision](https://github.com/roboflow/supervision) · [Roboflow Inference](https://github.com/roboflow/inference) · [Detectron2](https://github.com/facebookresearch/detectron2)

</details>

---

## 📚 Learning Resources

| Resource | Focus |
|----------|-------|
| [Flocode Newsletter](https://www.flocode.dev) | Python for civil/structural engineers |
| [Structural Python](https://www.structuralpython.com) | Automated Structural Engineering Toolkits (ASETs) |
| [Python Libraries for Engineers](https://github.com/joreilly86/Python-Libraries-for-Engineers) | Curated Python database for professional engineers |
| [SplineCloud Blog](https://splinecloud.com/blog/python-for-mechanical-engineers/) | Practical Python tutorials for mechanical engineers |
| [MIT OCW: Mechanical Engineering](https://ocw.mit.edu/courses/mechanical-engineering/) | Free university courses |
| [awesome-mecheng](https://github.com/m2n037/awesome-mecheng) | Classic mechanical engineering awesome list |
| [awsomeEngSci](https://github.com/Foadsf/awsomeEngSci) | FOSS list for engineering and science |
| [awesome-digital-twins](https://github.com/edt-community/awesome-digital-twins) | Digital twin papers, frameworks, and tools |
| [Roboflow Universe](https://universe.roboflow.com) | Open datasets for CV model training |
| [SimScale 2026 State of Engineering AI Report](https://www.simscale.com/the-state-of-engineering-ai-2026/) | Engineering AI adoption and workflow report |

---

## 🧹 Removed / Not Included

> This section makes curation decisions explicit and prevents the same bad links from being re-added.

| Entry | Decision | Reason |
|-------|----------|--------|
| `https://spectrallabs.co` | Removed | Wrong/suspicious domain; use `spectrallabs.ai` instead |
| `https://cadscribe.co` | Removed | Broken/old domain; use `cadscribelabs.com` instead |
| `https://www.lambdafunction.com` | Removed | Wrong/parked-style domain; use `lambdafunction.ai` instead |
| `https://www.productivemachines.com` | Removed | Wrong domain; use `productivemachines.co.uk` instead |
| `Kapow / kapow.ai` | Removed | Voice/chat assistant for local businesses; not engineering quoting or manufacturing software |
| Matmatch | Removed for now | Site/link instability during review; re-add only if the official site is stable and relevant |
| Generic LangChain/CrewAI-only entries | Not core | Useful frameworks, but not engineering-specific unless tied to CAD/CAE/CAM workflows |
| Visual text-to-3D tools as “CAD” | Reclassified | Tripo/Meshy are useful, but primarily mesh/asset generation unless paired with CAD/B-Rep conversion |
| Small abandoned toy demos | Not core | Re-add only under “Experimental” if maintained and clearly useful to engineers |

---

<div align="center">

## Contributing

</div>

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

> [!NOTE]
> **What belongs here:** AI tools that help design, simulate, manufacture, inspect, quote, operate, or validate physical products. Open-source libraries for engineering AI. MCP servers with engineering capabilities. Research papers and datasets advancing AI for physical engineering.

> [!WARNING]
> **What does not belong:** pure software-dev tools, generic AI/ML frameworks without engineering application, unrelated business automation tools, domain-parked links, spam links, and abandoned projects with no engineering value.

---

<div align="center">

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

**If this list helped you, star it ⭐ and share it with an engineer.**

</div>
