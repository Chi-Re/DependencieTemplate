# Java依赖模板(DependencieTemplate)
一个简单的Java依赖库
***
### 使用
~~直接用~~

使用时可以更改example为你的名称，具体用法我整理了教程。
* [发布依赖1](https://blog.csdn.net/qq_37492806/article/details/106252283)
* [发布依赖2](https://blog.csdn.net/tanlove1314/article/details/87094778)

模板使用时将代码放置在`example/src/main/java/example.util`下面。

当然，你可以自己制作模块。<br>
在`settings.gradle`下写入`include '模块名称'`并且创建同名的文件夹在项目根目录中，然后类似`example`一样就行。

记得更改`build.gradle`的`groupName`。
