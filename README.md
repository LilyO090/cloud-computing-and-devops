# 🌩️ Cloud Computing & DevOps Learning Journey

Hi, I'm Lily! I'm beginning my journey into Cloud Computing and DevOps.

---

## 📅 Learning Progress

- Week 1: Got introduced to cloud concepts (IaaS, PaaS, SaaS)
Started learning about AWS and created an S3 bucket

---

## 🔜 Coming Soon

- My notes on AWS services
- My first DevOps project (probably using Git or GitHub Actions)
- CI/CD pipeline practice

I'll keep updating this repo as I go!



# 🌩️ My Cloud Computing Journey: Introduction to AWS and Amazon S3 Bucket Features

Hi everyone! 👋  
As part of my journey into **Cloud Computing** and **DevOps**, I’ve been exploring **Amazon Web Services (AWS)** — one of the world’s leading cloud platforms. I’m documenting what I learn here, hoping it helps others who are just starting out, like me!

---

## 💡 What is AWS?

**Amazon Web Services (AWS)** is a **cloud computing platform** by Amazon that offers over 200 services for storing, computing, networking, security, artificial intelligence, and more.

In simple terms:  
> **AWS lets you rent computing power and storage over the internet instead of owning physical servers.**

This means:
- You don’t have to buy hardware.
- You only pay for what you use.
- You can scale (increase/decrease) easily based on your needs.

---

## ☁️ Types of Cloud Services in AWS

AWS offers different levels of cloud services. Here's a breakdown in **simple terms**:

### 1. IaaS – *Infrastructure as a Service*  
AWS provides the **raw infrastructure** — virtual machines, networking, and storage.

🖥️ Example: **Amazon EC2** (you rent a virtual computer/server).  
📦 You install and manage everything.

---

### 2. PaaS – *Platform as a Service*  
You get a **ready-to-use platform** to build and deploy applications without worrying about the underlying system.

🛠️ Example: **AWS Elastic Beanstalk**  
No need to manage OS, updates, or infrastructure.

---

### 3. SaaS – *Software as a Service*  
You use **ready-made software** hosted on the cloud — no coding or managing involved.

🧑‍💼 Example: **Google Docs, Gmail, Dropbox**  
Just sign in and start using.

---

## 🪣 Introduction to Amazon S3

One of the first AWS services I learned to use is **Amazon S3** — and it's amazing!

### ❓ What is S3?

S3 stands for **Simple Storage Service**.  
It allows you to **store files (called “objects”) in containers (called “buckets”)** on the cloud. You can store:
- Images, videos
- Backups
- Website files
- Documents

💾 Think of it as **your personal Google Drive on the cloud**, but with superpowers.

---
 🔍 Key Features of S3 Buckets

1. ✅ Lifecycle Management  
Automatically moves or deletes files based on rules you set.

📌 Example:  
- Move old logs to cheaper storage after 30 days.  
- Delete them after 90 days.  
This reduces storage cost without doing it manually.

---

 2. ✅ Bucket Policy  
Controls **who can access your bucket** and **what they can do**.

📌 Example:  
- Make a file public (e.g., image for a blog).  
- Restrict upload/download to your team only.

It’s like setting folder permissions.

---

 3. ✅ Data Encryption  
Protects your files by **locking them with encryption**.

📌 Two options:  
- *Server-side encryption* (AWS encrypts it for you).  
- *Client-side encryption* (you encrypt before uploading).

Even if a hacker gets the file, they can't read it.

---

 4. ✅ Versioning  
Keeps **every version** of a file — even after updates or deletions.

📌 Example:  
Upload `resume.pdf` today → upload a newer version tomorrow → both are saved.  
You can even recover deleted files!

🕒 Like Google Docs’ version history.

---

5. ✅ Cross-Region Replication (CRR)  
Copies your files automatically to **another AWS region** (another country/continent).

📌 Example:  
Main bucket in Europe → Replicated copy in Canada.  
Useful for backups or faster access globally.

---

6. ✅ Transfer Acceleration  
Speeds up file uploads/downloads for users **far from the S3 region**.

📌 Example:  
A user in Nigeria uploading to an S3 bucket in the US? Transfer acceleration uses AWS’s fastest route to upload faster.

⚡ Ideal for large files or international apps.

---

 ✨ Final Thoughts

Amazon S3 is powerful, and understanding these features has made me see how much control and flexibility cloud storage gives. I’m still learning, but documenting this helps me remember — and hopefully helps you too.

---

🔜 Coming Up Next:
- ✅ How I created my first S3 bucket step-by-step
- ✅ Hosting a static website using S3
- ✅ Setting up billing alerts to stay within Free Tier

Thanks for reading!  
Let’s keep learning  
Lily
