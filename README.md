hustoj from centos shell</br>
hustoj对centos的部署说明还是不是很清晰，所以写了个脚本能够做到自动化部署</br>
注册用户之后在数据库操作：</br>
use jol;</br>
insert into privilege(user_id,rightstr) values('admin','administrator');</br>
exit</br>
把hustoj的脚本稍加修改，做了一个centos一键搭建的脚本</br>
有问题请联系:</br>
tencent://AddContact/?fromId=50&fromSubId=1&subcmd=all&uin=954623886</br>
Email：954623886@qq.com</br></br></br></br></br>
安装完成后，注册用户并提升为管理员权限。</br>
next 修改以下配置文件，扯句英文。0.0</br>
chenge your /home/judge/etc/judge.conf </br>
adminuser and passwd for your user</br>
</br></br></br>
说下安装过程命令（在腾讯云centos6.5）：</br>
yum install git</br>
git clone https://github.com/knickersgod/oj.git</br>
cd oj</br>
chmod -R 777 *</br>
./install.sh</br>
