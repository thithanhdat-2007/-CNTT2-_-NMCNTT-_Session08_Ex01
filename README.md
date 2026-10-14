## **1. Mục tiêu**

- Phân biệt bản chất giữa Plain Text (văn bản thô) và Rich Text.
- Nhận diện ưu thế của Markdown trong việc chống hư hại file và hỗ trợ Git Diff.

## **2. Bối cảnh & Vấn đề**

Nam là sinh viên PTIT đang làm dự án nhóm. Nam viết tài liệu giới thiệu dự án bằng Microsoft Word (.docx) và đẩy lên GitHub. Tuy nhiên, các bạn trong nhóm phàn nàn rằng họ không thể xem nội dung trực tiếp trên trình duyệt và mỗi lần Nam sửa một dấu phẩy, hệ thống Git báo lỗi xung đột (Conflict) toàn bộ file.

[image](https://rikkeiedu-storage.s3.ap-southeast-2.amazonaws.com/uploads/editor-images/1787557183284_245daddb-78ec-43ef-965b-530f022a82d0.webp)

## **3. Hiện trường giả**

Nam lập luận: "Dùng Word tốt hơn vì có thanh công cụ chọn font chữ, màu sắc trực quan. Markdown chỉ là văn bản thô, không thể tạo được tài liệu chuyên nghiệp".

## **4. Ràng buộc & Bẫy dữ liệu**

- **Bẫy**: Nếu tệp Word của Nam bị lỗi mạng khi tải làm mất chỉ 1 byte dữ liệu, file sẽ hỏng hoàn toàn. Hãy đối chiếu với đặc tính của Markdown trong tình huống này.

## **5. Yêu cầu đầu ra**

### **Phần 1. Phân tích:**

Chỉ ra 2 sai lầm trong tư duy của Nam về việc dùng file Word cho lưu trữ mã nguồn. Giải thích tại sao Markdown lại an toàn và nhẹ hơn.

### **Phần 2. Hoàn thiện:**

Sử dụng StackEdit để chuyển đổi một đoạn giới thiệu ngắn từ Word sang Markdown, đảm bảo file có định dạng .md.