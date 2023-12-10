# as3p2-starter-f23

You will have to edit some of these files to get your web servers working.

The included backend server runs on port 8080, 127.0.0.1:8080

## Load Balancer Demo Video
- https://youtu.be/ZlpzJ6WgXiY

## Directories and Files
- hello-server: /var/www/hello-server
- hello-server.service: /etc/systemd/system/hello-server.service
- hello.conf: /etc/nginx/sites-available/hello.conf
- index.html: /var/www/my-site/index.html
- symbolic link: 
- ```sudo ln -s /etc/nginx/sites-available/hello.conf /etc/nginx/sites-enabled```
- cloud-config.yaml written when making droplet
## Included material

- backend binary, hello-server
- frontend, index.html
- nginx configuration file, hello.conf
- service file for backend, hello-server.service
- config for setting up servers, cloud-config.yml
- example curl commands for testing your server, curl.md
- README.md
