## 空间 {docsify-ignore}
Kubernetes的Namespace概念，空间之间存在资源隔离，进程相互独立。

## 镜像 {docsify-ignore}
Kubernetes的Image概念，容器应用打包的标准格式，除了包含应用代码，还包含应用运行所需的库、资源、配置等文件，集中存储在镜像仓库中。

## 仓库 {docsify-ignore}
仓库用来存放镜像，分公开仓库和私有仓库。    
**公开仓库** - 所有七牛容器云注册用户都可以访问拉取仓库内的所有镜像。    
**私有仓库** - 只有具备相关访问权限的用户才能拉取仓库内的镜像，一个组织下的成员可以同时访问。