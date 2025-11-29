# 🚀 Dự án AI: EchoMind thuộc Công ty Mindconnect Lab
_Nhóm 11 - Lớp Dự án Trí tuệ nhân tạo (UEH)_

![Project Banner]([https://i.imgur.com/g8c222j.png](https://www.google.com/url?sa=i&url=https%3A%2F%2Fstartupwheel.vn%2Fvi%2Fpartner%2Fueh-institute-of-innovation%2F&psig=AOvVaw1-Zj9uJUVChFWNxOy6DjeA&ust=1759931882442000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCNjR1KefkpADFQAAAAAdAAAAABAE))

## 1. Tổng quan (Overview)
**EchoMind** là dự án của **MindConnect Labs** nhằm trao lại tiếng nói cho người **mất khả năng nói** (do **đột quỵ**, **ALS**, **locked-in**). Hệ thống **đọc tín hiệu não** và **chuyển thành chữ** hiển thị **gần như tức thời**, để người bệnh có thể diễn đạt nhu cầu và cảm xúc một cách đơn giản, tự nhiên.

Nhóm đã dựng xong **pipeline dữ liệu** và **mô hình nguyên mẫu** trên bộ **Brain-to-Text (Kaggle)**, chạy thử trên **Colab** để **kiểm chứng tính khả thi**. Mục tiêu gần là có bản **demo ổn định** cho thí điểm tại **khoa Thần kinh/PHCN**, từ đó **hoàn thiện quy trình** sử dụng trong bệnh viện và tại nhà.

## 2. 🌐 Trung tâm Quản lý Dự án (Project Hub)
Tất cả các hoạt động lập kế hoạch, theo dõi tiến độ và tài liệu của dự án được quản lý tại:
* **[[Link đến trang Notion/Website của nhóm]]**(https://github.com/hwinhwork-dot/Du-an-AI---Group-11)

## 3. 👨‍💻 Đội ngũ Phát triển (The Team)

| STT | Họ và Tên | MSSV | Vai trò trong dự án | GitHub |
|:---:|:---|:---|:---|:---|
| 1 | Nguyễn Hoàng Minh | 31221021575 | Scrum Master | @hwinhwork-dot |
| 2 | Nguyễn Huyền Diệu | 31221024865 | Product Owner | @douongcocon2004-hash |
| 3 | Vũ Thị Như Quỳnh | 31221023513 | Development Team | @quynhquynhneee |
| 4 | Lương Duy Minh Kiệt| 31221023817 | Development Team | @kietueh |
| 5 | Nguyễn Lê Huy | 31221021402 | Development Team | @huyangry |
| 6 | Nguyễn Thiên Ân | 31221022348 | Development Team | @beiuthichcamhoa |
| 7 | Vương Thị Như Quỳnh| 31221021890 | Development Team | @quynhhvuong |


## 4. 🗺️ Lộ trình Phát triển Dự án (Project Roadmap)
Dự án được thực hiện theo phương pháp Agile/Scrum, chia thành các Sprint (chặng) với mục tiêu và kết quả rõ ràng. Lộ trình này tuân thủ khung sườn CPMAI để đảm bảo tính toàn diện từ kinh doanh đến kỹ thuật.

| Sprint | Mục tiêu (Objective) | Hoạt động chính (Key Activities) | Kết quả đầu ra chính (Key Deliverables) |
| :--- | :--- | :--- | :--- |
| **Sprint 0**<br>*(Tuần 1)*<br> **Khởi động (Kick-off)** | Chọn đề tài, lập AI Canvas v1, phân vai trò, thiết lập công cụ quản lý dự án. | - Brainstorm & chọn đề tài/công ty.<br>- Phân vai trò (SM, PO, Dev Team).<br>- Thiết lập GitHub repo & Notion.<br>- Xây dựng AI Canvas (v1). | 📄 **AI Canvas (v1)**<br>🛠️ **GitHub Repo & Notion** |
| **Sprint 1**<br>*(Tuần 2-3)*<br> **Phân tích Kinh doanh** | Hoàn thành **Pha 1 (CPMAI): Business Understanding**. Xây dựng luận cứ kinh doanh (business case) và báo cáo tiến độ lần 1. | - Phân tích bối cảnh (SWOT/PESTEL).<br>- Xác định KPI & Metrics (Kinh doanh & Kỹ thuật).<br>- Ước tính ROI, Hoàn thiện AI Canvas (v2). | 📈 **Báo cáo Phân tích Kinh doanh**<br>📄 **AI Canvas (v2)**<br>🗣️ **Báo cáo Tiến độ lần 1** |
| **Sprint 2**<br>*(Tuần 4)*<br> **Thiết kế Kỹ thuật** | Hoàn thành **Pha 2, 3, 4, 5 (CPMAI) - Phần kế hoạch**. Lên kế hoạch chi tiết về dữ liệu, mô hình, đánh giá, và triển khai. | - Mô tả nguồn dữ liệu (Data Understanding).<br>- Lên kế hoạch chuẩn bị dữ liệu (Data Prep Plan).<br>- Thiết kế kiến trúc mô hình (Modeling Plan).<br>- Thiết kế Mockups (Operationalization Plan). | 📐 **Tài liệu Thiết kế Giải pháp**<br>🖥️ **Mockups (Demo UI)**<br>🗣️ **Báo cáo Tiến độ lần 2** |
| **Sprint 3**<br>*(Tuần 5)*<br> **Pipeline Dữ liệu** | Hoàn thành **Pha 2 & 3 (CPMAI) - Phần thực thi**. Xây dựng pipeline (luồng) dữ liệu tự động, sẵn sàng cho mô hình. | - Thực hiện EDA (Phân tích dữ liệu).<br>- Xây dựng Vocabulary (từ vựng).<br>- Cài đặt `BrainToTextDataset` & `collate_fn`.<br>- Kiểm thử (Unit Test) DataLoader. | ⚙️ **DataLoader (train/val) hoàn chỉnh**<br>📦 **File `vocab.pt`** |
| **Sprint 4**<br>*(Tuần 6)*<br> **Mô hình V1 (Baseline)** | Hoàn thành **Pha 3 (CPMAI): Modeling (V1)**. Xây dựng và huấn luyện mô hình Seq2Seq (LSTM) cơ bản để làm mốc so sánh. | - Cài đặt kiến trúc Seq2Seq (Encoder/Decoder).<br>- Xây dựng vòng lặp huấn luyện (Training Loop).<br>- Huấn luyện và lưu trữ mô hình V1. | 🧠 **Model Checkpoint V1 (.pt)**<br>📉 **Báo cáo Training Loss V1** |
| **Sprint 5**<br>*(Tuần 7)*<br> **Đánh giá V1 & Cải tiến V2** | Hoàn thành **Pha 4 (CPMAI): Evaluation (V1)** và **Pha 3 (CPMAI): Modeling (V2)**. Đo lường V1 và xây dựng mô hình V2 (Attention). | - Xây dựng hàm đánh giá (WER).<br>- Chạy đánh giá V1 và phân tích lỗi.<br>- Cài đặt kiến trúc V2 (có Attention).<br>- Huấn luyện và lưu trữ mô hình V2. | 📊 **Báo cáo WER (V1)**<br>🧠 **Model Checkpoint V2 (.pt)** |
| **Sprint 6**<br>*(Tuần 8-9)*<br> **Hoàn thiện & Triển khai** | Hoàn thành **Pha 4 & 5 (CPMAI)**. Chọn mô hình tốt nhất (Best Model) và xây dựng sản phẩm demo (Prototype) để thuyết trình. | - Chạy đánh giá V2 & So sánh V1/V2.<br>- Xây dựng Giao diện Demo (Gradio).<br>- Hoàn thiện Báo cáo/Slide/Brochure.<br>- Quay video demo sản phẩm. | 🏆 **Báo cáo Đồ án Cuối kỳ**<br>🚀 **Link Demo (Gradio)**<br>📰 **Brochure & Video** |

## 5. 🛠️ Công nghệ & Phương pháp luận (Tech Stack & Methodology)
* **Phương pháp luận:** CPMAI x Agile/Scrum
* **Công cụ Quản lý:** GitHub (Issues, Projects, Milestones.
* **Công cụ Phân tích (đề xuất):** Python (Pandas, Scikit-learn), Orange Data Mining
* **Mô hình (đề xuất):** Sequence2Sequence, Transfomer
* **Ma trận Trách nhiệm (RACI):** [Xem chi tiết tại đây](./docs/00_project_management/RACI_Matrix.md)
* **Google Colab V1:** [Xem chi tiết tại đây](https://colab.research.google.com/drive/1nksTekQb7kQcq6jTkB6aap5OwyQ7kKc4)
* **Google Colab V2:** [Xem chi tiết tại đây](https://colab.research.google.com/drive/10P9imS2j7Kb1LgN3jcAu5sJOS5usXXii#scrollTo=u-ayRBll8Uor)
* **Brochure Dự án:** [Xem chi tiết tại đây](https://heyzine.com/flip-book/e34e5a1cf5.html)

---
_Đây là đồ án trong khuôn khổ môn học Dự án Trí tuệ nhân tạo tại Đại học Kinh tế TP. Hồ Chí Minh (UEH)._
