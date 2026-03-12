htmlreference.io
=> tra các thẻ inline blcok

- css referene.io
  => tra css

## các thẻ html trong nhóm block

- 1. thẻ heading
     tác dụng: thể hiện các tiêu đề được nhấn mạnh trên web thể càng bé kích thước càng lớn độ ưu tiên cao

```html

```

lưu ý : trên 1 trang web chỉ được 1 thẻ h1
h2 h3 h4 tùy theo phân cấp nội dung

2. thẻ đoạn văn
   chỉ chứa đoạn văn

</br> dùng để ngắt văn bản

3. thẻ danh sách

```html
<ul>
  <li></li>
</ul>
```

thẻ k có thứ tự

```html
<ol>
  <li></li>
</ol>
```

thẻ có thứ tự

4. thẻ phân chia khu vực Div

- thẻ này là thẻ non -semantic
  => tác dụng nhóm các thẻ khác để chia bố cục trang web

5. thẻ trích dẫn (blockquote)
   => trích dẫn nội dung từ trang web khác hoặc câu nói người nổi tiếng

## các thẻ trong nhóm inline

1.  thẻ liên kết (a=anchor)
    <a href = "địa chỉ trang web">nội dung hiển thị</a>

    target : mục tiêu khi mở liên kết

    - `_self`: mở tab hiện tại
    - `_blank`: mở tab mới

- title: khi trỏ chuột sẽ có tên trang web

2. thẻ chèn hình ảnh

```html
<img src="địa chỉ ảnh" alt="mô tả ảnh" />
```

- title : tiêu đề

3. 1 số thể định dạng văn bản

```html
<b>in đậm</b>
<i>nghiên</i>
<u>gạch chân</u>
<s>gạch ngang</s>
```

4. thẻ định dạng kiểu

```html
spam
```

thẻ non-semantic

- đảm bảo tính inline của 1 thẻ html

5. 1 số thể công thức toán học

- sub -> dưới
- sup -> trên

6. table
7. form

- dùng để gửi dữ liệu lên server
- cấu tạo bao gồm danh sách các trường
- nút gửi
  lưu ý: các form phải ngang hàng với nhau không được lồng

- nhóm 1:
  các trường nhập liệu 1 dòng

* text : nhập bất khì nội dung nào
* eamil: kiểm tra định dạng email
* password: mã hóa
* number: chỉ nhập số

- các trường chọn file
- hộp cho

* checkbox : cho phép chọn nhiều
* radio : chọn 1 trong 1 nhóm
