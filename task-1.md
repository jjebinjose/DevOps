# Installing and Configuring Nginx using Jenkins

In this assignment, I used Jenkins to automate the installation and configuration of Nginx on an  
Ubuntu system. I created a Freestyle Project in Jenkins and added a shell script in the build step  
to:

1. Update package lists using `sudo apt update`.  
2. Install Nginx using `sudo apt install -y nginx`.  
3. Enable and start the Nginx service using `sudo systemctl enable nginx` and `sudo systemctl start nginx`.  
4. Allow HTTP traffic (port 80) through the firewall using `sudo ufw allow 80/tcp` and `sudo ufw reload`.  
5. Verify Nginx status using `sudo systemctl status nginx --no-pager`.  

After successfully building the project in Jenkins, I accessed Nginx’s default web page using  
`http://127.0.0.1:80`. Finally, I verified the installation using terminal commands and  
documented the process with screenshots.  


![Screenshot from 2025-03-19 09-08-56](https://github.com/user-attachments/assets/0ef9809a-a806-462c-b5a4-f865c4947921)
![Screenshot from 2025-03-19 09-09-27](https://github.com/user-attachments/assets/cde56370-dc85-4b77-b9cd-5245c8bb4e67)
![Screenshot from 2025-03-19 09-09-47](https://github.com/user-attachments/assets/44545e59-b364-4f06-b538-98765d036fb0)
![Screenshot from 2025-03-19 09-10-31](https://github.com/user-attachments/assets/2bf1e595-9c87-465b-8bfe-d745d1d731e4)
