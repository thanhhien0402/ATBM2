# LAB 1 – MÃ HÓA ĐỐI XỨNG CỔ ĐIỂN

## 1. Thông tin sinh viên

- **Họ và tên:** Nguyễn Thị Thanh Hiền
- **Mã số sinh viên:** 1150080092
- **Lớp:** CNPM2

## 2. Giới thiệu

Ứng dụng thực hành các thuật toán mã hóa đối xứng cổ điển bằng Java Swing, hỗ trợ mã hóa, giải mã, kiểm tra tính hợp lệ của khóa, lưu và mở tệp bản mã.

## 3. Công nghệ sử dụng

- Java 17
- Apache NetBeans 25
- Maven
- Java Swing
- Java File I/O

## 4. Chức năng đã hoàn thành

- Mã hóa và giải mã Caesar.
- Mã hóa và giải mã Vigenère.
- Mã hóa và giải mã Rail Fence.
- Mã hóa và giải mã Playfair.
- Tạo và hiển thị ma trận khóa Playfair 5×5.
- Mã hóa và giải mã hoán vị cột (Transposition).
- Mã hóa và giải mã Autokey.
- Lưu và mở tệp bản mã (.txt).
- Kiểm tra dữ liệu đầu vào và thông báo lỗi.

## 5. Cấu trúc mã nguồn

Các lớp được lưu trong package `week_01` tại thư mục `src/main/java/`.

| Lớp xử lý thuật toán | Lớp giao diện |
|---|---|
| CaesarCipher.java | frm_Caesar.java |
| VigenereCipher.java | frm_Vigenere.java |
| RailFenceCipher.java | frm_RailFence.java |
| PlayfairCipher.java | frm_Playfair.java |
| TranspositionCipher.java | frm_Transposition.java |
| AutokeyCipher.java | frm_Autokey.java |

- `FileTextIO.java`: Hỗ trợ đọc và ghi tệp văn bản.
- `pom.xml`: Cấu hình Maven và các thư viện phụ thuộc.

## 6. Hướng dẫn chạy

1. Mở project `LAB1_MaHoaCoDien` bằng NetBeans.
2. Nhấp chuột phải vào project → Clean and Build.
3. Mở Source Packages → week_01.
4. Chọn form của thuật toán cần sử dụng.
5. Nhấn Shift + F6 (Run File).

## 7. Kết quả kiểm thử

| Thuật toán | Bản rõ | Khóa | Bản mã | Giải mã |
|---|---|---|---|---|
| Caesar | HELLO | 3 | KHOOR | HELLO |
| Vigenère | HELLO | KEY | RIJVS | HELLO |
| Rail Fence | HELLO WORLD | 3 | HOREL OLLWD | HELLO WORLD |
| Playfair | HELLOWORLD | KEYWORD | GYIZSCOKCFBU | HELXLOWORLDX |
| Transposition | BAOMAT | 2,3,1 | AAOTBM | BAOMAT |
| Autokey | HELLO | KEY | RIJSS | HELLO |
