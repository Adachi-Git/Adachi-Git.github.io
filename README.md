# Adachi 的个人主页

极简单页，纯 HTML + CSS，零依赖。托管于 GitHub Pages。

## 访问地址

部署后访问：**https://adachi-git.github.io**（小写）

## 上线步骤（本地执行）

1. 在 GitHub 新建仓库，仓库名填 **`Adachi-Git.github.io`**，勾选 Public（公开）。

2. 在本目录（`adachi-homepage`）打开终端，依次执行：

```bash
git init
git add .
git commit -m "init personal homepage"
git branch -M main
git remote add origin https://github.com/Adachi-Git/Adachi-Git.github.io.git
git push -u origin main
```

3. 打开仓库 **Settings → Pages**，确认 Source 是 `main` 分支、根目录 `/(root)`（一般默认即是）。

4. 等 1~2 分钟，访问 https://adachi-git.github.io 即可看到。

## 修改内容

- 所有文字都在 `index.html` 里，直接改后 `git add . && git commit -m "update" && git push`。
- 样式（颜色、字号、间距）在 `style.css`，配色变量在文件顶部的 `:root` 里。
- 头像当前是「A」字母圆形占位，换成图片时在 `index.html` 的 `.avatar` 处放 `<img>` 并调整 `style.css`。
