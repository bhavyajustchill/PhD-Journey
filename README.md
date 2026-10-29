# PhD Journey

I'm Bhavya Popat, a PhD scholar in Computer Science at **Atmiya University**. This repository is a public record of my PhD as it happens: coursework notes, assignments, presentations and milestone documents, added semester by semester.

**Enrollment No.:** 261881003 · **Registration No.:** 15616226003 · **Currently:** Semester 1

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

## What's Inside

### Semester 1

| Folder | Contents |
| --- | --- |
| [Proposal Presentation](Sem%201/Proposal%20Presentation) | Doctoral research proposal deck (PPTX + PDF) |
| [Recent Trends Presentation](Sem%201/Recent%20Trends%20Presentation) | A talk on **AirLLM**, which runs 70B-parameter LLMs on a 4 GB GPU by streaming one decoder layer at a time from disk. Includes the deck, a slide-by-slide speaker script, and the fonts needed to render it on Linux |
| [Assignments](Sem%201/Assignments) | `12-08-2026`: webinar summary report with session screenshots<br>`12-09-2026`: Scopus CiteScore ranking of Strategy & Management journals (2025) |
| [CourseWork](Sem%201/CourseWork) | Lecture notes, e.g. parametric test assumptions, the Shapiro–Wilk test, the Wilcoxon signed-rank test, two-way factorial ANOVA |
| [Docs](Sem%201/Docs) | Consent letter, Semester 1 NoC, and online course certificates: *Research Methodology*, *Research and Publication Ethics*, *AI and Engineering Economics for Managers* |

### Miscellaneous

[`_misc`](_misc) holds the university's checklist of documents research scholars must submit, the file-naming prefix, and logo assets.

---

## Repository Layout

```
.
├── Sem 1/
│   ├── Assignments/                 # one folder per assignment, named DD-MM-YYYY
│   ├── CourseWork/
│   ├── Docs/
│   │   └── Online Courses/
│   ├── Proposal Presentation/
│   └── Recent Trends Presentation/
└── _misc/
```

Each new semester gets its own `Sem N/` folder with the same structure.

## Conventions

- **Submitted files** follow `<EnrollmentNo>_<Name>_<Department>_<Title>`, e.g. `261881003_BhavyaPopat_ComputerScience_ResearchMethodologyCourse.pdf`. The prefix lives in [`_misc/FileNamePrefix.txt`](_misc/FileNamePrefix.txt).
- **Assignment folders** are named by date in `DD-MM-YYYY` format.

---

## Using This Material

You're welcome to read and learn from anything here, especially if you're starting a PhD yourself. Please don't submit any of it as your own coursework.
