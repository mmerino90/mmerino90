<div align="center">

# Manuel Merino

<a href="https://manuelmerino.vercel.app"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=3B82F6&center=true&vCenter=true&width=620&lines=Pricing+what+has+no+formula.;Testing+whether+ML+really+beats+GARCH.;Shipping+RAG+into+production.;Maths+%E2%86%92+money+%E2%86%92+machine+learning." alt="Typing animation" /></a>

<img src="https://skillicons.dev/icons?i=python,cpp,java,c,ts,react,nextjs,django,postgres,aws,docker,git,linux,sklearn,pytorch&perline=8" alt="Tech stack" />

</div>

> **Model card** for a fourth-year Computer Science & AI student who keeps ending up where maths, money and machine learning meet.

```yaml
model:       manuel-merino
version:     4.0               # fourth year, BSc Computer Science & AI, IE University
base:        Madrid, Spain
objective:   minimise ‖ maths − shipped software ‖
domain:      [fintech, quantitative finance, applied ML]
languages:   { natural: [English, Spanish, French], code: [Python, Java, C, TypeScript, SQL] }
status:      open to work
```

---

## Evaluation · selected work

Every project starts as a question I couldn't answer yet.

| The question | What I built | Result |
|:--|:--|:--|
| *Can you price what has no formula?* | [**mc-option-pricing**](https://github.com/mmerino90/mc-option-pricing) · Monte Carlo engine for options: variance reduction, pathwise Greeks, Asian, barrier and American options (Longstaff–Schwartz) | Variance cut **1,800×** on Asian options; American put within **0.0004** of a binomial tree |
| *Does ML beat GARCH?* | [**vol-forecasting**](https://github.com/mmerino90/vol-forecasting) · S&P 500 + 26 assets: GARCH, HAR, linear, XGBoost and an MLP, walk-forward with Diebold–Mariano tests | No: a linear model with the VIX beats XGBoost (p = 0.008). Better inputs, not bigger models |
| *Can a model beat the bookmakers?* | [**laliga_predictor**](https://github.com/mmerino90/laliga_predictor) · ELO + rolling form + odds → XGBoost outcome and Poisson scoreline models | **52.2%** over 3,040 out-of-sample matches vs the bookmakers' 53.0%. Found and fixed a leakage bug that had shown 58.1% |
| *What is this document, and what does it say?* | [**StatExtract-Classifier**](https://github.com/mmerino90/StatExtract-Classifier) · OCR fallback chain → TF-IDF + SVM → spaCy NER | Classifies 4 document types and pulls structured fields out of invoices |
| *Is this driver about to fall asleep?* | [**Driver-Fatigue-Detection**](https://github.com/beamartin27/Driver-Fatigue-Detection) · group project: 478 facial landmarks per frame, classical + deep models in late fusion, real-time alert | **86.3%** accuracy, F1 **0.89** |
| *Who's allowed to see the sales numbers?* | [**inventory-sales-retail-store**](https://github.com/mmerino90/inventory-sales-retail-store) · JavaFX desktop app: MVC + DAO, role-based access, SHA-256 auth | Admin and employee roles with their own views and analytics |

---

## Fine-tuning · in production

**AI Engineering Intern · ScaleWave Solutions** · Madrid, Feb–Aug 2026
- Built a system that tells a Spanish book publisher **which books to acquire before competitors do**: reader-growth signals across 380,000+ titles plus live TikTok, Instagram and Reddit trends, matched to the catalogue with embeddings. 4 pipelines and 13 scheduled jobs on AWS (Django, Celery), running 24/7 and writing answers back into the client's ERP.
- Shipped a **RAG assistant inside HubSpot** for a UK dental group (BM25 + embeddings via Reciprocal Rank Fusion, fail-closed guardrails). First six weeks live: first-reply time **−42%**, resolution time **−59%**, **+41%** tickets handled per day, zero hallucinated policies.

**AI Training Specialist · Outlier AI** · Remote, 2024–2025: nine months as the *human* in RLHF's loop, grading and correcting LLM answers in maths, physics and code.

**GenAI Mavericks · Accenture** · Nov 2025: agentic CV ↔ vacancy matcher with LLMs and n8n.

**Bachelor's thesis** (in progress): deepfake-resistant remote onboarding. An XceptionNet detector coupled with key-bound verification of agent delegation, tested on unseen generators at a 1% false-rejection rate.

---

## Training data

| Where | What |
|:--|:--|
| **IE University**, Madrid | BSc Computer Science & AI · 2023–2027 · GPA 8.1/10 · Academic Excellence Scholarship |
| **LSE Summer School**, London | Machine Learning in Practice (advanced) · **A+** |
| **Hastings School**, Madrid | A-Levels: Spanish A\*, Mathematics A, Computer Science A, French B |

---

## Known limitations

- **Explains things nobody asked about.** I've tutored STEM since I was 16: the fastest way to find out you don't understand something is to try to explain it.
- **Trusts walk-forward validation over vibes.** And then checks the vibes anyway.
- **Captain mode.** Eight years captaining a football team. Will organise your stand-up.
- **Bilingual by default.** Thinks in English and Spanish, occasionally in the same sentence.

---

## Intended use

Internships and graduate roles in **fintech, quantitative finance and ML engineering**.

[manuelmerino.vercel.app](https://manuelmerino.vercel.app) · [LinkedIn](https://www.linkedin.com/in/manuel-merino-21a586275/) · [mmerinojr05@gmail.com](mailto:mmerinojr05@gmail.com)

<sub>Weights updated continuously. Last eval: November 2026.</sub>
