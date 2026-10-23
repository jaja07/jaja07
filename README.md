## Hi, I'm Jarfino

**AI / ML Engineer.** I build LLM agents, RAG pipelines and the backends that bring them to users, with a background in data science and computer vision.

Engineer from ESIGELEC (Big Data) · MSc Artificial Intelligence at ECE Paris · Rennes, France
**Open to AI / ML Engineer roles from February 2027.**

---

### What I'm doing now

**AI Engineer intern @ ALTEN (Rennes)** — agentic application that helps map consultant missions: a ReAct agent (LangGraph) served through FastAPI, an MCP server (FastMCP) exposing an agentic RAG pipeline over internal technical documents, and human-in-the-loop validation of low-confidence extractions. Models served on Azure AI Foundry.

Previously: MLOps platform internship @ ALTEN (Sophia-Antipolis, 2025).

---

### Selected projects

**LLM agents & RAG**

- **[ARIA](https://github.com/jaja07/Hack2Cash)** — LangGraph agent that analyses activity reports (CSV, Excel, PDF…), applies the TRIZ method and returns traceable recommendations. A sub-agent writes, tests and registers missing extraction tools; tools exposed through MCP. *Hackathon, team of 3 — I built the FastAPI backend, persistence and real-time WebSocket streaming of the agent graph.* · [demo](https://hack2-cash.vercel.app)
- **[TARA](https://github.com/jaja07/Transformation-Analysis-Roadmap-Agent)** — six specialised LangGraph sub-agents turn a business case into a digital transformation roadmap, grounded in academic frameworks retrieved from a local RAG (ChromaDB, Llama 3.3 70B via NVIDIA NIM). *Team of 3 — project architecture, FastAPI API, frontend and agent integration.*

**LLM efficiency**

- **[Gemma 4 Pruning](https://github.com/jaja07/Gemma4-Pruning)** — training-free structured pruning of Gemma 4 E4B: redundant FFN neurons identified from their activations with mutual information, then clustered. 30 % fewer text FFN neurons (~1B parameters removed), whole pipeline running on an 8 GB laptop GPU in 4-bit. Model published on [Hugging Face](https://huggingface.co/Jaja07/gemma4-pruned-mi), vLLM-compatible.

**Computer vision**

- **[P.R.I.S.M.A](https://github.com/jaja07/P.R.I.S.M.A-PCB-Recognition-and-Inspection-Serverless-ML-Architecture-)** — PCB quality control: OpenCV comparison with a reference board + CNN exported to ONNX (96.2 % accuracy, 6 defect classes), on an event-driven serverless architecture (Azure Functions, Container Apps, Cosmos DB) that scales to zero.
- **[Human-Robot Interaction](https://github.com/jaja07/Human-robot-interaction-detection)** — two YOLOv8 models in parallel: person detection + 5 command gestures fine-tuned on HaGRID (mAP50 0.995, 2.2 ms per image). Streamlit and real-time webcam demos.

**Machine learning & RL**

- **[RescueBot](https://github.com/jaja07/Rescue-Bot)** — rescue robot trained from scratch with REINFORCE (CNN + MLP policy, action masking, custom Pygame environment): all 5 survivors evacuated in 91 % of test episodes. *Built with a teammate; the `rescue_bot` package is mine.*
- **[Urban Crime Analysis](https://github.com/jaja07/Urban_crime_analysis)** — 7.9 M Chicago police records cleaned down to 6 M reliable incidents, spatio-temporal forecasting with a chronological split (XGBoost: −37 % RMSE vs Ridge), KMeans risk zones.

---

### Tech stack

**LLM & agents** — LangGraph, LangChain, MCP (FastMCP), RAG (ChromaDB), Hugging Face Transformers, vLLM, Azure AI Foundry, NVIDIA NIM
**ML / DL** — PyTorch, scikit-learn, XGBoost, Ultralytics YOLOv8, OpenCV, ONNX Runtime
**Backend & data** — Python, FastAPI, SQLModel, PostgreSQL, Alembic, WebSocket, pandas
**Cloud & MLOps** — Docker, Azure (Functions, Container Apps, Cosmos DB), uv

---

### 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](www.linkedin.com/in/jarfino-houngbadji)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Jaja07-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/Jaja07)
[![Email](https://img.shields.io/badge/Email-jarfinoh%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:jarfinoh@gmail.com)

Outside of code: anime, video games and a lot of coffee ☕
