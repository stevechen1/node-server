# nodejs 实现后端服务器
* 使用http = reuire('http')模块化
* 使用http.createServer(function(req,res){ routePath(req,res)}
* 其中核心部分是.createSrever(){}
* routePath()是一个匿名函数
* 该函数通过分析res的内容来进行路由解析和静态路径的判断
* 路由解析中使用了匿名函数parseBody(){}
* 静态路径使用了匿名行数staticRoot(){}
