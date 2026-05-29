# 蔡欣宜的博客

欢迎来到我的个人博客！这是一个使用 Jekyll 构建的静态网站，部署在 GitHub Pages 上。

## 项目简介

这是一个现代化的个人博客网站，采用炫酷的紫色渐变主题，具有以下特点：

- 响应式设计，完美适配移动端和桌面端
- 炫酷的动画效果和粒子背景
- 深色科技感主题
- 毛玻璃效果和渐变色彩

## 技术栈

- **Jekyll 4.2.2** - 静态网站生成器
- **Docker** - 容器化开发环境
- **CSS3** - 现代化样式和动画
- **Liquid** - Jekyll 模板语言

## 本地开发

### 使用 Docker（推荐）

1. 确保已安装 Docker 和 Docker Compose

2. 克隆仓库：
```bash
git clone https://github.com/gulangqingcheng/gulangqingcheng.github.io.git
cd gulangqingcheng.github.io
```

3. 启动开发服务器：
```bash
docker-compose up
```

4. 在浏览器中访问：`http://localhost:4000`

### 不使用 Docker

1. 安装 Ruby 和 Jekyll：
```bash
gem install jekyll bundler
```

2. 安装依赖：
```bash
bundle install
```

3. 启动服务器：
```bash
bundle exec jekyll serve
```

4. 在浏览器中访问：`http://localhost:4000`

## 项目结构

```
.
├── _config.yml          # Jekyll 配置文件
├── _layouts/            # 页面布局模板
│   ├── default.html     # 默认布局
│   ├── home.html        # 首页布局
│   ├── post.html        # 文章布局
│   └── page.html        # 页面布局
├── _includes/           # 可复用的组件
│   ├── header.html      # 页头
│   ├── footer.html      # 页脚
│   └── navigation.html  # 导航栏
├── _posts/              # 博客文章
├── _data/               # 数据文件
│   └── navigation.yml   # 导航配置
├── assets/              # 静态资源
│   ├── css/             # 样式文件
│   └── js/              # JavaScript 文件
├── index.html           # 首页
├── about.html           # 关于页面
├── blog.html            # 博客列表页
└── docker-compose.yml   # Docker 配置
```

## 功能特性

- 首页炫酷动画效果
- 博客文章列表
- 关于页面
- 响应式导航栏
- 社交媒体链接
- 深色主题设计

## 自定义配置

编辑 `_config.yml` 文件来自定义你的博客：

```yaml
title: 你的博客标题
description: 你的博客描述
author: 你的名字
```

## 添加新文章

在 `_posts` 目录下创建新文件，命名格式为 `YYYY-MM-DD-title.md`：

```markdown
---
layout: post
title: "文章标题"
date: 2026-05-29
author: 你的名字
---

文章内容...
```

## 部署到 GitHub Pages

1. 将代码推送到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择部署分支（通常是 main 或 master）
4. 等待几分钟后即可访问

## 许可证

MIT License

## 联系方式

如有问题或建议，欢迎通过以下方式联系我：

- GitHub: [@gulangqingcheng](https://github.com/gulangqingcheng)

---

感谢访问我的博客！? 如果喜欢请给个星标！