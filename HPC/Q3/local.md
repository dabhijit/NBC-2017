[root@c09m ~]# cat /etc/yum.repos.d/local.repo 
[centos]
name=centos
baseurl=http://10.10.10.254/centos/x86_64/7.2/
enable=1
gpgcheck=0


[ganggpbs]
name=progang
baseurl=http://10.10.10.254/centos/x86_64/7.2_extras/
enable=1
gpgcheck=0

