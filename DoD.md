# ✅ Definition of Done (DoD)

Áp dụng cho từng User Story / Task trong quy trình phát triển phần mềm của team.

---

## 🎯 1. Yêu cầu nghiệp vụ

- [ ] Đã được **BA xác nhận rõ ràng** về nghiệp vụ, luồng xử lý.
- [ ] Đã được **PO đồng thuận** và approve trước khi bắt đầu phát triển.

---

## 🧱 2. Backend (Laravel API)

- [ ] API xử lý đúng logic nghiệp vụ mô tả.
- [ ] Có **validate đầu vào**, xử lý lỗi đúng chuẩn.
- [ ] Trả về **HTTP status code** và cấu trúc dữ liệu theo chuẩn chung.
- [ ] Có test API (unit test hoặc postman collection).
- [ ] Đã **code review**, không còn warning/error.
- [ ] Đã merge vào nhánh chính (hoặc nhánh release).
- [ ] Migration / script (nếu có) đã kiểm thử thành công.

---

## 💻 3. Frontend (SPA JS + Vite)

- [ ] Dựng đúng UI yêu cầu từ template (theo PO/BA).
- [ ] Đã tích hợp API đầy đủ, xử lý các trạng thái (loading, error...).
- [ ] Giao diện responsive cơ bản, kiểm tra trên ít nhất 2 độ phân giải.
- [ ] Tương tác người dùng đã kiểm thử: nhấn nút, form, popup...
- [ ] Code sạch, không lỗi console, pass basic review.

---

## 🎨 4. UI/UX

- [ ] Cắt ghép đúng từ template theo yêu cầu.
- [ ] Tuân thủ tiêu chuẩn UI: font, màu, khoảng cách, icon.
- [ ] Giao diện hiển thị ổn định, không bị vỡ layout hoặc lệch khung.

---

## 🧪 5. Kiểm thử (QA)

- [ ] Đã test đầy đủ tất cả chức năng theo kịch bản BA/PO.
- [ ] Đã test các trường hợp bất thường (edge case, error handling).
- [ ] Đã regression test, không ảnh hưởng chức năng khác.
- [ ] Không còn bug nghiêm trọng (blocker/critical).

---

## 📦 6. Chuẩn bị bàn giao / release

- [ ] Story đã chuyển trạng thái "Ready for Release" / "Done".
- [ ] Đã cập nhật release note (nếu cần).
- [ ] Đã demo thử trên staging hoặc môi trường demo.
- [ ] Đã chuẩn bị kịch bản demo cho PO/khách hàng.

---

## 📋 7. Tài liệu & xác nhận

- [ ] Có tài liệu mô tả nếu story cần hướng dẫn sử dụng.
- [ ] Đã được **PO/BA xác nhận hoàn thành**.
- [ ] Có thể demo lại đúng theo mô tả ban đầu.

---

**Lưu ý:** Tất cả thành viên trong team cần tuân thủ DoD này để đảm bảo chất lượng, tránh sai sót, và đồng bộ quy trình giữa backend, frontend, UI, BA, và PO.