# Chapter 7: Operational Implementation Mandates (Công văn 5588 & 5208/BGDĐT-GDPT)

## Core Idea
Beginning in the 2026–2027 academic year, MOET directives (Công văn 5588/BGDĐT-GDPT and Công văn 5208/BGDĐT-GDPT) mandate a minimum 12-period annual AI education allocation across all K-12 grades. Implementation enforces absolute financial equity: schools are strictly prohibited from requiring paid software subscriptions or proprietary hardware kits, mandating zero-cost, open-source, and web-based pedagogical tools.

## Frameworks Introduced

- **The 12-Period Multi-Track Integration Topology (Khung Tích hợp 12 Tiết AI Linh hoạt)**:
  - When to use: Annual school education plan (Kế hoạch giáo dục nhà trường) formulation by school administrators and department heads.
  - How: Schools select from four approved delivery pathways to complete the mandatory 12 periods per year:
    - *Track 1: Direct Informatics Integration (Tích hợp trong môn Tin học)*: Embedding AI learning outcomes directly into Strands A, D, E, F of the standard Informatics timetable (8–12 periods).
    - *Track 2: Interdisciplinary STEM/STEAM Modules (Chủ đề STEM liên môn)*: Delivering 1–2 comprehensive project modules linking Informatics, Technology, Natural Sciences, and Mathematics (6–12 periods).
    - *Track 3: Experiential & Career Guidance Activities (Hoạt động trải nghiệm, hướng nghiệp)*: Deploying ethical debate seminars, digital footprint audits, and AI career explorations (4–6 periods).
    - *Track 4: Autonomous School Curriculum (Kế hoạch giáo dục riêng của nhà trường)*: Utilizing flexible timetable allocations (12 standalone periods) for dedicated AI literacy courses.
  - Why it works / failure mode: Accommodates diverse school conditions without overburdening the statutory 35-week national curriculum timetable.

- **Zero-Fee Financial Equity Protocol (Nguyên tắc Bình đẳng và Không thu phí bổ sung)**:
  - When to use: Selecting software platforms, cloud services, and physical hardware for school deployment.
  - How:
    1. *No Paid Software*: Zero tolerance for mandatory student subscriptions, paid SaaS tokens, or paywalled generative AI accounts.
    2. *Zero-Install / Lightweight Access*: Prioritize browser-based, client-side tools (e.g., Teachable Machine, Scratch extensions, web simulators) that run on standard low-spec computer lab PCs without GPU requirements.
    3. *Data Minimization*: Prioritizing platforms that do not mandate personal email registrations, phone number verifications, or credit card collection for students under 16.
    4. *Hardware Neutrality*: Curriculum must be deliverable using generic school desktop computers or micro-controllers (e.g., standard micro:bit, ESP32, Arduino) without proprietary vendor lock-in.
  - Why it works / failure mode: Prevents socioeconomic stratification where affluent schools advance while underprivileged rural schools are excluded from AI literacy.

- **Lesson Study Professional Development Model (Sinh hoạt Chuyên môn theo Nghiên cứu Bài học)**:
  - When to use: Teacher training and interdisciplinary lesson co-design within school departments.
  - How:
    - *Phase 1 (Collaborative Design)*: Informatics, Science, and Humanities teachers co-design an AI-integrated lesson plan.
    - *Phase 2 (Classroom Observation)*: One teacher delivers the lesson while colleagues observe student engagement and cognitive friction rather than judging the teacher.
    - *Phase 3 (Reflective Dialogue)*: Department analyzes what students actually learned, identifying conceptual bottlenecks and refining the activity.
  - Why it works / failure mode: Replaces one-off top-down lecture workshops with grounded, reflective classroom experimentation.

## Key Concepts
- **Công văn 5588/BGDĐT-GDPT (2026)**: The definitive Ministry guidance letter instructing all Provincial Departments of Education and Training (Sở GDĐT) on implementing the QĐ 2422 AI Content Framework for 2026–2027.
- **Công văn 5208/BGDĐT-GDPT (2026)**: The comprehensive annual guideline detailing primary general education tasks, digital transformation, and STEM/AI integration mandates for the 2026–2027 school year.
- **12 Tiết định mức tối thiểu (12-Period Mandatory Benchmark)**: The baseline instructional duration dedicated to AI content that every Vietnamese student must receive each school year.
- **Kế hoạch giáo dục nhà trường (School Education Plan)**: The autonomous operational curriculum formulated by each school pursuant to Circular 32/2018 and Circular 28/2020.
- **Công cụ mã nguồn mở và miễn phí (FOSS - Free and Open-Source Software)**: Educational software licensed to permit free usage, modification, and offline redistribution in educational settings.
- **Bảo mật và Quyền riêng tư của Trẻ em (Child Digital Privacy & Consent)**: Legal compliance mandates ensuring student biometric data, faces, and classroom voices are never uploaded to commercial servers without explicit parental consent.

## Mental Models
- **"The 12 periods are water, the school curriculum is the sponge"**: You don't need a new glass to hold the water; the existing subjects (Informatics, STEM, Experiential Learning) absorb the 12 periods seamlessly.
- **"Low floor, high ceiling, zero tollbooth"**: Any tool introduced into the classroom must be easy to start with (low floor), capable of advanced extension (high ceiling), and completely free for every student (zero tollbooth).

## Anti-patterns
- **Commercial Vendor Takeover (Thương mại hóa chương trình nhà trường)**: Outsourcing mandatory AI periods to private commercial test-prep centers that charge supplementary tuition or demand proprietary software licenses.
- **Hardware-in-the-Closet Syndrome**: Purchasing expensive, fragile proprietary robotics kits that sit locked in storage cabinets because teachers fear damage or lack technical support.
- **Account Requirement Barriers**: Selecting tools that require individual student telephone numbers or credit cards, causing half the class to be locked out during a lab session.

## Reference Tables

### The 4 Implementation Pathways for the 12-Period AI Requirement

| Pathway | Primary Subject Anchor | Target Period Allocation | Key Advantages | Typical Constraints |
|---|---|---|---|---|
| **Pathway A: Informatics Integration** | Môn Tin học (Strands A, D, E, F) | 8–12 periods within regular timetable | High pedagogical alignment; taught by certified Informatics teachers | Tight existing Informatics syllabus; requires trimming legacy topics |
| **Pathway B: Interdisciplinary STEM** | Liên môn: Tin học + KHTN/Công nghệ | 2 project modules (6 periods each) | Real-world problem solving; high student engagement; physical hardware | Requires cross-departmental coordination between teachers |
| **Pathway C: Experiential Activities** | Hoạt động trải nghiệm, hướng nghiệp | 4–6 periods | Ideal for digital citizenship, AI ethics debates, and career orientation | Less emphasis on technical coding and deep algorithmic training |
| **Pathway D: Autonomous School Elective** | Kế hoạch giáo dục riêng (Tự chọn) | 12 standalone periods | Maximum flexibility; deep end-to-end curriculum design | Requires available timetable headroom and qualified teaching staff |

### Recommended Zero-Cost / Open-Source Tool Ecosystem

| Educational Tier | Recommended Platforms / Tools | Hardware Prerequisites | Data & Account Policy |
|---|---|---|---|
| **Primary (Lớp 1–5)** | Google Teachable Machine, Quick Draw!, Scratch AI Blocks, Code.org | Standard Lab PC or Tablet with webcam | No account required; client-side browser execution |
| **Lower Sec (Lớp 6–9)** | Teachable Machine, App Inventor + AI, MicroBlocks, micro:bit Simulator | Low-spec PC; optional standard micro:bit | Anonymous school accounts or local project storage |
| **Upper Sec (Lớp 10–12)** | Python (Google Colab / Jupyter), Scikit-Learn, Hugging Face Spaces (open demo), Gradio | PC with Internet access; runs in cloud or locally | Open-source libraries; zero-cost student cloud tiers |

## Worked Example

### Sample School Timetable Integration Plan (Lower Secondary School, Grade 8)
- **School**: Trường THCS Chu Văn An.
- **Target**: Deploy 12 periods of AI in Grade 8 without adding weekend or after-school sessions.

```markdown
### 12-Period Timetable Distribution Schedule:

Term 1 (Học kì 1) — 6 Periods:
- Week 4 (Informatics, Period 8): Bài học "Thị giác máy tính và Nhận diện đối tượng" (Thread A & C)
- Week 5 (Informatics, Period 10): Thực hành "Thu thập và Gán nhãn dữ liệu ảnh cho bài toán phân loại" (Thread B)
- Week 9 (Informatics, Period 18): Bài học "Đạo đức số: Công nghệ nhận diện khuôn mặt và Quyền riêng tư" (Thread D)
- Weeks 14–16 (STEM Project): Dự án "Thùng rác phân loại thông minh" (Liên môn Tin học - KHTN) (3 Periods)

Term 2 (Học kì 2) — 6 Periods:
- Week 21 (Informatics, Period 42): Bài học "Xử lý ngôn ngữ tự nhiên và Chatbot" (Thread A & C)
- Week 22 (Informatics, Period 44): Thực hành "Phân tích cảm xúc văn bản và Thiên vị dữ liệu" (Thread B)
- Week 27 (Experiential Activity, Period 81): Diễn đàn "Nhận biết tin giả, Deepfake và Ứng xử có trách nhiệm trên mạng xã hội" (Thread D) (2 Periods)
- Weeks 31–32 (Informatics, Periods 62–63): Bài tập nhóm "Thiết kế câu lệnh nhắc (Prompt) phục vụ tự học môn Tiếng Anh và Lịch sử" (2 Periods)

Total: Exactly 12 periods fully accredited, zero additional student fees, zero timetable conflicts.
```

## Key Takeaways
1. **12 periods per year is mandatory nationwide**: Beginning 2026–2027, every K-12 school in Vietnam must provide a structured minimum of 12 periods of AI education.
2. **Flexible multi-track integration is permitted**: Schools can distribute the 12 periods across Informatics, STEM, Experiential Activities, or school-designed elective modules.
3. **Zero-fee policy is legally binding**: Schools must never mandate paid software, private tutoring center contracts, or expensive single-vendor hardware.
4. **Professional development is grassroots and collaborative**: Lesson study (Nghiên cứu bài học) within school clusters drives authentic teacher capacity building.

## Connects To
- **Ch 1 & 2**: Operationalizes national standards into actual classroom timetable schedules.
- **Ch 6**: Directly guides teachers on how to assess these 12 periods without creating examination burdens.
- **Ch 8**: Provides the regulatory baseline upon which municipal educational authorities (such as HCMC) build local deployment ecosystems.
