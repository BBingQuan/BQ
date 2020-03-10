#[[任务详情：Github/BBingQuan/BQ]](https://github.com/BBingQuan/BQ)
##Git学习笔记-基础部分：
###一、关于Git的理解：开源的程序保存共享平台；

###二、学习过程及问题的解决：
    1、注册建库，安装git；
    2、打开git（bash/cmd/gui）
    输入  $ mkdir learngit//创建learngit
         $ cd learngit//创建.git
         $ pwd//路径
         /Users/michael/learngit
    或在选定文件夹鼠右Gitbash here(GUI/CMD也可)；
    3、git init初始化，建立.git文件；
    4、 git config --global user.name "xxx"
        git config --global user.email "xxx"
    (Please tell me who you are——格式规范，注意空格);
    5、创建密钥ssh-keygen -t rsa -C "xxx@xxx.com"，
    到显示的对应文件夹拷贝密钥（查无密钥文件——ls显示隐藏文件）
    6、打开id_rsa.pub全部拷贝，粘贴至github-settings-ssh-keys；
    7、回到gitbash，输入 ssh -T git@github.com，出现You've successfully authenticated
    (输入后出现warning...yes/no?回答yes);
    8、创建readme.txt测试，vi readme.txt ,按i然后输入文本，
    完毕按esc然后：wq保存返回；
    9、单个文件git add xxx(文件名)或整个文件夹git add .缓存；
    (LF will be replaced by CRLF in——不同操作系统所使用的换行符不同，git config --global core.autocrlf false即可);
    10、$ git commit -m "备注"提交到仓库；(注意空格)
    成功[master (root-commit) eaadf4e] wrote a readme file
        1 file changed, 2 insertions(+)
        create mode 100644 readme.txt；
    11、输入git push -u origin master或分支origin branchxxx提交到远程仓库(fatal: 'origin'does not appear to be a git repository——git remote add origin git@github.com:用户名/仓库.git)
###三、补充及尝试：
1、补充：

    git status查询状态；
    git diff查询修改内容；
    git log日志；git rm删除；
    git clone远程拷贝至本地；
2、建立多个分支，并上传已有文件至远程仓库：

[https://github.com/BBingQuan?tab=repositories]()
###四、感想：
第一次尝试在后台上传至网页中，很感兴趣，也对此系统感到好奇，更加坚定了我学习Linux开发系统的决心，不过目前能力不足，仍需努力。
    






