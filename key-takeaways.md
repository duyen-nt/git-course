# Playwright Lession 2 - 24/08/2024
## Version control system
### 1. Định nghĩa
Là hệ thống dùng để quản lý các phiên bản
### 2. Types of Version control system
- **Local**: lưu ở máy cá nhân
- **Centralize**: lưu ở một máy chủ tập trung
- **Distributed**: lưu ở nhiều máy khác nhau
## GIT
### 1. Định nghĩa
GIT là 1 công cụ dùng để quản lý phiên bản 
### 2. Đặc điểm
- Dễ dùng
- Tốc độ xử lý nhanh
- Branching
- Miễn phí
- Phổ biến ở nhiều công ty
### 3. Các vùng trạng thái của GIT
GIT có 3 vùng trạng thái:
- **Working Directory**: Vùng chứa các file mới hoặc file có thay đổi 
- **Staging Area**: Vùng chứa các file chuẩn bị commit tạo ra các phiên bản
- **Repository**: Vùng chứa các phiên bản code đã được commit thành công

### 4. Các câu lệnh thường dùng
- *git init*: Khởi tạo thư mục được quản lý bởi git
- Cấu hình Git cho 1 repository:
*git config user.name “name”*
*git config user.email “email”*
- Cấu hình Git cho toàn bộ máy tính:
git config --global user.name “user”
git config --global user.email “email”
- *git add <file_name>*: add 1  file cụ thể từ vùng working directory sang vùng staging area - add các file mới or có chỉnh sửa từ máy local sang vùng chuẩn bị commit để tạo ra các version
- *git add .*: mục đích tương tự như lệnh git add <file_name> nhưng scope rộng hơn, tác động tới toàn bộ các file đang có vùng working directory
- *git commit -m “message”*: đẩy các file có ở vùng staging area lên repository, mỗi commit là 1 phiên bản code
- *git status*: Xem trạng thái file đang ở vùng nào 
- *git log"*: Kiểm tra lịch sử commit
### 5. Git commit convention
Cấu trúc: type: short_description. Trong đó:
- Type = Feat/ Chore/ Fix
- Short_description: Mô tả ngắn gọn khoảng 50 ký tự về những thứ mình chuẩn bị commit

## Javascript Basic
- Variable = biến, dùng để lưu trữ giá trị có thể thay đổi được
- Constant = hằng số, dùng để khai báo các giá trị không thể thay đổi
- Cú pháp khai báo biến/ hằng số: var = x; or let = "aaa"; const = y;
- var khai báo lại được, let thì không
- Thường dùng let, const, không dùng var
- Có 8 loại kiểu dữ liệu: String, Number, Bigint, Boolean, Undefined, Null, Symbol, Object.
- So sánh == -> chỉ so sánh value, không quan tâm data type
- So sánh === -> so sánh cả value và datatype
- i++ bằng với i=i+1
- i-- bằng với i=i-1
- Format code Mac: Option + Shift + F
-  Format code Window: Alt + Shift + F
-  Conditional = điều kiện, dùng để kiểm tra có nên thực hiện một đoạn logic không.
-  Cú pháp: if (<điều kiện>) { // code }. Nếu điều kiện đúng, sẽ chạy đoạn code
-  Loops = vòng lặp = Dùng để thực hiện một đoạn logic một số lần nhất định
- Cú pháp: for(<khởi tạo>; <điều kiện dừng>; <điều kiện tăng>) {
// code }


