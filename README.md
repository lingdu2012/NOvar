# NOvar
outside of MVVM(vue\react\angular)，try to find a new  development mode.

借鉴cheerio.js、MVVM（vue\react\angular）数据驱动、svelte无运行时等

在组件内部使用类jQuery语法进行局部的DOM操作

简要说明：

cheerio.js: 实现了jQuery的一个子集,jquery核心功能的一个快速灵活而又简洁的实现，主要是为了用在服务器端需要对DOM进行操作的地方.
MVVM: 借鉴了桌面应用程序的MVC思想，在前端页面中，把Model用纯JavaScript对象表示，View负责显示，两者做到了最大限度的分离。把Model和View关联起来的就是ViewModel。ViewModel负责把Model的数据同步到View显示出来，还负责把View的修改同步回Model。
svelte: 不使用virtual DOM 技术，但会在编写代码时，通过实时编译的方式更新DOM代码，进而做到“边编译，边运行”。编译时静态分析确保浏览器不再需要更多的工作。
