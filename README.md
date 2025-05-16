<p align="center">
  <a href="https://www.uit.edu.vn/" title="Trường Đại học Công nghệ Thông tin" style="border: none;">
    <img src="https://i.imgur.com/WmMnSRt.png" alt="Trường Đại học Công nghệ Thông tin | University of Information Technology">
  </a>
</p>

<h1 align="center"><b>PHÁT TRIỂN ỨNG DỤNG WEB - IS207</b></h1>

## GIỚI THIỆU MÔN HỌC

-   **Tên môn học:** Phát triển ứng dụng Web
-   **Mã môn học:** IS207
-   **Mã lớp:** IS207.P22
-   **Năm học:** HK2 (2024 - 2025)
-   **Giảng viên:** Ths.Mai Xuân Hùng
-   **Email:** hungmx@uit.edu.vn

## GIỚI THIỆU ĐỒ ÁN

-   **Đề tài:** Trang web bán đồ thể thao đa môn - Sportiverse
-   **Repository:** [PHÁT TRIỂN ỨNG DỤNG WEB - IS207](https://github.com/bquochuy1514/Sportiverse)

## CÔNG NGHỆ SỬ DỤNG

-   **Backend:** [PHP](https://www.php.net/), [Laravel](https://laravel.com/)
-   **Frontend:** [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML), [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS), [JavaScript](https://www.javascript.com/), [ReactJS](https://reactjs.org/), [Tailwind CSS](https://tailwindcss.com/)
-   **Database:** [MySQL](https://www.mysql.com/)

## THÀNH VIÊN NHÓM

| STT | MSSV     | Họ và Tên            | GitHub                         | Email                  |
| :-- | :------- | :------------------- | :----------------------------- | :--------------------- |
| 1   | 23520594 | Bùi Quốc Huy         | https://github.com/LeHaGiaBao  | 23520594@gm.uit.edu.vn |
| 2   | 23520072 | Phan Hữu Việt Anh    | https://github.com/VietAnh1905 | 23520072@gm.uit.edu.vn |
| 3   | 23520376 | Nguyễn Khánh Duy     | https://github.com/GhetCodeSo1 | 23520376@gm.uit.edu.vn |
| 4   | 23521532 | Bùi Phan Thị Anh Thư | https://github.com/anhthu1102  | 23521532@gm.uit.edu.vn |

🗄️ Cơ sở dữ liệu (Database)
Dưới đây là danh sách các bảng chính được sử dụng trong hệ thống Sportiverse:

1. users – Người dùng
   Thông tin: tên, email, mật khẩu, vai trò, địa chỉ, số điện thoại, avatar...

Có xác thực email và hỗ trợ soft delete.

2. social_accounts – Tài khoản mạng xã hội
   Kết nối tài khoản Google, Facebook,... với user.

3. sports – Môn thể thao
   Dùng để phân loại các môn như bóng đá, bóng rổ, bơi lội,...

Có slug và icon để hỗ trợ SEO và giao diện.

4. categories – Danh mục sản phẩm
   Phân loại sản phẩm theo môn thể thao.

Hỗ trợ danh mục cha/con (cấu trúc phân cấp).

5. products – Sản phẩm
   Thông tin như tên, mô tả, giá, tồn kho, nổi bật,...

Có soft delete, hỗ trợ slug cho SEO.

6. product_images – Hình ảnh sản phẩm
   Cho phép một sản phẩm có nhiều hình ảnh.

Có thể đánh dấu hình ảnh chính.

7. carts & cart_items – Giỏ hàng và sản phẩm trong giỏ
   Giỏ hàng có thể thuộc về user hoặc guest.

Mỗi sản phẩm có số lượng đi kèm.

8. orders & order_items – Đơn hàng và chi tiết đơn hàng
   Gồm trạng thái đơn hàng, thông tin giao hàng, thanh toán,...

Lưu lịch sử giá từng sản phẩm khi đặt hàng.

9. coupons – Mã giảm giá
   Hỗ trợ theo phần trăm hoặc số tiền cố định.

Có điều kiện áp dụng, thời gian hiệu lực và giới hạn số lần sử dụng.

10. reviews – Đánh giá sản phẩm
    Người dùng có thể đánh giá và để lại nhận xét.

11. wishlists – Danh sách yêu thích
    Người dùng có thể lưu sản phẩm vào danh sách yêu thích để xem lại sau.
