# Rahulprasath Selvaraj

**AI & Automation Engineer** · Nuremberg, Germany

I build AI applications, train neural networks, and automate data workflows. My work spans document retrieval, local speech generation, and 3D reconstruction, from data preparation and GPU training to evaluation and model release.

[Portfolio](https://portfolio-nu-khaki-48.vercel.app) · [LinkedIn](https://linkedin.com/in/rahulprasath-s) · [Email](mailto:rahulprasathselvaraj@gmail.com)

---

### Selected work

| Project | What it does |
| :--- | :--- |
| **[Narrator](https://github.com/rahulprasath-s/Narrator)** | A reading and listening studio with Claude rewriting, saved AI briefs, and local CPU speech through KittenTTS Nano. |
| **[AI Daily Brief](https://github.com/rahulprasath-s/AI-Daily-Brief)** | Collects AI news and model updates, ranks and summarizes stories with NVIDIA NIM, and publishes deduplicated daily briefs to Notion. |
| **[Local Workspace Context Optimizer](https://github.com/rahulprasath-s/Local-Workspace-Context-Optimizer)** | Reusable workspace context and prompt caching for AI-assisted development. |
| **[Archisight](https://github.com/rahulprasath-s/3D-Visualization-of-Buildings)** | Interactive 3D building models from map data and manually traced footprints. |
| **[Careflow Intelligence](https://github.com/rahulprasath-s/Careflow_Intelligence)** | Local retrieval and question answering for medical PDFs, with source passages. |

Also built: [FabricIRIS](https://github.com/rahulprasath-s/FabricIRIS-Textile-Defect), for textile defect detection, and [Sign2Say](https://github.com/rahulprasath-s/Sign2Say), for gesture-to-speech accessibility.

### Trained models

**Koor v1 · Roof wireframe reconstruction**

Trained a [Point2Roof](https://github.com/Li-Li-Whu/Point2Roof)-based network to turn roof point clouds into 3D wireframes. Prepared synthetic data, adapted CUDA operations for university NVIDIA B200 GPUs, and completed training, evaluation, and a weights release.

At 2% corner tolerance, corner/edge micro-F1 reached **0.8891 / 0.8372** on 1,600 synthetic test roofs and **0.0212 / 0.0028** on 561 real Building3D buildings without fine-tuning. Training used synthetic data only; these results show a substantial real-data transfer gap. Outputs need inspection and do not represent complete buildings.

[Source code](https://github.com/rahulprasath-s/Koor) · [Hugging Face weights](https://huggingface.co/Uruva/Koor-building-reconstruction-v1) · [Evaluation methodology](https://github.com/rahulprasath-s/Koor/blob/main/docs/results.md) · [Licensing notes](https://github.com/rahulprasath-s/Koor/blob/main/LICENSING.md)

### Experience

**Soccerkinetics** · AI & Automation Engineer, Working Student · July–October 2026

Developed podcast summarization and financial-news monitoring applications, including backend integrations, background jobs, and persistent data storage. Contributed to an internal CRM for sales outreach and task coordination.

### Background

M.Sc. **Human & Artificial Intelligence**, University of Technology Nuremberg · 2025–present  
B.E. **Computer Science Engineering**, Sri Eshwar College of Engineering · 2021–2025

Published [research on making medical reports more accessible](https://ieeexplore.ieee.org/abstract/document/11108371) at ETCC 2025. Awarded **3rd prize at RTSH 2025** for an AI prototype built and pitched in 48 hours.

---

Python · PyTorch · CUDA · TypeScript · React · FastAPI · PostgreSQL · Docker · LLM APIs
