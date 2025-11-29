# Ma trận Phân công Trách nhiệm (RACI Matrix) - Hoàn chỉnh

Đây là tài liệu trung tâm để xác định vai trò của từng thành viên trong mỗi công việc của dự án.

**Chú giải:**
* **R**: Responsible (Người trực tiếp thực hiện)
* **A**: Accountable (Người chịu trách nhiệm cuối cùng)
* **C**: Consulted (Người cần được hỏi ý kiến)
* **I**: Informed (Người cần được thông báo)

---

### Sprint 0: Project Kick-off & Planning (01/10/2025 - 05/10/2025)

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 0] 1. Brainstorm & lựa chọn đề tài | **A** | R | R | R | R | R | R |
| [Sprint 0] 2. Thiết lập GitHub repo | **R,A** | C | I | I | I | I | I |
| [Sprint 0] 3. Họp bầu Leader và chốt ý tưởng | **R** | I | I | I | I | I | I |
| [Sprint 0] 4. Bản mô tả ý tưởng dự án | **R,A** | C | C | C | C | C | C |
| [Sprint 0] 5. Xây dựng AI Canvas v1 | **A** | **R** | I | C | C | **R** | I |
| [Sprint 0] 6. Phân vai trò & thiết lập công cụ | **A** | I | I | I | I | I | I |

---

### Sprint 1: Business Understanding & Case Building (06/10/2025 - 15/10/2025)

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 1] 1. Nghiên cứu Doanh nghiệp | C | I | I | **R** | **A** | C | I |
| [Sprint 1] 2. Phân tích Doanh nghiệp | C | I | **R** | I | I | C | **A** |
| [Sprint 1] 3. Kế hoạch phát triển dự án | **R, A** | I | I | C | I | C | C |
| [Sprint 1] 4. Họp brief & chia task AI Canvas V2 | **R,A** | I | I | I | I | I | I |
| [Sprint 1] 5. Ước tính ROI & Hoàn thiện AI Canvas (v2) | C | **R** | **A** | **R** | C | I | I |
| [Báo cáo lần 1] Phân công Slides và Thuyết trình | **A** | **R** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 2 & 3: Data & Modeling Planning (15/10/2025 - 19/10/2025)

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 2&3] 1. Kế hoạch dữ liệu | **A** | I | C | C | I | **R** | I |
| [Sprint 2&3] 2. Tìm kiếm và Mô tả nguồn dữ liệu | **R** | I | I | I | C | **A** | C |
| [Sprint 2&3] 3. Thiết kế mô hình & Lựa chọn thuật toán | I | **R** | C | **R** | **R** | **A** | C |
| [Sprint 2&3] 4. Xây dựng kế hoạch triển khai & Mockups | C | C | I | **A** | **R** | **R** | I |
| [Báo cáo lần 2] Phân công Slides và Thuyết trình | **A** | **R** | **R** | **R** | **R** | **R** | **R** |
---

### Sprint 4: Data Pipeline Execution (15/10/2025 - 19/10/2025)
* **Mục tiêu Sprint:** Thực thi Pha 2 & 3 (Data Understanding & Preparation).

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 4] 1. Phân tích & Khám phá Dữ liệu (EDA) | **A** | C | **R** | I | C | **R** | I |
| [Sprint 4] 2. Xây dựng Vocabulary & Dataset | I | I | C | **R** | **A** | C | **R** |
| [Sprint 4] 3. Xây dựng collate_fn & Unit Test | I | **R** | C | I | **A** | C | **R** |
| [Sprint 4] 4. Họp Sprint Review & Retrospective | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 5: Modeling (Xây dựng Mô hình Baseline) (11/10/2025 - 24/10/2025)
* **Mục tiêu Sprint:** Thực thi Pha 4 (Data Modeling - Vòng lặp 1).

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 5] 1. Cài đặt Baseline (Seq2Seq) & Training Loop | **R** | C | C | I | **A** | **R** | **A** |
| [Sprint 5] 2. Lưu Model Checkpoints & Log results | I | **R** | **A** | C | C | **A** | **R** |
| [Sprint 5] 3. Họp Sprint Review & Retrospective | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 6: Evaluation (V1) & Modeling (Cải tiến V2) (25/10/2025 - 03/11/2025)
* **Mục tiêu Sprint:** Thực thi Pha 5 (Evaluation - Vòng lặp 1) & Pha 4 (Data Modeling - Vòng lặp 2).

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 6] 1. Xây dựng Hàm Đánh giá (WER) & Đánh giá V1 | **R** | C | **R** | I | **A** | I | C |
| [Sprint 6] 2. Cài đặt Kiến trúc V2 & Huấn luyện V2 | I | C | **R** | C | **R** | I | **A** |
| [Sprint 6] 3. Họp Sprint Review & Retrospective | **R,A** | **A** | **R** | **R** | **R** | **R** | **R** |

---

### Sprint 7: Final Evaluation & Operationalization (04/11/2026 - 30/11/2025)
* **Mục tiêu Sprint:** Thực thi Pha 5 (Vòng lặp 2) & Pha 6 (Vận hành hóa).
* **Deliverables:** Báo cáo so sánh V1 vs V2; Link demo Gradio; Tài liệu dự án hoàn chỉnh.

| Công việc (Issue) | Minh (SM) | Diệu (PO) | Vũ Quỳnh | Kiệt | Huy | Ân | Vương Quỳnh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [Sprint 7] 1. Chạy Đánh giá V2 & Chọn Mô hình Tốt nhất | **R** | **A** | I | C | C | **R** | I |
| [Sprint 7] 2. Xây dựng Giao diện Demo (Gradio) | **R** | C | I | C | **R** | C | **A** |
| [Sprint 7] 3. Xây dựng Brochure | C | **A** | I | I | I | I | **R** |
| [Sprint 7] 4. Xây dựng giao diện Figma | C | I | **R** | I | **R** | **A** | I |
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
| [S4] 1. Phân tích & Khám phá Dữ liệu (EDA) (#17) | 2R, 1A, 2C, 2I | 56.00 | 24.25 | 13.50 | 8.00 | **101.75 giờ** |
| [S4] 2. Xây dựng Vocabulary, file `.pt` & Dataset (#18) | 2R, 1A, 2C, 2I | 55.25 | 23.25 | 14.00 | 8.00 | **100.50 giờ** |
| [S4] 3. Xây dựng collate_fn & Unit Test (#19) | 2R, 1A, 2C, 2I | 56.50 | 24.00 | 12.75 | 8.00 | **101.25 giờ** |
| [S4] 4. Họp Sprint Review & Retrospective | 7R, 2A, 0C, 0I | 192.50 | 55.25 | 0.00 | 0.00 | **247.75 giờ** |
| **Sprint 5** | | | | | | |
| [S5] 1. Cài đặt Baseline (Seq2Seq) & Training Loop (#20) | 2R, 2A, 1C, 1I | 56.00 | 48.50 | 7.00 | 4.00 | **115.50 giờ** |
| [S5] 2. Lưu Model Checkpoints & Log results (#21) | 2R, 2A, 1C, 1I | 55.50 | 47.75 | 6.75 | 4.00 | **114.00 giờ** |
| [S5] 3. Họp Sprint Review & Retrospective | 7R, 2A, 0C, 0I | 192.50 | 55.25 | 0.00 | 0.00 | **247.75 giờ** |
| **Sprint 6** | | | | | | |
| [S6] 1. Xây dựng Hàm Đánh giá (WER) & Eval V1 (#22) | 2R, 1A, 2C, 1I | 56.25 | 24.00 | 13.50 | 4.00 | **97.75 giờ** |
| [S6] 2. Cài đặt Kiến trúc V2 & Huấn luyện V2 (#23) | 2R, 1A, 2C, 2I | 55.75 | 23.50 | 12.50 | 8.00 | **99.75 giờ** |
| [S6] 3. Họp Sprint Review & Retrospective | 7R, 2A, 0C, 0I | 192.50 | 55.25 | 0.00 | 0.00 | **247.75 giờ** |
| **Sprint 7** | | | | | | |
| [S7] 1. Chạy Đánh giá V2 & Chọn Mô hình Tốt nhất (#24) | 2R, 1A, 2C, 2I | 56.00 | 24.25 | 14.00 | 8.00 | **102.25 giờ** |
| [S7] 2. Xây dựng Giao diện Demo (Gradio) (#25) | 2R, 1A, 2C, 1I | 55.50 | 23.75 | 13.00 | 4.00 | **96.25 giờ** |
| [S7] 3. Chuẩn bị Tài liệu Báo cáo & Brochure (#26) | 1R, 1A, 1C, 3I | 28.50 | 24.00 | 6.50 | 12.00 | **71.00 giờ** |
| [S7] 4. Xây dựng giao diện Figma (#27) | 2R, 1A, 1C, 2I | 56.25 | 23.50 | 7.00 | 8.00 | **94.75 giờ** |
| [S7] 5. Họp Sprint Review (Final Presentation Prep) | 7R, 2A, 0C, 0I | 192.50 | 55.25 | 0.00 | 0.00 | **247.75 giờ** |
