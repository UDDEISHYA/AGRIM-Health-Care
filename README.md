
# AGRIM Health Care 🏥

**AGRIM Health Care** is an AI-powered health document assistant that intelligently extracts, processes, and responds to user queries from complex medical documents. Using NLP, a chatbot interface, and a knowledge graph-based backend, the system makes health information more accessible and actionable.

---

## 🚀 Key Features

- 📄 **Document-Based Chatbot**: Upload medical documents and interact with them conversationally.
- 🧠 **Knowledge Graph Generation**: Automatically extract entities and relations to build a visual representation.
- 🔍 **Contextual Query Handling**: Supports dynamic user queries with intelligent context handling.
- 🌐 **API Ready**: Chatbot and graph generation services are exposed via `chatbot_api.py` and `graph_api.py`.
- ⚡ **Deployed on Vercel**: Lightweight backend ideal for scalable deployment (see `vercel.json`).

---

## 🛠️ Tech Stack

- **Languages**: Python, JavaScript, CypherQuery
- **Libraries/Frameworks**:
  - `Neo4j` – for Knowledge Graph
  - `LangChain`
  - `Flask` or custom backend – for API endpoints
  - `PyPDF2` – for parsing PDFs
- **Frontend (Optional)**: HTML/CSS (light styling support)
- **Deployment**: Vercel
- **Others**: JSON, REST APIs, Jupyter Notebooks for prototyping

---


