# GSLST 文件发布站

这是用于 GitHub Pages 的静态文件发布站。上传到 `GSLST.github.io` 仓库后，公开访问地址为：

```text
https://gslst.github.io/
```

## 首次部署

1. 登录 GitHub 账号 `GSLST`。
2. 新建公开仓库，仓库名必须为：

```text
GSLST.github.io
```

3. 把本目录中的所有内容上传到仓库根目录：

```text
index.html
.nojekyll
README.md
files/
```

4. 打开仓库的 `Settings` -> `Pages`。
5. 在 `Build and deployment` 中选择：

```text
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

6. 保存后等待 GitHub Pages 部署完成。

## 日常上传文件

1. 打开 `GSLST.github.io` 仓库。
2. 进入 `files` 文件夹。
3. 点击 `Add file` -> `Upload files`。
4. 上传文件并点击 `Commit changes`。
5. 如需在首页展示新文件，编辑 `index.html`，复制一段 `<article class="file-row">...</article>`，把文件名改成新文件名。

## 当前文件

```text
files/能动学院三长三融合研究生教学成果奖申请书附件-20260610.pdf
```

当前 PDF 直链为：

```text
https://gslst.github.io/files/能动学院三长三融合研究生教学成果奖申请书附件-20260610.pdf
```
