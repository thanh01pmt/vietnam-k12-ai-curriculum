# Chapter 4: AI in Lower Secondary Education (Cấp THCS: Lớp 6 – Lớp 9)

## Core Idea
In Lower Secondary education (THCS: Grades 6–9), Quyết định 2422/QĐ-BGDĐT transitions students from intuitive play to logical, scientific reasoning and verification. Instruction emphasizes empirical investigation: comparing rule-based systems with machine learning, logging prompt prompts and dataset sources, analyzing algorithmic bias, detecting deepfakes, and developing small-scale collaborative AI prototypes (chatbots, computer vision classifiers) with mandatory academic attribution.

## Frameworks Introduced

- **Rule-Based vs. Machine Learning Paradigm (Hệ chuyên gia vs Học máy từ dữ liệu)**:
  - When to use: Grade 6 introductory units to clarify how machine intelligence operates.
  - How:
    - *Rule-Based (Symbolic AI)*: Explicit human logic programmed as deterministic conditional statements (`IF [condition] THEN [action]`). Explainable, brittle in ambiguous or high-dimensional tasks.
    - *Machine Learning (Data-Driven AI)*: Statistical algorithms that induce decision patterns directly from labeled training data. Handles unstructured sensory data (images, voice, natural language) robustly, but requires rigorous testing on unseen data.
  - Why it works / failure mode: Dispels the myth that AI is magic, categorizing technology into explicit human rules and statistical induction.

- **The Verification & Prompt Logging Protocol (Quy trình Kiểm chứng & Nhật ký Câu lệnh - QĐ 2422 Phần V.4)**:
  - When to use: All lower secondary lab assignments involving Generative AI or search tools.
  - How:
    1. *Prompt Documentation*: Students record the exact prompt, constraints, role, and context provided to the model.
    2. *Input Data Source Tracking*: Documenting where training samples or reference documents originated.
    3. *Cross-Source Verification (Kiểm chứng đa nguồn)*: Checking AI claims against at least one trusted independent source (textbooks, official portals, teacher expertise).
    4. *Correction Log*: Recording where the AI generated inaccurate or hallucinated content and how the student corrected it.
  - Why it works / failure mode: Instills academic integrity and critical scrutiny; eliminates blind copy-pasting.

- **Tripartite Machine Learning Taxonomy (3 Phương pháp Học máy Cơ bản - Lớp 7 `7.C5.MR1`)**:
  - When to use: Grade 7 technical units.
  - How:
    - *Supervised Learning (Học có giám sát)*: Learning from human-labeled input-output pairs (e.g., spam filtering, image classification).
    - *Unsupervised Learning (Học không giám sát)*: Automatically discovering clusters, patterns, or groupings in unlabeled data (e.g., customer segmentation, document grouping).
    - *Reinforcement Learning (Học tăng cường)*: Learning optimal behaviors through environmental trial-and-error, rewards, and penalties (e.g., game-playing AI, robot navigation).

---

## Detailed Curricular Content & Learning Outcomes (YCCĐ) by Grade

### LỚP 6 (Grade 6)

| Chủ đề (Theme) | Nội dung (Content) | Mã & Yêu cầu cần đạt (YCCĐ Codes & Standards) |
|---|---|---|
| **A. Tư duy lấy con người làm trung tâm**<br>*(A1. Tính chủ động)* | Con người tạo và điều khiển AI | **6.A1.1.** Giải thích được AI là sản phẩm do con người tạo ra, lập trình và điều khiển để thực hiện những nhiệm vụ cụ thể; AI không tự sinh ra và không hoạt động độc lập với con người. Nêu được ví dụ về một số công cụ AI quen thuộc và chỉ ra vai trò của con người trong việc tạo ra chúng. |
|  | AI hoạt động theo lập trình | **6.A1.2.** Trình bày được vai trò của AI chỉ là công cụ hỗ trợ hoạt động của con người; con người đưa ra quyết định cuối cùng và chịu trách nhiệm khi sử dụng AI.<br>**6.A1.3.** Thực hiện được việc kiểm tra lại một kết quả do AI đưa ra (đối chiếu với sách giáo khoa, nguồn tin cậy khác hoặc hỏi thầy cô) trước khi sử dụng, thể hiện thói quen “con người quyết định cuối cùng”. |
| **A. Tư duy lấy con người làm trung tâm**<br>*(A3. Công dân trong kỉ nguyên AI)* | Con người ra quyết định với AI | **6.A3.1.** Nêu được ví dụ về tình huống con người ra quyết định với sự hỗ trợ của AI (y tế: bác sĩ xem xét gợi ý của AI; giao thông: người lái xe cân nhắc lộ trình AI đề xuất). Thực hành ra quyết định trong tình huống giả định có gợi ý của AI. |
|  | Học hỏi và phát triển với AI | **6.A3.2.** Trình bày được lợi ích của AI trong việc hỗ trợ con người học hỏi, rèn luyện kĩ năng khi được sử dụng đúng cách, có mục đích rõ ràng. Sử dụng được một công cụ AI phù hợp lứa tuổi để hỗ trợ một nhiệm vụ học tập đơn giản. |
|  | Quyền riêng tư & Bảo vệ dữ liệu cá nhân | **6.A3.3.** Giải thích được dữ liệu cá nhân (hình ảnh, giọng nói, họ tên, địa chỉ, thông tin học tập, thói quen mạng,...) là tài sản của mỗi người; chỉ chủ sở hữu mới có quyền quyết định việc chia sẻ hoặc cho phép sử dụng.<br>**6.A3.4.** Trình bày được khái niệm quyền riêng tư ở mức đơn giản; nêu tác hại khi dữ liệu cá nhân bị sử dụng sai mục đích; nhận biết cách ứng phó ban đầu khi có nguy cơ mất an toàn dữ liệu (dừng chia sẻ; báo cha mẹ, thầy cô; báo cáo trên nền tảng). |
| **B. Đạo đức AI**<br>*(B1. Khía cạnh đạo đức & B2. Sử dụng an toàn)* | Mặt tốt và mặt xấu & An toàn khi dùng AI | **6.B1.1.** Chỉ ra được mặt tích cực và hạn chế của một số tính năng AI cụ thể (tính năng thu thập dữ liệu giúp gợi ý chính xác hơn nhưng có thể ảnh hưởng quyền riêng tư).<br>**6.B2.1.** Đặt được một số câu hỏi đơn giản để kiểm tra tính an toàn và minh bạch của ứng dụng AI ("Công cụ này có an toàn không?", "Có thu thập thông tin cá nhân không?", "Có thể tắt tính năng này không?") và nhận xét về mức độ an toàn. |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C1. Đặc điểm chính của AI)* | Kiến trúc cơ bản và cách hoạt động của AI | **6.C1.1.** Giải thích được hai thành phần chính để huấn luyện (“dạy”) AI là dữ liệu và thuật toán. Mô tả các bước hoạt động chính của công cụ AI qua ví dụ (trợ lí ảo: thu âm thanh $\rightarrow$ chuyển giọng nói thành văn bản $\rightarrow$ xử lí ngữ nghĩa $\rightarrow$ tìm câu trả lời).<br>**6.C1.MR1.** Chỉ ra mối liên hệ giữa huấn luyện và hoạt động của AI (dữ liệu càng phong phú, câu trả lời càng chính xác). *(Mở rộng)*<br>**6.C1.MR2.** Thực hiện thử nghiệm đơn giản với công cụ AI và nhận xét các bước hoạt động (đặt cùng câu hỏi theo nhiều cách nói khác nhau và quan sát). *(Mở rộng)* |
|  | Tác động tích cực và tiêu cực của AI | **6.C1.2.** Nêu ví dụ về tác động tích cực và tiêu cực của AI đối với bản thân, gia đình.<br>**6.C1.MR3.** Phân tích tác động của công cụ AI cụ thể (tính năng gợi ý video giúp tìm nội dung nhanh nhưng dễ gây nghiện, mất thời gian). *(Mở rộng)* |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C2. Ứng dụng & C3. Công nghệ AI)* | Làm quen ứng dụng & Công nghệ AI quen thuộc | **6.C2.1.** Phân biệt được công cụ có ứng dụng AI và không ứng dụng AI (trợ lí ảo có AI; máy tính bỏ túi không có AI).<br>**6.C2.2.** Kể tên và mô tả chức năng của một số công cụ AI thông dụng (trợ lí ảo, bản đồ số, dịch thuật).<br>**6.C2.MR1.** Nêu ví dụ ứng dụng AI gắn với thực tiễn Việt Nam (nông nghiệp, giáo dục, dự báo lũ, dịch ngôn ngữ dân tộc). *(Mở rộng)*<br>**6.C3.1.** Kể tên một số công nghệ AI quen thuộc (nhận dạng hình ảnh, chuyển đổi văn bản và giọng nói).<br>**6.C3.MR1.** Trình bày tính năng AI tích hợp (gợi ý đề xuất nội dung mạng xã hội, quảng cáo cá nhân hóa) và ảnh hưởng đến quyết định của người dùng. *(Mở rộng)* |
| **D. Thiết kế hệ thống AI**<br>*(D1. Giải pháp & D2. Cải tiến)* | Lựa chọn sử dụng & Giới hạn của AI | **6.D1.1.** Nêu tình huống nên hoặc không nên dùng AI (nên dùng luyện phát âm, tìm đường; không nên nhờ AI viết hộ bài văn, làm hộ bài tập vì làm giảm khả năng tự suy nghĩ).<br>**6.D1.MR1.** Trình bày ý kiến cá nhân về việc nên hay không nên dùng AI trong tình huống thực tế kèm lí do. *(Mở rộng)*<br>**6.D2.1.** Trình bày giới hạn của AI so với con người qua các công việc cần thấu hiểu cảm xúc, sáng tạo, ra quyết định phức tạp.<br>**6.D2.MR1.** Giải thích vì sao AI gặp giới hạn (AI học từ dữ liệu quá khứ nên khó xử lí tình huống mới; AI không có cảm xúc thật). *(Mở rộng)*<br>**6.D2.MR2.** Đề xuất cách kết hợp giữa con người và AI để phát huy thế mạnh mỗi bên (AI gợi ý ý tưởng, con người lựa chọn và hoàn thiện). *(Mở rộng)* |

---

### LỚP 7 (Grade 7)

| Chủ đề (Theme) | Nội dung (Content) | Mã & Yêu cầu cần đạt (YCCĐ Codes & Standards) |
|---|---|---|
| **A. Tư duy lấy con người làm trung tâm**<br>*(A1. Quyền ra quyết định)* | Quyền ra quyết định & Xác thực kết quả | **7.A1.1.** Giải thích được lí do con người cần giữ quyền ra quyết định khi sử dụng AI (bảo đảm công bằng, xem xét hoàn cảnh/cảm xúc mà AI không hiểu; bảo đảm an toàn; bảo vệ quyền riêng tư, phẩm giá).<br>**7.A1.2.** Nêu ví dụ hậu quả có thể xảy ra khi không có sự xác thực của con người đối với kết quả do AI đưa ra.<br>**7.A1.MR1.** Thực hiện kiểm chứng một thông tin do AI cung cấp bằng ít nhất một nguồn tin cậy khác (sách giáo khoa, cổng thông tin chính thống, ý kiến thầy cô) trước khi sử dụng. *(Mở rộng)* |
| **A. Tư duy lấy con người làm trung tâm**<br>*(A2. Vì sự tiến bộ & A3. Quyền tự chủ)* | Hậu quả AI quyết định & Ngăn chặn AI có hại | **7.A2.1.** Phân tích các tác hại có thể xảy ra nếu con người cho phép AI đưa ra quyết định cuối cùng trong tình huống thực tế.<br>**7.A2.2.** Nêu hậu quả có thể xảy ra nếu không có quy định pháp lý ngăn chặn việc thiết kế, sản xuất công cụ AI có hại.<br>**7.A3.1.** Nêu ví dụ tình huống AI được tự động thực hiện thao tác thay con người (tự động sửa lỗi chính tả) và tình huống con người phải trực tiếp quyết định.<br>**7.A3.MR1.** Trình bày ví dụ về xung đột giữa quyền tự chủ của con người và mức độ tự chủ của AI. *(Mở rộng)*<br>**7.A3.MR2.** Nêu yêu cầu đánh giá mức độ tự chủ của AI dựa trên bối cảnh cụ thể. *(Mở rộng)*<br>**7.A3.2.** Giải thích sự cần thiết phải bảo vệ quyền tự chủ của con người khi sử dụng AI để ra các quyết định quan trọng. |
| **B. Đạo đức AI**<br>*(B2. An toàn & B3. Trách nhiệm cá nhân)* | Đánh giá môi trường an toàn & Trách nhiệm sử dụng | **7.B2.1.** Nêu một số tiêu chí đơn giản (dựa trên nguyên tắc đạo đức) để đánh giá mức độ phù hợp, an toàn của ứng dụng AI.<br>**7.B2.2.** Nêu ví dụ hành động cụ thể xây dựng môi trường AI có đạo đức (báo cáo lỗi, không dùng ứng dụng độc hại, yêu cầu sự minh bạch).<br>**7.B3.1.** Thể hiện thái độ và cam kết cá nhân sử dụng AI có trách nhiệm (bài viết ngắn, hùng biện). **Thể hiện được việc khai báo trung thực khi có sử dụng AI trong sản phẩm học tập.** |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C4. Dữ liệu & C5. Kĩ thuật AI)* | Đạo đức dữ liệu & 3 phương pháp học máy | **7.C4.1.** Trình bày các vấn đề đạo đức nảy sinh từ dữ liệu huấn luyện (dữ liệu thiếu đa dạng dẫn đến phân biệt đối xử, dữ liệu riêng tư bị xâm phạm).<br>**7.C4.MR1.** Phân tích tầm quan trọng của việc sử dụng bộ dữ liệu “sạch” và “công bằng” trong việc tạo ra công cụ AI có đạo đức. *(Mở rộng)*<br>**7.C5.1.** Mô tả các bước chính trong quá trình huấn luyện AI qua ví dụ cụ thể (thu thập và gán nhãn ảnh chó mèo $\rightarrow$ cho máy học $\rightarrow$ kiểm tra trên ảnh mới $\rightarrow$ điều chỉnh).<br>**7.C5.2.** Nêu ví dụ về các cách học khác nhau của AI (học từ dữ liệu gán nhãn sẵn; tự tìm quy luật; học qua thử nghiệm và rút kinh nghiệm).<br>**7.C5.MR1.** Phân biệt được ba phương pháp học máy cơ bản: **học có giám sát (supervised), học không giám sát (unsupervised), học tăng cường (reinforcement learning)**; nêu ứng dụng thực tế. *(Mở rộng)* |
| **D. Thiết kế hệ thống AI**<br>*(D1. Giải pháp & D2. Cải tiến)* | Ý tưởng dự án thực tiễn & Tạo sản phẩm AI | **7.D1.1.** Nêu ví dụ về vấn đề trong trường học hoặc cộng đồng có thể giải quyết bằng AI (chatbot giải đáp nội quy trường học; AI thị giác phân loại rác tái chế).<br>**7.D1.MR1.** Phân tích tính khả thi của ý tưởng dự án AI (dữ liệu có dễ thu thập không, rủi ro đạo đức, chi phí và độ phức tạp). *(Mở rộng)*<br>**7.D2.1.** Lập kế hoạch cho dự án sáng tạo có sử dụng AI theo nhóm nhỏ.<br>**7.D2.MR1.** Thực hành tạo được sản phẩm đơn giản theo kế hoạch đã xây dựng. *(Mở rộng)* |

---

### LỚP 8 (Grade 8)

| Chủ đề (Theme) | Nội dung (Content) | Mã & Yêu cầu cần đạt (YCCĐ Codes & Standards) |
|---|---|---|
| **A. Tư duy lấy con người làm trung tâm**<br>*(A1. Tính chủ động)* | AI không thay thế con người & Rủi ro lạm dụng | **8.A1.1.** Nêu một số lĩnh vực AI không nên thay thế con người (giáo dục: thầy cô hiểu tâm lí, dạy đạo đức; y tế: bác sĩ lắng nghe, động viên bệnh nhân; nghệ thuật: nghệ sĩ thể hiện cảm xúc và trải nghiệm sống).<br>**8.A1.2.** Nêu những rủi ro của việc lạm dụng AI tạo sinh, liên hệ nguy cơ suy giảm tư duy phản biện, kĩ năng sáng tạo; nêu sự cần thiết phải kiểm chứng nguồn thông tin khi dùng AI tạo sinh. |
| **A. Tư duy lấy con người làm trung tâm**<br>*(A2. Vì sự tiến bộ & A3. Công dân AI)* | Nguy cơ theo dõi, thao túng & Trách nhiệm giải trình | **8.A2.1.** Giải thích việc hệ thống AI có thể thu thập, phân tích dữ liệu cá nhân (vị trí, thói quen, giọng nói, sở thích) để kiểm soát hành vi hoặc thao túng quyết định của con người.<br>**8.A2.2.** Nhận biết hiện tượng sử dụng AI không minh bạch (bị theo dõi ngầm; bị đề xuất nội dung một chiều; bị thao túng tâm lý).<br>**8.A3.1.** Phân biệt vai trò của người dùng và người phát triển khi tương tác với AI.<br>**8.A3.MR1.** Giải thích việc người dùng cũng tác động đến công cụ AI (dữ liệu tương tác được dùng để huấn luyện tiếp; nội dung tương tác nhiều được ưu tiên đề xuất). *(Mở rộng)*<br>**8.A3.2.** Nêu ví dụ các bên (người sáng tạo, nhà cung cấp, người sử dụng) phải chịu trách nhiệm pháp lý khi AI gây hậu quả (người dùng tạo ảnh giả mạo; nhà cung cấp phát tán thông tin sai).<br>**8.A3.3.** Nêu những việc thể hiện trách nhiệm giải trình khi dùng AI trong học tập (nói rõ phần nào dùng AI; kiểm tra tính chính xác).<br>**8.A3.MR2.** Nêu trách nhiệm giải trình khi thiết kế AI (công khai nguồn dữ liệu, giải thích cách hoạt động). *(Mở rộng)* |
| **B. Đạo đức AI**<br>*(B1. Rủi ro, B2. An toàn & B3. Trách nhiệm)* | Phân loại rủi ro & Phòng tránh rủi ro dữ liệu | **8.B1.1.** Nhận diện và phân loại các rủi ro phổ biến khi dùng AI: (1) rủi ro dữ liệu và quyền riêng tư; (2) rủi ro thuật toán thiên vị hoặc kết luận sai; (3) rủi ro lừa đảo bằng nội dung giả mạo (hình ảnh, giọng nói, tin nhắn giả).<br>**8.B2.1.** Trình bày cách thức bảo vệ dữ liệu cá nhân, tôn trọng bản quyền và giảm thiểu rủi ro khi sử dụng AI.<br>**8.B3.1.** Nêu các vấn đề đạo đức cần lưu ý khi phát triển AI (bảo mật thông tin, không cung cấp thông tin sai lệch, không xúc phạm người khác). |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C1. Đặc điểm & C5. Kĩ thuật AI)* | Cơ chế Đọc - Nghe - Nhìn & Nhận diện cảm xúc | **8.C1.1.** Mô tả ở mức đơn giản cách AI thực hiện chức năng cơ bản: “nghe” (thu âm $\rightarrow$ chuyển thành văn bản $\rightarrow$ phân tích nội dung); “nhìn” (phân tích đặc trưng điểm ảnh $\rightarrow$ so sánh với mẫu đã học).<br>**8.C1.MR1.** Phân tích công nghệ đảm nhiệm chức năng đọc - nghe - nhìn: xử lý ngôn ngữ tự nhiên (NLP), nhận dạng giọng nói (ASR), thị giác máy tính (CV). *(Mở rộng)*<br>**8.C5.1.** Nêu cách AI nhận diện cảm xúc dựa vào đặc điểm (nét mặt, từ khóa văn bản, ngữ điệu giọng nói, cử chỉ).<br>**8.C5.MR1.** Nhận xét về độ tin cậy và giới hạn của AI nhận diện cảm xúc (cùng nét mặt có thể biểu thị cảm xúc khác nhau tùy bối cảnh văn hóa). *(Mở rộng)* |
| **D. Thiết kế hệ thống AI**<br>*(D1. Kế hoạch & D2. Dự án & UX)* | Kế hoạch dự án AI & Trải nghiệm người dùng (UX) | **8.D1.1.** Xác định vấn đề thực tế có thể giải quyết bằng AI.<br>**8.D1.MR1.** Lập kế hoạch sơ bộ cho dự án AI giải quyết vấn đề đã xác định. *(Mở rộng)*<br>**8.D2.1.** Trình bày kịch bản hội thoại cho một tình huống cụ thể có ứng dụng AI (chatbot, trợ lí ảo).<br>**8.D2.MR1.** Mô tả các đặc điểm cơ bản của một trải nghiệm người dùng (UX) tốt khi tương tác với AI.<br>**8.D2.MR2.** Lập kế hoạch và triển khai làm việc nhóm phát triển sản phẩm AI đơn giản (chatbot, mô hình nhận dạng) bằng công cụ có sẵn. *(Mở rộng)* |

---

### LỚP 9 (Grade 9)

| Chủ đề (Theme) | Nội dung (Content) | Mã & Yêu cầu cần đạt (YCCĐ Codes & Standards) |
|---|---|---|
| **A. Tư duy lấy con người làm trung tâm**<br>*(A1. Thách thức xã hội & A2. Tác động xã hội)* | Thách thức xã hội & Thiên vị trong AI | **9.A1.1.** Trình bày ý kiến cá nhân về thách thức xã hội trong kỉ nguyên AI (hy sinh sự an toàn của người dùng để ưu tiên đổi mới công nghệ).<br>**9.A2.1.** Nêu dẫn chứng giải thích vì sao AI có tác động sâu rộng đến kinh tế, giáo dục và việc làm.<br>**9.A2.2.** Giải thích các vấn đề “thiên vị”, “thành kiến” mà AI có thể gây ra đối với xã hội nếu dữ liệu huấn luyện bị lệch. |
| **A. Tư duy lấy con người làm trung tâm**<br>*(A3. Công dân trong kỉ nguyên AI)* | Định hướng học tập & Nghề nghiệp tương lai | **9.A3.1.** Trình bày những năng lực con người cần rèn luyện: học cách học (tự học suốt đời), tư duy phản biện (phân tích thông tin AI cung cấp), sáng tạo và cảm xúc, kĩ năng giao tiếp và hợp tác.<br>**9.A3.2.** Xác định mục tiêu học tập cá nhân trong thế giới có AI (dùng AI tóm tắt tài liệu, luyện ngoại ngữ, phát triển kĩ năng mềm).<br>**9.A3.3.** Nêu ví dụ dùng AI làm công cụ thể hiện bản thân và theo đuổi đam mê.<br>**9.A3.4.** Trình bày những thay đổi mà AI mang lại cho các ngành nghề trong tương lai; xác định kĩ năng cần trang bị để làm việc cùng AI. |
| **B. Đạo đức AI**<br>*(B2. An toàn & B3. Kiến tạo AI công bằng)* | Nhận diện Deepfake & Trách nhiệm khai báo | **9.B2.1.** Trình bày vai trò kiểm soát và chịu trách nhiệm đối với kết quả cuối cùng do AI tạo ra. **Khai báo được việc sử dụng AI trong sản phẩm học tập của bản thân.**<br>**9.B2.2.** Nêu vai trò của cá nhân và cộng đồng trong việc giám sát, phản hồi để sử dụng AI công bằng, an toàn.<br>**9.B2.3.** Phân tích dấu hiệu nhận biết nội dung giả mạo (deepfake); kiểm chứng thông tin đa nguồn và đề xuất cách ứng phó khi phát hiện nội dung lừa đảo.<br>**9.B3.1.** Giải thích tầm quan trọng của việc huấn luyện AI không phân biệt đối xử và tôn trọng sự đa dạng.<br>**9.B3.2.** Nêu cách thu thập dữ liệu bảo đảm công bằng, không bỏ sót hay thiên vị các nhóm đối tượng. |
| **C. Kĩ thuật và ứng dụng AI**<br>*(C2. Vận dụng & C4. Dữ liệu AI)* | Tạo sản phẩm đơn giản & Cải thiện bộ dữ liệu | **9.C2.1.** Đề xuất ý tưởng sáng tạo giải quyết vấn đề bằng AI.<br>**9.C2.MR1.** Vận dụng kiến thức tạo ra công cụ AI đơn giản (chatbot, nhận dạng hình ảnh) dựa trên nền tảng mở, miễn phí (Teachable Machine, App Inventor, MicroBlocks). *(Mở rộng)*<br>**9.C4.1.** Trình bày cách cải thiện bộ dữ liệu để nâng cao chất lượng sản phẩm AI (bổ sung dữ liệu thiếu, loại bỏ dữ liệu trùng, sửa nhãn sai).<br>**9.C4.MR1.** Chỉ ra những điểm cần cải thiện trong một bộ dữ liệu cụ thể làm giảm chất lượng mô hình. *(Mở rộng)*<br>**9.C4.MR2.** Thực hiện việc cải thiện bộ dữ liệu (thêm, xóa, sửa dữ liệu) để nâng cao chất lượng sản phẩm AI. *(Mở rộng)* |
| **D. Thiết kế hệ thống AI**<br>*(D1. Dẫn dắt & D2. Cải tiến sản phẩm)* | Con người dẫn dắt & Đánh giá kiểm thử sản phẩm | **9.D1.1.** Trình bày vai trò con người là người đồng sáng tạo và dẫn dắt trong thiết kế, vận hành và phát triển hệ thống AI.<br>**9.D1.MR1.** Phân tích vai trò dẫn dắt của con người qua công cụ cụ thể (xác định mục tiêu, chọn dữ liệu, đánh giá và điều chỉnh kết quả). *(Mở rộng)*<br>**9.D2.1.** Nêu cách kiểm tra đơn giản để đánh giá sản phẩm AI (với mô hình nhận dạng: thử với dữ liệu mới chưa dùng khi huấn luyện, đếm số lần đúng/sai; với chatbot: thử các câu hỏi bẫy).<br>**9.D2.MR1.** Thiết kế và thực hiện được các bài kiểm tra đơn giản để đánh giá sản phẩm AI. *(Mở rộng)*<br>**9.D2.MR2.** Phân tích kết quả kiểm tra và chủ động thử nghiệm cải tiến nhằm nâng cao chất lượng sản phẩm. *(Mở rộng)* |

---

## Pedagogical Anti-patterns in Lower Secondary AI

- **Accepting AI Outputs without Prompt Logs**: Allowing students to turn in essays or reports without submitting their prompt history, verification links, and correction notes.
- **Testing on Training Data**: Measuring model accuracy using the same photos used during training, generating illusory 100% scores.
- **Ignoring Data Imbalance**: Training a civic trash detector with 100 images of clean bottles and 5 images of crushed cans, failing to understand why real-world detection fails.

## Worked Example: Grade 8 Chatbot Scripting & UX Evaluation Lab
- **Target Codes**: `8.D2.1`, `8.D2.MR1`, `8.D2.MR2`.
- **Tool**: MIT App Inventor / Scratch Dialog Tree / Lightweight Python.
- **Duration**: 2 periods (90 minutes).

1. **Step 1: Scenario Design**: Build a "School Library Assistant Bot" answering hours, book borrowing rules, and overdue fines.
2. **Step 2: UX Failure Injection**: Test what happens when a student asks: "How much is the fine if my dog chewed the book?"
3. **Step 3: Verification Rule**: If confidence is $< 70\%$, the bot must state: *"I cannot answer this unusual circumstance. Please speak directly to Ms. Lan at the front counter."* (Enforces human oversight).

## Key Takeaways
1. **Con người luôn là người quyết định cuối cùng**: AI outputs are recommendations, not commands; students must cultivate verification reflexes.
2. **Trách nhiệm giải trình là bắt buộc**: Using AI in schoolwork mandates full disclosure of tools, prompts, and personal edits.
3. **Chất lượng dữ liệu quyết định chất lượng mô hình**: Garbage data produces biased, unreliable, or dangerous AI decisions.
4. **Kiểm chứng đa nguồn chống tin giả & deepfake**: Critical scrutiny of audio/video anomalies protects students against digital fraud.

## Connects To
- **Ch 3**: Builds on primary sensory classification and safe device habits.
- **Ch 5**: Prepares students for upper secondary formal neural network architectures, prompt optimization, and data governance.
- **Ch 6**: Operationalizes the lower secondary logical verification and formative assessment protocols of QĐ 2422.
