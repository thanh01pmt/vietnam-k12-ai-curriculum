# Chapter 5: AI in Upper Secondary Education (Cấp THPT: Lớp 10 – Lớp 12)

## Core Idea
Under Quyết định 2422/QĐ-BGDĐT, upper secondary education (THPT: Grades 10–12) focuses on career orientation, advanced architectural comprehension, and civic-legal governance. Didactic methods center on case studies, debate, algorithmic analysis, risk-tradeoff evaluation, and project-based system design. Students dissect Artificial Neural Networks (ANN), clustering/classification algorithms, advanced prompt engineering, Retrieval-Augmented Generation (RAG), autonomous AI Agents, and the full lifecycle of responsible AI governance in alignment with national laws (Luật An ninh mạng, Nghị định 13/2023/NĐ-CP).

## Frameworks Introduced

- **AI System Lifecycle Governance Model (Vòng đời Hệ thống AI & Quyền Kiểm soát của Con người)**:
  - When to use: Grades 11–12 project-based modules and system design evaluations.
  - How:
    1. *Problem & Ethics Definition*: Defining civic objectives, assessing risk levels, and establishing non-negotiable safety boundaries.
    2. *Data Governance*: Ensuring lawful collection, consent, data anonymization (Decree 13/2023/NĐ-CP), class balance, and feature engineering.
    3. *Model Design & Tuning*: Selecting appropriate architectures (classical ML vs ANN vs Foundation Model APIs), loss functions, and optimization strategies.
    4. *Evaluation & Overfitting Mitigation*: Stratified validation, Confusion Matrix analysis, Precision/Recall tradeoffs, and bias testing.
    5. *Deployment & Human Oversight*: Establishing Human-in-the-Loop approval gates and ongoing performance monitoring.
  - Why it works / failure mode: Ensures students do not treat AI as an isolated code snippet, but as a socio-technical system requiring continuous human stewardship.

- **The 6 Ethical Design Principles (6 Nguyên tắc Đạo đức Thiết kế AI - Lớp 12 `12.A2.1`)**:
  - When to use: Guiding high school capstone development and AI product reviews.
  - How:
    1. *An toàn (Safety)*: Does not endanger human life, physical well-being, or environmental sustainability.
    2. *Công bằng (Fairness)*: Free from algorithmic discrimination across gender, ethnicity, geography, or socioeconomic status.
    3. *Minh bạch (Transparency)*: Disclosing how the model operates, data sources, and training limitations.
    4. *Quyền riêng tư (Privacy & Data Sovereignty)*: Full compliance with user consent, right to know, and right to erasure.
    5. *Trách nhiệm giải trình (Accountability)*: Clear human responsibility for errors, harms, and corrective mechanisms.
    6. *Lợi ích xã hội (Social Good)*: Serving human flourishing, cultural preservation, and public welfare.

- **Advanced Prompting & RAG Architecture (Prompt Nâng cao & Truy xuất Tăng cường - Lớp 11 `11.C3.MR3`, `11.C3.MR4`)**:
  - When to use: Customizing LLM applications to eliminate hallucinations and constrain domain responses.
  - How:
    - *Advanced Prompting*: Structured system constraints, few-shot demonstration pairs, and chain-of-thought task decomposition (`11.C3.1`).
    - *Retrieval-Augmented Generation (RAG)*: Ingesting verified local reference documents $\rightarrow$ generating vector embeddings $\rightarrow$ retrieving exact semantic matches at query time $\rightarrow$ synthesizing answers grounded strictly in retrieved context.
  - Why it works / failure mode: Grounds generative responses in authoritative legal, curriculum, or scientific texts, preventing factual fabrication.

---

## Detailed Curricular Content & Learning Outcomes (YCCĐ) by Grade

### LỚP 10 (Grade 10)

| Chủ đề (Theme) | Nội dung (Content) | Mã & Yêu cầu cần đạt (YCCĐ Codes & Standards) |
|---|---|---|
| **A. Tư duy lấy con người làm trung tâm**<br>*(A1. Tính chủ động)* | Con người trong hệ thống & Kiểm soát AI | **10.A1.1.** Thực hành xác định vai trò của con người trong sử dụng, vận hành, tùy chỉnh một hệ thống AI cụ thể.<br>**10.A1.2.** Giải thích được tại sao việc con người kiểm soát AI là quan trọng, thông qua việc liên hệ đến các giá trị như an toàn, công bằng và quyền lợi con người. |
| **A. Tư duy lấy con người làm trung tâm**<br>*(A2. Rủi ro & A3. Luật pháp số)* | Rủi ro xã hội & Khung pháp lý với AI | **10.A2.1.** Nêu một số rủi ro đối với con người, xã hội mà một sản phẩm AI có thể đem lại.<br>**10.A2.MR1.** Nêu một số biện pháp hạn chế các rủi ro đối với con người, xã hội thông qua một dự án sáng tạo AI. *(Mở rộng)*<br>**10.A3.1.** Kể tên được các quy định pháp luật (ở mức độ khái niệm: Luật An ninh mạng, Luật Dữ liệu, Luật Bảo vệ dữ liệu cá nhân) có chức năng bảo vệ người dùng trong không gian số. |
| **B. Đạo đức AI**<br>*(B2. An toàn & B3. Trách nhiệm xã hội)* | Tuân thủ pháp luật & Đạo đức trong sáng tạo | **10.B2.1.** Nêu ví dụ về hành vi sử dụng AI vi phạm quy định nhà trường hoặc pháp luật CNTT.<br>**10.B2.MR1.** Nhận biết một số dấu hiệu của nội dung do AI tạo sinh tạo ra; kiểm tra và nhận xét mức độ minh bạch của việc khai báo sử dụng AI trong một sản phẩm. *(Mở rộng)*<br>**10.B3.1.** Trình bày ví dụ minh họa một số vấn đề đạo đức có thể phát sinh trong quá trình thiết kế và vận hành AI (thiên vị dữ liệu, vi phạm quyền riêng tư, thiếu minh bạch). |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C2. Ứng dụng thực tế & C3. Công nghệ AI)* | Vấn đề thực tiễn & Prompt mục tiêu cụ thể | **10.C2.1.** Xác định các vấn đề thực tế có thể ứng dụng AI để thực hiện, ưu tiên bối cảnh Việt Nam (sản xuất nông nghiệp, cộng đồng thiểu số,…).<br>**10.C2.2.** Liệt kê tên các ứng dụng AI theo tính năng của hệ thống.<br>**10.C2.MR1.** Xác định các yêu cầu cần có đối với việc ứng dụng AI thực hiện nhiệm vụ cụ thể. *(Mở rộng)*<br>**10.C2.3.** Nêu ví dụ trường hợp sử dụng AI hỗ trợ quá trình học tập.<br>**10.C2.MR2.** Sử dụng được một số ứng dụng AI trong học tập. *(Mở rộng)*<br>**10.C3.1.** Mô tả các yêu cầu để đưa ra prompt phù hợp với mục tiêu cụ thể.<br>**10.C3.2.** Thực hành đặt prompt giải quyết vấn đề gần gũi trong học tập, cuộc sống hiệu quả.<br>**10.C3.3.** Phân biệt được AI tạo sinh (Generative AI) với các hệ thống AI phân loại, dự đoán qua ví dụ cụ thể.<br>**10.C3.MR1.** Trình bày ví dụ mô tả một số công nghệ để thiết kế và tạo AI. *(Mở rộng)* |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C4. Dữ liệu trong AI)* | Các dạng dữ liệu & Chất lượng AI | **10.C4.1.** Phân tích sự ảnh hưởng của chất lượng dữ liệu đến chất lượng hệ thống AI.<br>**10.C4.MR1.** Phân tích các dạng dữ liệu (hình ảnh, âm thanh, từ ngữ, số liệu) được sử dụng để huấn luyện AI. *(Mở rộng)* |
| **D. Thiết kế hệ thống AI**<br>*(D1. Ý tưởng & D2. Thành phần hệ thống)* | Ý tưởng hệ thống & Các thành phần AI | **10.D1.1.** Nêu ví dụ cụ thể, xác định nhiệm vụ hoặc mục tiêu cụ thể mà một hệ thống AI cần thực hiện, nêu mối liên hệ giữa mục tiêu đó với các thành phần chính của hệ thống.<br>**10.D2.1.** Mô tả các thành phần cơ bản của hệ thống AI (dữ liệu, mô hình, thuật toán, đầu ra, phản hồi) phù hợp với nhiệm vụ cụ thể.<br>**10.D2.2.** Nêu ví dụ về một số vấn đề phát sinh trong quá trình vận hành hoặc tối ưu hóa AI và trình bày ý nghĩa của việc khắc phục. |

---

### LỚP 11 (Grade 11)

| Chủ đề (Theme) | Nội dung (Content) | Mã & Yêu cầu cần đạt (YCCĐ Codes & Standards) |
|---|---|---|
| **A. Tư duy lấy con người làm trung tâm**<br>*(A1. Nâng cao năng lực & A2. Bền vững)* | Quy trình an toàn & Bền vững, công bằng | **11.A1.1.** Xây dựng được quy trình sử dụng một sản phẩm AI cụ thể một cách thích hợp.<br>**11.A1.2.** Phân tích các trường hợp thực tế thấy được tầm quan trọng của việc dùng AI nâng cao năng lực con người mà vẫn bảo đảm sự kiểm soát của con người.<br>**11.A2.1.** Nêu ví dụ ứng dụng AI có tác động tích cực và lợi ích xã hội lâu dài (nông nghiệp thông minh, y tế cộng đồng).<br>**11.A2.2.** Phân tích các yếu tố thể hiện tính bền vững (sử dụng năng lượng hiệu quả, bảo vệ môi trường) và công bằng (mọi người đều hưởng lợi, không phân biệt đối xử). |
| **A. Tư duy lấy con người làm trung tâm**<br>*(A3. Quyền người dùng số)* | Quyền người dùng dữ liệu | **11.A3.1.** Trình bày các quyền cơ bản của người dùng dữ liệu: **quyền được biết, quyền được đồng ý, quyền yêu cầu xóa dữ liệu** (theo Nghị định 13/2023/NĐ-CP).<br>**11.A3.MR1.** Phân tích mức độ bảo đảm các quyền cơ bản của người dùng đối với một số sản phẩm AI thông qua dự án sáng tạo AI. *(Mở rộng)* |
| **B. Đạo đức AI**<br>*(B2. Phòng tránh rủi ro & B3. Sơ đồ hóa đạo đức)* | Phân loại rủi ro & Đạo đức trong thiết kế | **11.B2.1.** Nhận biết và phân loại các rủi ro, sự cố liên quan đến việc sử dụng AI có thể dẫn đến vi phạm quy định của nhà trường hoặc pháp luật.<br>**11.B3.MR1.** Xác định và sơ đồ hoá được các vấn đề đạo đức có thể phát sinh trong từng bước thiết kế và vận hành AI. *(Mở rộng)* |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C2. Học tập & C3. Prompt nâng cao & RAG)* | Tạo học liệu bằng AI, Prompt nâng cao, RAG | **11.C2.1.** Trình bày cách AI hỗ trợ học tập và thiết kế công cụ hỗ trợ.<br>**11.C2.2.** Đề xuất các tính năng AI hỗ trợ hoạt động học tập.<br>**11.C2.MR1.** Sử dụng công cụ AI để tạo và biên tập nội dung học liệu phục vụ học tập và đánh giá sản phẩm. *(Mở rộng)*<br>**11.C3.1.** Xác định một số kĩ thuật prompt nâng cao từ các yêu cầu cụ thể: **ràng buộc định dạng đầu ra, chia nhỏ nhiệm vụ**.<br>**11.C3.MR1.** Vận dụng được kĩ thuật prompt nâng cao (ràng buộc đầu ra, chain-of-thought). *(Mở rộng)*<br>**11.C3.2.** Mô tả các công nghệ AI cơ bản: chatbot, NLP, thị giác máy tính, cảm biến.<br>**11.C3.MR2.** Phân tích cách các công nghệ vận hành trong hệ thống AI. *(Mở rộng)*<br>**11.C3.MR3.** Xác định phương pháp tùy chỉnh hệ thống AI: bổ sung dữ liệu, điều chỉnh tham số, cung cấp chỉ dẫn hệ thống, sử dụng kĩ thuật RAG. *(Mở rộng)*<br>**11.C3.MR4.** Trình bày ở mức khái niệm cách hoạt động của kĩ thuật sinh nội dung tăng cường bằng truy xuất (**RAG**) và giải thích vì sao nó giúp giảm sai lệch/ảo giác. *(Mở rộng)* |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C5. Mạng nơ-ron & Thuật toán phân cụm/lớp)* | Mạng nơ-ron nhân tạo & Phân cụm/phân lớp | **11.C5.1.** Nêu được một số ứng dụng mạng nơ-ron nhân tạo (ANN).<br>**11.C5.MR1.** Trình bày được kiến thức cơ bản về mạng nơ-ron nhân tạo (nơ-ron, trọng số, bias, hàm kích hoạt). *(Mở rộng)*<br>**11.C5.2.** Nêu được một số ứng dụng thuật toán phân cụm (clustering), phân lớp (classification).<br>**11.C5.MR2.** Trình bày kiến thức cơ bản về thuật toán phân cụm, phân lớp và một số ý tưởng thực hiện (k-Means, k-NN, Decision Trees). *(Mở rộng)* |
| **D. Thiết kế hệ thống AI**<br>*(D1. Thiết kế & D2. Tối ưu hóa)* | Thiết kế hệ thống tổng thể & Tối ưu hóa | **11.D1.1.** Trình bày cách thức thiết kế và vận hành tổng thể của hệ thống AI, thể hiện mối quan hệ giữa mục tiêu, dữ liệu và các thành phần.<br>**11.D2.1.** Trình bày cách thức vận hành của công nghệ trong hệ thống AI, thể hiện mối liên hệ giữa các thành phần khi thực hiện nhiệm vụ cụ thể.<br>**11.D2.MR1.** Trình bày các cách thức giải quyết vấn đề phát sinh của hệ thống AI nhằm tối ưu hóa hiệu quả hoạt động. *(Mở rộng)* |

---

### LỚP 12 (Grade 12)

| Chủ đề (Theme) | Nội dung (Content) | Mã & Yêu cầu cần đạt (YCCĐ Codes & Standards) |
|---|---|---|
| **A. Tư duy lấy con người làm trung tâm**<br>*(A1. Kiểm soát vòng đời AI)* | Kiểm soát vòng đời & Trách nhiệm giải trình | **12.A1.1.** Phân tích một hệ thống AI nhằm đảm bảo con người có quyền kiểm soát và chịu trách nhiệm đối với tất cả các bước quan trọng trong vòng đời AI.<br>**12.A1.MR1.** Thực hiện phân tích quyền kiểm soát và trách nhiệm con người trong vòng đời AI thông qua dự án sáng tạo. *(Mở rộng)*<br>**12.A1.2.** Phân tích vai trò của con người và AI trong các bước chính của quá trình ra quyết định.<br>**12.A1.3.** Kiểm tra việc thực hiện trách nhiệm giải trình của con người đối với các quyết định, đối chiếu với các quy định hiện hành trong nước và quốc tế. |
| **A. Tư duy lấy con người làm trung tâm**<br>*(A2. Đạo đức thiết kế & A3. Trách nhiệm công dân)* | 6 Nguyên tắc đạo đức thiết kế & Công dân số | **12.A2.1.** Trình bày 6 nguyên tắc đạo đức cơ bản trong thiết kế, phát triển sản phẩm AI: **An toàn – Công bằng – Minh bạch – Tôn trọng quyền riêng tư – Trách nhiệm giải trình – Lợi ích xã hội**.<br>**12.A2.MR1.** Vận dụng các nguyên tắc để soạn thảo bộ nguyên tắc cá nhân cho một dự án AI cụ thể; đối chiếu các quyết định thiết kế (mục tiêu, dữ liệu, tính năng, kiểm thử) và điều chỉnh khi phát hiện nguy cơ vi phạm. *(Mở rộng)*<br>**12.A3.1.** Phân tích nội hàm của “trách nhiệm công dân trong xã hội AI”: sử dụng an toàn, trung thực, có đạo đức; tôn trọng quyền riêng tư; không dùng AI gian lận hay gây hại; đóng góp xây dựng môi trường số nhân văn. |
| **B. Đạo đức AI**<br>*(B1. Nguyên nhân sai lệch, B2. Đánh giá rủi ro & B3. Hệ sinh thái)* | Đạo đức, rủi ro & Trách nhiệm hệ sinh thái | **12.B1.MR1.** Phân tích nguyên nhân dẫn đến các vấn đề đạo đức hoặc sai lệch trong quá trình hoạt động của hệ thống AI. *(Mở rộng)*<br>**12.B2.1.** Xác định mức độ rủi ro khi sử dụng AI có thể dẫn đến vi phạm quy định nhà trường hoặc pháp luật.<br>**12.B3.1.** Trình bày quyền và trách nhiệm của người phát triển, người sử dụng AI; vai trò của cá nhân trong việc góp ý, đề xuất xây dựng chính sách, quy định liên quan đến AI. |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C2. Yêu cầu hệ thống & C3. Công cụ FOSS/Tối ưu)* | Công cụ FOSS, Tối ưu hóa & Quá khớp (Overfitting) | **12.C2.1.** Lựa chọn ý tưởng thiết kế một số công cụ AI để thực hiện các công việc khác nhau.<br>**12.C2.MR1.** Tùy chỉnh các yêu cầu hệ thống AI để hỗ trợ hoạt động học tập và xã hội. *(Mở rộng)*<br>**12.C3.1.** Nêu một số công cụ mã nguồn mở hoặc miễn phí dùng để thiết kế, huấn luyện, phát triển hệ thống AI: **Teachable Machine, ML5.js, TensorFlow.js, MIT App Inventor** hoặc công cụ phù hợp khác.<br>**12.C3.MR1.** Sử dụng công cụ mã nguồn mở/miễn phí để thiết kế, huấn luyện và phát triển hệ thống AI. *(Mở rộng)*<br>**12.C3.2.** Nêu ví dụ cách thức đánh giá hiệu quả của hệ thống AI.<br>**12.C3.MR2.** Đánh giá khả năng tối ưu hệ thống AI thông qua cập nhật công nghệ mới. *(Mở rộng)*<br>**12.C3.MR3.** Trình bày khái niệm cơ bản của hệ thống học máy: **hàm mục tiêu (objective function), tối ưu hoá hệ thống, mô hình quá khớp dữ liệu (overfitting)**. *(Mở rộng)* |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C4. Dữ liệu trong AI)* | Thu thập, cải thiện dữ liệu và nền tảng phát triển | **12.C4.MR1.** Thu thập và tổ chức dữ liệu đáp ứng yêu cầu của việc phát triển hệ thống AI. *(Mở rộng)*<br>**12.C4.MR2.** Phân tích và xác định các nền tảng hoặc bộ công cụ phát triển AI, cải thiện các bộ dữ liệu đáp ứng quá trình thiết kế, phát triển AI. *(Mở rộng)* |
| **D. Thiết kế hệ thống AI**<br>*(D1. Giải pháp & D2. Phát triển & Tác nhân AI)* | Vai trò nhóm & Hệ thống Tác nhân AI (AI Agent) | **12.D1.1.** Nhận biết các phương án thiết kế và vận hành hệ thống AI phù hợp để đạt hiệu quả cao trong nhiệm vụ cụ thể.<br>**12.D1.MR1.** Phân tích các phương án thiết kế và vận hành hệ thống AI phù hợp. *(Mở rộng)*<br>**12.D2.1.** Nhận biết các vai trò khác nhau trong phát triển sản phẩm AI (người đề xuất ý tưởng, lập trình, huấn luyện, kiểm thử) và yêu cầu hợp tác đa ngành.<br>**12.D2.MR1.** Phân tích nguyên nhân vấn đề phát sinh và lựa chọn cách giải quyết để hệ thống hoạt động ổn định. *(Mở rộng)*<br>**12.D2.MR2.** Trình bày được khả năng và cấu trúc cơ bản của một hệ thống **tác nhân AI (AI agent)**. *(Mở rộng)*<br>**12.D2.MR3.** Xây dựng và kiểm thử được hệ thống **tác nhân AI đơn giản** phục vụ một nhiệm vụ học tập hoặc cộng đồng. *(Mở rộng)* |

---

## Pedagogical Anti-patterns in Upper Secondary AI

- **Theoretical Mathematics without Execution**: Lecturing on vector spaces, gradient formulas, and calculus derivations without having students train, evaluate, or debug a real working model.
- **Unverified API Copy-Pasting**: Writing code that makes blind REST API calls to commercial LLMs without configuring temperature, system guardrails, or citation retrieval (RAG).
- **Ignoring Model Evaluation Trade-offs**: Reporting only raw accuracy percentage on severely imbalanced datasets instead of reporting Precision, Recall, and F1-score.

## Worked Example: Grade 12 AI Agent Prototype for High School Admissions
- **Target Codes**: `12.D2.MR2`, `12.D2.MR3`, `12.A2.MR1`.
- **System**: Multi-step AI Agent assisting 9th-grade parents in exploring high school enrollment criteria.
- **Workflow**:
  1. *Tool 1 (Retriever)*: Searches the official municipal admission handbook (Công văn tuyển sinh 10 Sở GDĐT).
  2. *Tool 2 (Calculator)*: Computes benchmark admission scores based on math, literature, and foreign language test scores.
  3. *Tool 3 (Form Generator)*: Formulates a recommended study plan for the candidate.
  4. *Human Oversight Gate*: Displays all calculated scores with citations directly to the official circular, warning: *"Recommendations are estimates; final admission depends on official score releases by the Examination Board."*

## Key Takeaways
1. **Human control spans the entire AI lifecycle**: Con người kiểm soát từ thiết kế, chọn dữ liệu, thẩm định đến quyết định sau cùng.
2. **AI Agents require bounded autonomy**: Multi-step AI agents must operate strictly within assigned parameters under explicit human monitoring (`12.D2.MR2`).
3. **RAG mitigates hallucination in high-stakes domains**: Grounding LLMs in authoritative retrieved documents is standard practice for educational and legal applications.
4. **F.A.T.E. principles guide career readiness**: High school graduates enter the workforce equipped with technical skills and ethical citizenship.

## Connects To
- **Ch 1**: Fulfills the specialized elective requirements for Upper Secondary Informatics (Tin học 10–12 and Chuyên đề học tập).
- **Ch 4**: Direct progression from lower secondary data pipelines and prompt design.
- **Ch 6 & 7**: Guided by the 12-period mandatory curriculum integration and non-exam formative assessment rules of QĐ 2422.
