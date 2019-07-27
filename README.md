# 使用网页幻灯片作为本github根页面展示



## page-build

<https://nanarino.github.io/>

由于本仓库为github的根页面，无法使用其他分支作为页面：

If your site is a User or Organization Page that has a repository named `<username>.github.io`or `<orgname>.github.io`, you cannot publish your site's source files from different locations. User and Organization Pages that have this type of repository name are only published from the `master`branch.

故而直接将dist目录的index.html解构到此目录中。



## page-cli-setup

```bash
#安装
npm install -g reveal-md
#dev指令
reveal-md index.md -w
#build指令
reveal-md index.md --static dist
```

For a detailed explanation on how things work, check out [docs for reveal-md](https://github.com/webpro/reveal-md).