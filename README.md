# Báo cáo Bài tập Lập trình Web

## Bài tập 1: Triển khai hạ tầng Docker & Reverse Proxy
- **Dịch vụ sử dụng:** Nginx, Node-RED, MariaDB, phpMyAdmin, Cloudflared (`docker-compose.yml`).
- **Cấu hình tên miền (`nginx/conf.d/domains.conf`):**
  - Website 1: https://web1.bt1.id.vn
  - Website 2: https://web2.bt1.id.vn

## Bài tập 2: Xây dựng API trên Node-RED & Tích hợp Frontend
- **API Endpoint:** `GET https://web1.bt1.id.vn/api/tacke` (hỗ trợ lọc tham số `?min=...`).
- **Source code Node-RED:** `nodered/flows.json`.
- **Giao diện Frontend gọi API (`fetch`):** `www/site1/index.html`.
