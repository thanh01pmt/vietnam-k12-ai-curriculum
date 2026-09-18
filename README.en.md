# Vietnam National K-12 AI Curriculum & GDPT 2018 Agent Skill

<p align="center">
  <a href="README.md"><strong>English</strong></a> ·
  <a href="README.vi.md">Tiếng Việt</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Agent_Skills-Open_Standard-blueviolet?style=for-the-badge" alt="Agent Skills Standard">
  <img src="https://img.shields.io/badge/Target-Vietnam_K--12_Education-green?style=for-the-badge" alt="Target: Vietnam K-12">
  <img src="https://img.shields.io/badge/Legal_Anchors-QĐ_2422_•_TT_32_•_CV_5588-blue?style=for-the-badge" alt="Statutory Anchors">
  <img src="https://img.shields.io/badge/Status-Production_Ready-success?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/License-CC_BY_4.0-lightgrey?style=for-the-badge" alt="License">
</p>

---

## 📖 Executive Summary

The **`vietnam-k12-ai-curriculum`** skill is a structured, production-grade knowledge base and autonomous decision engine designed for AI coding assistants and curriculum developers. It encodes Vietnam's official statutory frameworks, pedagogical sequences, and implementation directives for Artificial Intelligence in general education:

- **Quyết định 2422/QĐ-BGDĐT**: National K-12 Artificial Intelligence Curriculum Framework.
- **Thông tư 32/2018/TT-BGDĐT & TT 13/2022/TT-BGDĐT**: General Education Program 2018 (GDPT 2018) Informatics Curriculum (Tin học).
- **Công văn 5588/BGDĐT-GDPT & CV 5208/BGDĐT-GDPT**: Official directives mandating the annual 12-period minimum AI allocation and school implementation.
- **Công văn 8585/SGDĐT-GDPT (TP.HCM)**: Municipal rollout directives for digital schools, open learning repositories, and public-private partnerships.
- **Nghị định 13/2023/NĐ-CP**: Statutory mandates on personal data protection and child digital safety.

This skill equips AI agents (Claude Code, GitHub Copilot CLI, Amp, Hermes Agent, Antigravity) and human educators with immediate access to grade-level learning outcomes (*Yêu cầu cần đạt - YCCĐ*), lesson plan designs, statutory compliance checklists, and didactic decision trees.

---

## 🏛️ Core Statutory Principles & Mental Models

Every AI curriculum design, learning objective, and classroom artifact generated for the Vietnamese education system must adhere to these 6 foundational principles:

```
                          ┌──────────────────────────────────────────────┐
                          │   1. HUMAN-CENTRIC AI PHILOSOPHY (QĐ 2422)   │
                          │ AI is an engineered artifact, subservient to │
                          │  human agency, dignity, and moral oversight  │
                          └──────────────────────┬───────────────────────┘
                                                 │
            ┌────────────────────────────────────┼────────────────────────────────────┐
            │                                    │                                    │
┌───────────▼───────────┐            ┌───────────▼───────────┐            ┌───────────▼───────────┐
│ 2. 4 KNOWLEDGE THREADS│            │ 3. SPIRAL PROGRESSION │            │  4. 12-PERIOD MINIMUM │
│ A: Concepts & Apps    │            │ Primary: Senses/Rules │            │ Mandatory per year;   │
│ B: Data & ML Pipeline │            │ Lower Sec: Reasoning  │            │ Integrated across Tin │
│ C: AI Systems & Arch  │            │ Upper Sec: Model Math │            │ học, STEM, & HĐTN/HN  │
│ D: Ethics & Society   │            │                       │            │ (CV 5588 & CV 5208)   │
└───────────┬───────────┘            └───────────┬───────────┘            └───────────┬───────────┘
            │                                    │                                    │
            └────────────────────────────────────┼────────────────────────────────────┘
                                                 │
            ┌────────────────────────────────────┴────────────────────────────────────┐
            │                                                                         │
┌───────────▼───────────┐                                                 ┌───────────▼───────────┐
│ 5. ZERO-FEE & FOSS    │                                                 │ 6. FORMATIVE-FIRST    │
│ Strict ban on paid    │                                                 │ ≥ 70% process/rubrics;│
│ commercial software or│                                                 │ NO separate high-     │
│ vendor lock-in        │                                                 │ stakes written exams  │
└───────────────────────┘                                                 └───────────────────────┘
```

1. **Human-Centric AI (Tính nhân văn & Con người là trung tâm - QĐ 2422)**: AI is an engineered, non-sentient computational system created to enhance human capability. Anthropomorphism is strictly avoided; humans retain full academic and moral accountability for all AI-generated outputs.
2. **The 4 Curricular Knowledge Threads (4 Mạch nội dung)**:
   - **Thread A (*Khái niệm & Ứng dụng*)**: Demystifying AI, rule-based vs data-driven systems, smart devices.
   - **Thread B (*Dữ liệu & Học máy*)**: Data collection, cleaning, feature selection, labeling, train/test splitting, and bias.
   - **Thread C (*Kĩ thuật & Hệ thống*)**: Computer Vision (CV), Natural Language Processing (NLP), Decision Trees, Artificial Neural Networks (ANN), and Prompt Engineering.
   - **Thread D (*Tác động Xã hội & Đạo đức*)**: Child privacy (Nghị định 13), copyright, academic honesty, deepfakes, labor impact, and F.A.T.E. principles.
3. **Spiral Progression Model (*Đồng tâm xoắn ốc*)**: Concepts are introduced experientially in Primary school, formalized algorithmically in Lower Secondary, and mathematically modeled in Upper Secondary.
4. **Mandatory 12-Period Annual Allocation (*12 tiết/năm - CV 5588 & 5208*)**: Required for every student from Grade 1 to 12 through four flexible integration pathways without adding extra weekend classes.
5. **Zero-Fee & Open-Source Mandate (*Không thu phí bổ sung & FOSS*)**: Schools are prohibited from charging software license fees or demanding proprietary cloud subscriptions; classes must run on client-side, zero-install, or free open-source tools.
6. **Formative-First, Zero-Exam Policy (*Đánh giá quá trình - QĐ 2422 Phần VI*)**: At least 70% of evaluation weighting is assigned to development logs, error analysis, and teamwork; separate high-stakes written AI exams are prohibited.

---

## 📂 Repository Structure & Skill Contents

```
vietnam-k12-ai-curriculum/
├── SKILL.md                       # Core Agent prompt, mental models & fast navigation
├── README.md                      # English documentation (this file)
├── README.vi.md                   # Vietnamese documentation
├── cheatsheet.md                  # Decision trees, statutory thresholds & anti-pattern audits
├── patterns.md                    # 6 production-grade integration & governance patterns
├── glossary.md                    # Bilingual glossary of 50+ legal & technical terms
└── chapters/                      # Comprehensive reference manuals (loaded on-demand)
    ├── ch01-foundation-gdpt2018-informatics.md     # GDPT 2018, DL-ICT-CS Triad, Competencies
    ├── ch02-ai-framework-overview-principles.md    # QĐ 2422 Overview, 4 Threads, Philosophy
    ├── ch03-ai-primary-school-grade1-5.md          # Primary AI: Living vs Smart, Teachable Machine
    ├── ch04-ai-lower-secondary-grade6-9.md         # Lower Sec: 5-Step ML, CLEAR Prompts, Ethics
    ├── ch05-ai-upper-secondary-grade10-12.md       # Upper Sec: ANN, F1-Score, Decree 13, ICT vs CS
    ├── ch06-ai-teaching-methods-assessment.md      # 5E Didactics, Portfolios, Unplugged AI
    ├── ch07-implementation-guidelines-5588-5208.md # 12-Period Rollout, Zero-Fee Mandate, Lesson Study
    └── ch08-local-implementation-hcmc-8585.md      # HCMC Rollout, Smart Schools, 4-Gate PPP
```

### Reference Chapters Breakdown

| Chapter | Title | Primary Source | Core Topics Covered |
|---|---|---|---|
| [**ch01**](chapters/ch01-foundation-gdpt2018-informatics.md) | GDPT 2018 & Informatics Foundation | TT 32/2018, TT 13/2022 | DL-ICT-CS Triad, 5 Qualities, 3 General Competencies, 5 Informatics Competencies (NLa-NLe). |
| [**ch02**](chapters/ch02-ai-framework-overview-principles.md) | National K-12 AI Framework Overview | QĐ 2422/QĐ-BGDĐT | Human-centric philosophy, 4 knowledge threads (A, B, C, D), spiral developmental progression. |
| [**ch03**](chapters/ch03-ai-primary-school-grade1-5.md) | Primary School AI (Grades 1–5) | QĐ 2422 Sec IV.1 | Living beings vs smart devices, sensor exploration, Google Teachable Machine, screen hygiene. |
| [**ch04**](chapters/ch04-ai-lower-secondary-grade6-9.md) | Lower Secondary AI (Grades 6–9) | QĐ 2422 Sec IV.2 | Rule-based vs ML, 5-step ML pipeline, CLEAR prompt design, deepfakes, hallucination, dataset bias. |
| [**ch05**](chapters/ch05-ai-upper-secondary-grade10-12.md) | Upper Secondary AI (Grades 10–12) | QĐ 2422 Sec IV.3 | ANN mechanics, Confusion Matrix (Precision/Recall/F1), Decree 13/2023, Applied ICT vs CS tracks. |
| [**ch06**](chapters/ch06-ai-teaching-methods-assessment.md) | AI Didactics & Assessment Methods | QĐ 2422 Part V & VI | 5E inquiry cycle, formative dual-assessment portfolio, unplugged computing, rubrics. |
| [**ch07**](chapters/ch07-implementation-guidelines-5588-5208.md) | Implementation Mandates | CV 5588 & CV 5208 | 12-period absorption pathways, statutory zero-fee rule, teacher Lesson Study PD cycles. |
| [**ch08**](chapters/ch08-local-implementation-hcmc-8585.md) | Municipal Rollout: HCMC Case Study | CV 8585/SGDĐT-GDPT | Smart school 4 pillars, open shared repositories, 4-gate PPP corporate partnership governance. |

---

## 🛠️ Pedagogical Toolchain by Educational Tier

The curriculum framework mandates zero-cost, privacy-respecting classroom tools:

| Grade Tier | Recommended Tools | Primary Instructional Purpose | Privacy & Cost Profile |
|---|---|---|---|
| **Primary (Grades 1–5)** | Unplugged games, Quick Draw!, Google Teachable Machine | Distinguishing living vs smart machines, sensory inputs, basic image/sound classification | 100% Client-side in browser; no accounts, no storage of student photos |
| **Lower Secondary (Grades 6–9)** | Scratch AI Extension, MIT App Inventor, Teachable Machine, Micro:bit Python | 5-step ML workflow, training/test splits, block programming, CLEAR prompting | Client-side or school-managed accounts; zero token billing |
| **Upper Secondary: ICT Track** | Hugging Face Spaces (client-side), Orange Data Mining, Prompt Engineering Sandboxes | Practical prompt crafting, evaluating algorithmic bias, digital citizenship, career impact | Browser-based or desktop open-source software (FOSS) |
| **Upper Secondary: CS Track** | Python 3, Jupyter / Google Colab (Free), Scikit-Learn, TensorFlow Playground | ANN layer exploration, Precision/Recall/F1 metrics, Decision Trees, Transfer Learning | Free-tier cloud notebook or offline local Python environment |

---

## 🚀 How to Use This Skill

### For AI Agents (Claude Code, GitHub Copilot CLI, Amp, Hermes)

Once loaded in your workspace (`.agents/skills/vietnam-k12-ai-curriculum`), invoke with specialized contexts:

```bash
# Query grade-specific requirements
/vietnam-k12-ai-curriculum "Primary grade 4 learning outcomes for sensor classification"
/vietnam-k12-ai-curriculum "Grade 8 lesson plan for 5-step machine learning pipeline"
/vietnam-k12-ai-curriculum "Grade 11 CS track neural network activation functions"

# Query statutory compliance and decrees
/vietnam-k12-ai-curriculum "What are the legal conditions for commercial AI tools under CV 5588 and CV 8585?"
/vietnam-k12-ai-curriculum "Decree 13 requirements for student webcam data in schools"

# Query curriculum design patterns
/vietnam-k12-ai-curriculum "How to integrate 12 periods of AI without altering the 35-week timetable?"
/vietnam-k12-ai-curriculum "Generate a 5E lesson plan for CLEAR prompt engineering"
```

### For Curriculum Architects & School Administrators

1. **Verify Timetable Integration**: Use [patterns.md (Pattern 1)](patterns.md#1-12-period-modular-curricular-absorption-pattern) to distribute 12 periods into regular Informatics (6 periods), STEM modules (4 periods), and Experiential Activities (2 periods).
2. **Audit Commercial Proposals**: Apply [patterns.md (Pattern 6)](patterns.md#6-public-private-partnership-ppp-4-gate-governance-pattern) to verify external vendors through the 4-Gate Governance Check (Zero Cost, Academic Council Review, Data Sovereignty, No Lock-in).
3. **Detect Curriculum Anti-Patterns**: Consult [cheatsheet.md (Section 4)](cheatsheet.md#4-tells--smells-detecting-curriculum-anti-patterns) before submitting syllabi to Academic Councils.

---

## 📋 Statutory Compliance Checklist

Before approving any K-12 AI curriculum, syllabus, or lesson unit in Vietnam, verify:

- [ ] **12-Period Benchmark**: Does every student receive $\ge 12$ periods of AI instruction per academic year? (CV 5588)
- [ ] **Zero Software Fee**: Is the required software 100% free of licensing fees, SaaS subscriptions, or paid tokens? (CV 5588)
- [ ] **Child Data Privacy**: Are student photos, biometric inputs, and names kept anonymous on client devices without permanent cloud harvesting? (Nghị định 13/2023/NĐ-CP)
- [ ] **Assessment Model**: Is formative assessment weighted $\ge 70\%$, with **zero** separate written exams? (QĐ 2422)
- [ ] **Balanced Knowledge Threads**: Does the unit address ethics, bias, or safety (Thread D) alongside technical mechanics (Threads A, B, C)? (QĐ 2422)
- [ ] **No Anthropomorphism**: Is AI explicitly defined as a non-living computational tool created and governed by humans? (QĐ 2422)

---

## 📚 Supporting Resources

- [**cheatsheet.md**](cheatsheet.md): Quick-reference heuristics, decision trees, and statutory thresholds.
- [**patterns.md**](patterns.md): Concrete classroom and administrative design patterns.
- [**glossary.md**](glossary.md): Official English-Vietnamese legal and technical terminology definitions.

---

## 📄 License & Attribution

- **Standard**: Conforms to the open [Agent Skills Standard](https://github.com/agentskills/agentskills).
- **Content Reference**: Developed from publicly promulgated regulatory documents of the Ministry of Education and Training (BGDĐT) and municipal DOETs of Vietnam.
- **License**: Creative Commons Attribution 4.0 International (CC BY 4.0).
