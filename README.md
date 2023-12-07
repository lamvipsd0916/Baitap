Giao diện người dùng (GUI):

Cửa sổ chính của ứng dụng là lớp CustomerFrame kế thừa từ JFrame.
Giao diện chia thành hai phần chính: một phần để nhập thông tin khách hàng và một bảng hiển thị danh sách khách hàng.
Các thành phần chính trong giao diện:

JTextField: Dùng để nhập thông tin như tên, email, số điện thoại, số tài khoản, giới tính và số CCCD.
JTable: Dùng để hiển thị danh sách khách hàng dưới dạng bảng.
JButton: Các nút chức năng như Cập nhật, Xoá, Tìm kiếm và Tải lại.
Các chức năng chính:

Hiển thị danh sách khách hàng từ cơ sở dữ liệu khi ứng dụng khởi chạy.
Cho phép người dùng chọn một khách hàng từ bảng để xem hoặc chỉnh sửa thông tin.
Cập nhật thông tin khách hàng hoặc thêm mới thông tin nếu người dùng nhập mới.
Xoá thông tin khách hàng được chọn.
Tìm kiếm khách hàng dựa trên tên.
Tải lại danh sách khách hàng từ cơ sở dữ liệu.
Kết nối và thao tác với cơ sở dữ liệu:

Sử dụng lớp CustomerModify để thực hiện các thao tác CRUD (Create, Read, Update, Delete) với cơ sở dữ liệu.
Các phương thức trong CustomerModify thực hiện kết nối đến cơ sở dữ liệu, thực hiện các câu truy vấn SQL và trả về danh sách khách hàng.
