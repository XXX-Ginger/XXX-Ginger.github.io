---
title: Hello World
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

### Deploy method 2

```
git fp
```

快捷方法，在.github/workflows/deploy.yml 中配置push触发deploy

在.git/config中配置，fp即完成git add和git commit和git push

<img src="/Users/xiangjunjie/Library/Application Support/typora-user-images/image-20221201142407218.png" alt="image-20221201142407218" style="zoom:50%;" />

### 删除文章

```
1. 删除.deploy_git 文件夹
2. 执行hexo clean
3. 执行hexo deploy
```

