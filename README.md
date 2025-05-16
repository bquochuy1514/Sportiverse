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

## 🗄️ DATABASE SCHEMA

-   👤 **Người dùng & Xác thực:**

    -   `users`: Thông tin người dùng – tên, email, mật khẩu, vai trò, địa chỉ, avatar,...
    -   `social_accounts`: Đăng nhập bằng Google, Facebook, v.v.

-   🏷️ **Môn thể thao & Danh mục sản phẩm:**

    -   `sports`: Danh sách môn thể thao – bóng đá, bóng rổ,...
    -   `categories`: Danh mục sản phẩm theo từng môn thể thao. Hỗ trợ phân cấp danh mục cha/con.

-   🛍️ **Sản phẩm & Hình ảnh:**

    -   `products`: Thông tin sản phẩm – tên, mô tả, giá, tồn kho, nổi bật,...
    -   `product_images`: Nhiều hình ảnh cho một sản phẩm, có thể đánh dấu ảnh chính.

-   ❤️ **Danh sách yêu thích & Đánh giá:**

    -   `wishlists`: Danh sách sản phẩm yêu thích của người dùng.
    -   `reviews`: Người dùng đánh giá và bình luận sản phẩm (1–5 sao).

-   🛒 **Giỏ hàng & Đơn hàng:**

    -   `carts`: Giỏ hàng của người dùng (kể cả khách chưa đăng nhập).
    -   `cart_items`: Sản phẩm trong giỏ hàng với số lượng cụ thể.
    -   `orders`: Đơn hàng gồm địa chỉ, trạng thái, thanh toán, giảm giá,...
    -   `order_items`: Chi tiết sản phẩm trong mỗi đơn hàng.

-   🎁 **Mã giảm giá:**

    -   `coupons`: Mã khuyến mãi theo phần trăm hoặc số tiền cố định. Có giới hạn, điều kiện áp dụng, thời gian hiệu lực.

-   ⚙️ **Công nghệ hỗ trợ:**
    -   Hỗ trợ **soft delete** trên các bảng: `users`, `products`, `orders`.
    -   Sử dụng **slug** cho SEO: `sports`, `categories`, `products`.
    -   Thiết kế chuẩn quan hệ **khóa ngoại**, đảm bảo dữ liệu chặt chẽ.
