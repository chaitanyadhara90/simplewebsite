# simplewebsite
Simple website hosting on AWS Instance
create a new instance in aws console


amazon linux commands
sudo su
yum update -y
cd /var/www/html


create a simple html code 
as below
vim welcome.html
<html>
<title> Welcome </title>
<head> <h1> Simple web site host</h1>
<body> This is a sinple website hosted onn aws instacne</body>
</html>

:wq! //to save the file command is 

//To install httpd server
yum install httpd -y

commands for checking webiste : 
-----------------------------
systemctl status httpd
systemctl enable httpd
systemctl start httpd
systemctl restart httdp
systemctl stop httpd

enable security group http & https
open public ip 
publicip:80
website will be open.
------------------------------------------XXX---------------------------------------
