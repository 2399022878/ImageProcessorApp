每次开始写的时候，请记得开启虚拟环境：

```bash
.\env\Scripts\activate
```

git流命令行记录

- 关联你在github上创建的仓库

```
git remote add origin https://github.com/2399022878/ImageProcessorApp.git
```

- 提交代码到github

```
# 初始化本地仓库（如果尚未初始化）
git init

# 添加文件并提交
git add .
git commit -m "Initial commit"

# 关联远程仓库（首次）
git remote add origin https://github.com/2399022878/ImageProcessorApp.git

# 推送到远程
git push -u origin main
```

- 或者vscode里点source control图标（ctrl+shift+g）,勾选文件并输入提交信息
- 每日开发流程

```
git pull origin main  # 开始前先拉取最新代码
git checkout -b dev-feature1  # 为新功能创建分支
# 开发完成后...
git add .
git commit -m "Add image resize function"
git push origin dev-feature1
# 在 GitHub 提交 Pull Request 合并到 main
```
