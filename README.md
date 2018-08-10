# HOW TO USE #
1. get repo  
$ curl https://mirrors.tuna.tsinghua.edu.cn/git/git-repo -o repo  
$ chmod +x repo 
2. replace REPO\_URL  
$ vi repo +8  
REPO\_URL='https://mirrors.tuna.tsinghua.edu.cn/git/git-repo/'
3. download source  
$ export PATH=$PATH:$PWD  
$ repo init -u https://github.com/Ethan-Gao/repo-sample.git
