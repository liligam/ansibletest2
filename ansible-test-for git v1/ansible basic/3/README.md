# 3-1 project 개요 설명 및 필요한 도구 설명

우리는 KodeKloud 전자상거래 웹사이트를 구축하기 위한 플레이북을 개발할 것입니다.

KodeKloud 전자 상거래 웹 사이트는 가상의 온라인 스토어입니다.

전자기기를 파는 곳이죠 램프 스택 응용 프로그램입니다.

그림에서 나타나는 것과 같이

MariaDB

php
httpd

등을 사용해보겠습니다

# 3-2 project 시작

기존 사용하던 c# 서버에서 시작하겠습니다

#sudo yum install -y firewalld

#sudo service firewalld start

#sudo systemctl enable firewalld

#sudo yum install -y mariadb-server

#sudo service mariadb start

#sudo systemctl enable mariadb

#sudo service mariadb status

#sudo firewall-cmd --permanent --zone=public --add-port=3306/tcp

#sudo firewall-cmd --reload

#mysql






이렇게 저장

#mysql

#show databases;

#use ecomdb;

#select * from products;


#sudo yum install -y httpd php php-mysql

#sudo firewall-cmd --permanent --zone=public --add-port=80/tcp

#sudo firewall-cmd --reload

#sudo firewall-cmd --list-all

#sudo service httpd start

#sudo systemctl enable httpd

#sudo service httpd status

#sudo yum install -y git

#git clone https://github.com/kodekloudhub/learning-app-ecommerce.git /var/www/html/

#cd /var/www/html/

#vi index.php




