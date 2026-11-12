### Hey, I'm Shayan

Final-year AI student at GIKI (class of '27), based in Islamabad. Most of what I build is agentic: a few LLM agents splitting up a messy job and actually getting it done (with tests and guardrails, because the model will try to do something silly at some point).

**What I've been working on**

- **[OpenEdu Orchestrator](https://github.com/SubhanSandhu312/OpenEdu-Orchestrator)**: a 4-agent LangGraph pipeline that migrates university records from a legacy MySQL database into an Odoo ERP and keeps them synced. The LLM only plans; every plan is checked against the live schema before plain Python runs it. I led the build on a two-person team during my internship at the PIEAS Deep Learning Lab.
- **[PIEAS Vision Agent](https://github.com/wat144p/pieas-vision-agent)**: scrapes a university site on a schedule, describes every image with a locally run LLaVA model, and makes the collection searchable in plain English (no paid APIs).
- **[Churn prediction, scikit-learn vs TensorFlow](https://github.com/wat144p/churn-prediction-tf-vs-sklearn)**: two models on the same data, 0.852 vs 0.855 ROC-AUC, served by FastAPI in Docker at a 4.7 ms median, with 50 tests and CI.
- **[Chest X-ray pneumonia screening](https://github.com/wat144p/chest-xray-pneumonia-tf)**: MobileNetV2 transfer learning, 98.7% pneumonia recall, and an honest look at what that costs in false alarms.
- **[SmartSlot](https://github.com/wat144p/SmartSlot)**: a timetable optimizer using Simulated Annealing I wrote from scratch. It's [live](https://smartslot-207x.onrender.com) (give it a minute to wake up).

**Right now**: my final-year project, edge-fog AI smart glasses for people with Alzheimer's (on-device models, a caretaker app, and a safety layer that never depends on the language model).

**Stack**: Python, LangGraph, FastAPI, Docker, GitHub Actions, TensorFlow, PyTorch, ChromaDB, PostgreSQL.

Open to remote AI engineering work. [LinkedIn](https://linkedin.com/in/shayan144p)
