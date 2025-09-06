# IAM Roles & Policies Showcase

## 📌 Description
This project demonstrates IAM users, groups, roles, and policies, along with AWS CLI access for secure operations.

## 🏗️ Architecture
(User → IAM Group → IAM Policy → EC2 Role)

## 🛠️ AWS Services Used
- IAM
- AWS CLI
- EC2 (role demo)

## 🚀 Implementation Steps
1. Create an IAM user and group.
2. Attach a custom IAM policy (`policy.json`).
3. Assign an IAM role to an EC2 instance.
4. Configure AWS CLI credentials and run `aws s3 ls`.

## 📸 Screenshots
- IAM user & group
- Attached policy JSON
- CLI `aws s3 ls` output

## 🔑 Key Takeaways
- Groups simplify permissions.
- Roles > long-lived keys.
