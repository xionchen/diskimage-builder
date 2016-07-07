=======
passwd
=======
Use this element to set a password for a certain user(Default user is root,default password is rootpasswd)

You can customeize your password and password of user by changing the content of  environment.d/10-linux-user-passwd.bash

Example:disk-image-create centos7 passwd vm   can build a centos7 bootable mirror with root password which is 'rootpasswd'.(If you haven't changed the content of environment.d/10-linux-user-passwd.bash ) 
