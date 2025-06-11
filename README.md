📱 EduLawAI_MO - Mobile Frontend (Flutter)
Đây là phần ứng dụng di động được xây dựng bằng Flutter cho dự án EduLawAI_MO – Chatbot AI hỗ trợ tra cứu và hỏi đáp các vấn đề liên quan đến luật giáo dục.

Ứng dụng giúp người dùng tiếp cận các văn bản luật một cách dễ hiểu, nhanh chóng, và tiện lợi ngay trên điện thoại.

🎯 Tính năng chính
💬 Chatbot AI: Giao tiếp với chatbot thông minh để hỏi đáp về luật giáo dục.

🔍 Tra cứu điều khoản pháp luật: Tìm kiếm nội dung luật theo từ khóa hoặc chủ đề.

🌐 Đa ngôn ngữ (tùy chọn): Hỗ trợ tiếng Việt và tiếng Anh.

📄 Trích dẫn điều luật: Cung cấp tham chiếu chính xác từ các văn bản pháp lý.

🎨 Giao diện thân thiện, dễ dùng trên di động.

🧱 Công nghệ sử dụng
Flutter: Framework xây dựng ứng dụng di động đa nền tảng (Android & iOS).

Dart: Ngôn ngữ lập trình chính.

Provider / Riverpod: Quản lý trạng thái (state management).

HTTP / Dio: Gửi yêu cầu đến backend AI chatbot.

Firebase (tùy chọn): Xác thực, lưu trữ hoặc thông báo đẩy.

Responsive UI: Tối ưu hóa trải nghiệm trên nhiều kích thước màn hình.

🚀 Khởi chạy ứng dụng
Yêu cầu:
Flutter SDK (>=3.0.0)

Android Studio hoặc Xcode (tùy nền tảng)

Thiết bị giả lập hoặc điện thoại thật

Các bước thực hiện:
bash
Sao chép
Chỉnh sửa
git clone https://github.com/yourusername/EduLawAI_MO_Mobile.git
cd EduLawAI_MO_Mobile
flutter pub get
flutter run
📁 Cấu trúc thư mục
css
Sao chép
Chỉnh sửa
lib/
├── main.dart                // Điểm khởi đầu ứng dụng
├── screens/                 // Các màn hình (Home, Chat, Luật, Giới thiệu)
├── widgets/                 // Các widget tái sử dụng
├── services/                // Gửi/nhận dữ liệu từ API
├── models/                  // Cấu trúc dữ liệu (luật, câu hỏi, phản hồi)
├── providers/               // Quản lý trạng thái (Provider hoặc Riverpod)
└── utils/                   // Các hàm tiện ích
📱 Giao diện mẫu (UI mockup)
(Bạn có thể chèn hình ảnh hoặc link Figma tại đây nếu có)
Giao diện bao gồm:

Màn hình chính

Giao diện chatbot

Trang tra cứu luật

Trang thông tin ứng dụng

⚠️ Lưu ý
Ứng dụng chỉ mang tính chất tham khảo, hỗ trợ thông tin pháp luật giáo dục, không thay thế tư vấn pháp lý chính thức.
Người dùng nên tham khảo ý kiến chuyên gia luật hoặc cơ quan nhà nước khi cần tư vấn pháp lý chính xác.

📌 Định hướng phát triển
✅ Giao diện tối/đẹp (dark/light mode)

🔐 Đăng nhập/Đăng ký với Firebase Auth

💡 Lưu lại lịch sử trò chuyện

📲 Hỗ trợ ngoại tuyến (offline laws caching)

📥 Tải tài liệu luật về máy

🤝 Đóng góp
Chúng tôi hoan nghênh mọi sự đóng góp!
Fork repo, tạo branch mới, commit thay đổi và gửi Pull Request.

📜 Giấy phép
Dự án được phát hành dưới MIT License.
