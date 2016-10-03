# git_workspace

git --version
#
mkdir mygit_workspace
cd mygit_workspace
git init
git add test.txt
git commit -m "创建了一个test文本"
ssh-keygen -t rsa -C "youremail@example.com"
cd mygit_workspace

git remote add origin git@github.com:zzxb/mygit_workspace.git
git push -u origin master
git push origin master
git pull
git clone git@github.com:zzxb/mygit_workspace.git
Host git.coding.net
    HostName        git.coding.net
    User            yourname
    IdentityFile    /Users/zzxb/.ssh/id_rsa

Host github.com
    HostName        github.com
    User            yourname
    IdentityFile    /Users/zzxb/.ssh/github

