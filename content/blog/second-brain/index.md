---
title: 🛠️ Nâng cao kiến thức cơ khí với hệ thống ghi chú thông minh
summary: Xây dựng kho kiến thức cá nhân về cơ khí và chia sẻ với đồng nghiệp.
date: 2023-10-26
authors:
  - admin
tags:
  - Cơ Khí
  - Ghi chú
  - Markdown
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

Xây dựng kho kiến thức cá nhân về cơ khí và chia sẻ với đồng nghiệp.

Hugo Blox web framework giúp bạn dễ dàng tạo hệ thống ghi chú linh hoạt, phù hợp cho kỹ sư và sinh viên ngành cơ khí.

Tạo kho kiến thức mạnh mẽ dựa trên các file Markdown đơn giản, dễ dàng lưu trữ các tài liệu kỹ thuật, bản vẽ, quy trình gia công, và kinh nghiệm thực tế.

Bạn có thể sử dụng hệ thống này để chia sẻ công khai trên website hoặc lưu trữ riêng tư trên GitHub, bảo vệ bằng mật khẩu cho cá nhân hoặc nhóm.

## Sơ đồ tư duy (Mindmaps)

Hugo Blox hỗ trợ mở rộng Markdown cho sơ đồ tư duy, rất hữu ích để tổng hợp quy trình sản xuất, phân tích lỗi, hoặc lập kế hoạch bảo trì máy móc.

Chỉ cần chèn một khối mã Markdown với nhãn `markmap` và tùy chọn chiều cao như ví dụ dưới đây:

```markmap {height="200px"}
- Quy trình gia công
  - Tiện
  - Phay
  - Hàn
  - Lắp ráp
```

Hiển thị như sau:

```markmap {height="200px"}
- Quy trình gia công
  - Tiện
  - Phay
  - Hàn
  - Lắp ráp
```

Một ví dụ nâng cao hơn với liên kết, định dạng và mã nguồn:

```markmap
- Cơ khí hiện đại
  - Tài liệu tham khảo
    - [Tiêu chuẩn ISO](https://www.iso.org/)
    - [Diễn đàn cơ khí](https://www.cokhivietnam.net/)
  - Kỹ năng
    - Đọc bản vẽ kỹ thuật
    - **Tính toán** ~~sai số~~ *dung sai*
    - `Mã CNC`
    -
      ```gcode
      G01 X10 Y20 F100
      ```
    - Công thức: $F = m \times a$
```

## Đánh dấu nổi bật

<mark>Đánh dấu</mark> thông tin quan trọng với thẻ `mark`:

```html
<mark>Thông tin cần chú ý</mark>
```

## Ghi chú nổi bật (Callouts)

Sử dụng [callouts](https://docs.hugoblox.com/reference/markdown/#callouts) để nhấn mạnh lưu ý, mẹo hoặc cảnh báo trong tài liệu kỹ thuật.

Ví dụ:

```markdown
{{%/* callout note */%}}
Kiểm tra dầu bôi trơn trước khi vận hành máy.
{{%/* /callout */%}}
```

Hiển thị như sau:

{{% callout note %}}
Kiểm tra dầu bôi trơn trước khi vận hành máy.
{{% /callout %}}

Hoặc sử dụng loại `warning` để cảnh báo:

{{% callout warning %}}
Luôn ngắt nguồn điện trước khi bảo trì thiết bị.
{{% /callout %}}

## Bạn thấy bài viết hữu ích? Hãy chia sẻ cho đồng nghiệp trong ngành cơ khí! 🙌

