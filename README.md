# 我的个人网站

GitHub Pages 静态个人主页与博客初始版本，无需安装依赖。

## 修改内容
- `index.html`：个人介绍、教育经历、兴趣与文章列表。
- `style.css`：页面样式与手机适配。
- `blog/hello-world.html`：示例博客；复制后编辑，再在首页加入链接。

目前博客使用 HTML。需要 Markdown 写作时，可在此仓库中迁移至 Astro。

## 本地查看
直接用浏览器打开 `index.html`。

## 发布
1. 在本机执行 `gh auth login -h github.com` 完成 GitHub 登录。
2. 检查账号与已有仓库，创建公开的 `用户名.github.io` 仓库。
3. 将本目录的 main 分支推送至该仓库。
4. 仓库 Settings → Pages → Source 选择 GitHub Actions。
5. 如首次工作流未成功，手动运行 Deploy GitHub Pages。
6. 等待工作流成功，再验证 `https://用户名.github.io`。

工作流只上传网页和样式文件，不上传初始化记录。
已发布：https://baobooooo.github.io/

仓库：https://github.com/baobooooo/baobooooo.github.io

后续更新：修改网页后执行 `git add .`、`git commit -m "Update website"`、`git push`，GitHub Actions 会自动发布。
