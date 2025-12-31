# 如何本地部署 CourseViz

这个文件夹包含了 CourseViz 网站的所有静态文件。由于现代浏览器对安全性的限制（CORS 策略），直接双击打开 `index.html` 可能无法正常加载某些功能。

推荐使用以下任意一种方法来运行网站：

## 方法一：使用 Python (推荐，无需安装额外软件)

如果您电脑上安装了 Python (Mac 和 Linux 通常自带)：

1. 打开终端 (Terminal) 或命令提示符 (CMD)。
2. `cd` 进入到解压后的文件夹目录。
3. 运行以下命令：
   ```bash
   python -m http.server
   # 或者 python3 -m http.server
   ```
4. 在浏览器中访问：`http://localhost:8000`

## 方法二：使用 Node.js

如果您安装了 Node.js：

1. 在终端中运行：
   ```bash
   npx serve
   ```
2. 访问终端显示的地址（通常是 `http://localhost:3000`）。

## 方法三：使用 VS Code Live Server

如果您使用 VS Code：

1. 用 VS Code 打开此文件夹。
2. 安装 "Live Server" 插件。
3. 右键点击 `index.html`，选择 "Open with Live Server"。

---
文件结构说明：
- `index.html`: 网站入口文件
- `assets/`: 包含网站所需的图片、样式和脚本文件
