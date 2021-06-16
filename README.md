# libs

### 介绍


+ 给某个package安装依赖：yarn workspace packageB add packageA 将packageA作为packageB的依赖进行安装
+ 给所有的package安装依赖: 使用yarn workspaces add lodash 给所有的package安装依赖
+ 给root 安装依赖：一般的公用的开发工具都是安装在root里，如typescript,我们使用yarn add -W -D typescript来给root安装依赖
  
删除：

+ yarn workspace packageB remove packageA
+ yarn workspaces remove lodash
+ yarn remove -W -D typescript


