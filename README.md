# 🌸 Sakura Japanese App

## Mô tả

**Sakura Japanese** là một ứng dụng học tiếng Nhật đa nền tảng, được phát triển bằng React Native. Ứng dụng mang đến trải nghiệm học tập thú vị và hiệu quả, nhấn mạnh vào việc cải thiện trình độ tiếng Nhật thông qua giao diện thân thiện, các tính năng học tập trực quan, và sự tương tác tối ưu.

## Lí do phát triển

Trong bối cảnh toàn cầu hóa ngày càng phát triển, việc học ngoại ngữ không chỉ là một lợi thế cá nhân mà còn là một yêu cầu cần thiết để cạnh tranh và thành công trong môi trường làm việc hiện đại. Trong số các ngôn ngữ được người học quan tâm, tiếng Nhật nổi bật với vị trí đặc biệt, không chỉ là ngôn ngữ của một quốc gia phát triển mạnh mà còn là ngôn ngữ của văn hóa đa dạng, nền kinh tế mạnh mẽ và công nghệ tiên tiến.

Để đáp ứng nhu cầu ngày càng tăng của người học tiếng Nhật, việc sử dụng các nền tảng trực tuyến để học ngôn ngữ đã trở thành một xu hướng không thể phủ nhận. Tuy nhiên, sự thành công của một nền tảng học trực tuyến phụ thuộc không chỉ vào chất lượng nội dung mà còn vào trải nghiệm người dùng thông qua giao diện. Tuy nhiên đến thời điểm hiện tại, việc tìm ra một website học tiếng Nhật có giao diện trực quan, đẹp mắt là một điều rất khó. 

Nhận thức rõ ràng về tầm quan trọng của việc tạo ra một giao diện trực quan, thân thiện và hiệu quả cho một website học tiếng Nhật, chúng tôi đã tập trung vào việc nghiên cứu, phân tích để hiểu rõ nhu cầu của người dùng, từ đó đề xuất các giải pháp thiết kế giao diện hợp lý, đặt mục tiêu tạo ra một giao diện mang lại trải nghiệm học tập đáng nhớ, khuyến khích sự tương tác và nâng cao hiệu suất học tập.

## Một số hình ảnh giao diện

Dưới đây là một số hình ảnh giao diện của Sakura Japanese được thiết kế bằng Figma:

### Trang đăng nhập/đăng ký

<img src="images/Dang_nhap.jpg" alt="Đăng nhập" width="300" />
<img src="images/Dang_ky.jpg" alt="Đăng ký" width="300" />

### Trang chủ

<img src="images/Trang_chu.jpg" alt="Trang chủ" width="300" />

### Trang tra cứu từ vựng

<img src="images/Tra_cuu.jpg" alt="Tra cứu" width="300" />

### Trang tài liệu ofline

<img src="images/Tai_lieu_offline.jpg" alt="Tài liệu offline" width="300" />
<img src="images/Danh_sach_bai_hoc.jpg" alt="Danh sách bài học" width="300" />
<img src="images/Tu_vung.jpg" alt="Từ vựng" width="300" />


### Trang khóa học

<img src="images/Khoa_hoc.jpg" alt="Khóa học" width="300" />

### Trang giỏ hàng

<img src="images/Gio_hang.jpg" alt="Giỏ hàng" width="300" />

### Trang thi thử

<img src="images/Thi_thu.jpg" alt="Thi thử" width="300" />

### Trang thông báo

<img src="images/Thông báo.jpg" alt="Thông báo" width="300" />


## Tính năng chính

- **Tài liệu học tập**: Tài liệu học tập miễn phí, được chia theo từng level của người dùng, giúp người dùng có thể dễ dàng lựa chọn bài học phù hợp với trình độ của mình.

- **Khóa học đa dạng**: Bao gồm nội dung từ cơ bản đến nâng cao, phù hợp với mọi cấp độ người học, mỗi bài học có video bài giảng và tài liệu kèm theo.
  
- **Bài tập và kiểm tra**: Giúp người học củng cố kiến thức và đánh giá trình độ thông qua các bài kiểm tra định kỳ.
  
- **Từ điển**: Tích hợp từ điển tiếng Nhật hỗ trợ quá trình học tập, giúp năng mức độ tập trung của người dùng khi học tiếng Nhật.


## Công nghệ sử dụng

### Backend
- **Node.js**: Nền tảng chính để xây dựng API cho ứng dụng.
- **Backend Dependencies**:
  - Express.js: Framework cho việc xử lý các yêu cầu HTTP.
  - Mongoose: Quản lý cơ sở dữ liệu MongoDB.
  - JSON Web Token (JWT): Xác thực và bảo mật.

### Frontend
Ứng dụng React Native sử dụng các công nghệ sau để tối ưu hóa giao diện và trải nghiệm người dùng:
1. **Navigation**: Quản lý điều hướng giữa các màn hình.
2. **Axios**: Thư viện gọi API.
3. **Async Storage**: Lưu trữ dữ liệu cục bộ trên thiết bị di động.
4. **Nativewind**: Thư viện hỗ trợ sử dụng Tailwind CSS với React Native.
5. **React Native Reanimated**: Tạo hiệu ứng động mượt mà.
6. **React Native Safe Area Context**: Quản lý khoảng cách an toàn trên các thiết bị di động.
7. **React Native SVG & React Native SVG Transformer**: Hiển thị và quản lý các hình ảnh SVG.
8. **React Native Video**: Phát video trong ứng dụng.
9. **React Native Webview**: Hiển thị nội dung web bên trong ứng dụng.
10. **React Native Youtube Iframe**: Nhúng và phát video YouTube.
11. **Swiper**: Tạo hiệu ứng trượt cho giao diện.
12. **Lottifile**: Hiển thị các hiệu ứng động Lottie.

## Cách cài đặt và chạy ứng dụng

### Yêu cầu hệ thống
- Node.js (phiên bản >= 14).
- React Native CLI hoặc Expo CLI.
- Thiết bị di động (Android/iOS) hoặc trình giả lập.

### Hướng dẫn cài đặt

1. **Clone dự án**:
   ```bash
   git clone https://github.com/your-repo/sakura-japanese.git
   cd japanese-learning-app
   ```
2. **Cài đặt phụ thuộc**:
   ```bash
   cd frontend
   npm i
   ```
   ```bash
   cd backend
   npm i
   ```
3. **Chạy dự án (mở 2 terminal)**:
   ```bash
   cd frontend
   npm start
   ```
   ```bash
   cd backend
   npm start
   ```
4. **Chạy demo**
   Dùng điện thoại quét QR code để chạy demo trên Expo Go. Bạn cũng có thể chạy demo trên Android Studio bằng cách ấn phím "a"

## Đóng góp

Tôi hoan nghênh mọi đóng góp để hoàn thiện dự án này. Nếu bạn có ý tưởng hoặc muốn tham gia phát triển, vui lòng fork repository và gửi pull request. Bạn cũng có thể mở issues để báo cáo lỗi hoặc đề xuất tính năng mới.

## Liên hệ

Nếu có bất kỳ câu hỏi hoặc phản hồi nào, vui lòng liên hệ qua email: ntruong0961@gmail.com.

---

Tôi hy vọng Sakura Japanese sẽ là một công cụ hữu ích cho bạn trên con đường học tiếng Nhật. Cảm ơn bạn đã quan tâm và ủng hộ dự án!
   
