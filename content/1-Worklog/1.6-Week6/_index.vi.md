---
title: 'Worklog Tuần 6'
date: 2026-05-31
weight: 1
chapter: false
pre: ' <b> 1.6. </b> '
---

{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 6:

Lab 4: Triển khai ứng dụng trên EC2 (Linux & Windows)

- Node.js, MySQL
- Chính sách IAM (IAM Policies)
- Tối ưu chi phí (Cost Optimization)
- Bảo mật và Kiểm soát truy cập (Security & Access Control)

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc                                                                                                                                                                                         | Ngày bắt đầu | Ngày hoàn thành | Trạng thái                          |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Cài đặt Node.js trên Amazon Linux 2023 bằng NVM - Cài đặt Git và clone mã nguồn ứng dụng - Cấu hình biến môi trường và triển khai ứng dụng trên EC2 Linux                                       | 25/05/2026   | 25/06/2026      |Hoàn thành|
| 3   | - Cài đặt XAMPP trên Windows Server - Tạo cơ sở dữ liệu MySQL và bảng dữ liệu bằng phpMyAdmin - Triển khai và kiểm thử ứng dụng Node.js trên Windows Instance                                     | 26/05/2026   | 26/05/2026      | Hoàn thành |
| 4   | - Tìm hiểu cơ chế kiểm soát truy cập theo Region của IAM - Tạo chính sách RegionRestrict - Cấu hình IAM Group và IAM User - Kiểm tra quyền truy cập EC2 ở các AWS Region khác nhau                | 27/05/2026   | 27/05/2026      | Hoàn thành |
| 5   | - Tìm hiểu cơ chế giới hạn EC2 Instance Family - Tạo chính sách EC2_FamilyRestrict - Cấu hình và kiểm tra các Instance Family được phép và bị từ chối - Triển khai giới hạn theo Instance Type    | 28/05/2026   | 28/05/2026      | Hoàn thành |
| 6   | - Triển khai giới hạn loại EBS Volume - Cấu hình quyền xóa EC2 dựa trên địa chỉ IP - Triển khai giới hạn xóa EC2 theo khoảng thời gian - Kiểm tra hiệu lực của các IAM Policy thông qua thực hành | 29/05/2026   | 29/05/2026      | Hoàn thành |
| 7   | - Tìm hiểu cách thiết kế giao diện người dùng (UI) và tạo các thành phần UI cơ bản trong Unity                                                                                                    | 30/05/2026   | 31/05/2026      | Hoàn thành |

### Kết quả đạt được tuần 6:

- Cài đặt và cấu hình thành công Node.js trên Amazon Linux 2023.
- Triển khai thành công ứng dụng Node.js trên cả EC2 Linux và Windows.
- Cấu hình cơ sở dữ liệu MySQL và tích hợp với ứng dụng.
- Tìm hiểu cách quản lý các thư viện phụ thuộc bằng NPM.
- Có kinh nghiệm sử dụng phpMyAdmin để tạo cơ sở dữ liệu, bảng dữ liệu và nhập dữ liệu mẫu.
- Triển khai các IAM Policy nhằm giới hạn việc sử dụng tài nguyên AWS dựa trên:

* AWS Region
* EC2 Instance Family
* EC2 Instance Type
* EBS Volume Type
* Địa chỉ IP nguồn (Source IP Address)
* Khoảng thời gian (Time Period)

- Tạo IAM Group và IAM User để kiểm thử các chính sách kiểm soát truy cập.
- Xác minh hiệu quả của các Policy thông qua việc thử nghiệm các hành động được phép và bị từ chối.
- Nâng cao hiểu biết về các thực tiễn bảo mật tốt nhất trên AWS, bao gồm:

* Nguyên tắc đặc quyền tối thiểu (Least Privilege Principle)

- Mô hình bảo mật Zero Trust
- Các chiến lược tối ưu chi phí (Cost Optimization)

* Phát triển kỹ năng quản lý tài nguyên EC2 và triển khai các cơ chế quản trị thông qua IAM Policy.
* Nâng cao kiến thức về triển khai hạ tầng đám mây, quản trị hệ thống và quản lý bảo mật trên nền tảng AWS.
