# 洪八公粤菜酒楼 - 智能点菜 Demo

一个简单的 H5 点菜页面，用户扫码后可浏览菜品并提交点菜需求。

## 功能

- 🔥 热门菜品展示（带图片）
- 🤖 智能点菜需求提交
- 📱 响应式设计，手机端友好

## 部署到 GitHub

1. 创建 GitHub 仓库
2. 上传 `index.html` 文件
3. 仓库设为公开

## 部署到 Cloudflare Pages

1. 登录 https://dash.cloudflare.com
2. 进入 **Pages** → **创建项目**
3. 选择 **连接到 GitHub**
4. 选择刚刚创建的仓库
5. 构建命令和输出目录保持默认（因为是纯静态页面）
6. 点击 **保存并部署**

## 部署到 Vercel（备选）

1. 登录 https://vercel.com
2. Import GitHub 仓库
3. 自动部署，无需配置

## 自定义

- 修改 `index.html` 中的 `dishes` 数组可以更新菜品
- 修改 `webhookUrl` 可以接入真实的消息推送服务

## 预览效果

直接用浏览器打开 `index.html` 即可预览。
