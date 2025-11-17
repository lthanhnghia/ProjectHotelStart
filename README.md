#  Hotel Management System + AI Chatbot (Spring Boot • React • Docker • Gemini)

Hệ thống quản lý khách sạn có tích hợp **AI Chatbot (Gemini)** tư vấn khách hàng, sử dụng **Docker Compose** và được deploy trên **Render / Vercel / TibiCloud** để thuận tiện chạy và thử nghiệm.

##  Features nổi bật
-  **AI Chatbot (Gemini API)** – hỗ trợ tư vấn, trả lời câu hỏi của khách hàng.
-  **Full-stack**: Spring Boot (BE) + React (FE) + MySQL.
-  **Docker Compose** – chỉ cần 1 lệnh để chạy toàn bộ hệ thống.
-  **Multi-deployment**:
  - Backend: Render
  - Frontend: Vercel
  - Database: TibiCloud
-  CRUD cơ bản (đặt phòng, lọc phòng trống, quản lý hồ sơ khách hàng).

---

#  1. Demo Deploy Online
> Không cần cài đặt – mở link là chạy được.

- **Backend (Render):** `https://hotelstarbe.onrender.com/api/ping`  
  > Lưu ý:Render (free-tier) sẽ “sleep” sau một thời gian không có request.
    Khi truy cập link trên trình duyệt, nếu server đã sẵn sàng bạn sẽ thấy "pong" ngay.
    Nếu server đang ngủ, cần chờ 5–6 phút để Render khởi động lại.
- **Frontend (Vercel):** `https://hotelstar.vercel.app/client/home`
- **AI Chatbot:** tích hợp sẵn trong giao diện

---

#  2. Chạy bằng Docker Compose
Yêu cầu:
- Docker Desktop

###  Khởi chạy
Mở terminal tại thư mục project và chạy:
```bash
docker-compose up --build
