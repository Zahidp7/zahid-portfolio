# Zahid's Portfolio Website

This is my personal portfolio website, built using plain HTML and hosted on an AWS EC2 instance. The purpose was to get hands-on experience with Linux, EC2, Apache, and GitHub.

---

## 🔧 What I Did

- Created an EC2 instance (Amazon Linux 2)
- Installed Apache web server to serve the site
- Transferred my `index.html` file to the Apache root directory
- Allocated an Elastic IP for consistent access
- Configured security groups to allow HTTP (port 80)
- Installed Git, initialized a local repo, and pushed the project to GitHub

---

## 📁 Files

- `index.html`: My portfolio homepage
- `README.md`: This file you're reading right now

---

## 💡 Commands I Used

**Apache Installation**
```bash
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
