# Sanjaii Vijayakumar

### Computer vision · Robotics · Spatial AI

I build systems that connect visual perception to action: reconstructing spaces, detecting changes in 3D, and helping robots understand and interact with their surroundings.

I'm pursuing an **M.S. in Computer Science, Machine Learning Track, at Columbia University**, with graduation expected in **December 2026**. My work spans 3D vision, robot learning, and the engineering behind efficient AI systems.

[Email](mailto:sv2851@columbia.edu) · [LinkedIn](https://www.linkedin.com/in/sanjaiiv/) · [Explore my repositories](https://github.com/sanjaiiv04?tab=repositories)

## Selected work

### [What Changed in the Room?](https://github.com/sanjaiiv04/3D-Point-Cloud-Diffing)
**Two phone recordings → a spatial report of what was added, removed, or moved.**

A local pipeline combining joint COLMAP reconstruction, metric depth, occlusion-aware change detection, CLIP labeling, and interactive Rerun visualization. Includes the reasoning behind the design choices and the limits of monocular reconstruction.

`Python` · `COLMAP` · `Depth Anything V2` · `CLIP` · `Rerun`

### [Sparse 3D Reconstruction](https://github.com/sanjaiiv04/SfM-Sparse-3D-Reconstruction)
**From image correspondences to camera poses and sparse geometry.**

Built a structure-from-motion pipeline using SIFT, geometric filtering, RANSAC-based pose estimation, and iterative triangulation. Reported mean reprojection error below **0.8 pixels** in project evaluation.

`Computer vision` · `Multi-view geometry` · `Structure from motion`

### [Autonomous Robotic Manipulation](https://github.com/sanjaiiv04/VLA-ARM)
**Natural-language instructions → object detection → pick-and-place control.**

Built a 2D robotic manipulation system with a fine-tuned YOLOv11 detector and a UDP control pipeline sustaining **60 Hz servo updates**, with **18 ms servo delays** in project testing.

`Robot learning` · `YOLOv11` · `UDP` · `Real-time control`

### [MoodRoom](https://github.com/jklingen92/MoodRoom)
**From real-world captures to interactive Gaussian-splatted objects in Unity.**

Led a four-person Columbia team and architected an AnySplat-to-Unity pipeline for processing captures and streaming reconstructed assets through a Google OAuth-secured backend. The project supports object selection, runtime Gaussian-splat rendering, and 6DOF manipulation in a Meta Quest XR experience.

`Unity` · `C#` · `AnySplat` · `Gaussian splatting` · `Meta Quest` · `OpenXR`

### [AssetOpsBench: TSFM Agent Optimization](https://github.com/sanjaiiv04/AssetOpsBench)
**Profiling and optimizing an agent workflow built on IBM's AssetOpsBench.**

In a Columbia project, reduced workflow latency by **68%**, accelerated model inference **3.3×**, and reduced tool-call overhead **9×** in test runs through direct batched inference, model preloading, and caching.

`PyTorch Profiler` · `Weights & Biases` · `Inference optimization` · `AI agents`

### [CapRate Prompt Studio](https://github.com/sanjaiiv04/PromptChain-HumorProject)
**An interface for configuring, executing, and inspecting multi-step AI prompt chains.**

Supports ordered chain editing, model selection, per-step outputs, timing and token records, and generation history. Built with Next.js and a shared backend, with server-side provider credentials and role-based access.

`Next.js` · `LLM workflows` · `Full-stack development`

## Research & experience

- **Columbia CAVE Lab · Research Assistant · Jan–Apr 2026** — Contributed multi-camera dataset collection and setup for *Squash: 3D Object Assets and their Material Properties*, and worked on ROS2 communication and tactile-feedback monitoring for object manipulation.
- **IIT Madras Research Park, HTIC · Research Intern · Sep–Dec 2023** — Co-developed stereo-camera 3D mapping and integrated it with a modified SCARA robot for surgical registration; reported reconstruction error below **5 mm** and latency below **100 ms**.
- **VIT · Research Intern · Mar–Dec 2024** — Designed a vision transformer for NIR-based root-rot detection, achieving **86% accuracy**, and collaborated on a hydroponic growth chamber for training-data collection.

## Publications & intellectual property

- Contributing author, **“Beyond Static Leaderboards: Rank-Transfer Stability for the Evaluation of LLM Agents”** — arXiv preprint, 2026.
- **“Systems and Methods for Early Detection of Root Rot in Hydroponically Grown Plants”** — patent application **202541009221**, filed February 4, 2025.

## Tools I work with

- **Languages:** Python, C++, C#, TypeScript, JavaScript, SQL
- **Perception & 3D:** OpenCV, Open3D, COLMAP / pycolmap, Gaussian splatting, Agisoft Metashape, Rerun, Three.js
- **Robotics & XR:** ROS2, Unity, Unity XR Interaction Toolkit, OpenXR, Meta Quest, Unity Sentis, NVIDIA Omniverse, Arduino, UDP control
- **ML & inference:** PyTorch, TensorFlow, scikit-learn, Hugging Face Transformers, CUDA, vLLM
- **Vision & action models:** OpenVLA, YOLO, CLIP, Depth Anything V2 / V3, Qwen3-VL, AnySplat
- **Agents & evaluation:** LangChain, MCP / FastMCP, PyTorch Profiler, Weights & Biases
- **Audio & transcription:** librosa, faster-whisper, Qwen3-ASR, NVIDIA Parakeet, noisereduce
- **Web & applications:** React, Next.js, Tailwind CSS, Framer Motion, FastAPI, Streamlit
- **Data & scientific computing:** PostgreSQL, Supabase, NumPy, SciPy, Pandas, Matplotlib
- **Development & deployment:** Git, GitHub Actions, Docker, Linux, uv, AWS, SST, Vercel

## What I want to build next

I'm interested in spatially aware AI and robots that can move from interpreting a scene to acting within it. I want to deepen my work in robot learning, 3D scene understanding, and efficient perception-to-action systems, with an emphasis on reproducible evaluation and real-world constraints.

If you're working on related research or engineering problems, [let's connect](mailto:sv2851@columbia.edu).
