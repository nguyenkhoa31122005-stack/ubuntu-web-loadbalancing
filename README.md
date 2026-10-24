# Ubuntu Web Load Balancing System

Hệ thống cân bằng tải (Load Balancing) cho ứng dụng Web sử dụng Nginx Reverse Proxy và Docker Compose trên Ubuntu Server.

## 🚀 Kiến trúc hệ thống
- **Nginx Load Balancer**: Đóng vai trò Reverse Proxy nhận request từ khách hàng và phân phối đều tới các Web Backend.
- **Web Backend 1 & 2**: Các container Nginx chạy dịch vụ web (Phượt app/website).

## 🛠️ Hướng dẫn triển khai
1. Clone repository:
   ```bash
   git clone [https://github.com/nguyenkhoa31122005-stack/ubuntu-web-loadbalancing.git](https://github.com/nguyenkhoa31122005-stack/ubuntu-web-loadbalancing.git)
   cd ubuntu-web-loadbalancing
