# Khung Chương trình Trí tuệ Nhân tạo K-12 Việt Nam & Kỹ năng Tác tử GDPT 2018

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.vi.md"><strong>Tiếng Việt</strong></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Chuẩn_Agent_Skills-Open_Standard-blueviolet?style=for-the-badge" alt="Chuẩn Agent Skills">
  <img src="https://img.shields.io/badge/Đối_tượng-Giáo_dục_Phổ_thông_Việt_Nam-green?style=for-the-badge" alt="Đối tượng: K-12 Việt Nam">
  <img src="https://img.shields.io/badge/Căn_cứ_pháp_lý-QĐ_2422_•_TT_32_•_CV_5588-blue?style=for-the-badge" alt="Căn cứ pháp lý">
  <img src="https://img.shields.io/badge/Trạng_thái-Sẵn_sàng_Triển_khai-success?style=for-the-badge" alt="Trạng thái">
  <img src="https://img.shields.io/badge/Giấy_phép-CC_BY_4.0-lightgrey?style=for-the-badge" alt="Giấy phép">
</p>

---

## 📖 Tóm tắt Tổng quan

**`vietnam-k12-ai-curriculum`** là bộ kỹ năng tác tử (Agent Skill) chuẩn hóa, đóng vai trò là cơ sở tri thức chuyên sâu và công cụ hỗ trợ ra quyết định dành cho các trợ lý AI lập trình, chuyên gia thiết kế chương trình và giáo viên. Bộ kỹ năng này mã hóa toàn diện các khung pháp lý, chuỗi sư phạm và hướng dẫn chỉ đạo chính thức của Việt Nam về giáo dục Trí tuệ Nhân tạo trong nhà trường phổ thông:

- **Quyết định 2422/QĐ-BGDĐT**: Khung nội dung giáo dục Trí tuệ Nhân tạo cấp Tiểu học, THCS và THPT.
- **Thông tư 32/2018/TT-BGDĐT & Thông tư 13/2022/TT-BGDĐT**: Chương trình Giáo dục Phổ thông 2018 (GDPT 2018) môn Tin học.
- **Công văn 5588/BGDĐT-GDPT & Công văn 5208/BGDĐT-GDPT**: Hướng dẫn chỉ đạo thực hiện định mức tối thiểu 12 tiết học AI/năm học và tích hợp kế hoạch nhà trường.
- **Công văn 8585/SGDĐT-GDPT (Sở GD&ĐT TP.HCM)**: Hướng dẫn triển khai trường học số, kho học liệu mở dùng chung và cơ chế xã hội hóa giáo dục AI.
- **Nghị định 13/2023/NĐ-CP**: Quy định pháp lý về bảo vệ dữ liệu cá nhân và bảo đảm an toàn số cho trẻ em.

Kỹ năng này giúp các Agent (Claude Code, GitHub Copilot CLI, Amp, Hermes Agent, Antigravity) và nhà sư phạm truy xuất tức thì Yêu cầu cần đạt (YCCĐ), xây dựng giáo án bài dạy chuẩn 5E, rà soát tính tuân thủ pháp lý và lựa chọn công cụ học tập phù hợp từng lứa tuổi.

---

## 🏛️ Các Trụ cột Pháp lý & Mô hình Tư duy Sư phạm

Mọi nội dung giáo dục, mục tiêu học tập và tài liệu bài giảng AI thiết kế cho học sinh Việt Nam đều phải tuân thủ nghiêm ngặt 6 nguyên tắc cốt lõi:

```
                          ┌──────────────────────────────────────────────┐
                          │    1. TRIẾT LÝ AI LẤY CON NGƯỜI LÀM TRUNG TÂM │
                          │  AI là công cụ tính toán do con người tạo ra,│
                          │   phục vụ phẩm giá và nằm dưới sự kiểm soát  │
                          │            của con người (QĐ 2422)           │
                          └──────────────────────┬───────────────────────┘
                                                 │
            ┌────────────────────────────────────┼────────────────────────────────────┐
            │                                    │                                    │
┌───────────▼───────────┐            ┌───────────▼───────────┐            ┌───────────▼───────────┐
│  2. BỐN MẠCH NỘI DUNG │            │ 3. ĐỒNG TÂM XOẮN ỐC   │            │ 4. ĐỊNH MỨC 12 TIẾT   │
│ Mạch A: Khái niệm-Ứng │            │ Tiểu học: Nhận biết   │            │ Bắt buộc tối thiểu    │
│ Mạch B: Dữ liệu & ML  │            │ THCS: Quy trình logic │            │ 12 tiết/năm/học sinh; │
│ Mạch C: Kĩ thuật & HT │            │ THPT: Mô hình toán học│            │ Tích hợp Tin học/STEM/│
│ Mạch D: Đạo đức-Xã hội│            │                       │            │ HĐTN (CV 5588 & 5208) │
└───────────┬───────────┘            └───────────┬───────────┘            └───────────┬───────────┘
            │                                    │                                    │
            └────────────────────────────────────┼────────────────────────────────────┘
                                                 │
            ┌────────────────────────────────────┴────────────────────────────────────┐
            │                                                                         │
┌───────────▼───────────┐                                                 ┌───────────▼───────────┐
│ 5. NGUYÊN TẮC 0 ĐỒNG  │                                                 │ 6. ĐÁNH GIÁ QUÁ TRÌNH │
│ Nghiêm cấm thu phí mua│                                                 │ Trọng số ≥ 70% nhật ký│
│ phần mềm bản quyền; ưu│                                                 │ & thái độ; CẤM tổ chức│
│ tiên FOSS/Client-side │                                                 │ thi viết riêng về AI  │
└───────────────────────┘                                                 └───────────────────────┘
```

1. **Triết lý AI lấy con người làm trung tâm (*QĐ 2422 Phần I*)**: Trí tuệ Nhân tạo là sản phẩm công nghệ thuần túy, không có tri giác, cảm xúc hay ý thức. Nghiêm cấm thần thánh hóa hoặc nhân hóa máy móc; người học luôn chịu 100% trách nhiệm đạo đức, pháp lý và học thuật đối với kết quả do AI hỗ trợ.
2. **Bốn Mạch nội dung giáo dục AI xuyên suốt (*4 Mạch nội dung*)**:
   - **Mạch A (*Khái niệm & Ứng dụng AI*)**: Làm sáng tỏ bản chất AI, phân biệt hệ thống dựa trên luật vs học từ dữ liệu, nhận diện thiết bị thông minh.
   - **Mạch B (*Dữ liệu & Học máy*)**: Nền tảng dữ liệu số: thu thập, tiền xử lý, gán nhãn, phân tách tập Train/Test, kiểm soát độ lệch/thiên vị (bias).
   - **Mạch C (*Kĩ thuật & Hệ thống AI*)**: Cơ chế tính toán: Thị giác máy tính (CV), Xử lý ngôn ngữ tự nhiên (NLP), Cây quyết định, Mạng nơ-ron nhân tạo (ANN), và Kỹ thuật viết câu lệnh nhắc (Prompt Engineering).
   - **Mạch D (*Tác động Xã hội & Đạo đức AI*)**: Quyền riêng tư trẻ em (Nghị định 13), bản quyền số, liêm chính học thuật, phòng chống deepfake, chuyển dịch việc làm và nguyên tắc F.A.T.E.
3. **Mô hình Đồng tâm Xoắn ốc (*Spiral Progression*)**: Khái niệm được khám phá cảm quan ở Tiểu học, hình thành tư duy quy trình ở THCS, và phân tích sâu cấu trúc/toán học ở THPT.
4. **Định mức Bắt buộc 12 tiết/năm (*CV 5588 & CV 5208*)**: Từ năm học 2026–2027, mỗi học sinh K-12 được học tối thiểu 12 tiết AI/năm, phân bổ linh hoạt qua 4 lộ trình mà không làm phát sinh học thêm hay quá tải thời khóa biểu.
5. **Nguyên tắc Bình đẳng và Không thu phí bổ sung (*Zero-Fee & FOSS*)**: Nghiêm cấm tuyệt đối việc ép buộc phụ huynh mua tài khoản phần mềm thương mại, gói token dịch vụ đám mây, hoặc bộ kit phần cứng độc quyền. Giáo dục phổ thông bắt buộc dùng công cụ mã nguồn mở, miễn phí hoặc xử lý trực tiếp trên trình duyệt (client-side).
6. **Đánh giá Chú trọng Quá trình, Cấm thi riêng biệt (*QĐ 2422 Phần VI*)**: Tối thiểu 70% điểm số đánh giá dựa trên nhật ký học tập, dữ liệu huấn luyện, báo cáo sửa lỗi và làm việc nhóm. Nghiêm cấm các trường tổ chức bài thi viết lý thuyết riêng biệt tính điểm học bạ môn AI.

---

## 📂 Cấu trúc Thư mục & Nội dung Kỹ năng

```
vietnam-k12-ai-curriculum/
├── SKILL.md                       # Chỉ dẫn chính cho AI Agent, mô hình tư duy & chỉ mục tra cứu
├── README.md                      # Tài liệu tiếng Anh
├── README.vi.md                   # Tài liệu tiếng Việt (tệp này)
├── cheatsheet.md                  # Cây quyết định, ngưỡng định mức pháp lý & chẩn đoán lỗi sư phạm
├── patterns.md                    # 6 mẫu thiết kế sư phạm & quản trị triển khai thực tế
├── glossary.md                    # Thuật ngữ song ngữ Anh - Việt đối chiếu văn bản quy phạm pháp luật
└── chapters/                      # Các chương tài liệu nguồn chi tiết (nạp theo nhu cầu)
    ├── ch01-foundation-gdpt2018-informatics.md     # GDPT 2018, Bộ 3 DL-ICT-CS, 5 Phẩm chất, Năng lực
    ├── ch02-ai-framework-overview-principles.md    # QĐ 2422 Tổng quan, 4 Mạch nội dung, Triết lý
    ├── ch03-ai-primary-school-grade1-5.md          # AI Tiểu học: Vật sống vs Đồ vật, Teachable Machine
    ├── ch04-ai-lower-secondary-grade6-9.md         # AI THCS: 5 bước Học máy, Câu lệnh CLEAR, Đạo đức
    ├── ch05-ai-upper-secondary-grade10-12.md       # AI THPT: Mạng ANN, F1-Score, NĐ 13, Định hướng Tin học
    ├── ch06-ai-teaching-methods-assessment.md      # Phương pháp 5E, Hồ sơ học tập kép, AI không dùng máy
    ├── ch07-implementation-guidelines-5588-5208.md # Triển khai 12 tiết, Quy định không thu phí, Lesson Study
    └── ch08-local-implementation-hcmc-8585.md      # Triển khai TP.HCM, Trường học số, Cơ chế 4 Cổng PPP
```

### Danh mục Chi tiết các Chương Chuyên đề

| Mã Chương | Tên Chương | Văn bản Nguồn | Nội dung Trọng tâm |
|---|---|---|---|
| [**ch01**](chapters/ch01-foundation-gdpt2018-informatics.md) | Nền tảng GDPT 2018 & Môn Tin học | TT 32/2018, TT 13/2022 | Tam giác DL-ICT-CS, 5 Phẩm chất cốt lõi, 3 Năng lực chung, 5 Năng lực Tin học (NLa–NLe), định hướng ICT vs CS. |
| [**ch02**](chapters/ch02-ai-framework-overview-principles.md) | Tổng quan Khung AI Quốc gia K-12 | QĐ 2422/QĐ-BGDĐT | Triết lý AI nhân văn, 4 mạch nội dung (A, B, C, D), mô hình đồng tâm xoắn ốc theo từng cấp lớp. |
| [**ch03**](chapters/ch03-ai-primary-school-grade1-5.md) | Giáo dục AI Cấp Tiểu học (Lớp 1–5) | QĐ 2422 Mục IV.1 | Phân biệt sinh vật sống vs vật thông minh, nhận diện cảm biến giác quan, Google Teachable Machine, vệ sinh thị giác. |
| [**ch04**](chapters/ch04-ai-lower-secondary-grade6-9.md) | Giáo dục AI Cấp THCS (Lớp 6–9) | QĐ 2422 Mục IV.2 | So sánh hệ luật vs học máy, quy trình 5 bước ML, kỹ thuật prompt CLEAR, deepfake, ảo giác AI, lệch dữ liệu. |
| [**ch05**](chapters/ch05-ai-upper-secondary-grade10-12.md) | Giáo dục AI Cấp THPT (Lớp 10–12) | QĐ 2422 Mục IV.3 | Cấu trúc mạng ANN, ma trận nhầm lẫn (Precision/Recall/F1), Nghị định 13/2023, phân nhánh Tin học ứng dụng vs KHMT. |
| [**ch06**](chapters/ch06-ai-teaching-methods-assessment.md) | Phương pháp Dạy học & Đánh giá | QĐ 2422 Phần V & VI | Mô hình dạy học 5E, hồ sơ học tập kép (Dual Portfolio), phương pháp AI không dùng máy tính (Unplugged), rubric. |
| [**ch07**](chapters/ch07-implementation-guidelines-5588-5208.md) | Hướng dẫn Chỉ đạo Thực hiện | CV 5588 & CV 5208 | 4 phương thức hấp thụ định mức 12 tiết, nguyên tắc pháp lý cấm thu tiền, sinh hoạt chuyên môn nghiên cứu bài học. |
| [**ch08**](chapters/ch08-local-implementation-hcmc-8585.md) | Triển khai Địa phương: Bài học TP.HCM | CV 8585/SGDĐT-GDPT | 4 trụ cột trường học thông minh, kho học liệu số dùng chung, quản trị xã hội hóa giáo dục 4 cổng kiểm soát. |

---

## 🛠️ Ma trận Công cụ Dạy học Theo Cấp học

Bộ khung chương trình yêu cầu công cụ học tập phải minh bạch, bảo vệ dữ liệu và hoàn toàn miễn phí:

| Cấp học | Công cụ Đề xuất | Mục tiêu Sư phạm Chính | Đặc điểm Bảo mật & Chi phí |
|---|---|---|---|
| **Tiểu học (Lớp 1–5)** | Trò chơi Unplugged, Quick Draw!, Google Teachable Machine | Phân biệt vật sống và máy thông minh, quan sát cảm biến, phân loại hình ảnh/âm thanh đơn giản | Chạy 100% trên trình duyệt (client-side), không cần tạo tài khoản, không lưu trữ dữ liệu học sinh |
| **THCS (Lớp 6–9)** | Tiện ích AI của Scratch, MIT App Inventor, Teachable Machine, Mô phỏng Micro:bit Python | Quy trình 5 bước học máy, phân tách dữ liệu Train/Test, lập trình kéo thả, câu lệnh CLEAR | Nền tảng miễn phí giáo dục, quản lý tài khoản trường học, không phát sinh chi phí token |
| **THPT: Định hướng ICT** | Không gian Hugging Face (mã nguồn mở), Orange Data Mining, Công cụ Prompt Sandbox | Thực hành thiết kế câu lệnh chuyên sâu, đánh giá định kiến thuật toán, văn hóa ứng xử số | Phần mềm mã nguồn mở chạy máy tính để bàn (FOSS) hoặc dịch vụ miễn phí |
| **THPT: Định hướng CS** | Python 3, Jupyter / Google Colab (Free), Scikit-Learn, TensorFlow Playground | Cơ chế lan truyền nơ-ron, tính toán ma trận F1-score, xây dựng Cây quyết định, Học chuyển giao | Môi trường Python nội bộ trên phòng máy hoặc nền tảng đám mây phi lợi nhuận |

---

## 🚀 Hướng dẫn Sử dụng Kỹ năng

### Dành cho Trợ lý AI (Claude Code, Copilot CLI, Amp, Hermes, Antigravity)

Khi kỹ năng được kích hoạt trong thư mục dự án (`.agents/skills/vietnam-k12-ai-curriculum`), Agent có thể tiếp nhận các yêu cầu truy vấn cụ thể:

```bash
# Tra cứu yêu cầu cần đạt (YCCĐ) theo cấp học
/vietnam-k12-ai-curriculum "YCCĐ giáo dục AI môn Tin học lớp 4 về phân loại dựa trên cảm biến"
/vietnam-k12-ai-curriculum "Thiết kế giáo án lớp 8 bài quy trình 5 bước huấn luyện mô hình học máy"
/vietnam-k12-ai-curriculum "Nội dung mạng nơ-ron nhân tạo và hàm kích hoạt cho học sinh lớp 11 chuyên đề KHMT"

# Tra cứu căn cứ pháp lý và chính sách
/vietnam-k12-ai-curriculum "Điều kiện triển khai chương trình AI liên kết doanh nghiệp theo CV 5588 và CV 8585"
/vietnam-k12-ai-curriculum "Quy định thu thập hình ảnh học sinh trong giờ học AI theo Nghị định 13/2023"

# Áp dụng các mẫu thiết kế sư phạm
/vietnam-k12-ai-curriculum "Cách phân bổ 12 tiết học AI vào Kế hoạch giáo dục nhà trường 35 tuần mà không học thêm"
/vietnam-k12-ai-curriculum "Xây dựng giáo án tiến trình 5E cho chủ đề kỹ thuật viết prompt CLEAR"
```

### Dành cho Chuyên gia Thiết kế Giáo trình & Ban Giám hiệu

1. **Phân bổ Thời lượng 12 tiết**: Tham khảo [patterns.md (Mẫu 1)](patterns.md#1-12-period-modular-curricular-absorption-pattern) để tích hợp vào môn Tin học chính khóa (6 tiết), mô-đun STEM liên môn (4 tiết), và Hoạt động trải nghiệm (2 tiết).
2. **Thẩm định Đề án Hợp tác Doanh nghiệp**: Áp dụng [patterns.md (Mẫu 6)](patterns.md#6-public-private-partnership-ppp-4-gate-governance-pattern) qua cơ chế 4 Cổng kiểm soát (Tự nguyện không thu phí, Hội đồng sư phạm phê duyệt, Chủ quyền dữ liệu, Không khóa mã độc quyền).
3. **Phát hiện Dị tật Sư phạm**: Tra cứu [cheatsheet.md (Mục 4)](cheatsheet.md#4-tells--smells-detecting-curriculum-anti-patterns) để rà soát giáo án trước khi đưa vào giảng dạy.

---

## 📋 Bảng Kiểm Tuân thủ Pháp lý (Compliance Checklist)

Trước khi ký duyệt hoặc ban hành bất kỳ kế hoạch bài dạy, giáo trình hay mô-đun học tập AI nào trong nhà trường, cần xác nhận:

- [ ] **Định mức 12 tiết**: Kế hoạch giáo dục bảo đảm mỗi học sinh được học tối thiểu 12 tiết AI/năm học? (CV 5588)
- [ ] **Tuyệt đối Không thu phí phần mềm**: Công cụ sử dụng có hoàn toàn miễn phí, không phát sinh chi phí mua bản quyền hay gói token cho phụ huynh? (CV 5588)
- [ ] **Bảo vệ Dữ liệu Trẻ em**: Hình ảnh gương mặt, giọng nói và định danh của học sinh có được bảo vệ bảo mật trên thiết bị nội bộ, không bị chia sẻ lên máy chủ đám mây thương mại? (Nghị định 13/2023/NĐ-CP)
- [ ] **Hình thức Đánh giá**: Tỷ trọng đánh giá quá trình có đạt $\ge 70\%$, và **hoàn toàn không** tổ chức thi viết lý thuyết riêng biệt môn AI? (QĐ 2422)
- [ ] **Cân đối 4 Mạch nội dung**: Nội dung bài học có kết hợp giáo dục đạo đức, kiểm soát định kiến và an toàn số (Mạch D) bên cạnh kỹ thuật công nghệ (Mạch A, B, C)? (QĐ 2422)
- [ ] **Ngăn ngừa Nhân hóa AI**: Học sinh có được giảng giải rõ AI là cỗ máy tính toán phi sinh học, phục vụ con người và con người làm chủ? (QĐ 2422)

---

## 📚 Tài liệu Hỗ trợ Kèm theo

- [**cheatsheet.md**](cheatsheet.md): Bảng tra cứu quy tắc quyết định nhanh, ngưỡng định mức và chẩn đoán phản mẫu sư phạm.
- [**patterns.md**](patterns.md): Tuyển tập 6 mẫu thiết kế sư phạm và mô hình quản trị nhà trường chuẩn mực.
- [**glossary.md**](glossary.md): Bảng tra cứu thuật ngữ chuyên ngành giáo dục AI và luật giáo dục song ngữ Anh – Việt.

---

## 📄 Bản quyền & Quy chuẩn

- **Chuẩn kỹ năng**: Xây dựng tương thích hoàn toàn chuẩn mở [Agent Skills Standard](https://github.com/agentskills/agentskills).
- **Căn cứ nội dung**: Hệ thống hóa dựa trên các văn bản quy phạm pháp luật công khai của Bộ Giáo dục và Đào tạo và các Sở GD&ĐT tại Việt Nam.
- **Giấy phép**: Creative Commons Ghi nhận công của tác giả 4.0 Quốc tế (CC BY 4.0).
