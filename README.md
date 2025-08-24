# Finance Research Assistant (Class-Ready LLM + Optional RAG)

A small, class-ready chatbot using Phi-3 Mini.  
Flip a config to enable a **finance** mode with retrieval over short excerpts from SEC filings or investor letters.  
Designed to be reusable for courses, portfolio projects, and recruiter demos.
---
## Design Choices
- Built on Phi-3 Mini to keep it light enough for Colab demos.
- Started with my own investor letter summaries for safe testing.
- Config files make it easy to switch modes for future class projects.
- Plan to expand RAG with real filings and evaluation metrics.
---

## Why This Exists
- ✅ Simple chatbot for class projects (fast to demo in Colab)
- 🔍 Finance mode for grounded answers **with citations**
- 🗂️ Clean repo structure for future expansion and portfolio use

---

## Project Status (Fall 2025 Semester)(CSCI 6970)
- ✅ Working Colab notebook in `notebooks/`
- 🧩 Repo scaffolding complete
- 🔜 Finance seed docs + evaluation set
- 🌐 Public demo (HF Space) coming soon

---

## Repo Structure

notebooks/ # Colab notebooks
app/ # Future Gradio app
configs/ # Mode toggles (class.yaml, finance.yaml)
data/seed/ # Seed texts for finance retrieval
eval/ # Evaluation questions/results
docs/ # Diagrams, screenshots


---

## Modes
- **Class mode:** plain chatbot (no retrieval)
- **Finance mode:** retrieval over documents, shows citations

---

## Disclaimer
Educational demo only. **Not investment advice.**

---

## Contact
Hetul Patel  
📧 hetul.patel.career@outlook.com  
🔗 www.linkedin.com/in/hetul-patel-- 

---

### License
MIT License

