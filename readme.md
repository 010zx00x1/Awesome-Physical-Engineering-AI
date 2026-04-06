<div align="center">

# 🔧 Awesome Physical Engineering AI🔧

<img width="460" height="232" alt="image" src="<img width="995" height="430" alt="image" src="https://github.com/user-attachments/assets/59b75d8f-be40-461d-a701-3865d0b71f1f" />
" />

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Last Update](https://img.shields.io/badge/Last_Update-April_2026-blue.svg)](#)

**A curated list of AI tools for hardware engineering — CAD, simulation, manufacturing, and beyond.**

Software engineers have thousands of AI tools.<br>
Hardware engineers get an afterthought sidebar.<br>
**This list fixes that.**

[Submit a Tool](#contributing) · [Report Broken Link](../../issues/new) · [Suggest Category](../../issues/new)

</div>

---

## Contents

- [🎨 CAD AI & Generative Geometry](#-cad-ai--generative-geometry)
- [⚡ Generative & Topology Optimization](#-generative--topology-optimization)
- [🧪 AI-Powered Simulation](#-ai-powered-simulation)
- [🏭 Design for Manufacturing (DFM)](#-design-for-manufacturing-dfm)
- [⚙️ CAM & CNC AI](#%EF%B8%8F-cam--cnc-ai)
- [👁️ Quality Inspection & Computer Vision](#%EF%B8%8F-quality-inspection--computer-vision)
- [🔮 Digital Twins & Predictive Maintenance](#-digital-twins--predictive-maintenance)
- [🔢 Engineering Calculations & Computation](#-engineering-calculations--computation)
- [🧱 Materials & Material Selection](#-materials--material-selection)
- [🔌 MCP Servers for Engineering](#-mcp-servers-for-engineering)
- [🤖 Robotics & Controls](#-robotics--controls)
- [🖨️ 3D Printing & Additive Manufacturing](#%EF%B8%8F-3d-printing--additive-manufacturing)
- [📦 PLM, PDM & Knowledge Management](#-plm-pdm--knowledge-management)
- [🧰 Open-Source CAD & CAE Foundations](#-open-source-cad--cae-foundations)
- [📄 AI Research Papers & Models](#-ai-research-papers--models)
- [🐍 Python Libraries for Engineers](#-python-libraries-for-engineers)
- [📚 Learning Resources](#-learning-resources)

---

## 🎨 CAD AI & Generative Geometry

> Tools that use AI to **create, edit, or understand** CAD models from text, sketches, or scans.

| Tool | Type | What it does | Open Source |
|------|------|-------------|:-----------:|
| [Zoo Design Studio](https://zoo.dev) | Platform | Text-to-CAD generating editable B-Rep STEP files via KCL language | Partial |
| [Spectral Labs (SGS-1)](https://spectrallabs.co) | Platform | Generates parametric 3D models from text, sketches, or 3D scans | ❌ |
| [Tripo](https://tripo3d.ai) | Platform | High-quality text/image-to-3D. Exports FBX, GLB, OBJ. Blender/Unity plugins | Partial |
| [Meshy](https://meshy.ai) | Platform | Text-to-3D and image-to-3D with PBR textures. Rapid prototyping | ❌ |
| [CADAM](https://github.com/Adam-CAD/CADAM) | Web App | Text-to-CAD using Claude API + OpenSCAD + WebAssembly. Exports STL/SCAD | ✅ |
| [CQAsk](https://github.com/OpenOrion/CQAsk) | CLI/Web | LLM-powered CAD generation using CadQuery. Exports STL/STEP | ✅ |
| [text-2-cad](https://github.com/roberto-ceraolo/text-2-cad) | Library | LLM-generated OpenSCAD code with RAG for steerable CAD | ✅ |
| [GenCAD-3D](https://arxiv.org/abs/2409.17106) | Research | Converts point clouds into editable parametric feature trees | ✅ |
| [CADScribe](https://cadscribe.co) | Web App | Text prompts → editable STEP files in browser | ❌ |
| [SolidWorks AURA](https://www.solidworks.com) | Plugin | AI assistant in 3DEXPERIENCE: command prediction, smart mates | ❌ |
| [Autodesk Fusion AI](https://www.autodesk.com/products/fusion-360) | Built-in | Auto sketch constraints, drawing creation, CNC toolpath | ❌ |
| [Siemens NX AI](https://plm.sw.siemens.com/en-US/nx/) | Built-in | Predictive modeling, feature recognition, learns user patterns | ❌ |
| [PTC Creo AI](https://www.ptc.com/en/products/creo) | Built-in | Part recognition, assembly management, simulation prediction | ❌ |

<br>

## ⚡ Generative & Topology Optimization

> AI-driven tools that **generate or optimize geometry** for weight, strength, cost, or thermal performance.

| Tool | Key Strength | Best For | Open Source |
|------|-------------|----------|:-----------:|
| [Autodesk Fusion Generative Design](https://www.autodesk.com/solutions/generative-design-ai-software) | Multi-method optimization (additive, milling, casting) | Comparing manufacturing methods | ❌ |
| [nTopology (nTop)](https://www.ntop.com) | Implicit modeling, field-driven lattices, gyroids | Aerospace/medical lightweighting | ❌ |
| [Siemens NX Generative Engineering](https://plm.sw.siemens.com/en-US/nx/) | Convergent Modeling: mesh + B-Rep in same model | Large enterprises on Siemens stack | ❌ |
| [MSC Apex Generative Design](https://hexagon.com/products/product-groups/computer-aided-engineering-software) | Auto re-surfacing: optimization → print-ready surfaces | Bridging optimization to production | ❌ |
| [PTC Creo GDX](https://www.ptc.com/en/products/creo/generative-design) | Cloud optimization → editable B-Rep in native Creo | Creo-native workflows | ❌ |
| [Altair HyperWorks](https://altair.com/hyperworks) | PhysicsAI surrogates 100-1000x faster. NL optimization setup | High-throughput design exploration | ❌ |
| [Monolith](https://www.monolithai.com) | No-code AI from test & simulation data | Teams without ML expertise | ❌ |
| [PartCAD](https://github.com/openvmp/partcad) | Open-source digital thread with AI. CadQuery/build123d support | Open-source product documentation | ✅ |

<br>

## 🧪 AI-Powered Simulation

> AI that **accelerates or replaces** traditional FEA/CFD solvers.

| Tool | Approach | Speedup | Open Source |
|------|----------|---------|:-----------:|
| [Ansys SimAI](https://www.ansys.com/products/simai) | Generative AI trained on historical simulation data | 10-100x | ❌ |
| [Ansys Engineering Copilot](https://www.ansys.com) | NL assistant in Discovery & Fluent | Setup time | ❌ |
| [Altair PhysicsAI](https://altair.com) | Trained surrogates replacing solvers | 100-1000x | ❌ |
| [Neural Concept](https://www.neuralconcept.com) | Deep learning for aero/thermal from 3D geometry | Real-time | ❌ |
| [SimScale](https://www.simscale.com) | Cloud CFD/FEA with AI-driven meshing | Variable | ❌ |
| [Productive Machines (SenseNC)](https://www.productivemachines.com) | AI milling optimization: chatter, tool wear, breakage prediction | 2-5x tool life | ❌ |
| [NVIDIA Modulus](https://developer.nvidia.com/modulus) | Framework for physics-informed neural networks | GPU-accel | ✅ |
| [PhiFlow](https://github.com/tum-pbs/PhiFlow) | Differentiable PDE solving (PyTorch/TF/JAX) | Variable | ✅ |
| [DeepXDE](https://github.com/lululxvi/deepxde) | PINNs and deep operator networks | Variable | ✅ |
| [FourCastNet](https://github.com/NVlabs/FourCastNet) | Fourier neural operators for high-res prediction | 1000x+ | ✅ |

<br>

## 🏭 Design for Manufacturing (DFM)

> AI tools for catching manufacturability issues **before they become expensive**.

| Tool | What it checks | Integrations | Open Source |
|------|---------------|-------------|:-----------:|
| [bananaz](https://www.bananaz.ai) | DFM, GD&T, tolerance analysis, drawing review, 3D assembly comparison | SolidWorks, Creo | ❌ |
| [CoLab AutoReview](https://www.colabsoftware.com) | Multi-step agentic review: title blocks, callouts, DFM, cross-view consistency | Native CAD files | ❌ |
| [Leo AI](https://www.getleo.ai) | Part search, calculations, design validation from PLM data + 1M sources | CAD/PLM platforms | ❌ |
| [Autodesk Fusion DFM](https://www.autodesk.com/products/fusion-360/design-for-manufacturing) | Injection molding simulation, toolpath generation, cost estimation | Fusion ecosystem | ❌ |
| [DFMPro](https://dfmpro.geometricglobal.com) | Rules-based checks: machining, molding, casting, sheet metal | SW, Creo, NX, CATIA | ❌ |
| [Xometry Instant Quoting](https://www.xometry.com) | AI-powered quotes with DFM feedback | Upload STEP/STL | ❌ |
| [Hubs (Protolabs)](https://www.hubs.com) | Instant DFM analysis + quoting for CNC, 3D printing, injection molding | Upload STEP/STL | ❌ |

<br>

## ⚙️ CAM & CNC AI

> AI tools that **automate CNC programming**, optimize toolpaths, and capture machinist knowledge.

| Tool | What it does | Integrations | Open Source |
|------|-------------|-------------|:-----------:|
| [CloudNC CAM Assist](https://www.cloudnc.com) | AI toolpath generation for 3- and 3+2-axis. Physics-based feeds & speeds. 1000+ shops using it daily | Mastercam, Fusion, GibbsCAM, SolidCAM, NX | ❌ |
| [Lambda Function](https://www.lambdafunction.com) | AI CNC assistant with feature recognition. Learns from machinists. Closed-loop shop floor feedback | Siemens NX (Mastercam, Fusion coming) | ❌ |
| [LimitlessCNC](https://www.limitlesscnc.com) | AI CAM agent that adapts to your tools, tolerances, and machine limits. Learns from historical programs | Mastercam | ❌ |
| [Toolpath](https://toolpath.com) | AI-powered CAM: op planning, estimating, DFM, and Fusion-ready toolpaths using your tools | Autodesk Fusion | ❌ |
| [Mastercam Copilot](https://www.mastercam.com) | Voice-controlled AI assistant. 200 toolpath types. Adjusts feeds/speeds across operations | Mastercam 2026.R2 | ❌ |
| [Siemens NX Manufacturing Copilot](https://plm.sw.siemens.com/en-US/nx/) | AI-guided programming decisions and automated repetitive steps | NX CAM | ❌ |

<br>

## 👁️ Quality Inspection & Computer Vision

> AI-powered **visual inspection, defect detection**, and quality control for manufacturing.

| Tool | What it does | Open Source |
|------|-------------|:-----------:|
| [Roboflow](https://roboflow.com) | End-to-end CV platform: annotate, train, deploy. 200M+ images, 200K+ datasets. Edge + cloud | Partial ✅ |
| [Roboflow Inference](https://github.com/roboflow/inference) | Production-ready inference server for CV models. Edge to cloud. Apache 2.0 | ✅ |
| [Roboflow Supervision](https://github.com/roboflow/supervision) | Reusable CV tools: annotation, tracking, counting. Apache 2.0 | ✅ |
| [Landing AI (LandingLens)](https://landing.ai) | Visual inspection platform by Andrew Ng. No-code defect detection for manufacturing | ❌ |
| [Lincode LIVIS](https://lincode.ai) | AI visual inspection with pre-trained manufacturing models. No-code training. SOC 2 | ❌ |
| [Overview.ai](https://www.overview.ai) | Sub-100ms defect detection. Browser-based setup in under 1 hour | ❌ |
| [Tritva (Ombrulla)](https://ombrulla.com) | AI visual inspection with continuous model monitoring and drift detection | ❌ |
| [NVIDIA DeepStream](https://developer.nvidia.com/deepstream-sdk) | Streaming analytics SDK for multi-sensor processing on edge | Partial |
| [Ultralytics YOLOv8/YOLO11](https://github.com/ultralytics/ultralytics) | State-of-the-art object detection. Widely used for manufacturing inspection | ✅ |
| [OpenCV](https://github.com/opencv/opencv) | The foundational open-source computer vision library | ✅ |

> [!TIP]
> [Roboflow Universe](https://universe.roboflow.com) hosts thousands of free manufacturing-specific datasets (PPE detection, defect classification, assembly verification) ready to train on.

<br>

## 🔮 Digital Twins & Predictive Maintenance

> AI for **virtual representations of physical systems**, condition monitoring, and failure prediction.

| Tool | What it does | Open Source |
|------|-------------|:-----------:|
| [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/) | Platform for building physically accurate digital twins. USD-based. Real-time simulation | Partial |
| [Eclipse Ditto](https://github.com/eclipse-ditto/ditto) | Framework for digital twins of IoT devices. Manages thing state, messaging, access | ✅ |
| [Azure Digital Twins](https://azure.microsoft.com/en-us/products/digital-twins) | Cloud platform for modeling physical environments. DTDL ontology | ❌ |
| [AWS IoT TwinMaker](https://aws.amazon.com/iot-twinmaker/) | Build digital twins from IoT data, video, and 3D models | ❌ |
| [predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) | MCP server for vibration analysis, bearing fault detection, ISO compliance via LLMs | ✅ |
| [Open Source Digital Twin](https://github.com/Open-Source-Digital-Twin) | Open-source motion control playground and controller for digital twin research | ✅ |
| [awesome-digital-twins](https://github.com/edt-community/awesome-digital-twins) | Curated list of digital twin resources, papers, frameworks | ✅ |

<br>

## 🔢 Engineering Calculations & Computation

> Libraries for **unit-aware calculations, automated reporting**, and engineering math.

| Library | What it solves | Language | Open Source |
|---------|---------------|---------|:-----------:|
| [handcalcs](https://github.com/connorferster/handcalcs) | Renders calculations as handwritten LaTeX from code | Python | ✅ |
| [forallpeople](https://github.com/connorferster/forallpeople) | SI units that look like real engineering notation | Python | ✅ |
| [MechLab](https://pypi.org/project/mechlab/) | Statics, dynamics, thermo, fluids, control systems | Python | ✅ |
| [DynPy](https://github.com/bogumilchilinski/dynpy) | Dynamic mechanical & electrical system simulation | Python | ✅ |
| [PyniteFEA](https://github.com/JWock82/PyNite) | 3D structural finite element analysis | Python | ✅ |
| [sectionproperties](https://github.com/robbievanleeuwen/section-properties) | Cross-section analysis: elastic, plastic, warping | Python | ✅ |
| [structuralcodes](https://github.com/fib-international/structuralcodes) | Structural calculations per international codes | Python | ✅ |
| [fluids](https://github.com/CalebBell/fluids) | Pipe flow, compressible flow, open channel, two-phase | Python | ✅ |
| [CoolProp](https://github.com/CoolProp/CoolProp) | Thermophysical properties for 100+ fluids | C++/Python | ✅ |
| [pint](https://github.com/hgrecco/pint) | Physical quantities with unit conversion | Python | ✅ |
| [Engineering Equation Solver (EES)](https://fchartsoftware.com/ees/) | Coupled nonlinear equations with built-in thermo property functions | Proprietary | ❌ |

<br>

## 🧱 Materials & Material Selection

> AI for **finding, comparing, and optimizing** material choices.

| Tool | Type | Description | Open Source |
|------|------|-------------|:-----------:|
| [Granta MI (Ansys)](https://www.ansys.com/products/materials) | Enterprise | AI-powered material selection integrated with simulation | ❌ |
| [Citrine Informatics](https://citrine.io) | Platform | AI for materials R&D. Predicts properties, optimizes formulations | ❌ |
| [MatWeb](https://www.matweb.com) | Database | Free searchable database: metals, plastics, ceramics, composites | ❌ |
| [Matmatch](https://matmatch.com) | Platform | AI-assisted material search and supplier matching | ❌ |
| [thermo](https://github.com/CalebBell/thermo) | Library | Thermodynamics & phase equilibrium. Equation of state calculations | ✅ |
| [chemicals](https://github.com/CalebBell/chemicals) | Library | Chemical properties database and estimation | ✅ |
| [pymatgen](https://github.com/materialsproject/pymatgen) | Library | Materials analysis library. Crystal structures, phase diagrams, electronic properties | ✅ |

<br>

## 🔌 MCP Servers for Engineering

> [Model Context Protocol](https://modelcontextprotocol.io) servers that give AI agents **engineering superpowers**.

> [!TIP]
> MCP servers let you control CAD software from Claude, Cursor, or any MCP-compatible AI client using natural language.

| Server | Target | Features | Note |
|--------|--------|----------|:----:|
| [freecad-mcp](https://github.com/neka-nat/freecad-mcp) (neka-nat) | FreeCAD | Documents, primitives, booleans, export, remote control | ⭐ Most complete |
| [freecad-mcp](https://github.com/contextform/freecad-mcp) (contextform) | FreeCAD | PartDesign (13 ops), Part (18 ops). One-command npm install | ⭐ Easiest setup |
| [freecad-mcp](https://github.com/bonninr/freecad_mcp) (bonninr) | FreeCAD | Script execution, scene inspection | — |
| [cadquery-mcp-server](https://github.com/rishigundakaram/cadquery-mcp-server) | CadQuery | NL → parametric CAD with geometric verification | — |
| [mcp-cadquery](https://github.com/bertvanbrakel/mcp-cadquery) | CadQuery | Full-featured: scripts, SVG export, part library | — |
| [CAD-MCP](https://github.com/daobataotie/CAD-MCP) | AutoCAD+ | Controls AutoCAD, GstarCAD, ZWCAD via natural language | — |
| [predictive-maintenance-mcp](https://github.com/LGDiMaggio/predictive-maintenance-mcp) | PdM | Vibration analysis, bearing faults, ML anomaly detection, ISO reports | ⭐ Unique |

<br>

## 🤖 Robotics & Controls

> AI tools for **mechanism design, control systems**, and robotic systems.

| Tool | Domain | Open Source |
|------|--------|:-----------:|
| [ROS 2 + MoveIt](https://moveit.ai) | Motion planning, AI-powered grasping | ✅ |
| [NVIDIA Isaac](https://developer.nvidia.com/isaac) | Robotics simulation, synthetic data generation | Partial |
| [MuJoCo](https://mujoco.org) | Physics engine for RL and model-based optimization | ✅ |
| [PyBullet](https://pybullet.org) | Physics simulation for robotics and ML | ✅ |
| [python-control](https://python-control.readthedocs.io) | Transfer functions, state space, frequency response | ✅ |
| [Pyslvs](https://github.com/KmolYuan/Pyslvs-UI) | Planar linkage mechanism simulation & synthesis | ✅ |
| [Drake](https://drake.mit.edu) | Model-based design and control. Multibody dynamics, optimization | ✅ |

<br>

## 🖨️ 3D Printing & Additive Manufacturing

> AI tools for **optimizing additive manufacturing** workflows.

| Tool | What it does | Open Source |
|------|-------------|:-----------:|
| [nTop Lattice Optimization](https://www.ntop.com) | AI-driven lattice generation, field-driven density | ❌ |
| [Materialise Magics](https://www.materialise.com/en/industrial/software/magics) | AM data prep, AI build orientation & support generation | ❌ |
| [Autodesk Netfabb](https://www.autodesk.com/products/netfabb) | Build process simulation, distortion prediction | ❌ |
| [PrusaSlicer](https://github.com/prusa3d/PrusaSlicer) | Adaptive layer height, paint-on supports | ✅ |
| [CuraEngine](https://github.com/Ultimaker/CuraEngine) | Extensible slicing engine with plugin system | ✅ |
| [OctoPrint](https://github.com/OctoPrint/OctoPrint) | Printer management + AI failure detection via Obico | ✅ |
| [Obico](https://github.com/TheSpaghettiDetective/obico-server) | AI-powered 3D print failure detection. Watches your prints via webcam | ✅ |

<br>

## 📦 PLM, PDM & Knowledge Management

> AI for **managing engineering data**, capturing design intent, and preventing knowledge loss.

| Tool | Key Capability | Open Source |
|------|---------------|:-----------:|
| [CoLab](https://www.colabsoftware.com) | AI Knowledge Graph from collaborative design reviews. Surfaces past mistakes proactively | ❌ |
| [Leo AI](https://www.getleo.ai) | Engineering Q&A grounded in your PLM data + 1M sources. 96-98% accuracy. SOC 2 certified | ❌ |
| [OpenBOM](https://www.openbom.com) | Cloud BOM and inventory management for engineering teams | ❌ |
| [Aras Innovator](https://www.aras.com) | Open-source core PLM for complex product lifecycle management | Partial |
| [GrabCAD](https://grabcad.com) | Free CAD model library (millions of models) + GrabCAD Print for AM workflow management | ❌ |

<br>

## 🧰 Open-Source CAD & CAE Foundations

> The **base tools** that engineering AI is being built on top of.

<details>
<summary><b>CAD Kernels & Modelers</b></summary>

| Tool | Description |
|------|-------------|
| [FreeCAD](https://www.freecad.org) | Parametric 3D modeler with Python API. Foundation for most engineering AI integrations |
| [CadQuery](https://github.com/CadQuery/cadquery) | Python scripting CAD on OCCT. Outputs STEP/STL/DXF. Ideal for AI code generation |
| [build123d](https://github.com/gumyr/build123d) | Modern Python CAD API on OCCT. Successor to CadQuery's builder pattern |
| [OpenCASCADE (OCCT)](https://dev.opencascade.org) | The open-source geometry kernel powering FreeCAD, CadQuery, and most OSS CAD |
| [OpenSCAD](https://openscad.org) | Script-based solid modeler. CSG via code. Popular for AI-generated geometry |
| [ImplicitCAD](https://github.com/Haskell-Things/ImplicitCAD) | Programmatic CAD with implicit functions. Rounded unions, smooth interfaces |

</details>

<details>
<summary><b>Simulation Solvers</b></summary>

| Tool | Domain |
|------|--------|
| [OpenFOAM](https://www.openfoam.com) | CFD toolbox. Industry-standard for fluid dynamics |
| [CalculiX](http://www.calculix.de) | FEA: structural, thermal, multiphysics. ABAQUS-compatible |
| [Elmer](https://www.elmerfem.org) | Multiphysics FEM: fluid, structure, thermal, electromagnetics |
| [FEniCS](https://fenicsproject.org) | PDE computing platform using finite elements |
| [SfePy](https://sfepy.org) | Simple Finite Elements in Python |
| [SU2](https://su2code.github.io) | CFD and multiphysics optimization. Used in aerospace |
| [MFEM](https://mfem.org) | Scalable finite element library. High-order methods. GPU support |

</details>

<details>
<summary><b>Meshing & Visualization</b></summary>

| Tool | Purpose |
|------|---------|
| [Gmsh](https://gmsh.info) | 3D finite element mesh generator with CAD engine |
| [ParaView](https://www.paraview.org) | Data analysis and visualization for simulation results |
| [Salome](https://www.salome-platform.org) | Pre/post-processing for numerical simulations |
| [PyVista](https://docs.pyvista.org) | 3D mesh visualization and analysis in Python |
| [VTK](https://vtk.org) | Visualization toolkit. Foundation for ParaView and PyVista |

</details>

<br>

## 📄 AI Research Papers & Models

> Academic work **pushing the boundaries** of AI in physical engineering.

<details>
<summary><b>CAD Generation</b></summary>

| Paper | Venue | Contribution |
|-------|-------|-------------|
| [Text2CAD](https://arxiv.org/abs/2409.17106) | NeurIPS 2024 Spotlight | Sequential CAD from beginner-to-expert text prompts |
| [DeepCAD](https://github.com/ChrisWu1997/DeepCAD) | ICCV 2021 | Deep generative network for CAD autocompletion |
| [BrepGen](https://arxiv.org/abs/2401.15563) | 2024 | B-Rep model generation via diffusion |
| [HNC for CAD](https://github.com/3dlg-hcvc/s2cad) | ICML 2023 | Hierarchical neural coding for controllable CAD generation |
| [Point-E](https://github.com/openai/point-e) | OpenAI 2023 | Point cloud generation from text. Fast 3D object creation |

</details>

<details>
<summary><b>Physics & Simulation</b></summary>

| Paper | Venue | Contribution |
|-------|-------|-------------|
| [PINNs](https://github.com/maziarraissi/PINNs) | JCP 2019 | Physics-constrained neural network PDE solving |
| [Fourier Neural Operator](https://github.com/neuraloperator/neuraloperator) | ICLR 2021 | Learning mappings between function spaces |
| [MeshGraphNets](https://arxiv.org/abs/2010.03409) | ICML 2021 | Mesh-based simulation with graph neural networks |
| [Modulus Sym](https://github.com/NVIDIA/modulus-sym) | NVIDIA 2023 | Symbolic PINNs framework for multi-physics |

</details>

<details>
<summary><b>3D Reconstruction & Perception</b></summary>

| Paper | Venue | Contribution |
|-------|-------|-------------|
| [3D Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) | SIGGRAPH 2023 | Real-time radiance field rendering. Scan-to-model |
| [PointFlow](https://github.com/stevenygd/PointFlow) | ICCV 2019 | 3D point cloud generation with continuous normalizing flows |
| [NeRF](https://www.matthewtancik.com/nerf) | ECCV 2020 | Neural radiance fields for 3D scene representation |

</details>

<br>

## 🐍 Python Libraries for Engineers

> The scientific Python stack **every engineering AI tool is built on**.

<details>
<summary><b>Core Scientific Stack</b></summary>

[NumPy](https://numpy.org) · [SciPy](https://scipy.org) · [SymPy](https://www.sympy.org) · [Matplotlib](https://matplotlib.org) · [pandas](https://pandas.pydata.org)

</details>

<details>
<summary><b>3D & Mesh Processing</b></summary>

[PyVista](https://docs.pyvista.org) · [trimesh](https://trimsh.org) · [meshio](https://github.com/nschloe/meshio) · [pygmsh](https://github.com/meshpro/pygmsh) · [Open3D](http://www.open3d.org)

</details>

<details>
<summary><b>Simulation Interfaces</b></summary>

[PyFoam](https://github.com/oxygen-dioxide/PyFOAM) · [pyNastran](https://github.com/SteveDoyle2/pyNastran) · [OpenAeroStruct](https://github.com/mdolab/OpenAeroStruct) · [OpenMDAO](https://openmdao.org)

</details>

<details>
<summary><b>Computer Vision for Manufacturing</b></summary>

[OpenCV](https://opencv.org) · [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) · [Roboflow Supervision](https://github.com/roboflow/supervision) · [Roboflow Inference](https://github.com/roboflow/inference) · [Detectron2](https://github.com/facebookresearch/detectron2)

</details>

<br>

## 📚 Learning Resources

| Resource | Focus |
|----------|-------|
| [Flocode Newsletter](https://www.flocode.dev) | Python for civil/structural engineers. Beginner to advanced |
| [Structural Python](https://www.structuralpython.com) | Automated Structural Engineering Toolkits (ASETs) |
| [Python Libraries for Engineers](https://github.com/joreilly86/Python-Libraries-for-Engineers) | Curated database for professional engineers |
| [SplineCloud Blog](https://splinecloud.com/blog/python-for-mechanical-engineers/) | Practical Python tutorials for mechanical engineers |
| [MIT OCW: Mechanical Engineering](https://ocw.mit.edu/courses/mechanical-engineering/) | Free university courses |
| [awesome-mecheng](https://github.com/m2n037/awesome-mecheng) | Classic awesome list: books, courses, references |
| [awsomeEngSci](https://github.com/Foadsf/awsomeEngSci) | Comprehensive FOSS list for engineering & science |
| [awesome-digital-twins](https://github.com/edt-community/awesome-digital-twins) | Papers, frameworks, and tools for digital twins |
| [Roboflow Universe](https://universe.roboflow.com) | 200M+ images, 200K+ open datasets for CV model training |

<br>

---

<div align="center">

## Contributing

</div>

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

> [!NOTE]
> **What belongs here:** AI tools that help design, simulate, manufacture, or validate physical products. Open-source libraries for engineering AI. MCP servers with engineering capabilities. Research papers advancing AI for physical engineering.

> [!WARNING]
> **What doesn't belong:** Pure software dev tools. Generic AI/ML frameworks without engineering application. Abandoned projects (no activity 12+ months).

---

<div align="center">

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

**If this list helped you, star it ⭐ and share it with an engineer.**

</div>
