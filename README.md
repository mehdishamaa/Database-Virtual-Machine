# Database-Virtual-Machine


## Multi-Machine Vagrant 

## Steps to install VM:            
- vagrant up 
- vagrant ssh
- sudo apt-get update -y
- sudo apt- get instal nginx
- systemctl status nginx  


--------

RAKE SPEC
- rake spec runs the the test written rakefile 
- if tests fail 
- install packages for success
- inside the vm run:
	- sudo apt-get update
	- sudo apt-get install nginx 
	- systemctl status nginx (checks status)
	- sudo apt-get upgrade
	
	- __install node js__
	- pm2 
	- sudo apt-get install -y nodejs
	- run in root sudo su
	- npm install pm2 -g  

	- cd app 
	- npm install in the app folder 
	- development.localhost:3000
	
	- touch nginx_installation_script.sh
	- chmod +x turns files into executable 
	- chmod +x nginx_installation_script.sh	
  
  
  
  
  To test the app is running, run node app.js
