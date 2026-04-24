# Instruction - Education Bootstrap Template

**Instruction** là một giao diện website giáo dục hiện đại, chuyên nghiệp và có khả năng tương thích cao trên nhiều thiết bị (Responsive). Dự án được xây dựng dựa trên framework Bootstrap 4, kết hợp với các thư viện phổ biến như Owl Carousel để tạo hiệu ứng slider mượt mà và Font Awesome cho hệ thống biểu tượng.

---

## Tính Năng Nổi Bật

* **Thiết kế Responsive:** Giao diện tự động thích ứng với mọi kích thước màn hình (Desktop, Tablet, Mobile) nhờ hệ thống Grid của Bootstrap.
* **Thanh Điều Hướng Trực Quan:** Navbar tích hợp menu thả xuống (Dropdown) và nút toggle cho giao diện di động.
* **Hiệu Ứng Carousel:** Banner chuyển động tự động và section phản hồi của học viên (Testimonials) sử dụng thư viện Owl Carousel 2.
* **Cấu Trúc Rõ Ràng:** Chứa đầy đủ các phần thiết yếu của một trang web giáo dục: Header, Carousel, Welcome (Các khóa học), Our Stats (Thống kê), What We Offer (Chương trình đào tạo), Feedback (Cảm nhận học viên), News & Events (Tin tức & Sự kiện), và Footer.
* **Tích Hợp Modal:** Cửa sổ Pop-up (Modal) được tích hợp sẵn bằng Bootstrap để hiển thị chi tiết tin tức.

## Công Nghệ Sử Dụng

* **HTML5 & CSS3**
* **Bootstrap v4.5.3:** Framework CSS hỗ trợ thiết kế responsive nhanh chóng.
* **jQuery v3.7.1:** Thư viện JavaScript cần thiết để chạy các component của Bootstrap và Owl Carousel.
* **Owl Carousel v2.3.4:** Thư viện tạo các thanh trượt (slider/carousel) cho phần banner và đánh giá.
* **Font Awesome v6.0.0:** Hệ thống icon vector.
* **Google Fonts:** Sử dụng font chữ "Work Sans" thanh lịch và hiện đại.

## Cấu Trúc Thư Mục

```text
Instruction-Bootstrap/
├── .vscode/               
│   └── settings.json      # Cấu hình Live Server (Port: 5501)
├── css/                   
│   ├── index.css          # CSS tùy chỉnh chính của dự án
│   ├── owl.carousel.min.css # CSS của thư viện Owl Carousel
│   └── owl.theme.default.min.css # Theme mặc định của Owl Carousel
├── img/                   # Chứa toàn bộ hình ảnh (Banner, logo, ảnh nền, avatar...)
├── js/                    
│   └── owl.carousel.min.js # File JavaScript của thư viện Owl Carousel
└── index.html             # Trang chủ chính chứa mã HTML
