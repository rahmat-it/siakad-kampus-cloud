# SIAKAD KAMPUS - Cloud & DevOps

Aplikasi layanan akademik (Pendaftaran, KRS, Nilai, UKT) 
yang dimigrasi dari server lokal ke AWS Cloud.

## Arsitektur
- Cloud: AWS Public Cloud (PaaS)
- Compute: ECS + Auto Scaling (Min 2 - Max 10)
- Database: RDS PostgreSQL Multi-AZ
- Storage: S3 + ElastiCache Redis
- CI/CD: GitHub Actions + Docker
- IaC: Terraform

## Tim
- Developer: @developer-a
- Tester / QA: @tester-a
- Operations: @ops-lead

## Fix Log
- v1.1 - Perbaiki validasi pembayaran UKT
