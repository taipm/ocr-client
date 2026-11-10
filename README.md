# OCR Client

App macOS (Apple Silicon) để OCR PDF/ảnh thành Markdown, JSON, LaTeX và PDF qua dịch vụ
https://ocr.codereview.club. Repo này chỉ chứa bản cài; mã nguồn không công khai.

## Cài đặt

1. Tải `OCR-Client_<phiên bản>_aarch64.dmg` ở trang [Releases](../../releases/latest).
2. Mở file `.dmg`, kéo **OCR Client** vào **Applications**.
3. Lần đầu mở: chuột phải vào app → **Open** (app chưa được ký bởi Apple).
4. Vào **Cài đặt**, dán API key dạng `ocrk_…` (xin từ quản trị viên dịch vụ).

## Dùng

- **Thêm tệp…** chọn PDF/ảnh, tích định dạng muốn nhận (`md`, `json`, `tex`, `pdf`), có thể ghi phạm vi trang (ví dụ `1-5,8`).
- **Gửi OCR**. `md`/`json` có trước, `tex`/`pdf` có sau vài giây.
- File kết quả lưu cạnh file gốc với đuôi `.ocr` (ví dụ `de-thi.ocr.pdf`), không bao giờ ghi đè file gốc.
