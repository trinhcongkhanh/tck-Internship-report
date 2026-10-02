---
title: "Tuần 09: CI/CD Pipelines"
weight: 9
---

## 1. Tóm tắt tuần

| Hạng mục | Mô tả |
|---|---|
| **Tuần** | Tuần 09 |
| **Chủ đề** | AWS CodeCommit, CodeBuild, CodeDeploy, và CodePipeline |
| **Mục tiêu chính** | Tích hợp liên tục (CI), Triển khai liên tục (CD), và tự động hóa build |

## 2. Nhật ký công việc hàng ngày

| Ngày | Kế hoạch | Tác vụ chính | Hoạt động chi tiết | Kết quả |
|---|---|---|---|---|
| **Thứ Hai** | Ngày 1 | Quản lý mã nguồn | Đưa code lên AWS CodeCommit repositories | Repositories được phân quyền bảo mật qua IAM |
| **Thứ Ba** | Ngày 2 | AWS CodeBuild | Tạo file buildspec.yml để biên dịch code và chạy unit test | Unit test tự động pass trên CodeBuild |
| **Thứ Tư** | Ngày 3 | Docker trong CodeBuild | Cập nhật buildspec để tự build và push Docker images lên ECR | Image tự động push mỗi lần có commit mới |

## 3. Kỹ năng công nghệ học được

| Công nghệ | Kiến thức đạt được |
|---|---|
| **AWS CodePipeline** | Điều phối pipeline, các stages (bước), và artifacts |
| **AWS CodeBuild** | File Buildspec, môi trường build |
| **AWS CodeDeploy** | Deployment groups, định tuyến Blue/Green |

