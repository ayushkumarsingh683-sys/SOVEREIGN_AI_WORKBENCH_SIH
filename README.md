# Sovereign AI Workbench

A private, on-premise industrial AI analysis platform that intelligently processes technical documents and industrial images to identify risks, defects, safety concerns, and compliance issues in real-time.

---

## 🎯 Overview

**Sovereign AI Workbench** is an enterprise-grade AI system designed for industrial environments where data sovereignty and privacy are critical. It combines:

- **LLM-based Document Analysis** — Intelligent reasoning over technical documents (PDFs, Word, TXT)
- **Vision Inspection** — AI-powered image analysis for diagrams, P&IDs, schematics, and equipment photos
- **Risk Assessment** — Automated identification of technical and safety concerns with severity scoring
- **Private On-Premise Deployment** — 100% local processing using open-source models (no cloud dependency)

### Key Features

✅ **Multi-Format Document Support** — TXT, DOCX, PDF  
✅ **Industrial Vision Analysis** — Inspect equipment, diagrams, and schematics  
✅ **Risk Scoring & Severity Classification** — Automated risk quantification (0-100 scale)  
✅ **Component Identification** — Extracts technical components and equipment details  
✅ **Actionable Recommendations** — Suggests corrective actions with priority levels  
✅ **MongoDB Integration** — Persistent storage for workspaces and analysis results  
✅ **Industry-Specific Analysis** — Configurable by industry (mechanical, chemical, electrical, etc.)  
✅ **RESTful API** — Easy integration with existing systems  

---

## 🏗️ Architecture

### Technology Stack

| Component | Technology |
|-----------|-----------|
| **Backend Framework** | FastAPI + Uvicorn |
| **Language** | Python 3.x |
| **LLM Engine** | Ollama (Local inference) |
| **Document LLM** | Qwen 2.5 (7B Instruct) |
| **Vision LLM** | LLaVA (MoonDream) |
| **Document Parsing** | python-docx, PyPDF, python-multipart |
| **AI Orchestration** | LangChain + LangChain-Ollama |
| **Database** | MongoDB |
| **Data Validation** | Pydantic |

### Directory Structure
