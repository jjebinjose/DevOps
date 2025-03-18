# DevOps

For this assignment, I used Jenkins to automate the installation and configuration of Nginx on an Ubuntu system. I created a Freestyle Project in Jenkins and included a shell script in the build step to:

Update the package lists with sudo apt update.
Install Nginx using sudo apt install -y nginx.
Enable and start the Nginx service with sudo systemctl enable nginx and sudo systemctl start nginx.
Allow HTTP traffic (port 80) through the firewall by running sudo ufw allow 80/tcp followed by sudo ufw reload.
Verify the Nginx service status using sudo systemctl status nginx --no-pager.
After successfully building the Jenkins project, I accessed the default Nginx web page via http://127.0.0.1:80. Finally, I validated the installation using terminal commands and documented the entire process with screenshots.









![WhatsApp Image 2025-03-18 at 10 17 44_2fe2c551](https://github.com/user-attachments/assets/59d4653c-e963-4118-a205-cc76c2650ff2)
![WhatsApp Image 2025-03-18 at 10 17 43_9aa7a44a](https://github.com/user-attachments/assets/2fe0a220-e5e0-4312-8e91-7421ae2de566)
![WhatsApp Image 2025-03-18 at 10 17 43_7ece30e3](https://github.com/user-attachments/assets/c797b550-836f-46d3-8c01-2b54eecfa87d)
![WhatsApp Image 2025-03-18 at 10 17 44_a1931c81](https://github.com/user-attachments/assets/aeee9f08-0561-4630-a1c5-2e1d40537de3)
