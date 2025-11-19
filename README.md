# 🚀 AutoRAG OS — The RAG Factory for Every Business

AutoRAG OS is an end-to-end platform that **automatically converts messy enterprise documents** (PDFs, scans, images, audio, PPTs, screenshots) into a fully-governed, citation-backed **RAG assistant**—in under **60 seconds**.

Built for non-technical teams. Powered by **Gemini**, **Opus**, **AIML OCR/STT**, and **Qdrant**.

> **Upload → AutoRAG → Trustworthy AI Assistant. Automatically.**

---

# 🔥 Demo

👉 **Live Demo URL:** *https://autoragos.vercel.app/*

👉 **Demo Files Included:** https://drive.google.com/drive/folders/1Ql1omj50BiCgeOiOaouivg0SxDDbSlVC?usp=drive_link

---

# 📽 Video Demo

👉 *https://drive.google.com/file/d/1m3leArJ4W8G3L6oGo9lY1ZX2CrQoSUqc/view?usp=sharing*

---

# 📄 Slide Deck (PDF)

👉 *https://drive.google.com/file/d/1WhKQMPH-l7avGIdCi_ymxCQTiwPBIV17/view?usp=sharing*

---

# 🎯 What AutoRAG OS Does

AutoRAG OS eliminates the complexity of RAG systems by automating the **entire pipeline**:

1. **Multimodal Ingestion**
   PDFs → scans → screenshots → PPTX → audio → everything processed automatically
   (OCR, STT, captioning)

2. **Data Cleaning & Chunking**
   Gemini rewrites messy text → semantic chunking → metadata labeling

3. **Embeddings & Indexing**
   High-quality Gemini embeddings stored in **Qdrant** (workspace-isolated)

4. **RAG Assistant Generation**
   Auto-created system prompt
   Grounded generation using retrieved context only

5. **Validation & Governance**
   Opus validates hallucinations
   Confidence scoring
   Human review escalation

6. **Instant Deployment**
   Your workspace becomes a fully functional AI assistant with citations

---

# 🧩 Architecture Overview

**Gemini** – Multimodal extraction, chunking, embeddings, grounded generation
**AIML API** – OCR + Speech-to-Text
**Opus** – Workflow orchestration + validation engine
**Qdrant** – Vector database (semantic search)
**Python Backend** – Ingestion, APIs, embedding helpers
**Streamlit / Web UI** – Demo interface

```
Upload Files →
  Extract (OCR/STT) →
    Clean & Chunk →
      Embed (Gemini) →
        Store (Qdrant) →
          Retrieve →
            Validate (Opus) →
              Answer with citations
```

---

# 🧪 Features

✔ Automatic multimodal ingestion
✔ Smart chunking using Gemini
✔ One collection per workspace
✔ RAG Quality Score computation
✔ Citations + confidence scoring
✔ Clarifying questions for ambiguous queries
✔ “I don’t know” safe fallback
✔ Human-in-the-loop review
✔ Plug-and-play demo UI

---

# 🚀 Quick Start (Local Setup)

### 1. Clone Repo

```bash
git clone https://github.com/banikunjpatel/autoragos2.git
cd autoragos2
```

### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

### 3. Add Environment Variables

Create `.env`:

```
GEMINI_API_KEY=your_key
QDRANT_URL=your_url
QDRANT_API_KEY=your_key
QDRANT_COLLECTION=autorag
OPUS_API_KEY=your_key
OPUS_WORKFLOW_ID=your_endpoint
OPUS_RUN_URL=your_endpoint
```

# 📁 Repository Structure

```
autorag-os/
├─ backend/
│  ├─ services/                
│     └─ aiml_client.py
      └─ gemini_client.py
      └─ opus_client.py
      └─ qdrant_client.py
    ├─ main.py
    ├─ requirements.txt
     
client/
├── public/
├── src/
│   ├── components/
│   │   ├── ui/
│   │   └── NavLink.tsx
│   ├── hooks/
│   ├── lib/
│   ├── pages/
│   │   ├── Chat.tsx
│   │   ├── Dashboard.tsx
│   │   ├── Index.tsx
│   │   ├── Landing.tsx
│   │   ├── NotFound.tsx
│   │   ├── Processing.tsx
│   │   └── WorkspaceSetup.tsx
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── package.json
├── tsconfig.json
└── README.md
```

---

# 📦 Tech Stack

| Component             | Technology                   |
| --------------------- | ---------------------------- |
| Multimodal Extraction | Gemini Vision + AIML OCR/STT |
| Embeddings            | Gemini Embedding             |
| Vector DB             | Qdrant                       |
| Workflow Engine       | Opus                         |
| Backend               | Python / FastAPI             |
| Demo UI               | Streamlit                    |
| Deployment            | Vercel / Streamlit Cloud     |

---

# 🧮 Business Model

**Freemium → Pro → Team → Enterprise**

* Freemium: 1 workspace
* Pro: 5 workspaces, APIs, validation
* Team: SSO, unlimited workspaces
* Enterprise: private infra, governance controls, custom copilots

---

# 🏆 Six Competitive Advantages

1. **Fully Multimodal** (PDF → image → audio → slides)
2. **Zero-Code** (anyone can build assistants)
3. **Governed & Safe** (validation, confidence scoring, human loop)
4. **Instant Deployment** (RAG in under 60 seconds)
5. **Workspace Isolation** (each workspace = mini AI product)
6. **Enterprise Architecture** (scalable, API-first, secure)

---

# 📈 Roadmap

* Confluence, Notion, Slack connectors
* API-first enterprise deployment
* Domain-specific copilots
* More validators & governance modes

---

# 🤝 Contributing

PRs and feedback welcome!
Please open issues for bugs, discussions, or features.

---

# 📬 Contact

**Author:** Nikunj Patel
**Email:** *banikunjpatel@gmail.com*
**Website / LinkedIn / Portfolio:** *add links*

---

# ⭐ Support the Project

If you liked AutoRAG OS, please ⭐ the repo — it helps visibility!

