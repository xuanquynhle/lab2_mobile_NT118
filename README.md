# YÊU CẦU THỰC HÀNH

## 1. Trường hợp 1: Sử dụng ListView control với mảng dữ liệu định sẵn
Sử dụng ListView control với mảng dữ liệu định sẵn. Xây dựng Listview như hình minh họa:
- Giao diện trên có 2 control:
  + ListView: dùng để hiển thị mảng dữ liệu
  + TextView: có màu xanh lục: Dùng để hiển thịvị trí và giá trị của phần tử được chọn trong ListView.
    
## 2. Trường hợp 2: Sử dụng ArrayList và Listview control
Xây dựng ứng dụng như sau:
- Mô tả:
  + Nhập dữ liệu và nhấn nút “Nhập” thì sẽ đưa vào ArrayList và hiển thị lên ListView.
  + Nhấn vào phần tử nào thì hiển thị vị trí và giá trị của phần tử đó lên TextView
  + Nhấn thật lâu (long click) vào phần tử nào đó trên ListView thì sẽ xóa phần tử đó.

## 3. Trường hợp 3: Sử dụng ArrayList và ListView mà từng phần tử trong ArrayList là các Object bất kỳ
Xây dựng ứng dụng theo mô tả sau: Có 2 loại nhân viên: 
  Nhân viên chính thức (EmployeeFullTime) và nhân viên thời vụ (EmployeePartime). Mỗi loại nhân viên sẽ có cách tính lương khác nhau. Mỗi nhân viên có phương thức toString để xuất thông tin, Nội 
dung xuất khác nhau. 

## 4. Trường hợp 4: Sử dụng CustomAdapter cho Listview
Xây dựng ứng dụng với giao diện như sau:
  Người dùng nhập thông tin ở trên, sau đó nhấn Add. Thông tin employee sẽ được hiện xuống listview. Nếu là Manager thì hiện thêm icon 
manager ở bên phải ngược lại hiện chữ Staff. Ngoài ra, giữa 2 employee liên tiếp trong listview sẽ được hiện background màu khác nhau cho dễ nhìn.

## 5. Sử dụng GridView, Spinner
Các bước thiết đặt adapter để hiển thị nội dung lên gridview và spinner trong Android cũng tương tự trên listview. Sinh viên viết ứng dụng theo mô tả sau:
  - Ứng dụng hỗ trợ chức năng thêm món ăn mới gồm các thông tin: tên món ăn, hình đại diện, và thông tin có khuyến mãi hay không. Sau khi thêm một món ăn, các trường name, thumbnail, promotion được reset về trạng thái ban đầu (name trống, thumbnail, promotion hiển thị giá trị mặc  định). Thông báo “Added successfully”  được hiển thị dưới dạng Toast.
  - Danh sách các món ăn được hiển thị bằng gridview theo thiết kế như hình gồm 2 cột. Mỗi món ăn hiển thị hình đại diện, tên món ăn, nếu có khuyến mãi thì thêm icon star. Nếu tên món ăn quá dài, nội dung tên sẽ hiển thị trên gridview dạng chữ chạy.
  - Hình đại diện được chọn từ spinner chứa 4 hình có sẵn. Danh sách này được hiển thị ở dạng dialog (không phải dạng dropdown sổ xuống thông thường) như hình minh họa gồm tên hình và hình. Khi một hình được chọn chỉ có tên được hiển thị lên spinner.

## 6. RecyclerView - Trường hợp 6: Sử dụng CustomAdapter cho Listview) bằng RecyclerView
Về nhà tìm hiểu và so sánh Listview và RecyclerView. Làm lại bài ở mục 4. 
