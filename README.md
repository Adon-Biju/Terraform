# AWS S3 Static Website with Terraform (Demo-Only)

This repo shows how to provision an S3 static website using Terraform.
- Live demo of the website HTML is hosted via **GitHub Pages** (free).
- Please visit to view the static webpage https://adon-biju.github.io/Terraform/ 

## Terraform
- Run locally (no backend):
  ```bash
  terraform init -backend=false
  terraform fmt -check
  terraform validate
  terraform plan -lock=false -input=false
