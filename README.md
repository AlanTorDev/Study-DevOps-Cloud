# Study-DevOps-Cloud
Project to study Dev Ops and Try to get money

# Tam's DevOps Learning Journey & Portfolio

Hành trình tự học DevOps từ technical support → Cloud/DevOps Engineer (2026).

**Mục tiêu**: Mid-level DevOps Engineer (AWS, Terraform, Docker, Kubernetes, Python automation).

**Tiến độ hiện tại**:
- Giai đoạn 1: Nền tảng Linux & Scripting (đang học)
- Chứng chỉ: AWS SAA-C03 (dự kiến Q2/2026)

## Cấu trúc Repo
- **stage1-foundations/**: Linux, Bash, Python cho DevOps
- **stage2-aws-cloud/**: AWS labs & chứng chỉ
- **stage3-devops-tools/**: Docker, Terraform, K8s, CI/CD
- **projects/**: Dự án thực tế end-to-end
- **docs/notes/**: Ghi chép học tập hàng tuần

## Projects nổi bật (cập nhật dần)
1. **Backup Automation Script** (Giai đoạn 1) → [stage1-foundations/linux/backup-script.sh](link)

## Công cụ & Skills đang học
- Linux (Ubuntu via WSL2)
- Bash & Python scripting
- Git/GitHub
- AWS (SAA-C03)
- Docker, Terraform, Kubernetes...

## Liên hệ
- LinkedIn: [linkedin.com/in/tam-devops](link)
- Email: tam@example.com

Cập nhật lần cuối: Tháng 2/2026

# Stucture Tree
tam-devops-learning/                  # Tên repo gốc
├── README.md                         # Trang chính, mô tả tổng quan hành trình
├── .gitignore                        # Bỏ qua file không cần (tạo mặc định khi tạo repo)
├── docs/                             # Tài liệu học, ghi chép
│   ├── notes/                        # Ghi chép hàng ngày/tuần
│   │   ├── week1-linux-basics.md     # Ví dụ: lệnh học tuần 1
│   │   └── bash-scripting-tips.md
│   └── resources.md                  # Link khóa học, tài liệu hay (Udemy, freeCodeCamp, AWS docs)
├── stage1-foundations/               # Giai đoạn 1: Nền tảng
│   ├── linux/                        # Lệnh Linux, script Bash
│   │   ├── commands-cheatsheet.md
│   │   ├── backup-script.sh          # Script thực hành backup
│   │   └── screenshots/              # Ảnh chụp màn hình terminal (nếu cần minh họa)
│   └── python-devops/                # Python cho automation
│       ├── automate-tasks.py
│       └── boto3-intro.py            # Sau này khi học AWS
├── stage2-aws-cloud/                 # Giai đoạn 2: AWS + chứng chỉ
│   ├── aws-cli-commands.md
│   ├── labs/                         # Lab thực hành SAA-C03
│   │   └── vpc-multi-subnet.tf       # Terraform code nếu bắt đầu sớm
│   └── cert-prep/                    # Practice exam notes
├── stage3-devops-tools/              # Giai đoạn 3: Core tools
│   ├── docker/                       # Dockerfile, Compose files
│   │   ├── Dockerfile
│   │   └── docker-compose.yml
│   ├── terraform/                    # IaC projects
│   │   ├── modules/
│   │   └── aws-vpc-ec2/
│   ├── kubernetes/                   # Manifests YAML
│   │   └── deployment-nginx.yaml
│   └── cicd/                         # GitHub Actions workflows
│       └── workflows/
│           └── ci-build-docker.yml
├── projects/                         # Dự án end-to-end (từ giai đoạn 3-4)
│   ├── project1-aws-webapp/          # Ví dụ: Deploy app 3-tier với Terraform + EKS
│   │   ├── terraform/
│   │   ├── app/
│   │   └── README.md                 # Chi tiết project
│   └── project2-gitops-eks/          # Sau này
├── monitoring/                       # Monitoring setups (Prometheus, Grafana)
└── LICENSE                           # MIT hoặc Apache 2.0 (tùy chọn)