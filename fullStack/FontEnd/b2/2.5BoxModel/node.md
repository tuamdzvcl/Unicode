#box moudel

##boder
boder = with +style + color

-boder-{side}-width
-boder-{side}-style
-boder-{side}-color

- thuộc tính gộm
  -border:width style color
  -border-{side}:width style color

## padding - phầm đệm

-không có giá trị âm
-không có giá trị auto
thuộc tính
padding-top
padding-left
padding-right
padding-bottom

Lưu ý :
-Nếu dùng đơn vị phần trăm , padding tỷ lệ theo width của thẻ cha
-padding-top và padding-bottom chỉ hoạt động với thẻ blook còn inline thì k

- cần phải chuyển thành block ,display block , inlina-block

## margin

- căn lề
  -Nếu dùng đơn vị phần trăm , padding tỷ lệ theo width của thẻ cha
  -padding-top và padding-bottom chỉ hoạt động với thẻ blook còn inline thì k
- giá trị auto chỉ khả dụng với thẻ block

##box-sizing

- quyết định kích thức của box theo conten hay border 

-box-sizing = contentbox(Mặc định)
-width mới = width conten + padding + border

## width , height
-Chỉ áp dụng được với thẻ block 
- đơn vị 
%: Tỷ lệ theo kích thước của thẻ cha  
vw : tỷ lệ theo chiều rộng của viewport
vh: tỷ lệ theo chiều cao của viewport

thuộc tính 
-min width max width
-min height và max height 

## boder-radius

-tạo bo góc cho phần tử html
-Nếu dùng đơn vị phần trăm 
+hình vông, border-radius >= 50% tự thành hình tròn
-Để tạo hiệu ứng ôm 2 bên : đặt border-radius có giá trị lớn hơn hoặc bằng chiều cao 
