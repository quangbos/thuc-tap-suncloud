- [Phần mềm tạo máy chủ ảo Vmware Workstation](#phần-mềm-tạo-máy-chủ-ảo-vmware-workstation)
  - [1. Giới thiệu về VMware Workstation](#1-giới-thiệu-về-vmware-workstation)
  - [2. Tầm quan trọng?](#2-tầm-quan-trọng)
  - [3. Các tính năng](#3-các-tính-năng)
  - [4. Hướng dẫn sử dụng](#4-hướng-dẫn-sử-dụng)
    - [4.1. Tải phần mềm](#41-tải-phần-mềm)
    - [4.2. Cách sử dụng phần mềm](#42-cách-sử-dụng-phần-mềm)
      - [4.2.1. Cách chỉnh sửa lại vào dọn rác máy ảo vào phần edit](#421-cách-chỉnh-sửa-lại-vào-dọn-rác-máy-ảo-vào-phần-edit)
      - [4.2.2. Cách cài VMW Tool đề có thể chuyển file hay thư mục từ máy thật sang máy ảo](#422-cách-cài-vmw-tool-đề-có-thể-chuyển-file-hay-thư-mục-từ-máy-thật-sang-máy-ảo)
      - [4.2.3. Cách kết nối mạng và các thiết bị vào máy ảo như DVD,Vm](#423-cách-kết-nối-mạng-và-các-thiết-bị-vào-máy-ảo-như-dvdvm)
      - [4.2.4. Cách tạo bảo sao cho văn bản](#424-cách-tạo-bảo-sao-cho-văn-bản)
    - [4.3. Tải file ISO Windowns 10 cho máy ảo](#43-tải-file-iso-windowns-10-cho-máy-ảo)
    - [4.4.  Cài windowns 10  vào phần mềm VMware của bạn](#44--cài-windowns-10--vào-phần-mềm-vmware-của-bạn)

# Phần mềm tạo máy chủ ảo Vmware Workstation 
## 1. Giới thiệu về VMware Workstation
- VMware là phần mềm tạo máy ảo làm việc trên máy tính của bạn 
- VMware hoạt động độc lập nên đây sẽ là môi trường thích hợp để người dùng thử nghiệm vài hệ điều hành mới như Linux hoặc truy cập website có độ tin cậy thấp 
- Công dụng là hạn chế tối đa rủi ro ảnh hưởng đến hện điều hành của máy tinshh thật 
## 2. Tầm quan trọng?
- Cung cấp môi trường an toàn với người dùng thử nghiệm các ứng dụng mới hoặc cập nhật  hệ thống mà không làm hỏng hay ảnh hưởng tới hệ thống hiện đang chạy 

## 3. Các tính năng
- Bất kỳ hệ điều hành nao cũng có thể tạo máy ảo và thử nghiệm như hệ điều hành Linux,Windows..
- Hỗ trợ đa dạng hệ điều hành đám mây với các vùng chứa Docker,Kubernetes..
- Có thể thử nghiệm chạy cùng một lúc nhiều hệ điều hành khác nhau trên máy tính 
- Hoạt động trên máy ảo như chạy di chuyển , chia sẻ, kết nối dễ dàng 
- Tối đa hóa các phần cứng, năng suất cho phép dễ dàng thêm hoặc xóa máy tính ảo ra khỏi máy tính vật lý của bạn 
## 4. Hướng dẫn sử dụng 
### 4.1. Tải phần mềm 
- Chọn Next để tiếp tục cài đặt > Đánh dấu tick vào mục `I accept the terms in the License Agreement` và chọn **Next > Chọn Next > Chọn Next > Chọn Next > Bấm Install và chờ đợi > Bấm Finish**

[Link download]( https://download.com.vn/download/vmware-workstation-8587?linkid=83201)

### 4.2. Cách sử dụng phần mềm  

Tắt máy ảo thì có thể chọn 1 trong 2 cách sau:
- Chọn Power Off trên thanh công cụ của VM

- Chọn **Shut Down Guest**. Nếu tắt máy bằng cách này thì máy ảo sẽ tự động mở khi bạn đăng nhập vào VMware.

![example](/ANH/Screenshot_51.png)

- Power off để tắt máy ảo 

![example](/ANH/Screenshot_52.png)

#### 4.2.1. Cách chỉnh sửa lại vào dọn rác máy ảo vào phần edit

![example](/ANH/Screenshot_69.png)

#### 4.2.2. Cách cài VMW Tool đề có thể chuyển file hay thư mục từ máy thật sang máy ảo 

![example](/ANH/Screenshot_70.png)

- Sau đó sẽ xuất hiện DVD Drive  và click vào

![example](/ANH/Screenshot_71.png)

- Nhấn để cài đặt tool
- Ta nhấn Next rồi sau đó FInish 
 
#### 4.2.3. Cách kết nối mạng và các thiết bị vào máy ảo như DVD,Vm  

![example](/ANH/Screenshot_72.png)


#### 4.2.4. Cách tạo bảo sao cho văn bản 
Ta tắt máy ảo đi 
Rồi chọn VM rồi chọn SNAPSHOT rồi TAKESPAPSHOT

![example](/ANH/Screenshot_73.png) 


![example](/ANH/Screenshot_74.png)


![example](/ANH/Screenshot_75.png)

- Chọn **Take snapshot**
 
Ta có thể thay đổi tên rồi ấn **Take snapshot**

![example](/ANH/Screenshot_76.png)

- Muốn xóa ta nhấn vào tên snapshot  rồi nhấn Delete



### 4.3. Tải file ISO Windowns 10 cho máy ảo 
- Ta làm theo như hướng dẫn để tải file về và cài đặt 
[Link hướng dẫn](https://www.youtube.com/watch?v=sL0UMOAMXLA&t=0s)
### 4.4.  Cài windowns 10  vào phần mềm VMware của bạn 

![example](/ANH/Screenshot_53.png)

- Ta nên chọn **Custom** để tùy chỉnh thiết lập để cấu hình phù hợp với máy tính thật 
- 
![example](/ANH/Screenshot_54.png)

- Ta chọn **Next** 2 lần tiếp theo 
- Ta chọn để chỉnh sửa sau 

![example](/ANH/Screenshot_55.png)

- Tiếp theo ta chọn các phiên bản phù hợp cho windowns 10 64bit 

![example](/ANH/Screenshot_56.png)

- Làm như trên hình và tùy chỉnh chọn file lưu trữ sau đó ấn *NEXT*

![example](/ANH/Screenshot_57.png)
- Ấn Next

![example](/ANH/Screenshot_58.png)
- Ta nên chọn số nhân và số luồng nhỏ hơn so với máy tính thật 
- khuyến cáo nên để 2x2

![example](/ANH/Screenshot_59.png)

- Các bước tiếp theo ta nhấn Next 
- Ta nên nhấn theo gợi ý của phần mềm 

![example](/ANH/Screenshot_60.png)

![example](/ANH/Screenshot_61.png)
- Ta next các bước tiếp và finish .Vậy là ta đã tạo song máy ảo 
- Các thông số của máy ảo 
- Ta có thể tùy chỉnh các thông số của máy vào mục **Edit virtual machine** 
- Tiếp theo ta thêm file Iso vào vmare

![example](/ANH/Screenshot_61.png)

![example](/ANH/Screenshot_62.png)

- CHọn thư mục đã lưu ISO tải về trước đó rồi ấn OK

 ![example](/ANH/Screenshot_64.png)

- Ta khởi chạy máy ảo 

![example](/ANH/Screenshot_65.png)

``CTRL ALT để tắt hoặc 
  CTRL + G để điều khiển chuột ``

- Ta chọn Next đến phần Password 

![example](/ANH/Screenshot_66.png) 


![example](/ANH/Screenshot_67.png)

Các bước tiếp theo ta làm như màn hình của máy ảo 

- Hoàn thành cài đặt máy ảo 

![example](/ANH/Screenshot_68.png)



