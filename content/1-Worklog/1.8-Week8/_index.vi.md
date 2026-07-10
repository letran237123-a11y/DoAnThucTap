---
title: 'Worklog Tuần 8'
date: 2026-06-14
weight: 1
chapter: false
pre: ' <b> 1.8. </b> '
---


### Mục tiêu tuần 8:

- Lab 11
- Lab 13
- Lab 28

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                                                                                                                            | Ngày bắt đầu | Ngày hoàn thành | Trạng thái |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ---------- |
| 2   | - Cài đặt AWS CLI <br> - Xem tài nguyên bằng CLI <br> - Sử dụng AWS CLI với Amazon S3 <br> - Sử dụng AWS CLI với Amazon SNS <br> - Sử dụng AWS CLI với IAM                                                                                                                                           | 06/08/2026   | 06/08/2026      | Done       |
| 3   | - AWS CLI với VPC <br>&emsp; + Quản lý VPC bằng AWS CLI <br>&emsp; + Quản lý Internet Gateway bằng AWS CLI <br> - Tạo EC2 bằng AWS CLI<br> - Khắc phục sự cố (Troubleshooting)                                                                                                                       | 06/09/2026   | 06/09/2026      | Done       |
| 4   | - Chuẩn bị <br>&emsp; + Tạo S3 Bucket <br>&emsp; + Triển khai hạ tầng <br> - Tạo Backup Plan                                                                                                                                                                                                         | 06/10/2026   | 06/10/2026      | Done       |
| 5   | - Thiết lập thông báo (Notifications) <br> - Kiểm tra khôi phục dữ liệu (Test Restore)                                                                                                                                                                                                               | 06/11/2026   | 06/11/2026      | Done       |
| 6   | - Tạo IAM User <br> - Tạo IAM Policy <br> - Tạo IAM Role <br> -Kiểm tra Policy <br> &emsp; + Chuyển đổi Role (Switch Roles) <br> &emsp; + Kiểm tra IAM Policy <br> - **Thực hành:** <br>&emsp; + Truy cập EC2 Console tại khu vực Tokyo <br>&emsp; + Truy cập EC2 Console tại khu vực North Virginia | 06/12/2026   | 06/12/2026      | Done       |
| 7   | - **Thực hành:** <br>&emsp; + Tạo EC2 Instance khi không có hoặc có Tag hợp lệ <br>&emsp; + Chỉnh sửa Resource Tag trên EC2 Instance <br>&emsp; + Kiểm tra Policy                                                                                                                                    | 06/13/2026   | 06/13/2026      | Done       |

### Kết quả đạt được tuần 8:

### Lab 11:

- Cài đặt AWS CLI và tạo, quản lý các profile.
- Xem và kiểm tra các EC2 Instance và S3 Bucket.
- Học cách tạo, liệt kê và xóa Bucket cũng như các đối tượng trong S3 bằng AWS CLI.
- Làm quen với AWS CLI thông qua dịch vụ SNS.
- Tạo IAM Group, IAM User và IAM Policy bằng CLI.
- Tạo VPC bằng CLI.
- Học cách tạo và quản lý Internet Gateway trên AWS.
- Tạo Security Group cho EC2.

### Lab 13:

- Tạo S3 Bucket.
- Sử dụng AWS Backup để tạo kế hoạch sao lưu (Backup Plan) cho các tài nguyên đang chạy trên AWS.
- Thực hiện sao lưu bằng AWS Backup với chế độ quản lý toàn diện, cho phép tự động sao lưu dữ liệu từ nhiều nguồn như EC2, EBS,...
- Thiết lập thông báo trên nền tảng đám mây.
- Sử dụng AWS Lambda để tự động kiểm tra khả năng khôi phục thành công của các bản sao lưu và dọn dẹp tài nguyên.

### Lab 28:

- Tạo 4 IAM Policy gồm:

* ec2-create-tags-existing
* ec2-list-read
* ec2-create-tags
* ec2-run-instances

- Tạo IAM Role.
- Kiểm tra quyền truy cập tại khu vực Tokyo và North Virginia.
- Tạo EC2 Instance khi không có hoặc có Tag hợp lệ.
- Chỉnh sửa Resource Tag trên EC2 Instance.
- Kiểm tra và xác thực Policy.
