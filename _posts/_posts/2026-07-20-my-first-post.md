---
layout: post
title: "我的第一篇博客文章"
date: 2026-07-20
categories: 学习笔记
---

## 关于本次作业

通过本次开源实践作业，我完成了以下任务：

### 1. 创建 GitHub 仓库
创建了一个公开仓库，用于存放个人博客内容，并学习了 Git 的基本操作。

### 2. 使用 Jekyll 搭建博客
在本地安装了 Ruby 和 Jekyll 环境，通过 `jekyll new` 命令初始化了博客站点，并修改了 `_config.yml` 配置文件。

### 3. 配置 GitHub Actions 自动部署
编写了 `.github/workflows/deploy.yml` 工作流文件，实现了代码推送后自动构建并部署到 GitHub Pages。

### 4. 发布到 GitHub Pages
部署成功后，通过 `https://IMT11D.github.io/BMParams-CBMS/` 访问到了我的博客网站。

---

## 遇到的问题与解决方案

| 问题 | 解决方案 |
|------|----------|
| `gem: command not found` | 安装 Ruby 环境 |
| Git 提示 `Author identity unknown` | 配置 `user.name` 和 `user.email` |
| `git push` 连接失败 | 改用 SSH 方式连接 |
| `bundle install` 速度慢 | 更换为国内镜像源 `gems.ruby-china.com` |
| Actions 构建失败 | 删除 `Gemfile.lock` 让 Actions 重新生成 |

---

## 总结

本次作业让我初步掌握了：

1. **Git 和 GitHub** 的基本使用
2. **Jekyll** 静态站点生成器的搭建与配置
3. **GitHub Actions** 自动化部署流程
4. **GitHub Pages** 网站托管服务

通过实践，我对开源工具的生态和自动化工作流有了更深入的了解。
