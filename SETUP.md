# 个人网站初始化记录

日期：2026-10-08
目标：建立可发布到 GitHub Pages 的个人主页与博客骨架。

## 流程与结果
- 检查本机 Git、Node 和 GitHub CLI。
- GitHub CLI 保存账号 baobooooo，但认证失败，尚未创建远程仓库或发布。
- 使用无构建依赖的 HTML/CSS 初始化，个人资料留待用户填写。
- 在此目录建立独立 Git 仓库，避免使用上层目录的 Git 仓库。

## 验证
- 两个 HTML 页面的本地资源与页面链接检查通过。
- 已建立 main 分支并提交初始化版本。
- 未进行浏览器视觉验证；未发布到公网。

## 发布
重新登录 GitHub 后确认账号与现有仓库，再创建或使用对应的 用户名.github.io 仓库。

## 公网发布完成
- GitHub 登录成功，账号 baobooooo，凭据保存于系统钥匙串。
- 创建公开仓库 baobooooo/baobooooo.github.io，推送 main。
- 通过 GitHub API 启用 Pages，build_type=workflow。
- 部署运行 37781603879 成功。
- 为此仓库单独设置 Git HTTPS 代理端口 59527，修复旧端口导致的推送失败。
- 首页、博客和 CSS 的公网内容检查完成。浏览器视觉检查因组件签名错误未完成。
- 在线地址：https://baobooooo.github.io/
