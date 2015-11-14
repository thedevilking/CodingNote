git使用帮助
===

github上clone私有仓库问题
---
 1. 如果clone的仓库是私有的，会出现403拒绝访问的问题。
 >解决办法：首先配置SSH key,然后配置git config 的用户名和邮箱来尝试访问。
 >如果依旧不能clone，那么可以通过 git clone https://username@github.com/target-username/repository.git 的方式输入密码来clone。这里的username是自己在github上的账户，而target-username则是要clone的私有仓库的所有者的id。
 >参考链接：http://stackoverflow.com/questions/10054318/how-to-provide-username-and-password-when-run-git-clone-gitremote-git