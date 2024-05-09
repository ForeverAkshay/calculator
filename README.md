# calculator
Create linux image
Select instance copy auto assigned api
Paste it
Connect
Sudo su –
yum update -y
Yum install -y httpd
Systemctl status httpd
mkdir aws_assg3
cd aws_assg3
wget (paste gtihub repo uri)
ls -lrt
wget (got to github -> download zip -> github cli)
ls -lrt
unzip master.zip
ls -lrt
cd Smitafulari_Portfolio-master
ls -lrt
mv * /var/www/html/
cd /var/www/html
ls -lrt
select instance -> security groups -> add http and https anywhere ,web port
status httpd
systemctl enable httpd
systemctl start httpd
