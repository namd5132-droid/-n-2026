# 🚀 ElectroShop - Đồ Án Website Thương Mại Điện Tử

Hệ thống website thương mại điện tử công nghệ và thiết bị điện tử, xây dựng theo kiến trúc tách biệt **Frontend (React + Vite)** và **Backend (Laravel RESTful API)**.

---

## 📖 Tài Liệu Hướng Dẫn & Báo Cáo Đồ Án

- 📘 **Hướng dẫn chạy dự án chi tiết nhất**: [**HUONG_DAN_CHAY_PROJECT.md**](./HUONG_DAN_CHAY_PROJECT.md)
- 📑 **Báo cáo đồ án chuyên ngành (Markdown)**: [**BAO_CAO_DO_AN_CHUYEN_NGANH.md**](./BAO_CAO_DO_AN_CHUYEN_NGANH.md)
- 📝 **File Báo cáo Word hoàn chỉnh (.docx)**: [**Bao_Cao_Do_An_Duong_Van_Nam.docx**](./Bao_Cao_Do_An_Duong_Van_Nam.docx) *(và bản trên Desktop: `Báo cáo đồ án hoàn chỉnh - Dương Văn Nam.docx`)*

---

## ⚡ Khởi Chạy Nhanh Trên Windows (1-Click)

1. Đảm bảo dịch vụ **MySQL** (trong XAMPP hoặc Laragon) đã được bấm **Start**.
2. Nhấp đúp chuột vào file:
   - 👉 **`start_all.bat`** (Mở cả Backend và Frontend cùng lúc).
3. Mở trình duyệt vào: **http://localhost:5173**

---

## 🛠️ Khởi Chạy Thủ Công Bằng Dòng Lệnh

### 1. Backend (Laravel API)
```powershell
cd backend
composer install
php artisan migrate --seed
php artisan storage:link
php artisan serve
```
*Backend chạy tại: `http://127.0.0.1:8000`*

### 2. Frontend (React 19 + Vite)
```powershell
cd frontend
npm install
npm run dev
```
*Frontend chạy tại: `http://localhost:5173`*

---

## 🔑 Tài Khoản Quản Trị Viên Mặc Định (Admin)
- **Đường dẫn Admin**: [http://localhost:5173/admin](http://localhost:5173/admin)
- **Email**: `admin@electroshop.vn`
- **Mật khẩu**: `password123`
