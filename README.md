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

## Design Choices (by Hetul Patel)
- **Phi-3 Mini on Colab:** Small instruct model that runs reliably in class with GPU, fast enough for demos.
- **Two modes via config:** `class.yaml` (no retrieval) and `finance.yaml` (RAG toggle) so I can reuse this project across courses.
- **Seed texts I authored:** Starting with my own summaries avoids copyright issues and keeps the demo lightweight.
- **Citations-first UX:** Finance mode will always show a source (file name + chunk) to build trust.
- **Simple evaluation set:** I maintain `eval/questions.csv` with my own questions to measure correctness and latency.
- **Portfolio-ready structure:** Clean folders, README, and a future public demo link so recruiters can quickly evaluate the project.



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

