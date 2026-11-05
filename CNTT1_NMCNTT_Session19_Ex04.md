# BÀI TẬP VỀ NHÀ
##    Bài 4 : Rủi ro đánh cắp mật khẩu từ trình duyệt
### Bài làm
## 1. Bảng so sánh

**Tiêu chí**

**Google Chrome**

**Bitwarden**

**Chống Infostealer**

❌ **Yếu.** Khóa mã hóa lưu sẵn trên HĐH. Mã độc trích xuất file `Login Data` là đọc được ngay.

✅ **Mạnh.** Mã hóa bằng Master Password. Mã độc lấy được file cũng chỉ thấy dữ liệu rác.

**Zero-Knowledge**

❌ **Không.** Google vẫn quản lý cơ chế xác thực và khóa giải mã trên hệ thống.

✅ **Có.** Giải mã hoàn toàn tại thiết bị. Máy chủ Bitwarden không giữ Master Password.

**Đồng bộ chéo**

⚠️ **Hạn chế.** Phụ thuộc vào trình duyệt Chrome và tài khoản Google.

✅ **Toàn diện.** Chạy độc lập trên mọi HĐH (Windows, Mac, iOS, Android) và mọi trình duyệt.

## 2. Lý do Bitwarden thắng thế

-   **Mã độc không thể tự giải mã: Chrome dùng sẵn khóa của HĐH nên mã độc tự lấy được. Bitwarden yêu cầu Master Password (chỉ có trong đầu nhân viên), mã độc chịu chết nếu không có mật khẩu này.
    
-   Tự động khóa (Auto-Lock):** Bitwarden tự khóa khi không dùng. Dù máy bị dính malware, dữ liệu vẫn an toàn.
    
-   Đánh đổi đáng giá: Mất 2 giây gõ Master Password để bảo vệ toàn bộ tài sản dữ liệu của công ty.
