# Read-Deep-map-by-ORBBEC-Astra-Pro-Camera
Đọc bản đồ độ sâu bằng camera Orbbec Astra Pro bằng ngôn ngữ Python

Bạn cần tải Orbbec SDK từ website của hãng:
https://www.orbbec.com/developers/orbbec-sdk/

Sau khi tải về thì giải nén hãy vào thư mục "bin" sau đó copy đường dẫn của thư mục "bin" này
<img width="608" height="37" alt="image" src="https://github.com/user-attachments/assets/823455fb-506c-46f5-abcb-11aab3cd3072" />

Tiếp theo bạn vào chỉnh sửa đường dẫn trong file read_deep.py thành đường dẫn mà bạn đã copy. Ví dụ như tôi thì câu lệnh sẽ là như thế này.
Và cuối cùng trước khi chạy chương trình bạn cần tải thư viện openni, numpy, opencv.

# Khởi tạo với đường dẫn bạn cung cấp
openni2.initialize("C:/Users/Admin/Downloads/AstraSDK-v2.1.3-94bca0f52e-20210608T034051Z-vs2015-win64/bin")
