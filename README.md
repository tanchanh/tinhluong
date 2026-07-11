# 💵 Trình Tính Lương Công Chức, Viên Chức

Ứng dụng web công cụ gọn nhẹ chạy hoàn toàn độc lập, hỗ trợ tính toán chi tiết cơ cấu thu nhập dành cho cán bộ, công chức, viên chức và người lao động dựa trên hệ số lương, phụ cấp, thâm niên và khấu trừ bảo hiểm bắt buộc theo thời gian thực.

---

## ✨ Tính Năng Nổi Bật

* **Hoạt động Offline an toàn:** Toàn bộ thuật toán tính toán tiền lương và phân tích khấu trừ diễn ra hoàn toàn cục bộ trên trình duyệt của người dùng, không truyền tải dữ liệu cá nhân hay thông tin tài chính lên máy chủ.

* **Tính toán cơ cấu thu nhập tự động:**
* Tự động tính toán Lương cơ bản dựa theo Hệ số và Lương cơ sở cập nhật.

* Tích hợp cơ chế tính lũy tiến tiền phụ cấp ngành và phụ cấp thâm niên theo tỷ lệ phần trăm.

* Tự động tính toán mức trích đóng Bảo hiểm xã hội (BHXH) bắt buộc dựa trên tổng tiền lương ngạch bậc và thâm niên.

* **Xuất phiếu lương chuẩn hóa:** Tích hợp mô hình Popup Modal thu thập thông tin họ tên người nhận để kết xuất thành một Phiếu tính lương có cấu trúc định dạng hoàn chỉnh, căn lề phải đối xứng tuyệt đối (Khổ 28 ký tự cố định), sẵn sàng hiển thị trên các thiết bị.

* **Đa phương thức kết xuất:**
* Hỗ trợ nút **Sao Chép** nhanh toàn bộ nội dung phiếu lương dạng ảnh vào bộ nhớ đệm (Clipboard).

* Hỗ trợ nút **Lưu File** để trích xuất phiếu lương thành tệp tin ảnh `.png`, tự động đặt tên tệp tin theo họ tên người nhận.

* **Trải nghiệm giao diện đồng bộ:** Thiết kế tinh gọn, responsive linh hoạt theo kích thước màn hình thiết bị di động và máy tính.

---

## 📐 Định Dạng Dữ Liệu & Quy Chuẩn Đầu Vào

Để hệ thống xử lý, phân tách và kết xuất phiếu lương chính xác, các thông số đầu vào cần tuân thủ cấu trúc quy định:

* **Lương Cơ Sở:** Nhập theo đơn vị nghìn đồng (Ví dụ mặc định định cấu hình: `2530` tương đương **2.530.000 đ**).

* **Hệ Số Lương:** Nhập số thập phân theo thang bảng lương quy định (Ví dụ: `3.96`).

* **Tỷ lệ phần trăm (%):** Áp dụng cho các trường Thâm niên, Phụ cấp và Trừ Bảo hiểm xã hội (Khấu trừ đóng BHXH mặc định là `10.5%`).

* **Quy tắc tính BHXH:** Tiền bảo hiểm được tính dựa trên tổng giá trị của Lương cơ bản cộng với Tiền thâm niên. Các khoản phụ cấp khác không tính đóng bảo hiểm.

---

## 🛠️ Hướng Dẫn Sử Dụng

* **Nhập thông số tiền lương:** Điền đầy đủ các thông tin gồm Lương cơ sở, Hệ số lương, % Thâm niên, % Phụ cấp và % Khấu trừ bảo hiểm vào các ô tương ứng. Biểu đồ kết quả sẽ tự động cập nhật ngay lập tức sau mỗi thao tác thay đổi ký tự.

* **Theo dõi bảng kết quả:**
* Xem chi tiết giá trị phân rã tại khung **Kết Quả (x 1.000 đ)** bao gồm các dòng Lương cơ bản, Thâm niên, Phụ cấp, Trừ bảo hiểm.

* Khối **Tổng Thực Lĩnh** nổi bật phía dưới sẽ hiển thị số tiền mặt thực tế nhận được sau khi đã thực hiện đầy đủ nghĩa vụ khấu trừ.

* **Xuất phiếu và Lưu trữ:**
* Nhấp nút **Sao Chép** hoặc **Lưu File** ở cuối trang.

* Hộp thoại **Xuất Phiếu Lương** sẽ hiển thị yêu cầu nhập Họ và Tên người nhận (bạn có thể bỏ trống và bấm Đồng ý trực tiếp nếu không cần điền tên).

* Sau khi xác nhận, hệ thống sẽ thực hiện sao chép văn bản phiếu lương đã định dạng vào Clipboard hoặc tải tệp văn bản về máy, đồng thời gửi thông báo Toast xác nhận thành công.

---

## 📝 Thông Tin Phát Triển

* **Tác giả:** Dương Tấn Chánh

* **Công nghệ tích hợp:** HTML5, CSS3 (Variables Custom Properties & Grid Layout), JavaScript Thuần (Vanilla JS - Vận hành thuật toán tính toán toán học và xử lý chuỗi logic thô, hoàn toàn không phụ thuộc vào thư viện bên ngoài để bảo đảm hiệu suất, dung lượng và khả năng hoạt động offline độc lập).