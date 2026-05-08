# 👨‍💻 Xin chào, mình là Nguyễn Phan Thanh (WinG-282k4)

---

### 💡 Về mình
Mình là sinh viên năm cuối ngành Công nghệ Thông tin tại Đại học Bách khoa - Đại học Đà Nẵng (DUT). Với nền tảng vững chắc về Java và Lập trình Hướng đối tượng, mình đang định hướng phát triển chuyên sâu ở vai trò Backend Developer và kỹ sư tích hợp AI. Mình có kinh nghiệm xây dựng các hệ thống có khả năng mở rộng như ứng dụng trò chuyện và game nhiều người chơi với giao tiếp thời gian thực WebSocket.

* **Học vấn:** Cử nhân Kỹ thuật Công nghệ Thông tin (GPA: 3.31/ 4.0).
* **Liên hệ:** npthanh60@gmail.com 

---

### 🛠 Kỹ năng cốt lõi
* **Backend Development:** Spring Boot, Django, RESTful APIs, WebSocket (STOMP), JPA/Hibernate. Lập trình kiến trúc phân tầng (Controller - Service - Repository), DTO Mapping (MapStruct).
* **Database & DevOps:** MySQL, PostgreSQL, Docker, GitHub Actions (CI/CD), Microsoft Azure.
* **AI & Computer Vision:** Tối ưu hóa YOLOv8, tiền xử lý ảnh CLAHE, phân tích chỉ số mAP, xử lý luồng dữ liệu (Data Pipeline).

---

### 🚀 Dự án tiêu biểu

#### 1. 🎮 Buckshot Roulette Game (Spring Boot & System Logic)
*Dự án tập trung vào quản lý trạng thái (state management) và xử lý luồng đồng thời.*
* **Công nghệ:** Spring Boot Framework, HTML, CSS, Javascript, Docker, GitHub Actions.
* **Chi tiết triển khai:**
  * Thiết kế backend trò chơi nhiều người chơi theo thời gian thực, xử lý các phiên đồng thời bằng Spring WebSocket (STOMP) và quản lý trạng thái trò chơi đồng bộ.
  * Lập trình logic trò chơi phức tạp tập trung vào kiểm soát đồng thời và quản lý phiên hiệu quả.
  * Giảm thời gian triển khai bằng cách tự động hóa CI/CD với GitHub Actions và container hóa bằng Docker.
* **Mã nguồn:** [Buckshot_Roulette_Game](https://github.com/WinG-282k4/Buckshot_Roulette_Game)

#### 2. 🌐 OCR_UIToCode Backend API (Web Architecture)
*Dự án tập trung vào thiết kế RESTful API và quản lý luồng tích hợp hệ thống đa nền tảng.*
* **Công nghệ:** Django, PostgreSQL, JWT Authentication.
* **Chi tiết triển khai:**
  * Lập trình RESTful API để vận hành nền tảng thiết kế UI cộng tác.
  * Triển khai xác thực JWT và kiểm soát truy cập dựa trên vai trò chi tiết (Chủ sở hữu, Người chỉnh sửa, Người xem).
  * Phát triển các endpoint có khả năng mở rộng hỗ trợ sửa đổi theo thời gian thực, quản lý phiên bản trạng thái đa màn hình và khả năng tạo mã linh hoạt trên HTML, React và Vue.

#### 3. 🧠 VinBigData_Detection (AI & Computer Vision)
*Dự án tập trung vào nghiên cứu độc lập và ứng dụng Computer Vision trong lĩnh vực Y tế.*
* **Công nghệ:** Python, YOLOv8, OpenCV.
* **Chi tiết triển khai:**
  * Huấn luyện và tinh chỉnh mô hình YOLOv8 trên bộ dữ liệu VinDr-CXR để phát hiện các dấu hiệu bất thường trên ảnh chụp X-quang lồng ngực.
  * Quản lý phiên bản thử nghiệm (`YOLOv8m_CLAHE_v1`), tập trung vào việc áp dụng kỹ thuật cân bằng biểu đồ mức xám (CLAHE) trong bước tiền xử lý để làm nổi bật các cấu trúc y khoa mờ.
  * Phân tích và xử lý vấn đề mất cân bằng lớp (class imbalance) đặc thù của dữ liệu y tế nhằm tối ưu hóa chỉ số mAP (Mean Average Precision).
