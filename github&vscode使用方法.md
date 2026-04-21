### 新建仓库+vscode终端直接复制使用

一、首次使用（配置git + SSH）

```bash
git config --global user.name "ugyhybnb"
git config --global user.email "heyabo1116@gmail.com"
git config --global core.sshcommand"C:/Windows/System32/OpenSSH/ssh.exe"
```

二、全新项目 - 推送到Github

```bash
git init
git remote add origin git@github.com:ugyhybnb/你的仓库名.git
git pull origin main --allow-unrelated-histories
git add . 
git commit -m "initial commit"
git push -u origin main
```

三、日常使用

```bash
git add .
git commit -m "这里写你改了什么，作为提示信息"
git push
```

四、拉取最新代码

```bash
git pull
```

