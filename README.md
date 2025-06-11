📱 EduLawAI_MO - Mobile Frontend (React Native)
Đây là phần ứng dụng di động được phát triển bằng React Native cho dự án EduLawAI_MO – Chatbot AI giúp người dùng tra cứu luật giáo dục và đặt câu hỏi pháp lý một cách dễ hiểu và nhanh chóng.
----------------------------------------------------------------------------------------------------
🎯 Tính năng chính
💬 Trò chuyện với AI: Giao diện trò chuyện tự nhiên, dễ sử dụng với chatbot AI về luật giáo dục.

🔍 Tra cứu điều luật: Tìm kiếm theo từ khóa hoặc điều khoản.

🌐 Hỗ trợ đa ngôn ngữ (tuỳ chọn): Tiếng Việt, Tiếng Anh.

📄 Hiển thị trích dẫn luật: Cung cấp câu trả lời có nguồn trích dẫn cụ thể.

📱 Thiết kế tối ưu cho thiết bị di động: Giao diện linh hoạt, dễ dùng trên Android và iOS.
----------------------------------------------------------------------------------------------------
🧱 Công nghệ sử dụng
React Native (Expo hoặc CLI): Xây dựng ứng dụng di động đa nền tảng.

JavaScript / TypeScript: Ngôn ngữ lập trình chính.

React Navigation: Điều hướng giữa các màn hình.

Axios / Fetch API: Gửi yêu cầu đến backend AI Chatbot.

Context API / Redux / Zustand (tùy chọn): Quản lý trạng thái ứng dụng.

Firebase / AsyncStorage (tuỳ chọn): Lưu trữ người dùng, dữ liệu cục bộ, thông báo đẩy.
----------------------------------------------------------------------------------------------------
🚀 Hướng dẫn khởi chạy
Yêu cầu:
Node.js (>=14)

Expo CLI hoặc React Native CLI

Android Studio / Xcode (nếu chạy trên thiết bị giả lập)

Các bước thực hiện:
bash
Sao chép
Chỉnh sửa
git clone https://github.com/yourusername/EduLawAI_MO_Mobile.git
cd EduLawAI_MO_Mobile
npm install
npx expo start      # hoặc: npm start
✅ Bạn có thể quét mã QR bằng ứng dụng Expo Go trên điện thoại để chạy nhanh ứng dụng.
----------------------------------------------------------------------------------------------------
📁 Cấu trúc thư mục
cpp
Sao chép
Chỉnh sửa
EduLawAI_MO_Mobile/
├── App.js
├── assets/                // Hình ảnh, icon
├── components/            // Các component tái sử dụng
├── screens/               // Các màn hình chính (Chat, Luật, Giới thiệu)
├── navigation/            // Cấu hình điều hướng
├── services/              // API kết nối đến chatbot
├── contexts/              // Context API (nếu dùng)
├── utils/                 // Hàm tiện ích
└── ...
📷 Giao diện dự kiến
Màn hình chính: Giới thiệu và nút bắt đầu chat

Màn hình Chatbot: Giao diện trò chuyện như ứng dụng nhắn tin

Màn hình Luật: Danh sách văn bản luật, tìm kiếm và xem chi tiết

Màn hình Giới thiệu: Thông tin về app và chatbot
----------------------------------------------------------------------------------------------------
⚠️ Lưu ý pháp lý
EduLawAI_MO không thay thế tư vấn pháp lý chuyên nghiệp.
Các câu trả lời từ chatbot chỉ mang tính tham khảo và hỗ trợ thông tin, người dùng nên tìm đến luật sư hoặc cơ quan chức năng khi cần tư vấn chính thức.
----------------------------------------------------------------------------------------------------
🔮 Dự định phát triển tiếp theo
📂 Lưu lịch sử trò chuyện

🌓 Giao diện Dark/Light mode

🔐 Đăng nhập và cá nhân hóa

📲 Lưu trữ dữ liệu offline

🧩 Tích hợp AI nội bộ (local model)
----------------------------------------------------------------------------------------------------
🤝 Đóng góp
Chào mừng mọi đóng góp từ cộng đồng!

Fork repository

Tạo branch mới: git checkout -b feature/tên-tính-năng

Commit và push

Gửi Pull Request
