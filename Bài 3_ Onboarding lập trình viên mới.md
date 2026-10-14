# Bài 3: Onboarding lập trình viên mới

## Phần 1\. Báo cáo phân tích (I/O)

### Input (văn bản thô)

Input là nội dung viết trong file .md, chỉ gồm ký tự thường và các ký hiệu Markdown. Máy tính và Git đọc được trực tiếp, người viết không cần phần mềm đặc biệt.

| Bạn gõ (Input) | Ý nghĩa ký hiệu |
| ----- | ----- |
| \`ten\` | Inline Code cho tên biến ngắn |
| \`\`\`python ... \`\`\` | Code Block, từ python báo trình render tô màu cú pháp |
| | A | B | và |---|---| | Bảng (Table) |
| \- \[x\] và \- \[ \] | Task List: đã xong / chưa xong |
| \\\* hoặc \\\# | Escape: hiển thị ký tự đặc biệt, không bị render |

### Output (giao diện render trên StackEdit)

Output là khung bên phải của StackEdit, nơi cùng nội dung trên hiện thành:

* Tên biến ten, diem nằm trong nền xám, dễ phân biệt với văn bản giải thích.  
* Đoạn Python có màu riêng cho từ khóa (def, if, return), chuỗi và số.  
* Lệnh Terminal nằm trong khung code, cho biết đây là thứ cần gõ.  
* Bảng kẻ ô gọn gàng, Task List hiện ô tích chọn.  
* Dòng dùng \\\* hiện đúng dấu \* thay vì làm chữ nghiêng.

### Vì sao cần tách Input và Output

Input nhẹ, dễ lưu và dễ so sánh bằng Git. Output chỉ là bản hiển thị đẹp mắt cho người đọc, người đọc không cần biết cú pháp.

### Xử lý "bẫy" ký tự Escape

Dấu \* và \# có chức năng riêng trong Markdown. Muốn hiển thị chính ký tự đó, thêm dấu \\ phía trước (ví dụ \\\* và \\\#). Nếu không có \\, \*chữ\* sẽ bị biến thành chữ nghiêng và \# chữ sẽ thành tiêu đề.

## Phần 2\. Source code (file .md)

Output (giao diện render trên StackEdit): là khung bên phải, nơi cùng nội dung trên hiện thành:

* Tên biến ten, diem nằm trong nền xám, dễ phân biệt với văn bản giải thích.  
* Đoạn Python có màu riêng cho từ khóa (def, if, return), chuỗi và số.  
* Lệnh Terminal nằm trong khung code, cho biết đây là thứ cần gõ.  
* Bảng kẻ ô gọn gàng và Task List hiện ô tích chọn.  
* Dòng dùng \\\* hiện đúng dấu \* thay vì làm chữ nghiêng.

Vì sao cần tách Input và Output: Input nhẹ, dễ lưu và dễ so sánh bằng Git. Output chỉ là bản hiển thị, người đọc không cần biết cú pháp.

