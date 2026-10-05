# Hướng dẫn đóng góp

Cảm ơn bạn đã quan tâm và muốn đóng góp cho dự án Hello OSS.

## 1. Báo lỗi (Issue)

Nếu phát hiện lỗi trong dự án, bạn có thể tạo một Issue trên GitHub.

Khi báo lỗi, vui lòng cung cấp các thông tin sau:

* Mô tả rõ lỗi gặp phải.
* Các bước để tái hiện lỗi.
* Kết quả thực tế.
* Kết quả mong đợi.
* Hệ điều hành đang sử dụng.
* Phiên bản GCC đang sử dụng.

Ví dụ:

**Mô tả lỗi:**
Chương trình không chạy được sau khi biên dịch.

**Các bước tái hiện:**

1. Clone repository.
2. Mở Terminal.
3. Chạy lệnh `gcc -o hello main.c`.
4. Chạy chương trình.

**Kết quả mong đợi:**
Chương trình hiển thị `Hello OSS`.

## 2. Gửi Pull Request

Nếu muốn sửa lỗi hoặc bổ sung tính năng, vui lòng thực hiện các bước sau:

### Bước 1: Fork dự án

Fork repository Hello OSS về tài khoản GitHub của bạn.

### Bước 2: Clone repository

Clone repository đã fork về máy:

```bash
git clone https://github.com/your-username/hello-oss-doc.git
```

### Bước 3: Tạo nhánh mới

Tạo một nhánh mới để thực hiện thay đổi:

```bash
git checkout -b fix/ten-loi-can-sua
```

Ví dụ:

```bash
git checkout -b fix/sua-loi-chuong-trinh
```

### Bước 4: Thực hiện thay đổi

Sửa lỗi hoặc bổ sung nội dung cần thiết trong dự án.

### Bước 5: Commit thay đổi

Sau khi hoàn thành, sử dụng:

```bash
git add .
git commit -m "fix: sua loi chuong trinh"
```

### Bước 6: Push lên GitHub

```bash
git push origin fix/ten-loi-can-sua
```

### Bước 7: Tạo Pull Request

Truy cập repository trên GitHub và chọn **Compare & pull request** để tạo Pull Request.

Trong Pull Request, hãy mô tả rõ:

* Bạn đã thay đổi những gì.
* Lý do thực hiện thay đổi.
* Cách kiểm tra thay đổi.

## 3. Quy tắc đóng góp

* Viết nội dung rõ ràng, dễ hiểu.
* Kiểm tra chương trình trước khi gửi Pull Request.
* Không đưa thông tin cá nhân hoặc thông tin bảo mật vào repository.
* Mỗi Pull Request nên tập trung vào một lỗi hoặc một thay đổi cụ thể.

Cảm ơn bạn đã đóng góp cho dự án Hello OSS!
git commit -m "docs: update project documentation"