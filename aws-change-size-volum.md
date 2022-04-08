# Thay đổi dung lượng server aws

1. Vào trang quản trị ec2 thao tác volume thêm mới dung lượng cho Tài khoản
2. Sau khi chờ đợi thực hiện xong thì phải reboot lại server
3. sudo server reboot -now
4. kiểm tra thiết lại cài đặt trong server và thực hiện các câu lệnh theo history

# Kiểm tra dung lượng ổ đĩa sử dụng

1. df -h
2. ls -la --block-size=M // show toàn bộ dung lượng theo Mb
