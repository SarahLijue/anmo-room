# ANMO ROOM

一个可直接部署的静态网页五子棋小游戏。手机和电脑浏览器均可使用，两个人共用一台设备轮流落子。

## 本地预览
直接用浏览器打开 `index.html` 即可。

## 免费发布到 GitHub Pages
1. 登录 GitHub，创建一个新的 **Public** 仓库，例如 `anmo-room`。
2. 将本文件夹中的 `index.html` 上传到仓库根目录（README 可一起上传）。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/ (root)`，点击 **Save**。
6. 等待发布完成，GitHub 会提供一个公开网址，通常形如：
   `https://你的GitHub用户名.github.io/anmo-room/`

## 游戏说明
- 15×15 标准棋盘，黑棋先手。
- 两人同设备轮流下棋。
- 支持悔棋、重新开始和本局胜负计分。
- 无需登录、无需后端服务。
