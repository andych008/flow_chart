# flow_chart
Android相关的一些流程图、时序图。帮助理解、记忆。


## svg图片，在浏览器上直接看
- [1.Android启动过程-时序图](https://raw.githubusercontent.com/andych008/flow_chart/master/dist/1.Android启动过程-时序图.svg)
- [2.App的冷启动-时序图](https://raw.githubusercontent.com/andych008/flow_chart/master/dist/2.App的冷启动-时序图.svg)
- [3.Activity的启动-调用关系-时序图](https://raw.githubusercontent.com/andych008/flow_chart/master/dist/3.Activity的启动-调用关系-时序图.svg)
- [4.DecorView调用关系-时序图](https://raw.githubusercontent.com/andych008/flow_chart/master/dist/4.DecorView调用关系-时序图.svg)
- [4.DecorView的显示流程_时序图](https://raw.githubusercontent.com/andych008/flow_chart/master/dist/4.DecorView的显示流程_时序图.svg)
- [5.WMS的事件生成过程_时序图](https://raw.githubusercontent.com/andych008/flow_chart/master/dist/5.WMS的事件生成过程_时序图.svg)
- [AOP_流程图](https://raw.githubusercontent.com/andych008/flow_chart/master/dist/AOP_流程图.svg)


## 如需要png文件
`java -jar -Dfile.encoding=UTF8 plantuml.jar xxx.txt`可以把txt源文件转成png格式。


## 欢迎pull request
图片使用 [plantuml](https://plantuml.com/zh/) 生成，源文件是纯文本文件。

个人觉得流程图、时序图要整体把控，不要太扣细节。不然，信息太多，更不好理解了。

1. 开发环境(推荐用第一种)：

   1. Android Studio + idea插件[PlantUML integration](https://plugins.jetbrains.com/plugin/7017-plantuml-integration/)
   2. 纯文本编辑器 + chrome插件[plantuml-viewer](https://chrome.google.com/webstore/detail/plantuml-viewer/legbfeljfbjgfifnkmpoajgpgejojooj)

   不管哪种方式，插件都只有实时预览的功能，没有编辑提示。plantuml语法很简单，纯手写也没压力。
2. 发布：

    最后使用`tosvg.bat`或`tosvg.sh`生成svg图片到dist目录。
    如新增文件，要在`README.md`里添加索引。
3. **要求**：

   `.txt`源文件使用`utf-8`编码。

