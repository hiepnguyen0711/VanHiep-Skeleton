## Xin chào tôi là Nguyễn Văn Hiệp,

#### # SkeletonThư viện Skeleton này chỉ sử dụng HTML/CSS hiện tại đang còn phát triển 

Đầu tiên các bạn import **CSS** vào trên thẻ  `</head>` và **JS** trước `</body>`

```html
<link rel="stylesheet" href="templates/css/vh-skeleton.css">
```
```javascript
<script src="templates/js/vh-skeleton.js"></script>
```

Sau đó các bạn **khởi tạo** bằng cách gọi hàm  `initializeVHSkeleton();`

    <script>
     document.addEventListener("DOMContentLoaded", function() {
            initializeVHSkeleton();
       });
    </script>
### Hướng dẫn Sử dụng:
- Đối với hình ảnh: Thêm thẻ `<div>` có class "**vh-skeleton vh-skeleton-image**" trước thẻ `<img>` hình ảnh, ví dụ code dưới    `<div class="vh-skeleton vh-skeleton-image"></div>` :

```php
<div class="j-design-product-detail-content-image-main ratio ratio-21x9 mb-3 mb-lg-4 ">
        <a href="anh.png" data-fancybox>
              <div class="vh-skeleton vh-skeleton-image"></div>
              <img src="anh.png" alt="anh">
        </a>
</div>
```
- **Đối với văn bản:** Thêm class "**vh-skeleton-container**" bao bọc đoạn văn bản, bên trong thì thêm thẻ  `<div class="vh-skeleton vh-skeleton-text"></div>` , ví dụ cụ thể:

```php
<h3 class="vh-skeleton-container">
       xin chào tôi là văn hiệp
       <div class="vh-skeleton vh-skeleton-text"></div>
</h3>
```
##### Ví dụ khác:
```php
 <div class="j-design-product-detail-content-item-box-des vh-skeleton-container">
       Xin chào tôi là văn hiệp
      <div class="vh-skeleton vh-skeleton-text"></div>
</div>
```
### Ảnh minh họa:

[![ảnh 2](https://i.imgur.com/CNvOdtm.png "ảnh 2")](https://i.imgur.com/CNvOdtm.png "ảnh 2")

[![ảnh](https://i.imgur.com/uNUKMeD.png "ảnh")](https://i.imgur.com/uNUKMeD.png "ảnh")


------------
###### Link Facebook liên hệ: https://www.facebook.com/G.N.S.L.7/
Nếu các bạn thấy hữu ích hãy donate tôi ly cà phê :smile:
- Số Tk: 0601 5576 3127
- Họ tên: NGUYEN VAN HIEP
- Ngân hàng : Sacombank
- Chi nhánh: PGD LÊ VĂN QUỚI

