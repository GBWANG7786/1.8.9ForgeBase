# 1.8.9 Forge Base

## By:GBWANG7786

Written 2024.1.30

啊 不知不觉这个项目从2021.6.19开始已经快3年了

在今天打开电脑看老文件的时候发现了这个老文件 发现还可以构建 那我就让他重见天日吧 至于维护什么的。。。。。。学业真的很繁忙 抱歉

`````Java
\**
    ForgeBase基于原版ForgeMDK构建 在用Forgebase之前要熟练掌握：
类（Class）
八大基本数据类型（Primitive），和三种引用类型
对象（Object），属性和方法

流程控制（while,if等）
包（Package），接口（Interface），多态
、继承以及重写（Override）、重载（Overload）
变量和运算符（这么重要的内容才想起来）
· 注解（最好了解）
    **\
\\Written in 2021.6.19
`````



构建方法:

1. Clone this repository.
2. Run the following command from the project's root directory:

```
./gradlew setupDevWorkspace idea genIntellijRuns build
```

3. Open IntelliJ IDEA.
4. Open `Open => Select FoxBase folder`
5. Click `Import gradle project`
6. Add VM options `-Dfml.coreMods.load=com.example.examplemod`

