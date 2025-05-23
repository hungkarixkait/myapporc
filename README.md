# OCRVID-MYAPP

## Giới thiệu

OCRVID-MYAPP là ứng dụng web chuyên dụng để xử lý và thuyết minh video bằng cách sử dụng công nghệ OCR, dịch thuật và chuyển văn bản thành giọng nói. Ứng dụng cho phép người dùng trích xuất phụ đề từ video, dịch sang tiếng Việt và tạo âm thanh thuyết minh từ phụ đề đã dịch.

## Tính năng chính

- **Trích xuất phụ đề**: Sử dụng Google Vision API để quét và trích xuất phụ đề từ video
- **Dịch thuật**: Dịch phụ đề sang tiếng Việt thông qua API của ChatGPT
- **Chuyển văn bản thành giọng nói**: Tạo âm thanh thuyết minh từ phụ đề đã dịch
- **Giao diện chỉnh sửa**: Sử dụng Remotion để cung cấp giao diện trực quan cho việc chỉnh sửa

## Công nghệ sử dụng

- **Frontend**: React, Remotion
- **Backend**: Python cho xử lý và render video
- **API**: Google Vision API, OpenAI ChatGPT API, Text-to-Speech API

## Giao diện người dùng

Ứng dụng có giao diện trực quan chia thành 4 phần chính:

1. **Thanh menu bên trái**:
   - Nút tải lên video
   - Danh sách video đã xử lý và trạng thái tương ứng
   - Nút yêu cầu lồng tiếng
   - Nút yêu cầu xuất video

2. **Khu vực hiển thị phụ đề** (bên phải):
   - Hiển thị nội dung phụ đề theo từng dòng
   - Cho phép chỉnh sửa nội dung phụ đề

3. **Timeline video** (phía dưới):
   - Hiển thị dòng thời gian của video
   - Cho phép điều chỉnh thời gian xuất hiện của phụ đề

4. **Khu vực xem trước** (ở giữa):
   - Hiển thị frame video
   - Các điều khiển phát video: phát/dừng, bật/tắt âm thanh gốc
   - Hiển thị thời gian hiện tại và tổng thời gian của video

## Quy trình làm việc

1. Tải video lên ứng dụng
2. Hệ thống tự động trích xuất phụ đề bằng OCR
3. Dịch phụ đề sang tiếng Việt
4. Chỉnh sửa phụ đề nếu cần
5. Tạo âm thanh thuyết minh từ phụ đề đã dịch
6. Xuất video với phụ đề và thuyết minh mới

## Triển vọng phát triển

Trong tương lai, ứng dụng sẽ được phát triển thêm các tính năng:
- Hỗ trợ nhiều ngôn ngữ dịch
- Công cụ chỉnh sửa video nâng cao
- Tối ưu hóa chất lượng âm thanh
- Hỗ trợ xử lý hàng loạt nhiều video

## Cài đặt và sử dụng

(Chi tiết hướng dẫn cài đặt và sử dụng sẽ được cập nhật sau)
