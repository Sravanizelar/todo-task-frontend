Fallowing are steps need to fallow in frontend in  todo task
#apt update 
#apt install nginx 
#apt install nodejs
#apt install npm -y
#cd /var/www/html/
#mkdir todo
#cd todo/
#git clone https://github.com/zelar-soft-todoapp/frontend.git
#ls
#cd frontend
#npm install
#npm run build
#vi /etc/nginx/sites-enabled/default Here we changed"root /var/www/html/todo/frontend/dist"
#systemctl restart nginx
#systemctl enable nginx
#vi config/index.js In this page we updated required private ip's"
#systemctl restart nginx
#systemctl enable nginx
#npm start
Take public ip of the server with 8080 port
