
## hexo每次部署的步骤，可按以下三步来进行。
>* hexo clean
>* hexo d -g (hexo g - d) //generate   deploy


## Project Pages 项目站点
* `master` 用于存放代码，
* `gh-pages分支`用于构建和发布；[Creating Project Pages manually](https://help.github.com/articles/creating-project-pages-manually/)


## hexo-server
Hexo 3.0 把服务器独立成了个别模块，您必须先安装 hexo-server 才能使用。
``` bash
$ npm install hexo-server --save
```
