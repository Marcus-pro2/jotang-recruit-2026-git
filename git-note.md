# Git学习笔记
## 基础命令
1. `git config --global user.name "名字"` 设置全局用户名
2. `git config --global user.email "邮箱"` 设置全局邮箱
3. `git clone 仓库地址` 将远程仓库下载到本地
4. `git status` 查看当前文件改动状态
5. `git add 文件名` 将文件加入暂存区
6. `git commit -m "提交描述"` 生成本地版本快照
7. `git push` 将本地版本推送到远程GitHub仓库
8. `ssh-keygen -t rsa -b 4096 -C "邮箱"` 生成SSH密钥，实现免密码访问github

## 学习总结
完整流程：创建远程仓库 → clone到本地 → 修改/新增文件 → add暂存 → commit提交本地 → push推送到远程仓库。
