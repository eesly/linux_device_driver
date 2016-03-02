# add ssh key 
- ssh-keygen -t rsa -C "you comment" 可以采用默认设置enter即可
- cat ~/.ssh/id_rsa.pub 然后拷贝
- 将拷贝内容复制到 github账号主页-右上角setting-SSH keys-New SSH key-第二个输入框中，然后起一个名字
- 查看当前本地resp的远程resp的url
~~~
git remote -v 
~~~
- 如果是https则改为git,在网页上复制ssh的url然后在本地输入
~~~
git remote set-url origin 复制的url
~~~
- 之后就可以不用输入密码了~
