# BÀI TẬP VỀ NHÀ
##   Bài 2 : Chuỗi tấn công từ mật khẩu bị rò rỉ
### Bài làm


**3. Yêu cầu đầu ra**

1.   Phân tích tại sao mật khẩu cảm tính lại dễ bị bẻ khóa hơn mật khẩu do máy tính sinh ra.

- Vì bình thường mật khẩu theo cảm tính đọ khó sẽ ít thường thường đề ghi theo những thứ quen thuộc dễ nhớ các chữ cái gắn liền với mình từ đó khi bị mã độc tấn công dễ dàng bẻ khóa được còn mật khẩu do máy tính tự sinh ra thì khác sẽ là một chuỗi ký tự cực kì khó nhớ gồm các ký tự đặc biệt, kí hiệu, số chữ sẽ đan sen lẫn nhau.

    
2.  Sử dụng tiêu chuẩn **AES-256** để giải thích tại sao việc lưu mật khẩu trong Password Manager lại an toàn hơn ghi chép thủ công.
- Ví dụ khi mật khẩu của mình là Matkhau123 nhưng khi lưu mật khẩu vào password manager thì sẽ sử dụng tiêu chuẩn AES-256 để mã hóa sẽ ra một chuỗi ký tự vô nghĩa , ví dụ:  `9f8a7b6c5d4e3f2a1b0c9d8e7f6a5b4c...`.
- Để giải mã chuỗi ký tự lộn xộn đó mà không có "mật khẩu chính" (Master Password) của bạn, hacker buộc phải thử từng trường hợp một 
