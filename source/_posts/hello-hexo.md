---
title: 使用hexo在github上搭建blog
date: 2018-11-03 10:46:07
catalog: true
toc_nav_num: true
tags: 
 - tool
 - blog
---

# 配置
## 配置仓库
在_config.yml中，修改部署repo：
``` yaml
# Deployment
## Docs: https://hexo.io/docs/deployment.html
deploy:
  type: git
  repository: git@github.com:xuyugang/xuyugang.github.io.git
  branch: master
```

# Hexo操作
## 创建Post
新建Post：hexo new "My New Post"

安装扩张：npm install hexo-deployer-git --save

部署： hexo d -g

```javascript
async("https://cdn.bootcss.com/anchor-js/1.1.1/anchor.min.js",function(){
        anchors.options = {
          visible: 'hover',
          placement: 'left',
          icon: ℬ // this is the header anchor "unicode" icon
        };
```