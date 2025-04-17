# AWS CLI Lab: S3 Bucket Creation, IAM Security & Real-World Troubleshooting

🔹 **Author:** Margaret Johnson  
🔹 **Project Type:** Hands-On AWS Lab  
🔹 **Focus Areas:** AWS CLI, S3, IAM, Troubleshooting, Public Access Policies

---

## 📚 Table of Contents

- [📁 Featured Labs](#-featured-labs)
- [🛠️ Skills Demonstrated](#️-skills-demonstrated)
- [🚀 Next Steps](#-next-steps)
- [🔐 Security Note](#-security-note)
- [📸 Screenshot Galleries (inside subfolders)](#-screenshot-galleries-inside-subfolders)

---

## 📁 Featured Labs

### 🔹 [AWS CLI Practice Lab](./AWS-CLI-Practice/S3-Bucket-Permission-Lab)
Hands-on AWS CLI project including:
- S3 bucket creation
- IAM configuration
- Public access policy using JSON
- Troubleshooting AccessDenied issues
- Screenshots & full documentation included

➡️ [View the full lab README](./AWS-CLI-Practice/S3-Bucket-Permission-Lab/README.md)

---

## 🧠 Why I Built This Lab

As I transition into the tech industry, I’m committed to not just collecting certificates — but **building real skills** through hands-on labs.

This lab was born out of my desire to go beyond tutorials and challenge myself to:
- Create and manage AWS resources using only the CLI  
- Solve problems in real time  
- Simulate real-world issues a Cloud Support Engineer might face  
- Document my process clearly — the wins *and* the setbacks

---

## 🔁 Midpoint Reflection (Day 1 Summary)

**On Day 1**, this lab tested not just my technical knowledge — but my ability to troubleshoot under pressure.

### ✅ What I Accomplished:
- Recovered access to my AWS **root account** by removing and reassigning a virtual MFA device  
- Created a secure IAM user (`margaret-cli-lab`) for CLI access  
- Installed and configured AWS CLI v2 on my Windows machine  
- Verified my IAM credentials using CLI  
- Created a clean folder system on my desktop with organized assets

### 🚧 What I Struggled With:
- I couldn’t remember my MFA code and had to go through recovery steps  
- GitHub Desktop was still linked to my old account — had to unlink and sign in with `Margaret-Johnson-ai`  
- CLI didn’t recognize paths inside OneDrive, so I had to reorganize all files to my local desktop

---

## 📅 Final Day Reflection (Day 2 Summary)

**On Day 2**, I moved into the technical execution — and quickly found myself facing real-world access errors.

### ✅ What I Accomplished:
- Created an S3 bucket using CLI  
- Wrote and uploaded a test file  
- Authored and applied a JSON policy to enable public access  
- Unblocked S3’s default public access restrictions via the AWS console  
- Verified the file was publicly accessible via browser  
- Deleted the bucket and verified cleanup using CLI  
- Captured all screenshots and organized them in GitHub

### 🚧 What I Struggled With:
- Got an `AccessDenied` error in the browser even after applying the bucket policy  
- Learned that AWS S3 also blocks public access by default — not just at the policy level  
- Had to carefully structure my local folders so I could upload to GitHub in the correct format  
- Learned to copy full projects using the Windows CLI (`xcopy`) to preserve folders and files

---

## 📸 Screenshot Reference Table

| Step | Description | Screenshot |
|------|-------------|------------|
| 1 | CLI Config Success | `aws-cli-config-success.png` |
| 2 | S3 Bucket Created | `s3-bucket-created.png` |
| 3 | File Uploaded | `s3-file-uploaded.png` |
| 4 | Bucket Policy Applied | `s3-bucket-policy-applied.png` |
| 5 | File Accessed in Browser | `s3-file-access-browser.png` |
| 6 | Permissions Unblocked | `s3-permissions-console.png` |
| 7 | Bucket Contents Visible | `s3-bucket-contents.png` |
| 8 | Bucket Overview | `s3-bucket-overview-console.png` |
| 9 | Deleted `test.txt` | `s3-object-deleted.png` |
|10 | Deleted Bucket via Console | `s3-delete-bucket-console.png` |
|11 | Confirmed Deletion via CLI | `s3-bucket-deletion-confirmed.png` |

---

## 🛠️ Skills Demonstrated

- AWS CLI (v2) configuration and usage
- S3 bucket management via command line
- JSON-based policy writing for public access
- IAM user creation and troubleshooting MFA issues
- CLI-based resource cleanup to avoid billing
- GitHub project structure and documentation
- Screenshot documentation and markdown formatting

---

## 🚀 Next Steps (Strategic Cloud Growth Plan)

- Build a serverless ticketing system using **AWS Lambda, DynamoDB, and API Gateway**
- Deploy a Linux-based web app on EC2 with custom security groups and **automated backups**
- Design an Infrastructure-as-Code project using **CloudFormation or Terraform** — including rollback testing
- Set up a CI/CD pipeline with **GitHub Actions + AWS CodePipeline** to automate deployment
- Explore **AWS IAM best practices for enterprise environments** (MFA, SCPs, cross-account roles)
- Build a “Cloud Cost Optimization” lab to showcase **budget-aware architecture**
- Begin prep for **AWS Certified Cloud Practitioner** to back up hands-on work with credentials

---

## 🔐 Security Note

All IAM credentials, AWS account numbers, and access keys were redacted or deleted.  
This lab was created using Free Tier resources and safely cleaned up.

---

## 📸 Screenshot Galleries (inside subfolders)

Screenshots for this lab are organized in:  
➡️ `AWS-CLI-Practice/S3-Bucket-Permission-Lab/screenshots/`

Each step is documented for proof of work and learning clarity.

---

## 💬 Final Thought

> “Always learning. Always building. Always improving.”

This lab wasn’t easy — but that’s what made it valuable.  
Every error taught me more than a course ever could.  
I didn’t just complete a project — I proved to myself I can build, break, and fix in AWS.

👩🏽‍💻 *– Margaret Johnson*

