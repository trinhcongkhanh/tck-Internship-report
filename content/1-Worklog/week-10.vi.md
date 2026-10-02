---
title: "Tuần 10: Bảo mật & Tuân thủ"
weight: 10
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 10 |
| **Chủ đề** | AWS KMS, AWS WAF, Amazon GuardDuty, và AWS Config |
| **Mục tiêu chính** | Mã hóa dữ liệu, phát hiện mối đe dọa, tường lửa web, kiểm toán tuân thủ |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | AWS KMS | Tạo CMKs và bắt buộc mã hóa S3 buckets và ổ EBS | Dữ liệu ở trạng thái nghỉ (Data at rest) đã được mã hóa |
| **Thứ Ba** | Ngày 2 | AWS Certificate Manager | Xin cấp chứng chỉ SSL/TLS và gắn vào Application Load Balancer | Dữ liệu trên đường truyền được mã hóa (HTTPS) |
| **Thứ Tư** | Ngày 3 | AWS WAF | Gắn Tường lửa WAF vào ALB để chặn SQL Injection và XSS | Ứng dụng được bảo vệ khỏi các lỗ hổng web phổ biến |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **AWS KMS** | Khóa đối xứng/bất đối xứng, Envelope Encryption (Mã hóa phong bì) |
| **AWS WAF** | Web ACLs, Managed rule groups (Bộ quy tắc có sẵn) |
| **AWS Config & GuardDuty** | Kiểm toán liên tục và phát hiện mối đe dọa bằng AI |

