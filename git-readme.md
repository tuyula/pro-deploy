#Git 使用规范///

$设置自己的用户名与密码
git config --global user.name "username"
git config --global user.email "your email"

$设置自己的SSH Key
ssh-keygen -t rsa -C "Your Email"
cd ~/.ssh
将id_rsa.pub将公钥发送给Github管理员

$克隆项目
git clone https://github.com/tuyula/pro-deploy.git

$创建分支
git branch dev-yourname(你的分支名)
git checkout dev-yourname(切换分支名)
git branch(查看自己是否切换成功到分支)

$进行代码修改后，提交代码到缓存区
git add change.txt(提交修改的文件到缓冲区)
git commit -m "提交说明"

$如果你完成了今天任务，就可以把本地分支的内容提交到github上
git push origin dev-yourname









