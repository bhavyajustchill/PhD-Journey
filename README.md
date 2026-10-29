# PhD Journey

I'm Bhavya Popat, a PhD scholar in Computer Science at **Atmiya University**. This repository is a public record of my PhD as it happens: coursework notes, assignments, presentations and milestone documents, added semester by semester.

**Enrollment No.:** 261881003 · **Registration No.:** 15616226003
---

## Research

### Multi-Agent Large Language Model Framework for Enterprise Decision Support

Enterprises produce huge amounts of structured and unstructured data. The people making decisions need insight that is timely, reliable and explainable, but most decision support systems are still rule-based, static and split across business functions. Using a single LLM brings its own problems: hallucinations, limited specialisation and no collaborative reasoning.

My proposal is a framework of specialised agents that reason together over an enterprise knowledge base:

```
Enterprise User
      │
      ▼
 Planner Agent ──► Research Agent ──► Analysis Agent ──► Verification Agent ──► Decision Agent
                         │                                                          │
                         ▼                                                          ▼
              Knowledge Base (Vector DB + RAG)                          Enterprise Recommendation
```

**Objectives**
- Design specialised agents and enable collaborative reasoning between them
- Ground answers in enterprise data with Retrieval-Augmented Generation (RAG)
- Reduce hallucinations through a dedicated verification agent
- Make recommendations transparent and explainable
- Evaluate scalability and how well the framework fits real enterprises

**Evaluation metrics:** decision accuracy, precision / recall, hallucination rate, response time, explainability, user satisfaction, scalability

**Target domains:** healthcare, finance, manufacturing, supply chain, smart governance

📄 [Proposal presentation (PDF)](Sem%201/Proposal%20Presentation/Doctoral%20Research%20Proposal%20Presentation.pdf), presented 11 July 2026

---

## Repository Layout

```
.
├── Sem 1/
│   ├── Assignments/                 # one folder per assignment, named DD-MM-YYYY
│   ├── CourseWork/
│   ├── Docs/
│   │   └── Online Courses/	     # if applicable
│   ├── Proposal Presentation/
│   └── Recent Trends Presentation/
│   └── _misc/
```

Each new semester gets its own `Sem N/` folder with the same structure.

## Conventions

- **Submitted files** follow `<EnrollmentNo>_<Name>_<Department>_<Title>`, e.g. `261881003_BhavyaPopat_ComputerScience_ResearchMethodologyCourse.pdf`. The prefix lives in [`_misc/FileNamePrefix.txt`](_misc/FileNamePrefix.txt).
- **Assignment folders** are named by date in `DD-MM-YYYY` format.

---

## Using This Material

You're welcome to read and learn from anything here, especially if you're starting a PhD yourself. Please don't submit any of it as your own coursework.
