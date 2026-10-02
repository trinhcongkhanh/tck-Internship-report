---
title: "Tuần 04: Các giải pháp lưu trữ"
weight: 4
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 04 |
| **Chủ đề** | Các dịch vụ lưu trữ AWS: S3, EBS, và EFS |
| **Mục tiêu chính** | Object storage, block storage, hệ thống file chia sẻ, chính sách vòng đời (lifecycle) |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | Cơ bản về S3 | Tạo buckets, bật versioning và mã hóa SSE | Bucket được tạo và bảo mật |
| **Thứ Ba** | Ngày 2 | S3 Lifecycle Rules | Cấu hình chuyển data cũ sang S3 Glacier | Tối ưu hóa chi phí lưu trữ S3 |
| **Thứ Tư** | Ngày 3 | Ổ cứng EBS | Tạo, gắn, và tăng dung lượng EBS trên EC2 đang chạy | Tăng dung lượng không cần downtime |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **Amazon S3** | Buckets, Objects, Versioning, Storage Classes, Lifecycle |
| **Amazon EBS** | Các loại ổ cứng (gp3, io2), Snapshots, DLM |
| **Amazon EFS** | Mount NFS, chia sẻ file liên Availability Zone (AZ) |

