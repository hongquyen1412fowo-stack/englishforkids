# EduKids English 4 - Tài liệu Yêu cầu Sản phẩm (PRD - Product Requirements Document)
**Phiên bản:** 1.0.0-PROD
**Tác giả:** Senior EdTech Product Manager (10+ YOE Vietnam Market)
**Chương trình:** Thông tư 32/2018/TT-BGDĐT - Chương trình GDPT môn Tiếng Anh Lớp 4
**Ngày tạo:** 2026-11-12
**Tình trạng:** Approved for Development (Sprint Ready)

---

## 1. TỔNG QUAN SẢN PHẨM (PRODUCT OVERVIEW)
### 1.1. Tầm nhìn & Mục tiêu sản phẩm (Vision & Goals)
- **Tầm nhìn:** Trở thành "Gia sư số tiếng Anh bám sát SGK thông minh và gần gũi nhất" cho hơn 1.8 triệu học sinh lớp 4 tại Việt Nam.
- **Nỗi đau học sinh lớp 4:** Quá tải từ vựng dài 3-4 âm tiết; sợ nói sai phát âm bị bạn bè trêu chọc; mất gốc căn bản từ lớp 3; thiếu động lực tự giác.
- **Nỗi đau phụ huynh:** Không có thời gian và khả năng phát âm chuẩn để kèm con; lo điểm số kiểm tra giữa kỳ/cuối kỳ; sợ con sa đà vào YouTube/Game; học phí trung tâm đắt đỏ nhưng lệch giáo trình trường học.

### 1.2. Chỉ số đo lường thành công (Success Metrics / KPIs)
- **DAU / MAU Ratio:** >= 42% (Gắn bó hàng ngày).
- **Retention Rate D7:** >= 55% | **D30:** >= 32%.
- **Unit Completion Rate:** >= 75% hoàn thành trọn vẹn Unit SGK.
- **Free-to-Paid Conversion:** >= 6.8% (Benchmark EdTech VN: 3.5% - 5.0%).
- **Speech AI Latency P95:** < 1,800 ms.

---

## 2. ĐỐI TƯỢNG NGƯỜI DÙNG & CHÂN DUNG KHÁCH HÀNG (PERSONAS)
### Primary User: Bé Nguyễn Minh Khôi (9 tuổi - Lớp 4)
- **Tâm lý:** Hiếu động, thích hoạt hình/game, khoảng tập trung ngắn 15-20 phút, ngại đọc khối văn bản dài.
- **Mục tiêu:** Được chơi vui mà vẫn được điểm 9, 10 ở trường; tự tin phát âm chuẩn; nuôi thú cưng ảo Bibo.

### Buyer / Secondary User: Chị Trần Thu Hương (36 tuổi - Mẹ của Khôi)
- **Đặc điểm:** Bận rộn công việc kế toán, vốn tiếng Anh hạn chế, sử dụng Zalo hàng ngày.
- **Mục tiêu:** Ứng dụng an toàn 100% không quảng cáo, nhận báo cáo tiến độ tuần qua Zalo OA, chi phí hợp lý (~2.400 đ/ngày).

---

## 3. LUỒNG NGƯỜI DÙNG CHÍNH (USER FLOWS)
1. **Luồng Onboarding:** Đăng ký SĐT phụ huynh -> Nhập tên bé & chọn Mascot -> Chọn 1 trong 3 bộ SGK (Global Success, Family & Friends, i-Learn Smart Start) -> Bài test 3 phút tùy chọn.
2. **Luồng Học tập Cốt lõi (Core Learning Loop - 20 phút/ngày):** Khởi động cùng Mascot -> Học từ vựng Flashcard tương tác -> Luyện phát âm AI Phoneme-level (Xanh/Vàng/Đỏ) -> Thực hành hội thoại Role-play -> Game hóa củng cố -> Nhận Sao & Kim Cương thưởng.
3. **Luồng Phụ huynh (Parent Zone):** Khóa Parental Gate (phép tính nhân/mã PIN) -> Báo cáo học tập & phân tích điểm yếu -> Cài đặt giới hạn thời gian (20-30 phút/ngày) & Bảo vệ mắt 20-20-20 -> Nâng cấp VIP qua VietQR/MoMo.

---

## 4. ĐẶC TẢ TÍNH NĂNG CHI TIẾT (FUNCTIONAL REQUIREMENTS)
- **Module 1 (Học liệu chuẩn SGK Lớp 4):** Đóng gói 20 Units chuẩn, khớp từng Lesson 1, 2, 3; hỗ trợ chuyển đổi linh hoạt giữa 3 bộ SGK; giải thích ngữ pháp song ngữ. (MVP)
- **Module 2 (AI Luyện phát âm & Giao tiếp):** Chấm điểm Phoneme-level hiển thị màu sắc Xanh/Vàng/Đỏ; đối thoại Role-play nhập vai theo tình huống SGK. (MVP & Phase 2)
- **Module 3 (Game hóa Gamification):** Mascot Bibo đồng hành; Chuỗi Streak học tập; Bảng xếp hạng tuần ẩn danh bảo vệ trẻ; Avatar Shop đổi quà bằng kim cương ảo. (MVP)
- **Module 4 (Kho đề thi Giữa kỳ & Cuối kỳ):** Ngân hàng đề thi chuẩn Bộ GD&ĐT (Nghe - Đọc - Viết); chấm điểm tự động kèm lời giải chi tiết bằng tiếng Việt. (MVP)
- **Module 5 (Khu vực Phụ huynh & Zalo OA):** Parental Gate toán học; Báo cáo tự động qua Zalo ZNS lúc 20:00 Chủ Nhật; Chế độ nhắc nghỉ mắt 20-20-20. (MVP)
- **Module 6 (Thanh toán & Gói cước):** Học thử 2 Unit; Gói 6 tháng (590k) & Gói 1 năm (890k); Thanh toán VietQR, MoMo, ZaloPay và In-App Purchase. (MVP)

---

## 5. YÊU CẦU PHI CHỨC NĂNG (NON-FUNCTIONAL REQUIREMENTS)
- **Hiệu năng:** Độ trễ AI < 1.8s; Hỗ trợ tải Offline trọn vẹn Unit; Khởi động ứng dụng < 1.5s.
- **An toàn trẻ em & Pháp lý:** 100% Không chứa quảng cáo (Zero 3P Ads); Tuân thủ Luật Trẻ em 2016 (VN) & COPPA; Parental Gate nghiêm ngặt.
- **UI/UX:** Touch target >= 44x44px; Typography cỡ chữ tối thiểu 18px; Tương thích hoàn hảo Smartphone & Máy tính bảng (Tablet).

---

## 6. QUẢN TRỊ RỦI RO & GIẢI PHÁP (RISKS & MITIGATION)
1. **AI nhận diện sai giọng trẻ em địa phương:** Fine-tune mô hình với 50.000+ mẫu âm thanh trẻ em Việt Nam lứa tuổi 8-11; cơ chế dung sai linh hoạt.
2. **Nội dung SGK thay đổi chỉnh lý:** Kiến trúc Headless CMS động từ Cloud; hình vẽ minh họa bản quyền độc quyền.
3. **Trẻ nghiện màn hình:** Khóa mắt khỏe tự động sau 20 phút (Quy tắc 20-20-20); giới hạn tối đa 40 phút/ngày.
4. **Phụ huynh ngại thanh toán thẻ quốc tế:** Tích hợp VietQR chuyển khoản ngân hàng tự động khớp lệnh trong 3 giây.
