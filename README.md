# AWS CLI Lab: S3 Bucket Creation, IAM Security & Real-World Troubleshooting

🔹 **Author:** Margaret Johnson  
🔹 **Project Type:** Hands-On AWS Lab  
🔹 **Focus Areas:** AWS CLI, S3, IAM, Troubleshooting, Public Access Policies

---

## 🌟 Why I Built This Lab

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

### ⚠️ What I Struggled With:
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

### ⚠️ What I Struggled With:
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

## 🧬 What I Learned

- How to use AWS CLI to configure, build, and clean up cloud resources  
- How to apply JSON-based bucket policies from the command line  
- Why it's critical to unblock public access in the AWS console  
- How to manage access credentials, folders, and version control  
- How to explain what I built in both human and technical language

---

## 🧹 Cleanup Confirmation

All AWS resources were deleted at the end of this lab:  
- File removed via AWS Console  
- Bucket deleted using `aws s3 rb`  
- Verified using `aws s3 ls`

📸 Screenshot proof included in `screenshots/`

---

## 📜 Project Folder Structure

```
AWS-CLI-Practice/
└── S3-Bucket-Permission-Lab/
    ├── README.md
    ├── aws_commands.md
    ├── test.txt
    ├── bucket_policy.json
    └── screenshots/
```

---

## 🔐 Security Note

All IAM credentials, AWS account numbers, and access keys were redacted or deleted.  
This lab was created using Free Tier resources and safely cleaned up.

---

## 💬 Final Thought

> “I am Always learning. Always building. Always improving.”

This lab wasn’t easy — but that’s what made it valuable.  
Every error taught me more than a course ever could.  
I didn’t just complete a project — I proved to myself I can build, break, and fix in AWS.

👩🏾‍💻 *– Margaret Johnson*
```
