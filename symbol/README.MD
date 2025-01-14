这是一个关于Github Copilot Symbol是吧功能的使用介绍

我们在进行开发过程中，有大量的内容没有源代码，所以需要通过关联的Symbol了解到相关类、方法的使用需要，并作为上下文传递到GHCP中，进行综合分析，指导相关开发工作。GHCP目前支持直接发掘对应的关键Symbol，从而提高代码生成效果。

### 1. 下面一个例子是通过引入直接导入DataAccessException Symbol进行代码优化建议：

![Video Project](https://github.com/CopilotNext/GHCP_Demo/blob/main/symbol/resources/symbol.gif)

### 2. 下面一个例子是在Github Copilot Chat中使用#sym，选择相关Symbol进行分析的情况：

![Video Project](https://github.com/CopilotNext/GHCP_Demo/blob/main/symbol/resources/symsel.gif)