#Answers and commands
sudo : it's a command that give the user admin previleges while executing other commands.
get  : it is a command used to install software packages 
IP adress : 34.245.27.185

Checkpoint 4 : 2)
To create the file .env i used cp .env.example .env   which copies the file

Checkpoint 6 : 2) 
sudo chgrp -R www-data storage bootstrap/cache : recursively changes a group name that a file belongs to 

sudo chmod -R ug+rwx storage bootstrap/cache : recursively changes the file's permissions i.e we're adding permissions : read write execute to the users and group

The commands i used:
My internet was very laggy so my terminal kept exiting, therefore i cannot access the history however here are the commands i used ( might be missing a couple)

sudo apt install apache2 mysql-server php-mysql php libapache2-mon-php php-pear curl php-curl php-cli git
sudo add-apt-repository ppa:ondrej/php
sudo apt-get install php7.1-mcrypt
sudo a2enmod rewrite 
sudo /etc/init.d/apache2 restart

cd / && cd html && cd www && cd html 
pwd
sudo git clone <link>

cd stunning-laravel
curl -sS https://getcomposer.org/installer | sudo php -- -- install-dir=/usr/local/bin -- filename=composer
composer install

pwd
sudo cp .env.example .env
sudo vim .env ( change it ) 
php artisan key:generate 

ps -ef | grep -i "httpd\|apache2"
sudo which apache2
cd /etc/apache2
sudo vim apache2.conf (change it)
cd sites-enabled
vim 000-default.conf  ( change it )
sudo /etc/init.d/apache2 restart

cd / && cd /var/www/html/stunning-laravel
sudo chgrp -R www-data storage bootstrap/cache
sudo chmod -R ug+rwx storage bootstrap/cache
