# 🗓️ Sprint Plan – Chu kỳ 2 Tuần (10 ngày làm việc)

Áp dụng cho team: Backend Laravel API, Frontend SPA (JS + Vite), UI từ Template, BA, PO, QA/QC.

---

## 🎯 Mục tiêu Sprint

- Hoàn thiện các User Story đã được lên kế hoạch trong Sprint Planning.
- Đảm bảo toàn bộ tính năng qua API Spec và được test end-to-end.
- Bàn giao kịch bản demo, chuẩn bị release cho khách hàng vào cuối Sprint.

---

## 📅 Timeline Chi Tiết theo Ngày

| Ngày | Giai đoạn | Hoạt động chính | Người thực hiện | Đầu ra |
|------|-----------|------------------|------------------|--------|
| **Day 1 (Thứ 2)** | Sprint Planning | Phân chia task, estimate, ưu tiên backlog | PO, BA, Dev Team | Sprint Backlog |
| Day 1 | Phân tích nghiệp vụ | Làm rõ User Stories, xác nhận dữ liệu đầu vào/ra | BA, PO, Dev, QA | User Story chi tiết |
| **Day 2** | Thiết kế API | Viết `openapi.yaml` đặc tả các endpoint | Backend Dev / Tech Lead | API Spec (YAML) |
| Day 2–3 | Thống nhất API | Frontend + QA review đặc tả API, feedback | Backend, Frontend, QA | Phiên bản final của API Spec |
| **Day 3–4** | Thiết kế UI | Cắt UI từ template, map với field trong API | UI Dev | Giao diện khớp yêu cầu |
| **Day 3–8** | Phát triển song song | Backend code API, Frontend dựng UI + tích hợp mock | Dev team | Chức năng hoạt động cục bộ |
| Day 4–6 | Viết test case | Viết test case từ user story & API spec | QA / QC | Test case cho mỗi story |
| **Day 6–8** | Tích hợp API thật | Frontend kết nối API thật sau khi backend hoàn thành | Dev team | Chức năng chạy được end-to-end |
| Day 6–9 | Thực hiện test | Thực hiện manual test, API test, UI test | QA / QC | Báo cáo lỗi, xác nhận Pass/Fail |
| Day 8–9 | Regression test | Kiểm tra toàn hệ thống không ảnh hưởng chức năng cũ | QA / QC | Regression checklist pass |
| **Day 9** | Chuẩn bị demo | Demo nội bộ, kịch bản demo gửi khách | PO, BA, Dev, QA hỗ trợ | Checklist test + script demo |
| **Day 10 (Thứ 6)** | Sprint Review | Demo cho khách hàng, ghi nhận feedback | Cả team | Biên bản review/demo |
| Day 10 (cuối buổi) | Retrospective | Rút kinh nghiệm, đề xuất cải tiến quy trình | Scrum Team | Lesson Learned Document |

---

## 📌 Phân Công Công Việc Chính

| Thời gian | Backend | Frontend | UI | QA / QC |
|----------|---------|----------|----|---------|
| D1–2     | Viết API Spec | Chuẩn bị cấu trúc UI + field mapping | Cắt template | Tham gia phân tích nghiệp vụ |
| D3–6     | Code API, xử lý logic | Dựng UI, fake API | Chỉnh sửa giao diện theo feedback | Viết test case chi tiết từ user story |
| D6–8     | Xong API, hỗ trợ bugfix | Tích hợp API thật | Final chỉnh UI | Test tính năng chính & API |
| D8–9     | Hỗ trợ fix bug | Polish UI | Support demo | Regression test, cập nhật kết quả |
| D9–10    | Hỗ trợ release | Final chỉnh sửa | Support demo | Tổng hợp test result, tham gia demo |

---

## ✅ Tài Liệu & Deliverables

- [ ] `openapi.yaml`: mô tả API toàn bộ module
- [ ] Giao diện UI dựng từ template
- [ ] Script demo và checklist test
- [ ] Release Note (nếu cần)
- [ ] Biên bản Sprint Review
- [ ] Test Case + Test Result file (Google Sheet, Zephyr, TestRail, Notion...)

---

> **Ghi chú:** Team nên cập nhật tiến độ mỗi ngày tại Daily Scrum (15 phút) và điều chỉnh task linh hoạt để đảm bảo kịp release đúng hạn vào ngày thứ 10.
