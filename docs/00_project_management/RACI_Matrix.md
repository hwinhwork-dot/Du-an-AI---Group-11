# Ma trận Phân công Trách nhiệm (RACI Matrix) - Hoàn chỉnh

Đây là tài liệu trung tâm để xác định vai trò của từng thành viên trong mỗi công việc của dự án.

**Chú giải:**
* **R**: Responsible (Người trực tiếp thực hiện)
* **A**: Accountable (Người chịu trách nhiệm cuối cùng)
* **C**: Consulted (Người cần được hỏi ý kiến)
* **I**: Informed (Người cần được thông báo)

---

### Sprint 0: Project Kick-off & Planning (06/10/2025 - 22/10/2025)

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 0] 1. Brainstorm & lựa chọn đề tài | **A** | R | R | R | R | R | R |
| [Sprint 0] 2. Thiết lập GitHub repo | **R,A** | C | I | I | I | I | I |
| [Sprint 0] 3. Họp bầu Leader và chốt ý tưởng | **R** | I | I | I | I | I | I |
| [Sprint 0] 4. Bản mô tả ý tưởng dự án | **R,A** | C | C | C | C | C | C |
| [Sprint 0] 5. Xây dựng AI Canvas v1 | **A** | **R** | I | C | C | **R** | I |
| [Sprint 0] 6. Phân vai trò & thiết lập công cụ | **A** | I | I | I | I | I | I |

---

### Sprint 1: Business Understanding & Case Building (23/10/2025 - 05/11/2025)

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 1] 1. Nghiên cứu Doanh nghiệp | C | I | I | **R** | **A** | C | I |
| [Sprint 1] 2. Phân tích Doanh nghiệp | C | I | **R** | I | I | C | **A** |
| [Sprint 1] 3. Kế hoạch phát triển dự án | **R, A** | I | I | C | I | C | C |
| [Sprint 1] 4. Họp brief & chia task AI Canvas V2 | **R,A** | I | I | I | I | I | I |
| [Sprint 1] 5. Ước tính ROI & Hoàn thiện AI Canvas (v2) | C | **R** | **A** | **R** | C | I | I |
| [Báo cáo lần 1] Phân công Slides và Thuyết trình | **A** | **R** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 2 & 3: Data & Modeling Planning (05/11/2025 - 15/11/2025)
*(Các task được cập nhật từ Issues #9, #10, #12, #14)*

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 2&3] 1. Kế hoạch dữ liệu | **A** | I | C | C | I | **R** | I |
| [Sprint 2&3] 2. Tìm kiếm và Mô tả nguồn dữ liệu | **R** | I | I | I | C | **A** | C |
| [Sprint 2&3] 3. Thiết kế mô hình & Lựa chọn thuật toán | I | **R** | C | **R** | **R** | **A** | C |
| [Sprint 2&3] 4. Xây dựng kế hoạch triển khai & Mockups | C | C | I | **A** | **R** | **R** | I |
| [Báo cáo lần 2] Phân công Slides và Thuyết trình | **A** | **R** | **R** | **R** | **R** | **R** | **R** |
---

### Sprint 4: Data Pipeline Execution (20/11/2025 - 03/12/2025)
* **Mục tiêu Sprint:** Thực thi Pha 2 & 3 (Data Understanding & Preparation).

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 4] 1. Phân tích & Khám phá Dữ liệu (EDA) | **A** | C | **R** | I | C | **R** | I |
| [Sprint 4] 2. Xây dựng Vocabulary & lưu file `.pt` | **A** | I | C | **R** | I | C | **R** |
| [Sprint 4] 3. Xây dựng lớp `BrainToTextDataset` | I | C | **R** | C | **R** | I | C |
| [Sprint 4] 4. Xây dựng `collate_fn` (Xử lý Padding) | I | I | C | **R** | **A** | I | **R** |
| [Sprint 4] 5. Kiểm thử (Unit Test) DataLoader | **A** | I | **R** | I | C | **R** | C |
| [Sprint 4] 6. Họp Sprint Review & Retrospective | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 5: Modeling (Xây dựng Mô hình Baseline) (04/12/2025 - 17/12/2025)
* **Mục tiêu Sprint:** Thực thi Pha 4 (Data Modeling - Vòng lặp 1).

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 5] 1. Cài đặt Kiến trúc Baseline (Seq2Seq) | **A** | I | **R** | **R** | C | I | I |
| [Sprint 5] 2. Xây dựng Vòng lặp Huấn luyện (Training Loop) | **A** | I | I | C | **R** | **R** | C |
| [Sprint 5] 3. Huấn luyện Mô hình Baseline (10 Epochs) | I | I | C | I | C | **A** | **R** |
| [Sprint 5] 4. Lưu Model Checkpoints & Log results | I | I | I | I | C | **R** | **A** |
| [Sprint 5] 5. Họp Sprint Review & Retrospective | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 6: Evaluation (V1) & Modeling (Cải tiến V2) (18/12/2025 - 31/12/2025)
* **Mục tiêu Sprint:** Thực thi Pha 5 (Evaluation - Vòng lặp 1) & Pha 4 (Data Modeling - Vòng lặp 2).

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 6] 1. Xây dựng Hàm Đánh giá (WER) | **A** | I | **R** | C | I | I | C |
| [Sprint 6] 2. Chạy Đánh giá V1 & Phân tích Lỗi | I | **A** | C | **R** | C | C | **R** |
| [Sprint 6] 3. Cài đặt Kiến trúc V2 (Attention) | I | I | **R** | **A** | **R** | C | I |
| [Sprint 6] 4. Huấn luyện Mô hình V2 (10 Epochs) | I | I | C | I | C | **R** | **A** |
| [Sprint 6] 5. Họp Sprint Review & Retrospective | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 7: Final Evaluation & Operationalization (01/01/2026 - 14/01/2026)
* **Mục tiêu Sprint:** Thực thi Pha 5 (Vòng lặp 2) & Pha 6 (Vận hành hóa).
* **Deliverables:** Báo cáo so sánh V1 vs V2; Link demo Gradio; Tài liệu dự án hoàn chỉnh.

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 7] 1. Chạy Đánh giá V2 & Chọn Mô hình Tốt nhất | I | **A** | **R** | **R** | I | I | I |
| [Sprint 7] 2. Xây dựng Giao diện Demo (Gradio) | **A** | C | I | C | **R** | C | **R** |
| [Sprint 7] 3. Chuẩn bị Tài liệu Báo cáo Cuối kỳ | **A** | **A** | **R** | **R** | **R** | **R** | **R** |
| [Sprint 7] 4. Quay video Demo & Thiết kế Brochure/Poster | I | **R** | C | I | **R** | **R** | C |
| [Sprint 7] 5. Họp Sprint Review (Final Presentation Prep) | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |

---
---

## Bảng Ước tính Khối lượng Công việc (Theo Task)

**Quy tắc tính:**
* **R / A (Responsible / Accountable):** 3-4 ngày (24-32 giờ), với sai lệch ngẫu nhiên 45-60 phút.
* **C (Consulted):** 6-7 giờ, với sai lệch ngẫu nhiên 15-45 phút.
* **I (Informed):** 4 giờ (cố định).

| Công việc (Issue) | Phân bố (R/A/C/I) | Chi tiết Giờ (R) | Chi tiết Giờ (A) | Chi tiết Giờ (C) | Chi tiết Giờ (I) | **Tổng Giờ Ước tính** |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Sprint 0** | | | | | | |
| [S0] 1. Brainstorm & lựa chọn đề tài (#1) | 6R, 1A, 0C, 0I | 166.25 | 31.00 | 0.00 | 0.00 | **197.25 giờ** |
| [S0] 2. Thiết lập GitHub repo | 1R, 1A, 1C, 6I | 31.25 | 23.25 | 6.75 | 24.00 | **85.25 giờ** |
| [S0] 3. Họp bầu Leader và chốt ý tưởng (#2) | 1R, 0A, 0C, 6I | 24.75 | 0.00 | 0.00 | 24.00 | **48.75 giờ** |
| [S0] 4. Bản mô tả ý tưởng dự án (#3) | 1R, 1A, 6C, 0I | 31.00 | 25.00 | 38.50 | 0.00 | **94.50 giờ** |
| [S0] 5. Xây dựng AI Canvas v1 (#4) | 2R, 1A, 2C, 2I | 56.00 | 31.25 | 12.50 | 8.00 | **107.75 giờ** |
| [S0] 6. Họp Brief về Doanh nghiệp và chia tasks (#5) | 0R, 1A, 0C, 6I | 0.00 | 23.00 | 0.00 | 24.00 | **47.00 giờ** |
| **Sprint 1** | | | | | | |
| [S1] 1. Nghiên cứu Doanh nghiệp (#6) | 1R, 1A, 2C, 3I | 31.25 | 24.25 | 12.75 | 12.00 | **80.25 giờ** |
| [S1] 2. Phân tích Doanh nghiệp (#7) | 1R, 1A, 3C, 2I | 23.25 | 32.00 | 19.00 | 8.00 | **82.25 giờ** |
| [S1] 3. Kế hoạch phát triển dự án (#8) | 1R, 1A, 4C, 1I | 23.00 | 31.00 | 25.50 | 4.00 | **83.50 giờ** |
| [S1] 4. Họp brief & chia task AI Canvas V2 (#15) | 1R, 1A, 1C, 4I | 31.25 | 23.25 | 6.25 | 16.00 | **76.75 giờ** |
| [S1] 5. Ước tính ROI & Hoàn thiện AI Canvas (v2) (#13) | 6R, 1A, 0C, 0I | 166.25 | 31.00 | 0.00 | 0.00 | **197.25 giờ** |
| [S1] 6. [Báo cáo lần 1] Phân công Slides và Thuyết trình (#11) | 5R, 1A, 1C, 0I | 141.25 | 25.00 | 6.75 | 0.00 | **173.00 giờ** |
| **Sprint 2 & 3** | | | | | | |
| [S2&3] 1. Kế hoạch dữ liệu (#9) | 1R, 1A, 2C, 3I | 24.75 | 31.25 | 12.50 | 12.00 | **80.50 giờ** |
| [S2&3] 2. Tìm kiếm và Mô tả nguồn dữ liệu (#10) | 1R, 1A, 2C, 3I | 31.00 | 23.00 | 13.75 | 12.00 | **79.75 giờ** |
| [S2&3] 3. Thiết kế mô hình & Lựa chọn thuật toán (#12) | 5R, 2A, 0C, 0I | 141.25 | 56.00 | 0.00 | 0.00 | **197.25 giờ** |
| [S2&3] 4. Xây dựng kế hoạch triển khai & Mockups (#14) | 3R, 1A, 0C, 3I | 81.50 | 23.25 | 0.00 | 12.00 | **116.75 giờ** |
| **Sprint 4** | | | | | | |
| [S4] 1. Phân tích & Khám phá Dữ liệu (EDA) | 2R, 1A, 2C, 2I | 56.00 | 31.25 | 12.50 | 8.00 | **107.75 giờ** |
| [S4] 2. Xây dựng Vocabulary & lưu file `.pt` | 2R, 1A, 2C, 2I | 55.00 | 23.00 | 13.75 | 8.00 | **99.75 giờ** |
| [S4] 3. Xây dựng lớp `BrainToTextDataset` | 2R, 0A, 3C, 2I | 55.25 | 0.00 | 19.00 | 8.00 | **82.25 giờ** |
| [S4] 4. Xây dựng `collate_fn` (Xử lý Padding) | 2R, 1A, 1C, 3I | 56.00 | 31.25 | 6.25 | 12.00 | **105.50 giờ** |
| [S4] 5. Kiểm thử (Unit Test) DataLoader | 2R, 1A, 2C, 2I | 55.00 | 23.00 | 13.75 | 8.00 | **99.75 giờ** |
| [S4] 6. Họp Sprint Review & Retrospective | 7R, 2A, 0C, 0I | 192.50 | 55.25 | 0.00 | 0.00 | **247.75 giờ** |
| **Sprint 5** | | | | | | |
| [S5] 1. Cài đặt Kiến trúc Baseline (Seq2Seq) | 2R, 1A, 1C, 3I | 55.25 | 32.00 | 6.75 | 12.00 | **106.00 giờ** |
| [S5] 2. Xây dựng Vòng lặp Huấn luyện (Training Loop) | 2R, 1A, 2C, 2I | 56.00 | 31.25 | 12.50 | 8.00 | **107.75 giờ** |
| [S5] 3. Huấn luyện Mô hình Baseline (10 Epochs) | 1R, 1A, 3C, 2I | 23.00 | 31.00 | 19.00 | 8.00 | **81.00 giờ** |
| [S5] 4. Lưu Model Checkpoints & Log results | 1R, 1A, 2C, 3I | 31.25 | 24.25 | 12.75 | 12.00 | **80.25 giờ** |
| [S5] 5. Họp Sprint Review & Retrospective | 7R, 2A, 0C, 0I | 192.50 | 55.25 | 0.00 | 0.00 | **247.75 giờ** |
| **Sprint 6** | | | | | | |
| [S6] 1. Xây dựng Hàm Đánh giá (WER) | 1R, 1A, 3C, 2I | 23.00 | 31.00 | 19.00 | 8.00 | **81.00 giờ** |
| [S6] 2. Chạy Đánh giá V1 & Phân tích Lỗi | 2R, 1A, 3C, 1I | 55.25 | 32.00 | 20.25 | 4.00 | **111.50 giờ** |
| [S6] 3. Cài đặt Kiến trúc V2 (Attention) | 2R, 1A, 2C, 2I | 56.00 | 31.25 | 12.50 | 8.00 | **107.75 giờ** |
| [S6] 4. Huấn luyện Mô hình V2 (10 Epochs) | 1R, 1A, 3C, 2I | 23.00 | 31.00 | 19.00 | 8.00 | **81.00 giờ** |
| [S6] 5. Họp Sprint Review & Retrospective | 7R, 2A, 0C, 0I | 192.50 | 55.25 | 0.00 | 0.00 | **247.75 giờ** |
| **Sprint 7** | | | | | | |
| [S7] 1. Chạy Đánh giá V2 & Chọn Mô hình Tốt nhất | 2R, 1A, 0C, 4I | 55.25 | 32.00 | 0.00 | 16.00 | **103.25 giờ** |
| [S7] 2. Xây dựng Giao diện Demo (Gradio) | 2R, 1A, 3C, 1I | 55.25 | 32.00 | 20.25 | 4.00 | **111.50 giờ** |
| [S7] 3. Chuẩn bị Tài liệu Báo cáo Cuối kỳ | 6R, 2A, 0C, 0I | 166.25 | 55.00 | 0.00 | 0.00 | **221.25 giờ** |
| [S7] 4. Quay video Demo & Thiết kế Brochure/Poster | 3R, 0A, 3C, 1I | 81.50 | 0.00 | 20.25 | 4.00 | **105.75 giờ** |
| [S7] 5. Họp Sprint Review (Final Presentation Prep) | 7R, 2A, 0C, 0I | 192.50 | 55.25 | 0.00 | 0.00 | **247.75 giờ** |
