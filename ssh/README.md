#如果第一次使用
设置用户名和邮箱

git config --global user.name "Luke.Deng"
git config --global user.email  "xiangshuo1992@gmail.com"
#非第一次使用
cd ~/.ssh

ls

或者

ll

//看是否存在 id_rsa 和 id_rsa.pub文件，如果存在，说明已经有SSH Key

如果没有，创建密匙

ssh-keygen -t rsa -C "xiangshuo1992@gmail.com"

cat id_rsa.pub

将密匙复制到github