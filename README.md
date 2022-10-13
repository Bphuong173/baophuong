# GIT

- Git dùng để quản lý mã nguồn`(source code)`
- Cung cấp kho chứa `Repository`
## Các thành phần cơ bản nhất trong Git:

1. **Branch**: dùng để phân nhánh và ghi lại luồng của lịch sử
   > Vd: tạo ra nhiều nhánh khác nhau để sửa lỗi cho Repository mà không ảnh hưởng đến nhau
2. **Commit**: Ghi lại việc thêm hay thay đổi file, thư mục vào Repository
3. **Index**: Là nơi để chuẩn bị cho việc Commit lên Repository, mọi file phải được Index thì mới Commit.
4. **Merge**: Dùng để hợp nhất các nhánh độc lập thành một nhất trong Git
5. **Checkout**: Dùng để di chuyển giữa các Branch
   > Vd: Nhập `git checkout master` để về Branch chính (Branch master)
6. **Push**: Để đẩy các Commit mới ở máy trạm (Local Repo) lên server (Remote Repo). Nguồn để đẩy lên là nhánh mà con trỏ HEAD nhắm tới (nhánh làm việc)
   >Vd: Nhập `git push repository refspec`. Trong đó Repository là địa chỉ  nơi sẽ Push lên, refspec là địa chỉ Branch sẽ Push
7. **Pull**: Dùng để tải xuống dữ liệu từ một Repository và cập nhật Local Repository phù hợp với dữ liệu đó
   > Vd: Nhập `git pull origin master` đồng bộ masster branch từ Remote Repo vào Local Repo.
8. **Repository**: Là nơi ghi lại trạng thái của thư mục và file   
  - Remo Repository: Để chia sẻ giữa nhiều người và bố trí trên server chuyên dụng
  - Local Repository: Là Repository trên máy tính của mình, dành cho 1 người sử dụng.
9. **Origin**: Là kho lưu trữ từ xa nơi mà mình Publish Commit của mình.
10. **Stash**: Để lưu lại các thay đổi chưa Commit 
    > Vd: đổi sang 1 Branch khác mà Branch đang làm dở dang.
11. **Pull Request**: Cơ chế để lập trình viên,nhà sáng lập,..tham gia đóng góp, review.
12. **Clone**: Dùng để sao chép Repository
    > Vd: Nhập `git clone repository directory` trong đó repository là địa chỉ URL của Remote Repository, directory là tên thư mục noi sẽ sao chép đến.