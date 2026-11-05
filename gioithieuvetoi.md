# Dương Đức Quân (DuongDucQuan) – Full Stack Web Developer

**Dương Đức Quân** (nick **duongducquan**, GitHub **DuongDucQuan**) là sinh viên và lập trình viên Full Stack ở Việt Nam. Repo này tổng hợp toàn bộ công nghệ mình đã học: frontend, backend, cơ sở dữ liệu, realtime, bản đồ GIS, triển khai và SEO.

Trang web của repo: [duongducquan.github.io](https://duongducquan.github.io)

## Mục lục

- [Giới thiệu](#giới-thiệu-dương-đức-quân-duongducquan)
- [Frontend](#frontend)
- [Backend](#backend)
- [Cơ sở dữ liệu](#cơ-sở-dữ-liệu)
- [API và realtime](#api-và-giao-tiếp-thời-gian-thực)
- [GIS – OpenStreetMap](#gis--bản-đồ-và-dữ-liệu-địa-lý)
- [Kiến trúc phần mềm](#kiến-trúc-phần-mềm)
- [DevOps và triển khai](#devops-và-triển-khai-website)
- [SEO On-page](#seo-on-page-mà-dương-đức-quân-đã-học)
- [AI hỗ trợ lập trình](#ai-và-công-cụ-hỗ-trợ-lập-trình)
- [Dự án đã làm](#dự-án-dương-đức-quân-đã-làm)
- [Tất cả liên kết](#tất-cả-liên-kết-của-dương-đức-quân-duongducquan)

## Giới thiệu Dương Đức Quân (DuongDucQuan)

Mình là **Dương Đức Quân**, trên mạng dùng tên **duongducquan** và **DuongDucQuan**. Mình học lập trình theo hướng **Full Stack**: tự dựng giao diện, viết API, thiết kế database rồi đưa website lên hosting. Phần lớn công nghệ bên dưới mình học qua đồ án, bài tập cuối kỳ và các dự án cá nhân.

> **Lưu ý trung thực:** một số mảng như kiến trúc phần mềm, Docker, CI/CD và triển khai nâng cao là kiến thức mình đang tìm hiểu thêm, chưa phải đã làm thành thạo trong dự án thực tế.

## Frontend

| Công nghệ | Mình dùng để |
|---|---|
| HTML5 | Dựng cấu trúc website, thẻ ngữ nghĩa |
| CSS3 | Thiết kế giao diện, responsive |
| JavaScript (ES6+) | Xử lý logic, DOM, bất đồng bộ |
| TypeScript | JavaScript có kiểu dữ liệu |
| ReactJS | Xây dựng giao diện SPA |
| Vite | Build tool, khởi tạo dự án React |
| Tailwind CSS | Viết giao diện bằng utility classes |
| Material UI (MUI) | Thư viện component cho React |

## Backend

| Công nghệ | Mình dùng để |
|---|---|
| Node.js | Chạy JavaScript phía server |
| Express.js | Xây dựng backend và REST API |
| PHP | Lập trình backend |
| CodeIgniter 4 | Framework PHP theo mô hình MVC |
| RESTful API | Thiết kế và quản lý API |
| JWT | Xác thực người dùng bằng token |
| Socket.IO | Giao tiếp thời gian thực |
| Event Loop, libuv | Hiểu cơ chế bất đồng bộ của Node.js |

## Cơ sở dữ liệu

- **MySQL:** SQL, JOIN, CRUD, cơ sở dữ liệu quan hệ.
- **MongoDB:** cơ sở dữ liệu NoSQL.
- **Connection Pool:** quản lý kết nối database.
- **Database Design:** thiết kế bảng, quan hệ, khóa chính, khóa ngoại.
- **JSON:** định dạng trao đổi dữ liệu giữa frontend và backend.

## API và giao tiếp thời gian thực

- HTTP: GET, POST, PUT, PATCH, DELETE.
- REST API và JSON, Authentication, Authorization.
- WebSocket và Socket.IO: chat realtime, room, event, emit, broadcast.
- Đồng bộ dữ liệu giữa điện thoại và máy tính.
- Tài liệu API với Swagger UI, OpenAPI; kiểm thử bằng Postman.

## GIS – bản đồ và dữ liệu địa lý

Mảng mình đang nghiên cứu trong quá trình thực tập.

| Công nghệ | Nội dung |
|---|---|
| OpenStreetMap (OSM) | Dữ liệu bản đồ mã nguồn mở |
| Nominatim | Geocoding và Reverse Geocoding |
| Overpass API, Overpass Turbo | Truy vấn dữ liệu OSM, công cụ viết và chạy truy vấn |
| GeoJSON | Chuẩn biểu diễn dữ liệu địa lý |
| Node / Way / Relation | Các kiểu đối tượng trong OSM |
| Point / LineString / Polygon | Các dạng hình học địa lý |
| Bounding Box, Latitude / Longitude | Vùng giới hạn tọa độ, vĩ độ và kinh độ |

## Kiến trúc phần mềm

MVC, Layered Architecture, Clean Architecture, Modular Monolith, Microservices, Event-Driven Architecture và mẫu Controller – Service – Repository. Mình áp dụng MVC thường xuyên nhất; các kiến trúc còn lại đang ở mức tìm hiểu.

## DevOps và triển khai website

- **Git và GitHub:** quản lý mã nguồn, version control, GitHub Pages.
- **Docker:** đóng gói ứng dụng bằng container.
- **Nginx:** web server và reverse proxy.
- **Ngrok:** public localhost để demo.
- **Hosting:** Firebase Hosting, Netlify, Vercel, GitHub Pages, Cloudflare Workers.
- **CI/CD:** tự động hóa build và deploy.

## SEO On-page mà Dương Đức Quân đã học

SEO On-page là phần tối ưu ngay trên website để Google hiểu nội dung. Với các trang của **DuongDucQuan**, mình áp dụng:

- Thẻ **title** và **meta description** chứa từ khóa chính.
- Một thẻ **H1** cho mỗi trang, các mục con dùng H2, H3 đúng thứ bậc.
- **HTML ngữ nghĩa:** header, nav, main, article, section, footer.
- **Canonical URL** để tránh trùng nội dung.
- **Open Graph và Twitter Card** để chia sẻ đẹp trên mạng xã hội.
- **Dữ liệu có cấu trúc JSON-LD** (Person, Article, FAQPage).
- Thuộc tính **alt** cho hình ảnh, ảnh tối ưu dung lượng.
- **Liên kết nội bộ** bằng mục lục và anchor text rõ nghĩa.
- **sitemap.xml, robots.txt**, xác minh bằng Google Search Console, theo dõi bằng Google Analytics.
- **Responsive và tải nhanh** cho cả điện thoại.

## AI và công cụ hỗ trợ lập trình

Groq API để tích hợp chatbot, Prompt Engineering, Claude Code, Gemini, API Integration và VS Code. Mình dùng AI để học nhanh và rà lỗi, còn kiến trúc và logic vẫn tự quyết định.

## Dự án Dương Đức Quân đã làm

| Dự án | Mô tả |
|---|---|
| TechShop VN | Website thương mại điện tử bằng Java, Servlet, JSP |
| Nông Sản Sạch | Website bán nông sản bằng CodeIgniter (PHP) |
| BuffVIP | Trang quản trị reseller dịch vụ SMM bằng Node.js và Express |
| Web vật liệu xây dựng | Đồ án tốt nghiệp: HTML/CSS, Node.js, MySQL |

## Tất cả liên kết của Dương Đức Quân (DuongDucQuan)

### Website cá nhân

- [duongducquan.web.app](https://duongducquan.web.app)
- [duongducquan.netlify.app](https://duongducquan.netlify.app)
- [duongducquann.netlify.app](https://duongducquann.netlify.app)
- [duongducquan.github.io](https://duongducquan.github.io)
- [duongducquan.quand7194.workers.dev](https://duongducquan.quand7194.workers.dev) (Cloudflare Workers)
- Google Sites: DuongDucQuan285 (dán link Google Sites vào đây)

### Mạng xã hội

- [Facebook – DuongDucQuann](https://www.facebook.com/DuongDucQuann)
- [Facebook – duongducquan285](https://www.facebook.com/duongducquan285)
- [Facebook – duongducquan.dev](https://www.facebook.com/duongducquan.dev)
- [Facebook – duongducquancutidz285](https://www.facebook.com/duongducquancutidz285)
- [TikTok – @duongducquan285](https://www.tiktok.com/@duongducquan285)
- [LinkedIn – duongducquan](https://www.linkedin.com/in/duongducquan)

### GitHub và mã nguồn

- [github.com/duongducquan](https://github.com/duongducquan)
- [Repository DuongDucQuan](https://github.com/duongducquan/DuongDucQuan)

### Dự án trên Vercel

- [Quanduong](https://v0-quanduong.vercel.app)
- [Quannek](https://v0-quannek.vercel.app)
- [Giáng Sinh](https://v0-giangsinh.vercel.app)

### Công ty

- [MidSortWare / MID Việt Nam](https://midvietnam.com/vi)

---

© 2026 Dương Đức Quân – DuongDucQuan (duongducquan). Cập nhật ngày 05/11/2026.