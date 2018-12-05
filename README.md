## Các phần mềm cần thiết bắt buộc cài đặt cho người mới bắt đầu 
 - [easyweb](https://easywebhub.com/)
 - [nodejs](https://nodejs.org/dist/v8.11.4/node-v8.11.4-x64.msi)
 - [github](https://github.com/git-for-windows/git/releases/download/v2.18.0.windows.1/Git-2.18.0-64-bit.exe)
 - [VScode](https://code.visualstudio.com/)
 - [totoisegit](https://download.tortoisegit.org/tgit/2.7.0.0/TortoiseGit-2.7.0.0-64bit.msi)
 - [easyweb tool](https://github.com/easywebhub/easyweb-tools )
 - [FSCapturet](http://www.faststone.org/FSCapturerDownload.htm) hoặc phần mềm  `paint` có sẵn trong windown ( phần mềm để chụp và sử lý ảnh )
 - [WinSCP](https://winscp.net/eng/download.php) + [putty](https://www.putty.org/) để deploy code lên server
  - `slack` để trao đổi trong nội bộ công ty 
  - `skype`,`zalo`,`facebook` để trao đổi với khách hàng
## kiến thức cơ bản
 - cách viết [markdown](https://viblo.asia/helps/cach-su-dung-markdown-bxjvZYnwkJZ) để báo cáo công việc hằng ngày cũng như trao đổi 
 - [gitlab](https://gitlab.com/vinaas/Tasks.git) (chứa thông tin các cuộc họp , kiến thứ tổng hợp ,kinh nghiệm ,vấn đề cũng như thông tin về dự án đã và đang thực hiện
 - kỹ năng gõ phím bằng mười ngón 
 - kỹ năng báo cáo vào cuối ngày,tuần ,tháng ,quý (sử dụng markdown)
 - các kiến thức cơ bản về hệ điều hành ( vd: cài đặt điều chỉnh màng hình ,các phím tắt cơ bản để xử lý nhanh vấn đề ,các lệnh cơ bản trên cmd   )
 - handlebar(đọc trong Handlebars)
 - truy xuất đối tượng cơ bản bằng handlebars (đọc trong Easyprotypw/syntax-easybuilding)

## I. Easyweb building
### Layout
 - layout partial : là một layout có thể sử dụng lại , Partial layout giúp loại bỏ lặp lại code bằng cách sử dụng lại cùng một partial layout ở nhiều layout khác. Chúng ta có thể sử dụng partial layout là một phần trong layout , cũng như nội dung layout khác
 - layout category : là layout sử dụng chung cho các phần tử trong category đó
 - layout tag :  là layout sử dụng chung cho các phần tử có cùng tag

 ### tag 
 ### Category 
 - category Name : tên của category bạn muốn tạo
 - Parent category : (có thể có hoặc không ) category bạn muốn tạo nằm trong category nào 
 - file name : easy tự động tạo ra một file .json chứa thông tin về định dạng của các thuộc tính trong category đó
 ### Page :
 - page title : tên của page bạn muốn tạo
 - layout : page đó sử dung layout nào 
 - category : page đó thuộc category nào
 - tag : bạn muốn đánh dấu page đó hay không , và đánh dấu nó bằn từ khóa nào để dễ dang nhận biết cũng như truy xuất 
 - page slug : easywev sẻ tự động tạo một file .md chứa nội dung của page bạn muốn tạo



## III. các phím tắt cơ bản thường gặp trong windown

- `Ctrl + C`  : sao chép mục đã chọn 
- `Ctrl + X`  : cắt mục đã chọn 
- `Ctrl + V`  : dán mục đã chọn 
- `Ctrl + Z`  : Hoàn tác một hành động
- `Ctrl + Y`  : Làm lại một hành động 
- `Ctrl + D` or `Delete`  : xóa mục đã chọn vào thùng rác
- `Shift + Delete`  :Xóa mục đã chọn mà không phải chuyển mục đó vào Thùng  rác trước   
- `F2`  :Đổi tên mục đã chọn 
- `Ctrl + `  : sao chép mục đã chọn 
- `Ctrl + A`  :  chọn tất cả các mục
- `Ctrl + Shift + nút lên / xuống`  : chọn khối văn bản bắt đầu trù con trỏ chuột đến các dòng kế tiếp 
- `F3`  : Tìm kiếm tệp hoặc thư mục
- `Atl + Enter`  : hiển thị thuộc tính cho mục đã chọn 
- `Ctrl + F4`  : Đóng tài liệu (cửa sổ or chương trình) đang hiện hoạt 
- `Atl + Tab`  : Chuyển đổi giữa các mục đang mở
- `Ctrl + Con lăn chuột`  : Thay đổi kích cỡ của các biểu tượng trên màn hình nền
- `Alt + Esc`  : Chuyển đổi giữa các mục theo thứ tự chúng được mở 
- `F5 (hoặc Ctrl + R)`  : Làm mới cửa sổ hiện hoạt
- `Esc`  : Hủy bỏ tác vụ hiện tại
- `Ctrl + Shift + Esc`  : Mở Trình quản lý Tác vụ
- `Ctrl + N`  : Mở cửa sổ mới 
- `Ctrl + W`  : Đóng cửa sổ hiện tại
- `Ctrl + Shift + N`  : Tạo thư mục mới 
- `F11`  : Phóng đại hoặc thu nhỏ cửa sổ hiện hoạt
- `Ctrl + Dấu chấm (.)`  : Xoay ảnh theo chiều kim đồng hồ
- `Ctrl + Dấu phẩy (,)`  :Xoay ảnh ngược chiều kim đồng hồ 
- `Alt + Mũi tên Phải`  : Xem thư mục tiếp theo 
- `Alt + Mũi tên Lên`  : Xem thư mục chính 
- `Ctrl + Shift + E`  : Hiển thị tất cả các thư mục phía trên thư mục đã chọn
- `Ctrl + Con lăn chuột`  : Thay đổi kích thước và diện mạo của biểu tượng tệp và thư mục 
- `Alt + D`  : Chọn thanh địa chỉ
- `Ctrl + E`  :  Chọn hộp tìm kiếm


## các phím tắt cơ bản thường gặp trong Paint có thể áp dụng cho photoshop
- `Ctrl + N`  : Tạo ảnh mới 
- `Ctrl + O`  : Mở ảnh hiện có 
- `Ctrl + S`  : Lưu thay đổi cho ảnh
- `F12`  :Lưu ảnh dưới dạng tệp mới 
- `Ctrl + P`  : In ảnh 
- `Alt + F4`  : Đóng ảnh và cửa sổ Vẽ 
- `Ctrl + Z`  : Hoàn tác thay đổi 
- `Ctrl + Y`  : Làm lại thay đổi
- `Ctrl + A`  : Chọn toàn bộ ảnh 
- `Ctrl + X`  : Cắt lựa chọn 
- `Ctrl + C`  : Sao chép lựa chọn vào Bảng tạm
- `Ctrl + V`  : Dán lựa chọn từ Bảng tạm
- `Esc`  : Hủy bỏ lựa chọn
- `Delete`  : Xóa lựa chọn
- `Ctrl + B`  : In đậm văn bản được chọn
- `Ctrl + +`  : Tăng độ rộng của chổi, đường thẳng hoặc viền hình dạng lên một điểm ảnh
- `Ctrl + -`  : Giảm độ rộng của chổi, đường thẳng hoặc viền hình dạng xuống một điểm ảnh
- `Ctrl + U`  : Gạch dưới văn bản được chọn
- `Ctrl + E`  : Mở hộp thoại Thuộc tính
- `Ctrl + Page Up`  :Phóng to
- `Ctrl + Page Down`  : Thu nhỏ
- `F11`  : Xem ảnh ở chế độ toàn màn hình
- `Ctrl + R`  : Hiển thị hoặc ẩn thước
- `Ctrl + G`  : Hiển thị hoặc ẩn đường lưới
- `Delete`  : Xóa lựa chọn
