# ACIT2420 Assignment 3 Part 2

This repository contains materials in order to run a reverse proxy server that will direct to a backend server located within the localhost.

The included backend server runs on port 8080, 127.0.0.1:8080

## Included material  
These are the materials with the file location they should be put into each server you want to run

- backend binary, hello-server, /var/www/my-site/ 
- frontend, index.html, /var/www/my-site/
- nginx configuration file, hello.conf, /etc/nginx/sites-available/ 
- service file for backend, hello-server.service /etc/systemd/system/
- config for setting up servers, cloud-config.yml, script is put in on droplet creation
- example curl commands for testing your server, curl.md, not required for the server
