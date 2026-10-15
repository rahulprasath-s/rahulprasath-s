# Rahulprasath Selvaraj

**AI & Automation Engineer · M.Sc. Human & Artificial Intelligence Student**

I build practical AI systems that turn information into useful tools and repeatable workflows. My work focuses on LLM applications, retrieval-augmented generation (RAG), privacy-first local AI, and reliable automation.

Based in Nürnberg, Germany, I am pursuing an M.Sc. in Human & Artificial Intelligence at the University of Technology Nuremberg and working part-time as an AI & Automation Engineer at Soccerkinetics.

[GitHub](https://github.com/rahulprasath-s) · [LinkedIn](https://linkedin.com/in/rahulprasath-s) · [Email](mailto:rahulprasath17@gmail.com)

## Currently Working On

- **Backtester:** Building a backtesting tool for evaluating trading strategies on historical data.
- **Quantitative Model:** Training a quantitative model as part of my ongoing work in quantitative research.

Both projects are in progress.

## Experience

**Working Student — AI & Automation Engineer**

Soccerkinetics · July 2026–October 2026

- Build AI workflows and automations for product and operational tasks.
- Integrate data sources, tools, and AI systems into reliable day-to-day processes.

## Core Skills

- **AI engineering:** LLM applications, RAG, prompt engineering, structured outputs, prompt caching, Anthropic API, NVIDIA NIM
- **Local AI and retrieval:** Ollama, Qdrant, privacy-first document retrieval
- **Programming and backend:** Python, JavaScript, FastAPI, Node.js, SQL, MongoDB
- **Automation and deployment:** n8n, agentic workflows, GitHub Actions, Cloudflare Workers, Docker, Git, REST APIs, Notion API
- **Applied AI:** PyTorch, LangChain, OpenCV, NLP, OCR

## Projects

### [AI-Daily-Brief](https://github.com/rahulprasath-s/AI-Daily-Brief)

An automated AI news and research pipeline that collects content from arXiv, Hacker News, Hugging Face, and Techmeme, ranks news and summarizes items with NVIDIA NIM, and publishes a structured brief to Notion.

- Runs twice daily through GitHub Actions, with up to five papers and ten news items per digest date.
- Checks Notion history for duplicate links, titles, and similar news summaries.
- Supports dated backfills, source debugging, and an automated regression suite.

`Python` `GitHub Actions` `NVIDIA NIM` `Notion API` `Cloudflare Workers`

### Local Workspace Context Optimizer

A privacy-first CLI that compresses local workspace state into reusable context capsules, using prompt caching and structured outputs to support repeated development tasks.

- Includes a workspace scanner, polling watcher, CLI, and local web UI for repository snapshots and context capsules.
- Tracks prompt-cache reuse with a token-usage ledger and supports offline capsule generation with secret-file and dependency exclusions.

`Python` `Anthropic API` `Prompt Caching` `CLI`

### Archisight

A full-stack 3D visualization application that turns searched or manually traced building footprints into configurable building massing models that users can export.

- Supports configurable roof styles and integrates Google Maps and Places, OpenStreetMap/Overpass, Nominatim, and satellite contour extraction.
- Uses fallback geometry and camera scaling to handle different building sizes.

`React` `Three.js` `React Three Fiber` `Google Maps` `Node.js` `Express` `MongoDB`

### Careflow Intelligence

A fully local RAG system for querying sensitive medical documents while keeping document processing and retrieval on local infrastructure.

- Combines medical PDF ingestion, overlapping text chunks, MiniLM embeddings, and cosine-similarity search.
- Returns source metadata with retrieved passages through FastAPI and runs with Ollama in a Docker Compose setup.

`Python` `FastAPI` `Streamlit` `Sentence Transformers` `Ollama` `Qdrant` `Docker`

### FabricIRIS — Textile Defect Detection

A textile inspection application with live-camera and snapshot interfaces for detecting fabric defects using YOLO.

- Applies region-of-interest cropping, confidence filtering, and annotated detection boxes.
- Supports Core ML models for Apple Silicon, a PyTorch-weight fallback in the live detector, and a Streamlit camera interface for snapshot analysis.

`Python` `Ultralytics YOLO` `OpenCV` `Core ML` `Streamlit`

### Podcast Summarizer

**Developed at Soccerkinetics.** A self-hosted application that resolves podcast sources, processes transcripts, and produces structured summaries with chapter segmentation.

- Runs background jobs with PostgreSQL and Redis/RQ for persistent processing.
- Uses local Qwen inference through Ollama with configurable cloud-model fallback, retry handling, and validation of word budgets and timestamps.

`Next.js` `FastAPI` `PostgreSQL` `Redis/RQ` `Ollama` `Whisper` `Docker`

### News Scraper — Financial News Monitoring

**Developed at Soccerkinetics.** A locally hosted pipeline that collects German financial news and press releases, extracts stock identifiers, and resolves company names, tickers, WKNs, and ISINs.

- Includes campaign-page discovery, promotion-warning signals, and daily regulatory-source monitoring.
- Provides searchable dashboards for reviewing articles and linked financial instruments.

`Python` `FastAPI` `SQLAlchemy` `SQLite` `Trafilatura` `RSS` `OpenFIGI`

### Internal CRM

**Contributed at Soccerkinetics.** An internal CRM that gives the sales team a shared place to coordinate lead outreach, divide tasks, and support go-to-market work.

## Education

- **M.Sc. Human & Artificial Intelligence**, University of Technology Nuremberg — 2025–Present
- **B.E. Computer Science Engineering**, Sri Eshwar College of Engineering — 2021–2025

## Highlights

- **3rd Prize, RTSH 2025 Hackathon** — built and pitched an AI model within 48 hours.
- Published **[AI in Healthcare: Simplifying Medical Reports for Enhanced Patient Comprehension](https://ieeexplore.ieee.org/abstract/document/11108371)** at ETCC 2025.

## Contact

Interested in building an LLM application, a local document retrieval system, or an automation workflow? I am open to discussing projects and collaboration in these areas.

- Email: [rahulprasath17@gmail.com](mailto:rahulprasath17@gmail.com)
- LinkedIn: [linkedin.com/in/rahulprasath-s](https://linkedin.com/in/rahulprasath-s)
