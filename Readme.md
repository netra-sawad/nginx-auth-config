- Install nginx
   sudo apt install nginx
- check the status of Nginx
   sudo systemctl status nginx
- inside /etc all configuration file , for nginx configuration
    cd /etc/nginx/
- Entry point of the nginx is the file
   nginx.config
- Create the  .conf fiele

- Save the user name and password in .htpasswd 

- Save username
   sudo  sh -c "echo -n 'username:' >> /etc/nginx/.htpasswd"
- save password
   sudo sh -c "openssl password -apr1 >> /etc/nginx/.htpasswd"

