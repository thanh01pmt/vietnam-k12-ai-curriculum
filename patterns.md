# Practical Integration Patterns: Vietnam K-12 AI Curriculum

Design and pedagogical patterns for teachers, school administrators, and curriculum architects implementing QĐ 2422/QĐ-BGDĐT and Công văn 5588/BGDĐT-GDPT.

---

## 1. 12-Period Modular Curricular Absorption Pattern
**When to use**: Accommodating the mandatory 12-period annual AI requirement within the existing statutory 35-week national timetable without creating overtime or weekend classes.

**How**:
1. *Audit Existing Timetables*: Identify existing Informatics (Tin học), Natural Sciences (KHTN), and Experiential Activities (HĐTN, HN) periods across semesters.
2. *Decompose the 12 Periods*:
   - Allocate 6 periods to regular Informatics (Strands A, D, E, F) targeting conceptual and coding YCCĐs.
   - Allocate 4 periods to a cross-disciplinary STEM module (combining biology/environmental science with sensor-driven classification).
   - Allocate 2 periods to Experiential Activities targeting digital safety, deepfakes, and social network responsibility.
3. *Formalize into Kế hoạch giáo dục nhà trường*: Submit the integrated schedule to the School Academic Council at the start of the school year.

**Trade-offs**:
- *Advantage*: Zero additional curriculum strain; leverages existing certified teachers and lab rooms.
- *Downside*: Requires interdepartmental coordination between Informatics and Science/Humanities faculty.

---

## 2. Unplugged-to-Plugged Scaffolding Pattern
**When to use**: Introducing abstract computational or machine learning concepts (such as neural network weights, decision trees, or sorting networks) in grades 3 through 9, especially in computer labs with limited machines or internet bandwidth.

**How**:
1. *Stage 1 (Unplugged Bodily Simulation)*: Students roleplay physical entities (e.g., human neurons passing tokens, sorting cards on physical chalk pathways).
2. *Stage 2 (Tactile Representation)*: Students draw branching trees or calculate activation thresholds on paper in pairs.
3. *Stage 3 (Plugged Digital Experimentation)*: Transition to browser-based visual simulation (e.g., TensorFlow Playground or Teachable Machine) to verify the physical intuition.
4. *Stage 4 (Code / Integration)*: Translate the logic into visual Scratch blocks or Python scripts.

**Trade-offs**:
- *Advantage*: Completely eliminates screen fatigue; builds indelible conceptual intuition before syntax.
- *Downside*: Takes slightly more classroom setup time than immediately opening computer monitors.

---

## 3. The CLEAR Structured Prompting Pattern
**When to use**: Lower and Upper Secondary students (Grades 8–12) utilizing Generative AI tools for research, language practice, or programming troubleshooting.

**How**:
Structure user prompts into five explicit sections:
```
1. [CONTEXT]: "I am a Grade 10 student preparing a biology report on cellular respiration."
2. [ROLE]: "Act as a patient high school biology tutor who uses Socratic questioning."
3. [TASK]: "Explain the Krebs cycle using an analogy to a bicycle factory."
4. [LIMITS]: "Keep your response under 250 words. Do not use complex college-level biochemical formulas. Format with 3 bullet points."
5. [VERIFICATION]: "Cite the textbook concept or reliable source this analogy aligns with."
```

**Trade-offs**:
- *Advantage*: Drastically reduces AI hallucinations, suppresses superficial boilerplate, and enforces concise, grade-appropriate responses.
- *Downside*: Requires conscious pre-thinking; students must overcome the habit of typing vague 3-word questions.

---

## 4. Teachable Machine Classroom Rapid-Prototyping Pattern
**When to use**: Grades 4 through 8 to demonstrate the entire Machine Learning lifecycle (collection $\rightarrow$ training $\rightarrow$ testing $\rightarrow$ bias detection) within a single 45-minute period.

**How**:
1. *Hardware Preparation*: One webcam-enabled PC per pair or trio of students. Open `teachablemachine.withgoogle.com`.
2. *Data Collection (10 mins)*: Class A (20 photos of open palms); Class B (20 photos of closed fists).
3. *One-Click Training (3 mins)*: Run in-browser client-side training (zero backend data upload ensures student privacy).
4. *Adversarial Testing (15 mins)*: Test with gloves, varying lighting, tilted angles, and different skin tones.
5. *Reflection Log (10 mins)*: Students record: "What example caused the model to misclassify, and what additional photos must be added to fix it?"

**Trade-offs**:
- *Advantage*: Zero installation, zero cloud fees, zero accounts; immediate visual feedback on machine learning concepts.
- *Downside*: Hides algorithmic internals (loss optimization, gradient descent) beneath an abstracted user interface.

---

## 5. Dual-Assessment Portfolio Pattern (Formative-First)
**When to use**: Assessing K-12 AI competence in compliance with MOET's mandate against high-stakes testing burdens.

**How**:
1. *Establish Digital Project Logs*: Each student team maintains a shared document or notebook recording:
   - Initial problem statement & target community user.
   - Dataset distribution chart (class sizes, sources, consent records).
   - Confusion matrix and accuracy logs across multiple iterations.
   - Ethical self-reflection on potential societal risks of the tool.
2. *Weighting*: Assign 70% of evaluation marks to the iterative development log and teamwork process; assign 30% to the working prototype.
3. *Integrate into Regular Informatics Grades*: Map the portfolio score to existing continuous assessment (Đánh giá thường xuyên) slots.

**Trade-offs**:
- *Advantage*: Rewards perseverance, rigorous testing, and ethical reflection rather than superficial programming flashiness.
- *Downside*: Higher grading workload for teachers compared to scanning multiple-choice answer sheets.

---

## 6. Public-Private Partnership (PPP) 4-Gate Governance Pattern
**When to use**: Evaluating external technology companies, universities, or private educational centers proposing AI programs in public schools (under CV 8585 and national socialization laws).

**How**:
- **Gate 1 (Zero Mandatory Cost)**: Is the school program completely voluntary for families, with a guaranteed zero-cost parallel pathway for non-paying students?
- **Gate 2 (Pedagogical Accreditation)**: Has the curriculum been reviewed and approved by the School Academic Council against QĐ 2422 learning outcomes?
- **Gate 3 (Data Sovereignty)**: Does the partner agree in writing that student faces, voices, and personal records will not be stored, commercialized, or shared?
- **Gate 4 (No Vendor Lock-in)**: Can students access, export, and continue their coursework on generic open-source tools without proprietary software subscriptions?

**Trade-offs**:
- *Advantage*: Protects schools from commercial exploitation, lawsuits, and parental backlash while welcoming legitimate technological expertise.
- *Downside*: Rejects many commercial off-the-shelf vendor packages that rely on proprietary SaaS subscriptions.
