# Cloud-Native Game Asset Delivery Pipeline

This repository demonstrates a **DevSecOps** approach to automating game asset distribution. 

## Technical Highlights
- **Infrastructure as Code (IaC):** Managed via [Terraform](https://www.terraform.io) to ensure reproducible and version-controlled AWS environments.
- **CI/CD Automation:** [GitHub Actions](https://github.com) workflow for building Godot projects and deploying artifacts.
- **Security Hardening:** Enforced **TLS/HTTPS** transport and Public Access Block (PAB) via S3 Bucket Policies.
- **Cost-Efficiency:** Optimized for AWS Free Tier and pay-as-you-go scaling.

## Architecture
1. **GitHub:** Source Control & Secret Management.
2. **GitHub Actions:** Automated build & security linting.
3. **AWS S3:** Secure, globally available storage for game updates.
