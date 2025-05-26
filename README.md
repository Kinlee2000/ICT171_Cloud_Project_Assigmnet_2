# ICT171_Cloud_Project_Assigmnet_2
# ICT171 Cloud Server Project - [Your Name] ([Student Number])

## 🌐 Live Server
- http://yourdomain.com (or your public IP)

## 🎥 Video Explainer
- [Video Link Here]

## 📄 About the Project
This project is part of ICT171 - Introduction to Server Environments and Architectures.  
It demonstrates how to set up a personal portfolio website using an EC2 Ubuntu server, Apache2, and a domain name.

## 🛠️ Technologies Used
- AWS EC2 (t2.micro)
- Ubuntu 22.04 LTS
- Apache2
- GitHub
- Cloudflare (for DNS)

## 🧰 Setup Instructions (Short Summary)
1. Create an EC2 instance
2. Install Apache2: `sudo apt update && sudo apt install apache2`
3. Upload your portfolio site to `/var/www/html`
4. Configure DNS via Cloudflare to point your domain to the EC2 public IP
5. (Optional) Add SSL with Certbot

Detailed documentation can be found in `documentation.pdf`.

## 📜 License
MIT License (or your preferred license)
