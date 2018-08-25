# 上传本地项目到github <br>
  1. 在github创建仓库 <br>
  2. 添加<font color=red>个人公钥 </font>
  3. 在本地新建文件夹test  `mkdir test` <br>
  4. 初始化git `git init` <br>
  5. 将本地仓库可github得仓库链接 `git remote add origin url` <br>
  6. 拉去githud仓库的主分支代码 `git pull origin master` <br>
  7. 查看本地代码状态： `git status ` <br>
  8. 将文件全部加入本地仓库 ` git add .` <br>
  9. `git commit -am 'des'` <br>
  10. 将文件推送到github ` git push ` <br>
  * * *
  # 从云拉去代码 
  `git pull origin master` 拉去项目主分支 <br>
  `git pull origin ortherBranch` 拉去其他分支代码 <br>
