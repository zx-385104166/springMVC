# springMVC
什么是SpringMVC
  前端控制器，处理映射器，处理适配器，视图解析器
SpringMVC入门程序
  目的：对前端控制器，处理映射器，处理适配器，视图解析器的学习
  非注解的处理映射器，处理适配器
  注解的处理映射器，处理适配器（掌握）
SpingMvc和mybatis的整合（掌握）

springMVC注解开发：
  常用的注解学习
  参数绑定


SpringMCV是spring框架的一个模块，springMVC和spring无需通过中间整合层进行整合
什么是MVC mvc是一个设计模式，


客户端发射请求，request C：controller控制器，M：moudle模型 service，dao，action都为模型处理控制器的request请求


客户端发射request请求到Controller控制器中，M模型处理conlltroller的请求返回response相应用户请求


第一步：发起请求到前端控制器（DispatcherServlet）
第二步：前端控制器请求HandlerMapping查找Hander
      可以根据xml配置，注解进行查找
第三步：处理器
