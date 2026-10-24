# Heart Particles · GitHub Pages

纯视觉粒子爱心网页（无画面文字），带可交互音乐、动态光晕、移动端适配。

## 本地播放

- 在电脑浏览器中双击 `index.html`，或者在 VS Code 中使用 Live Server 打开。
- 手机上可以在部署完成后直接打开 GitHub Pages 的 HTTPS 链接。
- 音乐需要用户首次点击爱心或播放图标才能启动（浏览器的音频自动播放限制）。

## 用 Codex 部署到 GitHub Pages

1. 将整个压缩包解压到 Windows 的一个独立文件夹，例如 `D:\YTR\heart-particles-deploy`。
2. 用 VS Code 打开这个文件夹。
3. 在该目录下打开 Codex，粘贴 `CODEX_DEPLOY_PROMPT.md` 的全部内容，让 Codex 执行。
4. 部署完成后，Codex 应报告实际可访问的 HTTPS 网页地址和仓库地址。

优先仓库名 `heart-particles`，账号 `yangtairan1229`。GitHub Pages 应设置为 `Deploy from a branch` → `main` → `/(root)`。如果目标仓库名已经被不相关项目占用，不得覆盖，改用未占用的新仓库名并据此更新链接。

## 预计链接（仅部署成功后有效）

`https://yangtairan1229.github.io/heart-particles/`

## 注意

- 这是静态网站，不需要服务器、Node、依赖安装或持续开启电脑。
- GitHub 仓库设置为 Public，网页源代码将公开，请勿上传账号密钥、私有研究材料、录制视频或其他无关文件。
- 网站部署后，若更新 `index.html` 并推送到 `main`，将重新发布网页。
- 如果自动设置 Pages 失败，可在仓库 Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save 手动设置。
