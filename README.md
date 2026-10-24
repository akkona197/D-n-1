# Trang web giới thiệu cá nhân

Dự án môn học năm nhất: trang web một trang giới thiệu thông tin cá nhân.

Demo: https://test-umber-psi-98.vercel.app

## Thông tin dự án

| Mục | Nội dung |
|---|---|
| Sinh viên | [Họ và tên] |
| MSSV | [Mã số sinh viên] |
| Lớp | [Lớp] |
| Trường | Đại học Trà Vinh |
| Môn học | [Tên môn học] |
| Giảng viên hướng dẫn | [Tên giảng viên] |

## Công nghệ sử dụng

| Thành phần | Công nghệ | Phiên bản |
|---|---|---|
| Framework | Next.js (App Router) | 16.2.6 |
| Thư viện giao diện | React | 19 |
| Ngôn ngữ | TypeScript | 5.7.3 |
| CSS | Tailwind CSS | 4.2 |
| Component | shadcn/ui (Radix UI) | - |
| Biểu tượng | lucide-react | 0.564 |
| Quản lý gói | pnpm | - |
| Triển khai | Vercel | - |

## Cấu trúc thư mục

```
.
├── app/            Trang và layout (Next.js App Router)
├── components/     Các component giao diện
├── hooks/          Custom hooks
├── lib/            Hàm tiện ích
├── public/         Tài nguyên tĩnh (ảnh, icon)
├── styles/         CSS toàn cục
├── components.json Cấu hình shadcn/ui
├── next.config.mjs Cấu hình Next.js
├── postcss.config.mjs
├── tsconfig.json
└── package.json
```

## Yêu cầu môi trường

- Node.js 20.9 trở lên
- pnpm

## Chạy dự án trên máy

```bash
# 1. Tải mã nguồn
git clone https://github.com/akkona197/D-n-1.git
cd D-n-1

# 2. Cài thư viện
pnpm install

# 3. Chạy chế độ phát triển
pnpm dev
```

Mở http://localhost:3000 để xem trang web.

## Các lệnh

| Lệnh | Chức năng |
|---|---|
| `pnpm dev` | Chạy server phát triển |
| `pnpm build` | Build bản production |
| `pnpm start` | Chạy bản đã build |
| `pnpm lint` | Kiểm tra lint |

## Triển khai

Dự án được triển khai trên Vercel. Mỗi lần push lên nhánh `main`, Vercel build và cập nhật lại trang demo.

## Giấy phép

Sản phẩm phục vụ mục đích học tập.
