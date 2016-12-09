## **Tìm hiểu github**

##1.Github
- **Githb** là môt dịch vụ cung cấp kho lưu trữ công cộng mã nguồn Git dựa trên nền web cho các dự án phát triển phần mềm (bao gồm miễn phí và có phí), các dự án mã nguồn mở sẽ được cấp kho lưu trữ miễn phí. Nếu sử dụng dịch vụu miễn phí thì mã nguồn được công khai.
- *Git* là tên một mô hình hệ thống quản lý phiên bản phân tán, nghĩa là hệ thống giúp mỗi máy tính có thể lưu trữ nhiều phiên bản khác nhau của một mã nguồn được nhân bản (clone) từ một kho chứa mã nguồn (repository), mỗi thay đổi vào mã nguồn trên máy tính sẽ có thể ủy thác (commit) rồi đưa lên máy chủ nơi đặt kho chứa chính. Và một máy tính khác (nếu họ có quyền truy cập) cũng có thể clone lại mã nguồn từ kho chứa hoặc clone lại một tập hợp các thay đổi mới nhất trên máy tính kia. Trong Git, thư mục làm việc trên máy tính gọi là Working Tree. 

![](https://thachpham.com/wp-content/uploads/2015/04/dvcs.png)

- **Cần phân biệt giữa GIT và GITHUB:** Git là chương trình và giao thức , GitHub là một trong nhiều trang web dịch vụ (như BitBucket hoặc GitLab) dùng để lưu trữ mã. 

## 2.Các khái niệm trong Github
- **Add:**
Bạn có thể đề xuất thay đổi (thêm nó vào chỉ mục Index) bằng cách sử dụng lệnh:
```````````````
git add <tên-tập-tin>
git add *
```````````````````

- **Remove:**
Xoá file đã tồn tại trong git và cập nhật gitignore giữa chừng dự án

- **Commit:** ghi lại việc thêm/thay đổi file hay thư mục vào repository.

Khi thực hiện commit, trong repository sẽ tạo ra commit (hoặc revision) đã ghi lại sự khác biệt từ trạng thái đã commit lần trước với trạng thái hiện tại.

Commit này đang được chứa tại repository, các commit nối tiếp với nhau theo thứ tự thời gian. Bằng việc lần theo commit này từ trạng thái mới nhất thì có thể biết được lịch sử thay đổi trong quá khứ hoặc nội dung thay đổi đó.
````
Git commit
````````
- **Push:** đẩy những thay đổi từ máy trạm vào máy chủ.

- **Pull:** Lấy tệp mã nguồn từ máy chủ về máy trạm
- **Fetch:** hủy tất cả thay đổi và commit cục bộ, lấy về (fetch) lịch sử gần nhất từ máy chủ và trỏ nhánh master cục bộ vào nó
-**Clone:**  sao chép 1 repository có sẵn ở trên máy cục bộ hoặc trên máy chủ khác.

`````````````````
git clone /đường-dẫn-đến/repository/
```````````````````

Nếu repository đó ở máy chủ khác 

``````````````````
git clone tênusername@địachỉmáychủ:/đường-dẫn-đến/repository
```````````````````````

- **Fork:** copy project có sẵn thành project cá nhân, rồi sau đó ta có thể tự do chỉnh sửa project đó . 
## 3. Setting up Git:
- download tại :https://desktop.github.com/
- cài đặt chương trình 
- tạo acc : chọn tool and options --> options--> add account (trong trường hợp đã có acc trên github thì chỉ cần đăng nhập)


## 4.Generate and add SSH key
SSH(Secure Shell) là một giao thức mạng dùng để thiết lập kết nối mạng một cách bảo mật.
Khi làm việc với git, ssh sẽ giúp ta trong 2 việc:
1. Bảo mật các kết nối của mình với server.
2. Không phải nhập mật khẩu mỗi lần push code.


-


. 
