#Tìm hiểu về ngôn ngữ Markdown và các đẩy lên web
##Khái niệm 
Được hiểu là công cụ để viết tài liệu kỹ thuật 
Ưu điểm : viết nhanh hơn vì format đơn giản ,khi copy paste cũng không lẫn như word 
 
**1.Cách viết tiêu đề**
đây là tiêu đề 1 của văn bản #
đây là tiêu đề 2 của văn bản ##
đây là tiêu đề 3 ###( tối đa 6 tiêu đề ) 

**2.Cách chấm đầu dòng**  
- đây là cách chấm đầu dòng 

**3.Cách viết số đầu dòng** 
1.day là cach viết số đầu dòng 1
2.day là cách viết số đầu dòng 2
**4.Cách viết in đậm**
** in đậm ** 
**5.Cách viết in nghiêng** 
*in nghiêng*
_in nghiêng_
*** in cả đậm cả nghiêng ***

**6.Cách để  gạch bỏ, xóa** 
~~xóa có dấu gạch~~

**7.Để dữ lại ký tự đặc biệt như * _**
\*\* đây là cách để giữ lại ký tự đặc biệt dấu sao  \*\*
\- đây là cách để giữ lại ký tự đặc biệt dấu gạch \-

**8.Cách tạo Quotation**
` tạo note có khung `
` Một ngày thật đẹp là ngày đi làm `

**9.Tạo bảng** 
| stt | cột 1 | cột 2 |
| --- | ----- | ----- |
| 1   | x21   | x22   |
| 2   | x31   | 32    |

**10.Cách code block** 
_Cách 1_
```c         
void main 
printf (“ đây là ví dụ code block”)          
end 
``` 
*Cách 2* 
Ta có thể nhấn phím **Tab**                          

**11.Cách tạo dấu gạch ngang dài** 
____
*** 
**12.Cách chèn link**

- Có thể chèn link bằng dấu ngoặc vuông và tròn như sau:
[ dây là link ](https://www.gggggg.com)

- Có thể tạo format cho link luôn: 
 <**https://www.gggggg.com**>

- Hoặc viết như thế này đề trông chuyên nghiệp hơn: 
[đây là google][1] là trang tìm kiếm nhớ cách ít nhất 1 dòng trống 

[1]:<https://www.gggggg.coccscs>

**13.Cách chèn hình ảnh** 
Để chèn ảnh trong vscode cần để ảnh cùng với folder với file Readme.md

! [example] (anh.png)   ( CÁCH 1)

< img src="link_anh_cua_ban"> ( CÁCH 2) 

**14.Cách vẽ biểu đồ** 
Dùng mermail 
[ mermaid](ttps:///gggg.com ) 
dùng PlanUML

**15.import file** 
@import"file"

**16.Math**

- Cần viết công thức toán cần đặt giữa 2 đầu \$ 

$\alpha$ 
$\varphi$
Số ở trên dưới : 
$x^2$    =x2

$ x^( 30y+) $

$x_1$  = x1

$ H_2SO_4 $

$ C_n^2 $  

Mũi tên $\to $ 

Dấu vô cùng  $\infty $ 

Phân số  $\ Frac (1)-(2) $ 

Căn thức $\sqrt (n) (k)$ 

Trang tạo code cho phần toán học : <**https://www.late4technics.com**>


# Cách đẩy code lên github 
- Tạo 1 cái tài khoản 
Đăng ký tài khoản trên trang  https://github.com  

 **Bước 1 : Vào Github desktop chọn Create New Repository**
Tạo 1 project 
<img src="/ANH/Screenshot_13.png">

- Đặt tên cho project 

![example](/ANH/Screenshot_2.png)

![example](/ANH/Screenshot_3.png)

**Bước 2 : Tạo 1 project trên file của máy tính tên là thuchanh**

![example](/ANH/Screenshot_4.png)

- Ta nhấn SAVE để code chuyển đến github desktop 
- Thông thường thì sẽ có 2 nhánh : main (code đã fix lỗi)
 ...................................................dev( nhánh chưa fix lỗi ) 

![example](/ANH/Screenshot_5.png)

Nhấn tải lên trang Web 
t nhấn _commit_ sau đó nhấn _Petch_
![example](/ANH/Screenshot_6.png)

**Bước 3 vào trang github.com**

![example](/ANH/Screenshot_7.png)
Chọn vào nhánh main để xem thông tin code đã được lên web hay chưa 
![example](/ANH/Screenshot_8.png)
![example](/ANH/Screenshot_9.png)
**Bước 4 Mời thành viên ( thành viên có thể tham gia vào để chỉnh sửa code trên web )**

- Vào Setting  Chọn  Manage access

![example](/ANH/Screenshot_10.png)
**Bước 5 Vai trò**

- Nhóm trưởng : có thể thay đổi code và cập nhật vào nhánh dev và main 
- Thành viên: Thay đổi code và cập nhật vào nhóm  dev 

 Nhóm trưởng thay đổi code
![example](/ANH/Screenshot_11.png)

Sau đó vào VS code
![example](/ANH/Screenshot_12.png)
Nếu code lỗi t có thể  ấn **DISCARD CHANGE**  để hủy bỏ thay đổi 
![example](/ANH/Screenshot_14.png)

Vào Github  desktop để thấy code hiện lên file 
Nhấn **COMIT**  để tải lên máy ảo của laptop 
sau đó nhấn  **Fetch** origin  để tải lên GitHUb 
**Bước 7 Thành viên thay đổi code  và nhánh dev** 

![example](/ANH/Screenshot_1.png)

- Để lưu file từ trên web về máy tính 
![example](/ANH/Screenshot_15.png)
- Sau đó Nhấn Fetch để lưu ngược lại 
![example](/ANH/Screenshot_16.png)
- Ta vào **VS** code để kiểm tra sự thay đổi
 ![example](/ANH/Screenshot_16.png)

- Cuối cùng thấy code đã ổn Nhóm trưởng lưu file vào main 

- Vào github desktop
<img src="/ANH/Screenshot_18.png">

<img src="/ANH/Screenshot_19.png">

- chọn nhánh Dev cập nhật vào Main 
- Nhấn commit sau rồi nhấn Petch 
- Cách thay đổi github từ private sang Public 
<**https://www.youtube.com/watch?v=tEwmIoU1NUg**>

