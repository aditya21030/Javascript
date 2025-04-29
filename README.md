# Javascript
JS practice

#!/bin/bash
apt-get update
apt-get install -y nginx
systemctl start nginx
systemctl enable nginx
apt-get install -y git
curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
apt-get install -y nodejs
git clone https://github.com/itsmesneha/SNEHAREPO
cd SNEHAREPO
npm install
node index.js
