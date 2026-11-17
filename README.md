# github-cicd-practice

Lab 11 实验一：静态网页自动校验并部署到 GitHub Pages。

- `dist/index.html`：静态页面
- `.github/workflows/deploy-pages.yml`：push main 后校验 `dist/index.html` 并发布到 `gh-pages`
- `.github/workflows/hello.yml`：实验二 Hello World CI

## 验收

1. Actions 中 `CI/CD 自动校验并部署到 GitHub Pages` 运行成功；
2. Settings → Pages 来源为 `gh-pages` 分支根目录；
3. 访问 `https://<用户名>.github.io/github-cicd-practice/` 能看到页面。
