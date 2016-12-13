/************************************************************************
package.json 用来标记出本项目所需的 npm 依赖包。
tsconfig.json 定义了 TypeScript 编译器如何从项目源文件生成 JavaScript 代码。
typings.json 为那些 TypeScript 编译器无法识别的库提供了别的定义文件。








为什么要分别创建 main.ts 、应用模块 和应用组件的文件呢？
应用的引导过程与 创建模块或者 展现视图是相互独立的关注点。如果该组件不会试图运行整个应用，那么测试它就会更容易。

引导过程与平台有关的
但我们应该用正确的方式组织 Angular 应用的文件结构。 启动 App 与展现视图是两个相互分离的关注点。 把这些关注点混在一起会增加不必要的难度。 可以通过使用不同的引导器 (bootstraper) 来在不同的环境中启动 AppComponent
。 测试组件也变得更容易，因为不需要再运行整个程序才能跑测试。 让我们多花一点精力来用 “正确的方式” 实现它。









添加引用
typings search echarts

typings install --global --save dt~echarts

*************************************************************************/