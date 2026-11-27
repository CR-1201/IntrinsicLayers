# 主页上传说明

本仓库用于 IntrinsicLayers 论文主页。当前 index.html 是临时占位页，可以直接替换为正式主页。

## 上传网页

1. 接受仓库所有者发送的 GitHub 协作邀请。
2. 打开仓库，选择 main 分支。
3. 通过 Add file → Upload files 上传正式的 index.html 和图片、CSS、JavaScript 等资源，提交到 main。也可以通过 git push 上传。
4. index.html 必须位于仓库根目录，不要将整个网站放在额外的一层目录中。
5. 建议资源使用相对路径，例如 ./images/teaser.png、./css/style.css，避免 /images/teaser.png 这类指向域名根目录的路径。
6. 保留 .nojekyll 文件。只上传可直接运行的静态网页；如果项目需要构建，请上传构建后的文件。

## 发布设置（仓库所有者完成一次即可）

Settings → Pages → Source: Deploy from a branch → Branch: main → Folder: / (root) → Save。

启用并成功部署后，主页地址为：https://cr-1201.github.io/IntrinsicLayers/

之后提交到 main 会触发自动更新。可在 Actions 查看部署状态。

上传者使用自己的 GitHub 账号，无需服务器 IP 或仓库所有者的密码、Token。
