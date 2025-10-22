# Ma trận Phân công Trách nhiệm (RACI Matrix)

Đây là tài liệu trung tâm để xác định vai trò của từng thành viên trong mỗi công việc của dự án.

**Chú giải:**
* **R**: Responsible (Người trực tiếp thực hiện)
* **A**: Accountable (Người chịu trách nhiệm cuối cùng)
* **C**: Consulted (Người cần được hỏi ý kiến)
* **I**: Informed (Người cần được thông báo)

---

### Sprint 0: Project Kick-off & Planning (06/10/2025 - 16/10/2025)

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 0] 1. Brainstorm & lựa chọn đề tài | **A** | R | R | R | R | R | R |
| [Sprint 0] 2. Thiết lập GitHub repo | **R,A** | C | I | I | I | I | I |
| [Sprint 0] 3. Họp bầu Leader và chốt ý tưởng | **R** | I | I | I | I | I | I |
| [Sprint 0] 4. Bản mô tả ý tưởng dự án | **R,A** | C | C | C | C | C | C |
| [Sprint 0] 5. Xây dựng AI Canvas v1 | **A** | **R** | I | C | C | **R** | I |
| [Sprint 0] 6. Phân vai trò & thiết lập công cụ | **A** | I | I | I | I | I | I |

---

### Sprint 1: Business Understanding & Case Building 

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 1] 1. Nghiên cứu Doanh nghiệp / Bối cảnh | C | I | I | **R** | **A** | C | I |
| [Sprint 1] 2. Phân tích Doanh nghiệp (PESTEL, SWOT) | C | I | **R** | I | I | C | **A** |
| [Sprint 1] 3. Kế hoạch phát triển dự án (CPMAI) | **R, A** | I | I | C | I | C | C |
| [Sprint 1] 4. Xác định KPI & Metrics (Kỹ thuật & Kinh doanh) | C | C | **R** | **R** | **R** | **A** | **A** |
| [Sprint 1] 5. Ước tính ROI & Chi phí - Lợi ích | I | **A** | C | **R** | I | **R** | C |
| [Sprint 1] 6. Hoàn thiện AI Canvas (v2) | C | **A** | **R** | **R** | **R** | **R** | **R** |
| [Sprint 1] 7. Chuẩn bị tài liệu Báo cáo Tiến độ 1 | **A** | C | I | I | **R** | **R** | I |

---

### Sprint 2: Data Understanding & Modeling Planning 

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 2] 1. Tìm kiếm và Mô tả nguồn dữ liệu | **R** | I | I | I | C | **A** | C |
| [Sprint 2] 2. Kế hoạch và bước đầu chuẩn bị dữ liệu | **A** | I | C | C | I | **R** | I |
| [Sprint 2] 3. Thiết kế mô hình & lựa chọn thuật toán | I | C | I | C | **R** | **R** | C |
| [Sprint 2] 4. Thiết kế kế hoạch đánh giá (Evaluation Plan) | I | C | **R** | C | **R** | I | I |
| [Sprint 2] 5. Xây dựng kế hoạch triển khai & Mockups | I | **A** | C | I | C | **R** | **R** |
| [Sprint 2] 6. Chuẩn bị tài liệu Báo cáo Tiến độ 2 | **A** | C | **R** | I | I | C | **R** |

---

### Sprint 3: Data Pipeline Execution 

* **Mục tiêu Sprint:** Chuyển đổi dữ liệu thô từ HDF5 thành một pipeline tự động, sạch, và sẵn sàng cho mô hình.
* **Deliverables:** Bộ `DataLoader` hoàn chỉnh cho training/validation; file `vocab.pt` đã lưu.

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 3] 1. Phân tích & Khám phá Dữ liệu (EDA) | **A** | C | **R** | I | C | **R** | I |
| [Sprint 3] 2. Xây dựng Vocabulary | **A** | I | C | **R** | I | C | **R** |
| [Sprint 3] 3. Xây dựng lớp `BrainToTextDataset` | I | C | **R** | C | **R** | I | C |
| [Sprint 3] 4. Xây dựng `collate_fn` (Xử lý Padding) | I | I | C | **R** | **A** | I | **R** |
| [Sprint 3] 5. Kiểm thử (Unit Test) DataLoader | **A** | I | **R** | I | C | **R** | C |
| [Sprint 3] 6. Họp Sprint Review & Retrospective | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 4: Modeling (Xây dựng Mô hình Baseline) 

* **Mục tiêu Sprint:** Huấn luyện thành công mô hình Seq2Seq (LSTM) cơ bản (Baseline) để có một mốc so sánh hiệu năng.
* **Deliverables:** Các file checkpoint (`.pt`) của mô hình baseline; Báo cáo quá trình training (loss).

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 4] 1. Cài đặt Kiến trúc Baseline (Seq2Seq) | **A** | I | **R** | **R** | C | I | I |
| [Sprint 4] 2. Xây dựng Vòng lặp Huấn luyện (Training Loop) | **A** | I | I | C | **R** | **R** | C |
| [Sprint 4] 3. Huấn luyện Mô hình Baseline (10 Epochs) | I | I | C | I | C | **A** | **R** |
| [Sprint 4] 4. Lưu Model Checkpoints & Log results | I | I | I | I | C | **R** | **A** |
| [Sprint 4] 5. Họp Sprint Review & Retrospective | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 5: Evaluation (V1) & Modeling (Cải tiến V2) 

* **Mục tiêu Sprint:** Đánh giá hiệu năng (WER) của mô hình Baseline và bắt đầu xây dựng, huấn luyện mô hình V2 (có Attention) để cải thiện.
* **Deliverables:** Báo cáo WER của V1; Các file checkpoint (`.pt`) của mô hình V2 (Attention).

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 5] 1. Xây dựng Hàm Đánh giá (WER) | **A** | I | **R** | C | I | I | C |
| [Sprint 5] 2. Chạy Đánh giá V1 & Phân tích Lỗi | I | **A** | C | **R** | C | C | **R** |
| [Sprint 5] 3. Cài đặt Kiến trúc V2 (Attention) | I | I | **R** | **A** | **R** | C | I |
| [Sprint 5] 4. Huấn luyện Mô hình V2 (10 Epochs) | I | I | C | I | C | **R** | **A** |
| [Sprint 5] 5. Họp Sprint Review & Retrospective | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 6: Final Evaluation & Operationalization 

* **Mục tiêu Sprint:** Chọn ra mô hình tốt nhất (Best Model) dựa trên WER và xây dựng một sản phẩm demo tương tác (Prototype) để báo cáo cuối kỳ.
* **Deliverables:** Báo cáo so sánh V1 vs V2; Link demo Gradio; Tài liệu dự án hoàn chỉnh.

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 6] 1. Chạy Đánh giá V2 & Chọn Mô hình Tốt nhất | I | **A** | **R** | **R** | I | I | I |
| [Sprint 6] 2. Xây dựng Giao diện Demo (Gradio) | **A** | C | I | C | **R** | C | **R** |
| [Sprint 6] 3. Chuẩn bị Tài liệu Báo cáo Cuối kỳ | **A** | **A** | **R** | **R** | **R** | **R** | **R** |
| [Sprint 6] 4. Quay video Demo & Thiết kế Brochure/Poster | I | **R** | C | I | **R** | **R** | C |
| [Sprint 6] 5. Họp Sprint Review (Final Presentation Prep) | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |
