node -v # for checking nodejs is ready installed

npm -v # for checking npm is ready installed

git clone https://github.com/krishnasrinivas/wetty

cd wetty

sudo npm install
 

change PasswordAuthentication to yes in /etc/ssh/sshd_config

run user change root shell

modify /etc/passwd for changing root after guest logined in

chmod 755 loginin.sh # That must be done!

sudo nohup node app.js -p 3100 & # for running wetty
