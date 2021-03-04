# 2. 分支命名

开源项目的分支命名与Android版本对应,目前支持**Android Q**的机型适配

目录结构如下所示: 

      exTHmUI-patchrom 
     +-- manifest           项目清单
     +-- tutorials          教程文档
     +-- plugins            扩展插件，用于扩展已有功能
     +-- build              编译环境，用于构建和编译机型
     +-- tools              适配工具
     +--  exTHmUI       exTHmUI-patchrom 相关，内容定期更新
          +-- release       官方发布的ROM包
          +-- overlay       资源覆盖
     +-- devices            机型目录
          +-- base          官方提供的默认机型
          +-- your_device   待开发者适配的机型
