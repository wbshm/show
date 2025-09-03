# 个人作品展示网站

这是一个个人作品展示网站，托管在 GitHub Pages 上，用于展示我的开发项目。

## 项目特点

- 🎨 现代化的响应式设计
- 📱 移动端友好
- 🚀 快速加载
- 📊 项目展示和介绍
- 🔗 二维码扫描体验

## 包含项目

### 三角形计算器
一个功能强大的三角形计算工具，可以计算三角形的各种属性。

- 查看项目详情：[三角形计算器页面](mini_triangle.html)
- 扫描二维码体验：[项目二维码](mini_triangle/screenshot/qrcode.png)

## 技术栈

- HTML5
- CSS3
- JavaScript
- GitHub Pages

## 访问网站

🌐 **在线访问**: [https://yourusername.github.io/show](https://yourusername.github.io/show)

## 本地开发

1. 克隆仓库
```bash
git clone https://github.com/yourusername/show.git
cd show
```

2. 使用本地服务器运行
```bash
# 使用 Python
python -m http.server 8000

# 或使用 Node.js
npx serve .

# 或使用 PHP
php -S localhost:8000
```

3. 在浏览器中访问 `http://localhost:8000`

## 部署

网站通过 GitHub Actions 自动部署到 GitHub Pages。每次推送到 `main` 分支时，网站会自动更新。

## 项目结构

```
show/
├── index.html              # 主页面
├── mini_triangle.html      # 三角形计算器项目页面
├── styles.css              # 样式文件
├── PROJECT_DOCS.md         # 项目文档
├── mini_triangle/          # 三角形计算器项目
│   └── screenshot/         # 项目截图
│       ├── qrcode.png     # 项目二维码
│       ├── shot1.PNG      # 项目截图1
│       └── shot2.PNG      # 项目截图2
└── .github/
    └── workflows/
        └── deploy.yml     # GitHub Actions 部署配置
```

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！

## 许可证

MIT License
