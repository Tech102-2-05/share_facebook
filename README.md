# SHARE Facebook Auto [PRO]

## 📝 Giới thiệu

**SHARE Facebook Auto [PRO]** là công cụ tự động chia sẻ bài viết Facebook sử dụng cookie tài khoản, giúp bạn tăng tương tác, viral hoặc hỗ trợ các chiến dịch marketing nhanh chóng, hiệu quả.

---

## 🚀 Tính năng nổi bật

- Tự động share bài viết Facebook theo ID
- Hỗ trợ nhiều tài khoản cùng lúc (qua file cookies)
- Tùy chỉnh số lượng share, delay giữa các lần share
- Giao diện dòng lệnh đơn giản, dễ sử dụng
- Báo trạng thái thành công trực tiếp

---

## ⚙️ Yêu cầu hệ thống

- Python 3.7 trở lên
- Hệ điều hành: Windows, Linux, MacOS
- Kết nối Internet ổn định
- Cài đặt các thư viện:
  - `requests`
  - `pystyle`

---

## 🛠️ Hướng dẫn cài đặt

1. **Tải mã nguồn về máy**

   ```bash
   git clone https://github.com/thangthugian/tools_share.git
   cd tools_share
   ```

2. **Cài đặt thư viện cần thiết**
   ```bash
   pip install -r requirements.txt
   ```
   Nếu chưa có file `requirements.txt`, bạn có thể cài thủ công:
   ```bash
   pip install requests pystyle
   ```

---

## 📂 Chuẩn bị file cookies

- Tạo file text (ví dụ: `cookies.txt`) chứa mỗi dòng là 1 cookie Facebook hợp lệ.
- Không để dòng trống cuối file.

**Ví dụ nội dung file cookies.txt:**

```
c_user=xxx;xs=xxx;datr=xxx;... (cookie tài khoản 1)
c_user=yyy;xs=yyy;datr=yyy;... (cookie tài khoản 2)
```

---

## ▶️ Hướng dẫn sử dụng

1. **Chạy tool**

   ```bash
   python main.py
   ```

2. **Nhập các thông tin theo yêu cầu:**

   - **Tên file chứa Cookies:** Nhập tên file bạn đã chuẩn bị (ví dụ: `cookies.txt`)
   - **ID Cần Share:** Nhập ID bài viết hoặc trang Facebook cần share, hoặc có thể lấy qua [link này](https://id.traodoisub.com)
   - **Delay Share (giây):** Thời gian chờ giữa các lần share (ví dụ: 3)
   - **Bao Nhiêu Share Thì Dừng Tool:** Số lượng share tối đa muốn thực hiện

3. **Theo dõi trạng thái trên màn hình.**

---

## 🧩 Giải thích các tham số

- **Cookies:** Cookie tài khoản Facebook, lấy từ trình duyệt (khuyến nghị dùng tài khoản phụ, tránh tài khoản chính)
- **ID Cần Share:** ID bài viết/trang cần share (có thể lấy bằng cách copy link và lấy dãy số phía sau `posts/` hoặc `videos/`)
- **Delay Share:** Đặt thời gian nghỉ giữa các lần share để tránh checkpoint (khuyến nghị 3-10 giây)
- **Số lượng share:** Số lần share tối đa, tool sẽ tự dừng khi đạt số này

---

## 💡 Ví dụ sử dụng

```
Tên file chứa Cookies: cookies.txt
ID Cần Share: 1234567890123456
Delay Share (giây): 5
Bao Nhiêu Share Thì Dừng Tool: 20
```

---

## 🔒 Lưu ý bảo mật

- _Không dùng tài khoản Facebook chính để tránh bị khóa hoặc checkpoint_
- Không chia sẻ file cookies cho người khác, cookies đã sử dụng sẽ die sao một thời gian cần lấy lại bằng phiên đăng nhập khác.
- Tool chỉ phục vụ mục đích cá nhân, không sử dụng cho các hành vi vi phạm pháp luật hoặc spam

---

# Hướng dẫn cách lấy cookies

> Trên máy tính, truy cập vào thanh tìm kiếm và tìm _Get Token Cookie_ làm theo hướng dẫn và dùng _nick facebook clone_ để lấy cookies của phiên đăng nhập đó.

---

> Trên mobile tải ứng dụng _MonokaiToolkit Pro_ và đăng nhập vào nick facebook clone, sao đó tìm cookies và sao chép.

---

# 😀 Hỗ trợ

- Mọi thắc mắc và hỗ trợ vui lòng liên hệ với tôi qua:
  > [Facebook](https://facebook.com/thangthugian)

---

> [Gmail](mailto:dizzfeed@gmail.com)

**Chúc bạn sử dụng tool hiệu quả!**
