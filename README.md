

# Abhishekh's First EC2 Website 🚀

This is my very second project hosted using **Amazon EC2 (Elastic Compute Cloud)**!  
The site simply displays a "Hello World" message — all deployed from a cloud server 💻☁️

## 🌐 Live Project Description
- **Tech Used**: HTML, Amazon EC2 (t2.micro), Git bash
- **Hosting**: Deployed manually via Apache on EC2
- **Purpose**: To learn cloud infrastructure and static website hosting

## 📷 Screenshots

### 1. EC2 Instance Running
<img width="959" height="405" alt="ec2-instance-running" src="https://github.com/user-attachments/assets/a1d62db1-8d53-4fb0-9baf-9a1bd8f22a0c" />

### 2. Security Group with Port 80 Open
<img width="947" height="376" alt="security-group" src="https://github.com/user-attachments/assets/d7d1bdf3-519e-47fa-b28a-bad3c1499793" />


### 3. Website Live in Browser

<img width="419" height="165" alt="live-website" src="https://github.com/user-attachments/assets/7b27bc9d-aaf4-4169-be86-08d6c602ef4d" />

Steps I Followed
1. Launched EC2 instance on AWS
2. Configured **Security Group** to allow HTTP (port 80)
3. Installed Apache using:
   ```bash
   sudo yum update -y
   sudo yum install httpd -y
4. Enabled Apache:
   sudo systemctl start httpd
   sudo systemctl enable httpd
5. Uploaded the index.html:
   sudo mv index.html /var/www/html/
<img width="548" height="475" alt="Apache" src="https://github.com/user-attachments/assets/378f9e6d-9470-4b64-a58e-4d7835e2633e" />












   

