# 🌐 LLM Agent — Browser-Based Multi-Tool Chatbot

A **lightweight proof-of-concept** for running an **LLM-powered agent entirely in the browser**.  
This app shows how natural language reasoning can be extended with **external tools** like search engines, AI pipelines, and even **JavaScript execution** — all from a minimal, hackable frontend.

👉 Live Demo: [tds-bonus-project-llm-agent.vercel.app](https://tds-bonus-project-llm-agent.vercel.app/)

---

## ✨ Key Features

- **🔀 Multi-Provider Support**  
  Switch seamlessly between AI Pipe Proxy API (default), OpenAI, Google Gemini, Anthropic Claude, and others.

- **🔁 Autonomous Agent Loop**  
  Iteratively reasons, calls tools when needed, and continues until a final answer is reached.

- **🧰 Built-in Tools**
  - Web Search (snippet fetcher)  
  - AI Pipe API workflows  
  - JavaScript sandbox execution  

- **🎨 Clean UI/UX**
  - Bootstrap-based responsive layout  
  - Streaming-style chat interface  
  - File uploads, alerts, and debugging utilities  
  - Performance monitor + tool call logging  

---

## 🚀 Getting Started

### Requirements
- Any modern browser (Chrome, Edge, Firefox).  
- API credentials:
  - [AI Pipe](https://aipipe.org/) (recommended)  
  - Optional: OpenAI, Gemini, Claude  

### Quick Setup
1. Clone this repo:
   ```bash
   git clone https://github.com/23f1000805/tds-bonus-project-LLM-Agent.git
   cd tds-bonus-project-LLM-Agent
   ```
2. Open `index.html` directly in your browser. *(No backend needed!)*  
3. Enter your API key in the **Settings Panel** inside the app.  

---

## 🧩 Project Structure

```
├── index.html    # Chat interface + settings
├── agent.js      # Core agent logic, providers, tools
├── styles.css    # UI styles
├── README.md     # Documentation
└── LICENSE       # License file
```

---

## 📖 Example Interaction

**User:** Write me a blog draft about IBM.  
**Agent:** Sure! Let’s search for IBM...  
→ *(calls search tool)*  
**Agent:** IBM is a global tech company founded in 1911...  
**User:** Continue.  
**Agent:** Here’s a blog outline you could use...  

---

## ✅ Deliverable Checklist

- Browser-based LLM chat window  
- Google Search integration  
- AI Pipe proxy support  
- In-browser JavaScript sandbox  
- Error handling with Bootstrap alerts  
- Extendable architecture  

---

## 📊 Evaluation Rubric

| Criteria               | Marks   |
| ---------------------- | ------- |
| Output functionality   | **1.0** |
| Code quality & clarity | **0.5** |
| UI/UX polish & extras  | **0.5** |
| **Total**              | **2.0** |

---

## 🙌 Acknowledgements

- [AI Pipe](https://aipipe.org/) for proxy workflows  
- OpenAI, Anthropic, Google for LLM APIs  
- Bootstrap for frontend styling  

---

## 🔮 Next Steps

- Add session persistence (IndexedDB / localStorage).  
- Enable streaming token-by-token outputs.  
- Integrate more tools (file parsers, charts, SQL connectors).  

---
