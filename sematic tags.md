HTML5 giới thiệu nhiều thẻ ngữ nghĩa (semantic tags) mới, giúp cải thiện cấu trúc và ý nghĩa của tài liệu HTML. Các thẻ ngữ nghĩa này giúp trình duyệt và các công cụ tìm kiếm hiểu rõ hơn về nội dung và cấu trúc của trang web. Dưới đây là danh sách các thẻ ngữ nghĩa trong HTML5 và các trường hợp sử dụng chúng:

### 1. `<header>`
**Mô tả:** Thẻ này được sử dụng để chứa các nội dung phần đầu của một tài liệu hoặc một phần của tài liệu. Nó thường bao gồm logo, tiêu đề, và các liên kết điều hướng chính.

**Trường hợp sử dụng:**
- Làm phần đầu trang của website.
- Làm phần đầu của một phần hoặc bài viết trong một trang web.

**Ví dụ:**
```html
<header>
  <h1>My Website</h1>
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>
```

### 2. `<nav>`
**Mô tả:** Thẻ này chứa các liên kết điều hướng, thường là một menu hoặc danh sách các liên kết để dẫn tới các phần khác của trang hoặc tới các trang khác.

**Trường hợp sử dụng:**
- Menu điều hướng chính của trang web.
- Điều hướng phụ trong một phần cụ thể của trang.

**Ví dụ:**
```html
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#services">Services</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
```

### 3. `<section>`
**Mô tả:** Thẻ này đại diện cho một phần hoặc một đoạn của tài liệu, và thường bao gồm một tiêu đề.

**Trường hợp sử dụng:**
- Chia tài liệu thành các phần rõ ràng và có ý nghĩa.
- Tạo các phần khác nhau trong một bài viết hoặc một trang web.

**Ví dụ:**
```html
<section>
  <h2>About Us</h2>
  <p>We are a company that values...</p>
</section>
```

### 4. `<article>`
**Mô tả:** Thẻ này đại diện cho một khối nội dung tự chứa, độc lập và có thể được phân phối riêng lẻ. Thường được dùng cho bài viết, blog, bình luận, bài đăng diễn đàn, v.v.

**Trường hợp sử dụng:**
- Bài viết blog.
- Bình luận hoặc bài đăng trên diễn đàn.
- Bài viết tin tức.

**Ví dụ:**
```html
<article>
  <h2>New Features in HTML5</h2>
  <p>HTML5 introduces a range of new elements...</p>
</article>
```

### 5. `<aside>`
**Mô tả:** Thẻ này chứa nội dung phụ, không liên quan trực tiếp đến nội dung chính. Thường được dùng cho các ghi chú, liên kết liên quan, hoặc quảng cáo.

**Trường hợp sử dụng:**
- Thanh bên với các liên kết hoặc thông tin phụ.
- Các ghi chú hoặc liên kết đến các tài liệu liên quan.

**Ví dụ:**
```html
<aside>
  <h3>Related Articles</h3>
  <ul>
    <li><a href="#article1">Understanding HTML5</a></li>
    <li><a href="#article2">CSS Tips and Tricks</a></li>
  </ul>
</aside>
```

### 6. `<footer>`
**Mô tả:** Thẻ này đại diện cho phần cuối của tài liệu hoặc phần của tài liệu. Thường chứa thông tin bản quyền, liên kết tới chính sách bảo mật, thông tin liên hệ, v.v.

**Trường hợp sử dụng:**
- Chân trang của website.
- Chân trang của một phần hoặc bài viết.

**Ví dụ:**
```html
<footer>
  <p>&copy; 2024 My Website</p>
  <p><a href="#privacy">Privacy Policy</a> | <a href="#terms">Terms of Service</a></p>
</footer>
```

### 7. `<main>`
**Mô tả:** Thẻ này chứa nội dung chính duy nhất của tài liệu, tức là nội dung có liên quan trực tiếp đến nội dung chính của tài liệu.

**Trường hợp sử dụng:**
- Phần chính của một trang web, nơi chứa nội dung chính mà người dùng đang tìm kiếm.

**Ví dụ:**
```html
<main>
  <h2>Main Content</h2>
  <p>This is the main content of the page...</p>
</main>
```

### 8. `<figure>` và `<figcaption>`
**Mô tả:** Thẻ `<figure>` được sử dụng để chứa nội dung minh họa như hình ảnh, biểu đồ, hoặc mã nguồn, và `<figcaption>` là thẻ để thêm chú thích cho nội dung trong `<figure>`.

**Trường hợp sử dụng:**
- Chèn hình ảnh hoặc biểu đồ với chú thích.
- Chèn đoạn mã với chú thích.

**Ví dụ:**
```html
<figure>
  <img src="example.jpg" alt="Example Image">
  <figcaption>Figure 1: An example image.</figcaption>
</figure>
```

### 9. `<mark>`
**Mô tả:** Thẻ này dùng để đánh dấu văn bản quan trọng hoặc làm nổi bật văn bản được tìm kiếm.

**Trường hợp sử dụng:**
- Làm nổi bật văn bản khi tìm kiếm.
- Đánh dấu văn bản quan trọng cần chú ý.

**Ví dụ:**
```html
<p>This is a <mark>highlighted</mark> text.</p>
```

### 10. `<time>`
**Mô tả:** Thẻ này đại diện cho ngày và giờ hoặc khoảng thời gian.

**Trường hợp sử dụng:**
- Định dạng ngày hoặc thời gian trong tài liệu.
- Hiển thị thời gian sự kiện.

**Ví dụ:**
```html
<time datetime="2024-06-09">June 9, 2024</time>
```

### 11. `<details>` và `<summary>`
**Mô tả:** Thẻ `<details>` chứa thông tin bổ sung mà người dùng có thể mở rộng hoặc thu gọn, và `<summary>` cung cấp tóm tắt ngắn gọn cho nội dung này.

**Trường hợp sử dụng:**
- Tạo các phần nội dung có thể mở rộng/thu gọn, ví dụ như mục hỏi đáp.
- Hiển thị thông tin chi tiết khi người dùng muốn tìm hiểu thêm.

**Ví dụ:**
```html
<details>
  <summary>More information</summary>
  <p>Here is some more information...</p>
</details>
```

### 12. `<dialog>`
**Mô tả:** Thẻ này được sử dụng để tạo các hộp thoại hoặc các cửa sổ mô-đun chứa thông tin tương tác.

**Trường hợp sử dụng:**
- Hộp thoại xác nhận.
- Cửa sổ thông báo hoặc tương tác.

**Ví dụ:**
```html
<dialog open>
  <p>This is a dialog box.</p>
  <button>Close</button>
</dialog>
```

Những thẻ ngữ nghĩa này giúp tài liệu HTML trở nên rõ ràng và có cấu trúc hơn, giúp cải thiện SEO và trải nghiệm người dùng. Khi sử dụng, hãy cân nhắc tới ngữ cảnh và mục đích của nội dung để chọn thẻ phù hợp.