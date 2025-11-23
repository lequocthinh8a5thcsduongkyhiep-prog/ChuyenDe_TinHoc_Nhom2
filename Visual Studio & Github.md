# 💻 CHUYÊN ĐỀ TIN HỌC

## Làm quen với Visual Studio Code & Github

---

## A. TỔNG QUAN

* **VS Code (Visual Studio Code):** là trình soạn thảo mã nguồn miễn phí do Microsoft phát triển, hỗ trợ rất nhiều ngôn ngữ lập trình như C++, Python, Java, JavaScript…; sở hữu hệ thống extension phong phú.
* **Github:** là nền tảng lưu trữ và chia sẻ mã nguồn trực tuyến, dựa trên Git. Nó cho phép quản lý phiên bản, làm việc nhóm, và tham gia vào các dự án mã nguồn mở.
* **Git:** Git là hệ thống quản lý phiên bản (Version Control System) giúp theo dõi lịch sử thay đổi mã nguồn, tạo nhánh, hợp nhất và làm việc nhóm hiệu quả, do Linus Torvalds tạo ra.
* **GitHub Desktop:** GitHub Desktop là ứng dụng giao diện (GUI) giúp bạn sử dụng Git và GitHub dễ dàng hơn mà không cần dùng lệnh.

---

## B. CÀI ĐẶT & THIẾT LẬP

### I. CÀI ĐẶT

#### 1. VS Code

1.  Truy cập trang chính thức: [https://code.visualstudio.com](https://code.visualstudio.com).
2.  Chọn nút **Download** phù hợp với hệ điều hành (Windows, macOS, Linux).
3.  Mở file cài đặt → nhấn **Next** liên tục → chọn **Install**.
4.  Sau khi cài xong, mở VSCode để kiểm tra.
5.  **(Khuyến nghị)** Cài thêm extension:
    * **GitLens:** Xem lịch sử commit, tác giả từng dòng.
    * **Prettier:** Định dạng mã nguồn tự động.
    * **GitHub Pull Requests & Issues:** Quản lý PR trực tiếp trong VS Code.

> **Lưu ý:** Chỉnh cấu hình cơ bản (Theme, font, Tiếng Việt,.. nếu cần).

#### 2. Git

1.  Vào trang chính thức: [https://git-scm.com/downloads](https://git-scm.com/downloads).
2.  Chọn phiên bản phù hợp với hệ điều hành (Windows/macOS/Linux).
3.  Mở file cài đặt → nhấn **Next** liên tục → **Install** → **Finish**.
4.  Kiểm tra bằng cách mở Terminal/Command Prompt và gõ: `git --version`.
5.  Nếu hiện số phiên bản là cài thành công.
6.  Cấu hình thông tin lần đầu:
    * `git config --global user.name "Tên của bạn"`
    * `git config --global user.email "Email của bạn"`

> **Lưu ý:** Các cấu hình thông tin sẽ gắn liền với các commit.

#### 3. GitHub Desktop

1.  Truy cập [https://desktop.github.com](https://desktop.github.com).
2.  Tải về và cài đặt như phần mềm bình thường.
3.  Đăng nhập bằng tài khoản GitHub.

> **Lưu ý:**
> * Giao diện chính có các nút: **Clone a repository**, **Create a new repository**, **Add an existing repository**.
> * Có thể mở dự án bằng VSCode trực tiếp từ GitHub Desktop.

### II. THIẾT LẬP

#### 1. Tạo tài khoản GitHub

1.  Vào [https://github.com](https://github.com).
2.  Nhấn **Sign up** → nhập email, mật khẩu, username.
3.  Xác nhận email để hoàn tất.

> **Lưu ý:**
> * Sau khi đăng nhập, bạn có thể tạo repo mới bằng nút **New repository** (Tạo kho chứa mã nguồn mới).
> * Chỉnh **Public** & **Private**:
>     * **Public:** Ai cũng xem được.
>     * **Private:** Chỉ bạn (hoặc nhóm được cấp quyền) xem được.

#### 2. Kết nối VS Code với GitHub

1.  Mở VSCode → nhấn **Ctrl + Shift + P**.
2.  Gõ: **GitHub: Sign in** → chọn đăng nhập bằng trình duyệt.
3.  Đăng nhập tài khoản GitHub → cấp quyền truy cập.
4.  VSCode sẽ lưu token xác thực → có thể push/pull trực tiếp.
5.  Kiểm tra tab **Source Control** đã hoạt động.

> **Lưu ý:** Tab **Source Control** là nơi hiển thị mọi thay đổi.

#### 3. Đăng nhập tài khoản GitHub trên GitHub desktop