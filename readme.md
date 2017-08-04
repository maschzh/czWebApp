#git 学习笔记
> 主要记录的是Git学习过程中的笔记
1. git add 文件
2. git commit -m 描述
3. git reset HEAD 文件/commit id
4. cat 文件 读文件
5. git status 文件状态
6. git rm -- 文件名
7. git checkout -- 文件名
8. git remote add origin git@github.com:maschzh/czWebApp.git
9. git push -u origin master
10. git pull --rebase origin master
11. git clone git@github.com:maschzh/czWebApp.git 克隆远程库
12. git branch dev 创建分支
13. git checkout -b dev 创建分支并迁出 相当于 git branck dev 和 git checkout -- dev
14. git branch -d dev 删除分支
15. git branch 查看分支
16. git merge <name> 合并分支到当前分支
17. git log --graph 产看分支合并图
18. git merge --no-ff -m "merge with no-ff" dev --no-ff参数，表示禁用Fast forward
19. git stash 把当前工作现场“储藏”起来，等以后恢复现场后继续工作