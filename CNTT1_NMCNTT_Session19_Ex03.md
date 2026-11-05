# BÀI TẬP VỀ NHÀ
##  Bài 3 : Quản lý rủi ro khi mất thiết bị xác thực
### Bài làm
**3. Yêu cầu đầu ra**

**_Báo cáo phân tích (IPO)_**

1.  Input (Mã dự phòng), Process (Xác thực/Hủy mã cũ/Cấp mã mới), Output (Hệ thống an toàn).
```text
       [ INPUT ]                      [ PROCESS ]                      [ OUTPUT ]
┌──────────────────────┐      ┌─────────────────────────┐      ┌────────────────────────┐
│ - Tên đăng nhập/MK   │      │ 1. Xác thực danh tính   │      │ - Đăng nhập thành công │
│ - 1 Mã dự phòng      │ ───> │ 2. Hủy toàn bộ mã cũ    │ ───> │ - Kẻ gian bị chặn đứng │
│ - Thiết bị sạch      │      │ 3. Cấp bộ mã mới        │      │ - Hệ thống AN TOÀN     │
└──────────────────────┘      └─────────────────────────┘      └────────────────────────┘
```


    
3.  Giải thích tại sao không được lưu Backup Codes dưới dạng ảnh trong thư viện điện thoại.
- Vì khi lưu Backup Codes dưới dạng ảnh thì khi bị hack bẻ khóa máy và vào check thư viện và thấy ảnh backup sẽ làm lộ hết thành ra mất hết tài khoản.


