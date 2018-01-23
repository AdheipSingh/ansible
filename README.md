# ansible
This role is for installing LEMP STACK .
Before installing i had created a dependency to configure the Firewalld else you can manually open the ports.
You can change the variables accordingly to your will .
I have not done any changes in the default.conf a sepreate file will be created ie /etc/nginx/conf.d/server.conf.
Wordpress database and the fastcgi will be installed on the same server , you can change if you have a seperate DB server .


NOTE:: AT THE TIME OF DEPLOYMENT WORDPRESS LATEST VERSION WAS 7.1 , PLZ CHECK THE LATEST WORDPRESS VERSION AND DO THE CHANGES IN /nginx/tasks/php-fpm.yml , IN THE UNARCHIVE MODULE CHANGE THE WORDPRESS TO LATEST VERSION .
