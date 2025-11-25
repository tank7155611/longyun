# 部署指南：如何将网站发布到 GitHub Pages

这份指南将帮助您将个人网站免费发布到互联网上，让所有人都能访问。

## 第一步：准备 GitHub 账号
如果您还没有 GitHub 账号，请先访问 [github.com](https://github.com/) 注册一个。

## 第二步：创建新仓库
1. 登录 GitHub。
2. 点击右上角的 **+** 号，选择 **New repository**。
3. 在 **Repository name** 中输入项目名称，例如 `my-portfolio` 或 `resume-site`。
4. 确保选择 **Public**（公开）。
5. **不要**勾选 "Initialize this repository with a README"（因为我们本地已经有文件了）。
6. 点击 **Create repository**。

## 第三步：上传代码（网页版 - 无需代码）

1.  在您刚才创建的 GitHub 仓库页面中，点击 **Add file** 按钮，然后选择 **Upload files**。
2.  打开您电脑上的项目文件夹 `c:\Users\龙云\Desktop\pr-ati`。
3.  **全选**文件夹中的所有文件（`index.html`, `style.css`, `script.js`, `profile_photo.png` 以及 `images` 文件夹等）。
    *   *注意：请确保不要漏掉 `images` 文件夹和 `profile_photo.png`，否则图片无法显示。*
4.  将选中的文件直接**拖拽**到 GitHub 的网页上传区域中。
5.  等待所有文件上传进度条走完。
6.  在页面底部的 **Commit changes** 区域，直接点击绿色的 **Commit changes** 按钮。

## 第四步：开启 GitHub Pages
1.  文件上传成功后，点击仓库页面顶部的 **Settings**（设置）标签（通常在 Code, Issues 等标签的最右侧）。
2.  在左侧侧边栏菜单中，向下滚动找到 **Pages**（在 "Code and automation" 部分）。
3.  在 **Build and deployment** 下的 **Source** 保持选择 **Deploy from a branch**。
4.  在 **Branch** 下拉菜单中选择 **main** (或 master) 分支，右边的文件夹选择 **/(root)**。
5.  点击 **Save**（保存）按钮。

## 第五步：访问您的网站
1.  设置保存后，GitHub 会开始自动构建您的网站。
2.  停留在 Pages 设置页面，等待约 1-2 分钟。
3.  **刷新**该页面。
4.  您会在页面顶部看到一行提示：**Your site is live at...**
5.  点击那个链接，您的个人网站就正式上线了！您可以把这个链接发给任何人访问。

## 后续更新
如果您以后修改了简历内容：
1.  在电脑上修改好文件。
2.  回到 GitHub 仓库页面。
3.  再次点击 **Add file** -> **Upload files**。
4.  上传修改后的新文件。
5.  点击 **Commit changes**，网站会自动更新。
