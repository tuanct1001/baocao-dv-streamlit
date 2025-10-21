# 📊 Báo cáo Doanh thu Dịch vụ

Ứng dụng **Streamlit** giúp tổng hợp, phân tích và hiển thị báo cáo doanh thu dịch vụ từ hệ thống **HMS / HCR**.  
Hỗ trợ nhập file Excel, xử lý dữ liệu tự động và hiển thị trực quan các bảng thống kê, tỷ lệ và tổng hợp.

---

## 🚀 Cách chạy chương trình

### 1️⃣ Cài đặt môi trường
Yêu cầu Python **3.10+**

Clone hoặc tải repo này về máy:
```bash
git clone https://github.com/tuanct1001/baocao-dv-streamlit.git
cd baocao-dv-streamlit
Cài đặt thư viện:

bash
Copy code
pip install -r requirements.txt
2️⃣ Chạy ứng dụng
bash
Copy code
streamlit run kq_dtdv.py
Sau đó mở trình duyệt theo địa chỉ:

arduino
Copy code
http://localhost:8501
🗂 Cấu trúc thư mục
File	Mô tả
kq_dtdv.py	Mã nguồn chính của ứng dụng Streamlit
requirements.txt	Danh sách thư viện cần cài
.gitignore	Danh sách file bị bỏ qua khi commit
README.md	Mô tả dự án (file này)

💡 Tính năng chính
Đọc và xử lý file Excel báo cáo dịch vụ

Tính toán doanh thu phụ tùng, dầu, hao mòn, HCR

Hiển thị bảng tổng hợp trực quan trên giao diện web

Có thể chạy trực tiếp trên nội bộ hoặc deploy lên Streamlit Cloud

🧩 Công nghệ sử dụng
Python

Streamlit

Pandas / NumPy

OpenPyXL

📝 Giấy phép
Phát hành theo giấy phép MIT License — cho phép sử dụng, chỉnh sửa, chia sẻ tự do với ghi nhận nguồn.

📌 Tác giả: tuanct1001
