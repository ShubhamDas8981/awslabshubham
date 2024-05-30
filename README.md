#!/bin/bash
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash -
apt-get install -y nodejs
git clone http://github.com/sudip7407/Repo1.git
cd Repo1
npm install
node index.js


sudo nano infy.sh
sudo chmod +x infy.sh
sh infy.sh
#!/bin/bash
while(true)
do
echo "Inside loop"
done

location /  {
        proxy_pass http://localhost:4000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
    }
hosting on Ec2
sudo apt-get update
sudo apt-get upgarde
sudo apt-get install nginx
nginx -v
cd /
ls
cd var
ls
cd www
sudo chmod 777 html


local pc to github:
echo "# aws_practice" >> README.md
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SOUMYADIP76/aws_practice.git
git push -u origin main

github to local machine
git clone https://github.com/SOUMYADIP76/aws_practice.git


project github to EC2
sudo apt-get update
sudo apt-get upgarde
sudo apt-get install nginx
nginx -v
curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash
sudo apt install nodejs
git clone https://github.com/SOUMYADIP76/AWS_project1.git
ls
cd aws_project1
npm install
node index.js


project Github to EC2 by creating secrutiy group
//write in during creation of instance on ec2 advance settings
#!/bin/bash
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash -
apt-get install -y nodejs
git clone https://github.com/SOUMYADIP76/AWS_project1.git
cd AWS_project1
npm install
node index.js


project github to EC2 without port
sudo apt-get update
sudo apt-get upgarde
sudo apt-get install nginx
nginx -v
curl -SL https://deb.nodesource.com/setup_16.x|sudo -E bash
sudo apt install nodejs
git clone https://github.com/SOUMYADIP76/AWS_project1.git
ls
cd aws_project1
npm install
node index.js

//in another cmd promt
cd /
cd etc/nginx/sites-available/
sudo nano default

location /  {
        proxy_pass http://localhost:4000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
    }
sudo systemctl restart nginx

//load balance
pwd
sudo nano infy.h
while(true)
do
	echo "inf loop"
done
