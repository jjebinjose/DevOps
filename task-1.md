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



![WhatsApp Image 2025-03-18 at 10 17 44_2fe2c551](https://github.com/user-attachments/assets/e640c5fb-c815-4e19-b390-c6a7cb98dc70)
![WhatsApp Image 2025-03-18 at 10 17 43_9aa7a44a](https://github.com/user-attachments/assets/d5a91200-5b9e-4813-83c9-0319ef977627)
![WhatsApp Image 2025-03-18 at 10 17 43_7ece30e3](https://github.com/user-attachments/assets/99b802a7-9f54-4465-84db-af00188b0614)
![WhatsApp Image 2025-03-18 at 10 17 44_a1931c81](https://github.com/user-attachments/assets/8df79c49-06cb-4db7-a80a-f0fe6be72eeb)
