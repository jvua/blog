##### Maven 是什么？

Maven 是一个`项目管理工具`，主要用于项目构建，依赖管理，项目信息管理。

##### Maven 的作用

> 1.帮你下载 jar 包
>
> ```
> maven项目会有一个 pom.xml文件， 在这个文件里面，只要你添加相应配置，他就会自动帮你下载相应jar包，不用你铺天盖地的到处搜索你需要的jar包了
> ```
>
> 2.寻找依赖，帮你下载依赖
>
> ```
> 寻找jar包是第一基本功能，寻找依赖在这个是在这个基础上的功能。 
> 在maven的代码库中，每一个jar包也有自己的 pom.xml文件，而这个文件里面也会有<dependency>配置，只要你配置的jar包所依赖的其他jar包都会被maven自动下载下来。 
> ```
>
> 3.热部署，热编译
>
> ```
> 意思就是，在你web项目已经运行的时候，修改代码的能直接被web服务器所接受，就不需要你重启服务器了，或者重新部署代码了，而且你可以直接通过maven 打包war或者jar项目。
> ```
>
> 