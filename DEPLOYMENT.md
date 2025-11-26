# Deploy Stone Stories Game - 部署指南

## 最简单的方法 - 使用 Netlify Drop (推荐！)

这是最快的方法，无需注册或配置：

1. 访问：https://app.netlify.com/drop
2. 直接将 `index.html` 文件拖拽到页面上
3. 等待几秒钟
4. 获得永久的公开网址！

## 方法2：GitHub Pages

1. 访问您的GitHub仓库：https://github.com/qgao1-sudo/final
2. 点击 "Settings"（设置）
3. 在左侧菜单找到 "Pages"
4. 在 "Source" 下选择分支：`claude/setup-github-connection-01GXPkQBUYpZpqtU3JswCpo8`
5. 点击 "Save"
6. 等待几分钟后，您的网站将发布在：
   `https://qgao1-sudo.github.io/final/`

## 方法3：Vercel

1. 访问：https://vercel.com
2. 使用GitHub账号登录
3. 点击 "Import Project"
4. 选择您的 `final` 仓库
5. 点击 "Deploy"
6. 获得一个 `.vercel.app` 域名

## 方法4：Render

1. 访问：https://render.com
2. 注册/登录
3. 创建新的 "Static Site"
4. 连接您的GitHub仓库
5. 设置构建命令为空
6. 发布目录设为 `/`
7. 部署后获得公开URL

## 注意事项

⚠️ **重要**：无论使用哪种方法部署，游戏都需要：
- HTTPS 连接（摄像头权限要求）
- 浏览器摄像头权限
- 现代浏览器（Chrome、Edge、Safari等）

所有上述服务都自动提供HTTPS，所以摄像头功能可以正常工作。
