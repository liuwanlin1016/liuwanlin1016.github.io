# 个人博客网站

这是一个个人博客网站项目，采用HTML、CSS构建，具有响应式设计，可在不同设备上良好展示。

## 项目特点

- 现代化设计风格
- 响应式布局，适配移动设备
- 包含个人简介、笔记、教育经历、期刊会议和学术项目展示模块
- 使用CSS3动画和过渡效果
- 采用Font Awesome图标库

## 如何上传到GitHub并部署为GitHub Pages

### 第一步：创建GitHub仓库

1. 登录GitHub账户
2. 点击"New"按钮创建新仓库
3. 填写仓库名称（例如：your-username.github.io 或 my-blog）
4. 选择"Public"（如果希望公开）或"Private"
5. 不要初始化仓库（不勾选README、.gitignore、license）
6. 点击"Create repository"

### 第二步：准备本地文件

1. 确保你有Git客户端已安装
2. 在本项目的根目录下，将所有文件准备好

### 第三步：使用Git上传项目

1. 打开命令行工具（如Git Bash或PowerShell）
2. 进入项目目录：
   ```bash
   cd "c:\Users\28587\Desktop\Myself\liuwanlin"
   ```

3. 初始化Git仓库：
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Personal blog website"
   ```

4. 连接到GitHub仓库：
   ```bash
   git remote add origin https://github.com/你的用户名/仓库名.git
   git branch -M main
   git push -u origin main
   ```

### 第四步：配置GitHub Pages

1. 在GitHub仓库页面，点击"Settings"选项卡
2. 向下滚动到"Pages"部分
3. 在"Source"下拉菜单中选择"Deploy from a branch"
4. 选择"main"分支和"/root"文件夹
5. 点击"Save"
6. 等待几分钟，GitHub会自动构建并部署你的网站

### 第五步：访问你的网站

- 在仓库的"Settings" -> "Pages"部分，你会看到网站URL
- 通常格式为：`https://你的用户名.github.io/仓库名`
- 如果仓库名为`你的用户名.github.io`，则直接可通过`https://你的用户名.github.io`访问

## 注意事项

- 确保主页面文件命名为`index.html`
- 如果希望网站域名为`https://你的用户名.github.io`（不带仓库名），可以将仓库名改为`你的用户名.github.io`
- 项目中使用了一些外部图片链接，如需完全本地化可下载到本地
- 项目中的链接跳转功能需要实际链接才能工作

## 自定义

你可以修改以下内容来自定义网站：

- 个人信息（姓名、简介、联系方式）
- 博客内容、教育经历和学术项目
- 颜色主题（在CSS中修改颜色值）
- 图片资源