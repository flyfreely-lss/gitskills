# git 解决方案列表

1. 在B仓库使用 cherry-pick 从A仓库合代码

   ```bash
   # 可以使用 git remote -v 查看git地址
   # 在B仓库下执行下列命令
   $ git remote add A xxx(A仓库的git地址) # 将另一个仓库添加到远端分支
   $ git fetch A # 拉取远端仓库的数据
   $ git cherry-pick xxx # 合并指定的提交
   ```

   

   

