# New-Project
My new project

2018-07-05

####git常用指令

1. git status 查看状态

2. cat readme.md 查看文件内容

3. git add test.txt 添加文件到暂存区

4. git commit -m "describelo" 提交到代码仓库

5. Ctrl+C 退出命令行

6. git log 查看操作日志

7. git reflog 查看历史操作日志

8. git reset --hard HEAD^ 版本回退到上一个版本

9. git reset --hard 1094a   版本回退到commit id（版本号）等于1094a....的版本

10. rm test.txt 删除本地文件 git rm test.txt 版本库中删除该文件再git commit提交

11. git checkout -- readme.txt 让这个文件回到最近一次`git commit`或`git add`时的状态。 

12. git remote add origin git@github.com:huangyuc88/New-Project.git 加入远程GitHub库

13. git clone git@github.com:huangyuc88/New-Project.git 从远程库克隆到本地

14. git push -u origin master 第一次推送`master`分支时，加上了`-u`参数 

15. git push origin master 提交更新到GitHub

16. ```
    git branch dev  创建分支dev
    git checkout dev切换到分支dev
    可以用 git checkout -b dev 代替
    git branch列出所有分支
    当前分支前面会标一个*号。
    在dev分支上修改文件后正常提交，然后切换回master分支，可以看到刚才修改的内容不见了！因为那个提交是在dev分支上，而master分支此刻的提交点并没有变。
    git merge dev
    git merge命令用于合并指定分支到当前分支。合并后，再查看readme.txt的内容，就可以看到，和dev分支的最新提交是完全一样的。
    git branch -d dev 删除分支
    ```

sdgsdgsdg



