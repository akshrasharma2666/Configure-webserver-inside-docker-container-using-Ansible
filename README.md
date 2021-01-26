# Configure-webserver-inside-docker-container-using-Ansible
Task-14.2 ARTH.....!!


Task Description📄

🔰Write an Ansible PlayBook that does the following operations in the managed nodes:
🔹 Configure Docker
🔹 Start and enable Docker services
🔹 Pull the httpd server image from the Docker Hub
🔹 Run the docker container and expose it to the public
🔹 Copy the html code in /var/www/html directory and start the web server(Task-10)

In above task, You have to create an Ansible playbook that will retrieve newContainer IP and update the inventory. So that further Configuration of Webserver could be done inside that Container.(Task-14.2)

Hint:- Use Blockinfile module and
       Use customize docker image(your own customize docker image)
       
Output check by: https://baseOS_public_ip:exposePort/html_page
