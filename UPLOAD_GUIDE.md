# 主页上传说明

IntrinsicLayers 论文主页直接使用 main 分支，不需要单独的 homepage 分支。

## 上传网页

1. 接受 GitHub 协作邀请后，打开仓库并选择 main 分支。
2. 通过 Add file → Upload files 上传正式 index.html、图片、CSS 和 JavaScript 等资源，提交到 main；也可以使用 git push。
3. index.html 放在仓库根目录，替换临时占位页，不要额外套一层文件夹。
4. 资源使用相对路径，如 ./images/teaser.png 和 ./css/style.css。
5. 保留 .nojekyll；需要构建的项目请上传构建后的静态文件。

## GitHub Pages 发布设置

Settings → Pages → Source: Deploy from a branch → Branch: main → Folder: / (root) → Save。

只有在上述 Pages 设置保存成功后，提交到 main 才会按此方式自动发布。可在 Actions 查看部署状态。

主页地址：https://cr-1201.github.io/IntrinsicLayers/

上传者使用自己的 GitHub 账号，无需服务器 IP 或仓库所有者的密码、Token。
