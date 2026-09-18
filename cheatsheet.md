# Decision Cheatsheet: Vietnam K-12 AI Curriculum

Decision rules, diagnostic thresholds, heuristics, and quick-lookup matrices for educators and curriculum developers.

---

## 1. Core Decision Rules

1. **When selecting an AI classroom tool, choose client-side browser tools over cloud-hosted account platforms**, because client-side execution eliminates student email/phone registration, protects student privacy under Decree 13/2023/NĐ-CP, and works without high-bandwidth GPU servers.
2. **When planning the annual 12-period allocation, integrate into regular Informatics Strands A, D, E, F first**, because it utilizes existing scheduled hours without requiring extra weekend classes or school timetable restructuring.
3. **When teaching machine learning before Grade 10, emphasize data labeling and test-set errors over mathematical formulas**, because lower secondary learners grasp classification boundaries through visual examples, whereas early mathematical formalization causes cognitive overload.
4. **When a student project uses generative AI, require an explicit 'AI Attribution Log' documenting prompts and verifications**, because this upholds the GDPT 2018 core quality of "Trung thực" (Integrity) and prevents blind copy-pasting.
5. **When choosing between accuracy and precision/recall in class evaluations, prioritize the metric matching real-world failure costs**, because predicting rare events (e.g., medical anomalies or hazardous waste) renders raw accuracy deceptive.
6. **When external commercial vendors propose school partnerships, enforce the 4-Gate Governance Check**, because public schools are legally prohibited from mandating fee-based software or proprietary hardware kits.

---

## 2. Pedagogical Tool Selection Decision Tree

```
Does the target lesson involve programming syntax?
├── NO: Primary (Lớp 1-5) or Conceptual/Unplugged
│   ├── Is hardware/screen available?
│   │   ├── NO  → Use Unplugged Physical Roleplaying (Ch 6)
│   │   └── YES → Use Google Teachable Machine / Quick Draw! (Ch 3)
└── YES: Secondary (Lớp 6-12)
    ├── Target: Lower Secondary (Lớp 6-9)
    │   ├── Visual Block Programming → Scratch AI Extension / App Inventor (Ch 4)
    │   └── Algorithmic Logic        → Python with Scikit-Learn Decision Trees (Ch 4)
    └── Target: Upper Secondary (Lớp 10-12)
        ├── Applied Track (ICT)      → Prompt Engineering, Hugging Face Gradio Apps (Ch 5)
        └── CS Track (Khoa học máy tính) → Python (Jupyter/Colab), ANN, Scikit-Learn pipelines (Ch 5)
```

---

## 3. Statutory Thresholds & Defaults

| Parameter | Statutory / Recommended Threshold | Regulatory Anchor |
|---|---|---|
| **Annual Mandatory AI Duration** | Exactly $\ge 12$ periods per academic year across all K-12 grades | Công văn 5588 & 5208 |
| **Software Fee Cap** | Exactly **0 VND** (Mandatory zero-fee; open-source / free access) | Công văn 5588 / QĐ 2422 |
| **Assessment Weighting** | Formative Process: $\ge 70\%$ \| Final Prototype: $\le 30\%$ | QĐ 2422 Part VI |
| **Separate Written AI Exams** | **0 exams** (Strictly forbidden to create separate high-stakes exams) | QĐ 2422 Part VI |
| **Train/Test Data Split Ratio** | Standard 70% Training / 30% Testing (or 80/20 for datasets $> 200$ samples) | Standard ML didactics (Ch 4) |
| **Informatics Periods/Year** | Primary (35/yr), Lower Sec (35/yr), Upper Sec (70/yr + 35 chuyên đề) | Thông tư 32/2018 |

---

## 4. Tells & Smells: Detecting Curriculum Anti-Patterns

| You observe... | The underlying failure is... | Corrective Action |
|---|---|---|
| Students define AI terms word-for-word on a written test. | Rote memorization replacing competency assessment. | Replace test with a 3-part portfolio: Dataset, Confusion Matrix, Reflection. |
| Model reports 100% accuracy on first attempt. | Data leakage or evaluating on the training set. | Enforce strict Train/Test split before running any preprocessing or training. |
| Students attribute human consciousness or emotions to a chatbot. | Anthropomorphism / Lack of living vs machine boundary. | Revisit Primary Living vs Smart Artifact framework; inspect underlying token probabilities. |
| Teacher spends 35 minutes demonstrating a slide deck without student tool interaction. | Passive didactic lecture; violation of 5E/experiential model. | Flip lesson: 10 min Explore $\rightarrow$ 15 min Explain $\rightarrow$ 10 min Elaborate. |
| A private vendor requires student parent phone numbers to unlock AI lessons. | Violation of Decree 13/2023/NĐ-CP child privacy regulations. | Halt vendor onboarding; migrate to client-side anonymous FOSS tools. |

---

## 5. Trade-off Matrix: AI Integration Pathways

| Pathway | Speed of Rollout | Technical Depth | Cross-Disciplinary Value | Administrative Friction |
|---|---|---|---|---|
| **Informatics Subject Integration** | Fast | High (CS/Data) | Low | Minimal (Single department) |
| **Interdisciplinary STEM Module** | Moderate | Moderate | High (Science + Math) | Moderate (Cross-teacher planning) |
| **Experiential Activities (HĐTN)** | Fast | Low (Ethical focus) | High (Civic + Social) | Minimal (School assembly / homeroom) |
| **Dedicated School Elective** | Slow | Very High | Flexible | High (Requires dedicated timetable slots) |
