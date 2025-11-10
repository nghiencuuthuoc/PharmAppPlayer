# PharmAppPlayer v16.5.x

PharmAppPlayer là **trình phát video & bài giảng offline** dạng portable, phù hợp cho:
- Học Y học cổ truyền, dược, đào tạo nội bộ
- Quản lý nhiều thư mục video lớn
- Ghi nhớ vị trí xem dở, phụ đề, tìm kiếm nhanh

Không cần cài đặt phức tạp – chỉ 1 file `.exe` là sử dụng.

---

## 1. Cài đặt

1. Tạo thư mục dành cho chương trình, ví dụ:
   ```text
   D:\PharmAppPlayer\
````

2. Chép file:

   ```text
   PharmAppPlayer_v16.5.x.exe
   ```

   vào thư mục trên.

3. Chuẩn bị thư mục chứa video, ví dụ:

   ```text
   D:\YHCT_VIDEO\
   ```

   Có thể chia thành nhiều thư mục con:

   ```text
   D:\YHCT_VIDEO\duocthucdung1\
   D:\YHCT_VIDEO\duocthucdung2\
   ...
   ```

4. (Tuỳ chọn) Đặt file phụ đề `.srt` hoặc `.vtt` **trùng tên** với file video
   để chương trình tự nhận.

---

## 2. Khởi động & chọn thư mục

1. **Mở chương trình**
   Double–click `PharmAppPlayer_v16.5.x.exe`.

2. **Chọn thư mục video**

   * Bấm **“Open Folder [Ctrl+O]”**.
   * Chọn thư mục gốc chứa video (vd: `D:\YHCT_VIDEO`).
   * Danh sách video sẽ hiển thị ở bảng phía dưới.

3. **Phát video**

   * Chọn một dòng trong bảng rồi double–click hoặc bấm Play.
   * Thông tin tiêu đề, thời gian, phụ đề sẽ hiện phía trên.

---

## 3. Các nút điều khiển

### Left Controls

* **Open Folder [Ctrl+O]** – Chọn thư mục chứa video.
* **Open static.json [Ctrl+J]** – Mở file cấu hình/danh sách (dành cho quản trị).
* **Rescan [F5]** – Quét lại khi có thêm/bớt video.
* **Set Image [Ctrl+I]** – Chọn hình nền cố định.
* **Random Img** – Đổi hình nền ngẫu nhiên.

### Right Controls

* **Prev [Ctrl+←]** – Video trước.
* **Play/Pause [Space]** – Phát / Tạm dừng.
* **Next [Ctrl+→]** – Video kế tiếp.
* **Stop [S]** – Dừng phát.
* **Repeat [R]** – Bật/Tắt lặp lại.
* **Shuffle [H]** – Bật/Tắt phát ngẫu nhiên.

### Thanh công cụ giữa

* **Search** – Gõ từ khoá để lọc nhanh theo tiêu đề.
* **Sort** – Sắp xếp (vd: theo tên A–Z).
* **Folder (dropdown)** – Chọn nhanh thư mục con.
* **Vol + thanh trượt** – Chỉnh âm lượng.
* **Static write** – (Quản trị) Cho phép lưu cấu hình/danh sách.

### Phụ đề

* **Load Sub [Ctrl+L]** – Chọn file phụ đề thủ công.
* **Sub: On [Ctrl+K]** – Bật/Tắt phụ đề.
* **A- [Ctrl+-] / A+ [Ctrl+=]** – Giảm/Tăng cỡ chữ phụ đề.
* **Delay -5s / Delay +5s** – Lùi/Tiến thời gian phụ đề cho khớp tiếng.

### Bảng danh sách video

Hiển thị:

* **#** – Số thứ tự
* **Title** – Tên video/bài giảng
* **Folder** – Thư mục chứa
* **Duration / Size / Modified** – Thời lượng, dung lượng, ngày cập nhật

---

## 4. Tóm tắt phím tắt

* `Ctrl+O` – Chọn thư mục
* `F5` – Quét lại
* `Space` – Play/Pause
* `Ctrl+←` / `Ctrl+→` – Video trước / kế
* `S` – Dừng
* `R` – Lặp lại
* `H` – Ngẫu nhiên
* `Ctrl+L` – Chọn phụ đề
* `Ctrl+K` – Bật/Tắt phụ đề
* `Ctrl+-` / `Ctrl+=` – Đổi cỡ chữ phụ đề

---

## 5. Gợi ý triển khai cho trung tâm / đơn vị

* Mỗi khoá học dùng một thư mục riêng:

  * `YHCT_VIDEO`, `DUOC_LY`, `NOI_BO_BV`, ...
* Đặt tên file rõ ràng:

  * `B01_Bao_che_thuoc_co_truyen.mp4`
  * `B02_...`
* Khi phát hành cho học viên:

  * Gửi trọn bộ thư mục video + `PharmAppPlayer_v16.5.x.exe` + `README_VI.md`.
  * Học viên chỉ cần mở `.exe` là dùng, không cần cài thêm phần mềm.

---

## 6. Hỗ trợ

Hỗ trợ kỹ thuật & tuỳ biến:

* **Website:** [https://nghiencuuthuoc.com](https://nghiencuuthuoc.com)


```

