# Báo cáo Bài tập 2: Tái cấu trúc lịch sử commit bằng Interactive Rebase

## 1. Thông tin học viên
- **Họ và tên:** Nguyễn Văn A
- **Email:** nn650370@gmail.com
- **Đường dẫn Repository GitHub:** https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME

---

## 2. Quá trình thực hiện Interactive Rebase

### Bước 1: Khởi tạo 4 commit mô phỏng ban đầu
Tạo các thay đổi thử nghiệm vụn vặt trên nhánh làm việc:
1. `feat: khoi tao module auth` (Tạo tệp `auth.js`)
2. `fix typo` (Sửa lỗi nhỏ trong `auth.js`)
3. `adds utility functions` (Bổ sung hàm tiện ích vào `auth.js`)
4. `add temp file for debug` (Tạo tệp rác `temp.txt`)

Lịch sử commit ban đầu trước khi Rebase (`git log --oneline`):
```text
a547e84 (HEAD -> master) add temp file for debug
48deb45 adds utility functions
a1db3a9 fix typo
7fd60fd feat: khoi tao module auth