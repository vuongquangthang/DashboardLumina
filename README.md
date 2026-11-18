# Lumina Beach Hotel — Dashboard Hiệu Quả Truyền Thông & Đặt Phòng

Báo cáo phân tích tương tác và bảng điều khiển dữ liệu hiệu quả chiến dịch Marketing & Đặt phòng (Mùa Hè 2026) của Lumina Beach Hotel.

## 🚀 Triển khai trên Vercel (Deployment)

Dự án này là một Single Page Application (HTML/CSS/JS thuần, dùng Tailwind CSS, Chart.js, Lucide Icons qua CDN).

### Cách 1: Deploy tự động qua GitHub (Khuyên dùng)
1. Đẩy code lên GitHub repository (`origin/main`).
2. Truy cập [Vercel Dashboard](https://vercel.com/new).
3. Đăng nhập tài khoản Vercel và chọn **Import Git Repository** (`DashboardLumina`).
4. Tại bước **Configure Project**:
   - **Framework Preset**: Chọn **Other** (hoặc để mặc định).
   - **Root Directory**: `./`
   - Nhấn **Deploy**.
5. Vercel sẽ tự động cấp một domain miễn phí dạng `https://<ten-du-an>.vercel.app`. Mỗi khi bạn push commit mới lên nhánh `main`, Vercel sẽ tự động build & deploy lại.

### Cách 2: Deploy qua Vercel CLI
```bash
# Cài đặt hoặc chạy trực tiếp qua npx
npx vercel

# Deploy lên môi trường production
npx vercel --prod
```

## 📁 Cấu trúc thư mục
- `index.html`: Trang dashboard chính (điểm vào mặc định của Vercel).
- `vercel.json`: Cấu hình điều hướng và tối ưu đường dẫn cho Vercel.
- `.gitignore`: Loại bỏ các file tạm, thư mục `.vercel`, v.v.
- `lumina_beach_hotel_interactive_marketing_booking_dashboard.html`: File dashboard gốc.
