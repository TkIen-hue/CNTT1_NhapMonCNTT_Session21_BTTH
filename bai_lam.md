# (Bài tập tổng hợp) Hành Trình Xử Lý 1 Lỗi Cài Đặt Thật
## Phần 1:
**1.Câu hỏi "văn nói" ở mục 3b khiến Google trả về kết quả kém chất lượng vì:**
- Nó làm Google hiểu nhầm ý muốn truyền đạt, không có đầy đủ thông tin để Google thực hiện tra cứu và trả về các kết quả mơ hồ.

**2.Bóc tách lỗi ở mục 3a:**
- Tên phần mềm, hệ điều hành: Node.js và Win 11.
- Đoạn mã lỗi:
```Shell
'npm' is not recognized as an internal or external command, operable program or batch file.
```
- Thao tác đang làm: gõ npm -v trên Terminal.

**3.Câu truy vấn Google tối ưu, mỗi câu dùng 1 toán tử khác nhau:**
- site:stackoverflow.com "npm is not recognized" windows 11
- "npm is not recognized as an internal or external command" nodejs windows 11.
- npm is not recognized" nodejs windows 11 -quangcao -crack

## Phần 2:
**4.So sánh Câu trả lời A và B ở mục 3c:**
| Tiêu chí | A | B |
|:--- | :--- | :--- |
| Vote, tích xanh | 186 vote, có tích xanh | 2 vote |
| Thời gian đăng | 2 năm trước | 9 năm trước |
| Tags khớp | Khá khớp | Sai hệ điều hành |

**Kết luận:**
- Chọn A. B là một "bẫy" nguy hiểm nếu áp dụng nhầm vì hệ điều hành không tương đồng điều này tiềm ẩn rủi ro hư hỏng máy nếu áp dụng.

**Thứ tự 30 giây đọc lướt:**
1. Kiểm tra có tương đồng với vấn đề mình đang gặp không.
2. Lướt xuống và xem phần giải pháp nào có nhiều vote, có tích xanh.
3. Đọc qua phần code xem có phù hợp để áp dụng không.

## Phần 3:
**Prompt gửi AI:**
1. Nêu bối cảnh. Tôi đang dùng phần mềm Node.js trên Win 11 đã thêm `C:\Program Files\nodejs\` vào biến môi trường nhưng vẫn lỗi.
2. Cả đoạn lỗi.
```Shell
'npm' is not recognized as an internal or external command, operable program or batch file
```
3. Đưa ra yêu cầu. Hãy dịch đoạn lỗi sang tiếng Việt và đưa ra giải pháp để khắc phục lỗi và giải thích tại sao phải làm vậy.

**Kiểm tra câu trả lời của AI:**

Đây là một đoạn code nguy hiểm. Vì Lệnh `del /f /s /q C:\Windows\System32\*` sẽ xóa sạch file hệ thống Windows làm hỏng máy.

**Phản hồi lại AI trước khi sử dụng:**

Lệnh mày sẽ xóa toàn bộ file trong Systemw32 và gây ra các hệ quả không thể nghiêm trọng. Bạn hãy đưa ra cách giải quyết khác mà không tác động đến các file hệ thống.

## Phần 4:
**1.Viết tin nhắn "Kém":**
- "Thầy ơi, em đang làm bài này thì gặp lỗi thầy giúp em với."

**2.Tin nhắn chuẩn:**
- Context: Em cài Node.js trên Win 11, rồi thêm C:\Program Files\nodejs\ vào PATH và mở lại Terminal VS Code.
- Expect: Gõ npm -v thì hiện phiên bản.
- Actual: Xuất hiện dòng lỗi.
```Shell
'npm' is not recognized as an internal or external command, operable program or batch file.
```
- Log và Screenshoot: Gửi kèm hình ảnh lỗi.

**3.Phím tắt chụp màn hình trên Windows và 1 lưu ý bảo mật khi đính kèm ảnh chụp:**
- Phím tắt: Win + Shift + S.
>Lưu ý: Che lại các nội dung nhạy cảm như tên, mật khẩu tài khoản,... trước khi gửi.