JAVA Study
==

# Table Of Contents
<details>
<summary>day01_JAVA语言概述与基本语法</summary>

* [day01_JAVA语言概述与基本语法](./day01/README.md "day01")
    * [JAVA语言概述](./day01/README.md#JAVA语言概述)
        * [java语言特点](./day01/README.md#java语言特点)
        * [java两种核心机制](./day01/README.md#java两种核心机制)
        * [.java源文件要求](./day01/README.md#java源文件要求)
        * [注释](./day01/README.md#注释)
        * [javadoc生成文档说明](./day01/README.md#javadoc生成文档说明)
    * [关键字](./day01/README.md#关键字)
        * [定义数据类型的关键字](./day01/README.md#定义数据类型的关键字)
        * [定义数据类型值的关键字](./day01/README.md#定义数据类型值的关键字)
        * [定义流程控制的关键字](./day01/README.md#定义流程控制的关键字)
        * [定义权限修饰符的关键字](./day01/README.md#定义权限修饰符的关键字)
        * [定义类、函数、变量修饰符的关键字](./day01/README.md#定义类函数变量修饰符的关键字)
        * [定义类与类之间关系的关键字](./day01/README.md#定义类与类之间关系的关键字)
        * [定义建立实例及引用实例，判断实例的关键字](./day01/README.md#定义建立实例及引用实例判断实例的关键字)
        * [异常处理的关键字](./day01/README.md#异常处理的关键字)
        * [用于包的关键字](./day01/README.md#用于包的关键字)
        * [其他修饰符关键字](./day01/README.md#其他修饰符关键字)
        * [保留字](./day01/README.md#保留字)
    * [标识符](./day01/README.md#标识符)
        * [合法标识符规则](./day01/README.md#合法标识符规则)
    * [Java中名称命名规范](./day01/README.md#Java中名称命名规范)
    * [java中变量的声明与使用](./day01/README.md#java中变量的声明与使用)
        * [变量](./day01/README.md#变量)
        * [程序的执行过程](./day01/README.md#程序的执行过程)
        * [变量的分类](./day01/README.md#变量的分类)
            * [整数类型](./day01/README.md#整数类型)
            * [浮点型](./day01/README.md#浮点型)
            * [字符类型](./day01/README.md#字符类型)
            * [布尔类型boolean](./day01/README.md#布尔类型boolean)
        * [变量之间的运算](./day01/README.md#变量之间的运算)
    * [4种整数表达方式](./day01/README.md#4种整数表达方式)
    * [原码、反码、补码](./day01/README.md#原码反码补码)
    * [进制之间转换](./day01/README.md#进制之间转换)
        * [十进制转其它进制内置方法](./day01/README.md#十进制转其它进制内置方法)
    * [编码与字符集](./day01/README.md#编码与字符集)
        * [ASCII编码](./day01/README.md#ASCII编码)
        * [Unicode编码](./day01/README.md#Unicode编码)
            * [UTF-8](./day01/README.md#UTF-8)
</details>

<details>
<summary>day02_基本语法</summary>

* [day02_基本语法](./day02/README.md "day02")
    * [运算符](./day02/README.md#运算符)
        * [算术运算](./day02/README.md#算术运算)
            * [取模(取余数)：%](./day02/README.md#取模取余数)
            * [自增](./day02/README.md#自增)
            * [自减](./day02/README.md#自减)
            * [算术运算符的注意问题](./day02/README.md#算术运算符的注意问题)
            * [算术运算示例](./day02/README.md#算术运算示例)
        * [赋值运算符](./day02/README.md#赋值运算符)
        * [比较运算符](./day02/README.md#比较运算符)
        * [逻辑运算符](./day02/README.md#逻辑运算符)
            * [逻辑运算符对比示例](./day02/README.md#逻辑运算符对比示例)
        * [位运算符](./day02/README.md#位运算符)
            * [位运算符细节](./day02/README.md#位运算符细节)
            * [位运算应用例子](./day02/README.md#位运算应用例子)
        * [三元运算符](./day02/README.md#三元运算符)
        * [运算符的优先级](./day02/README.md#运算符的优先级)
    * [10进制数转以16进制格式打印出来](./day02/README.md#10进制数转以16进制格式打印出来)

</details>


<details>
<summary>day03_基本语法.程序流程控制</summary>

* [day03_基本语法.程序流程控制.循环结构](./day03/README.md "day03")
    * [程序流程控制](./day03/README.md#程序流程控制)
        * [结构类型](./day03/README.md#结构类型)
            * 顺序结构
            * 分支结构
            * 循环结构
    * [分支结构](./day03/README.md#分支结构)
        * [if-else](./day03/README.md#if-else)
        * [switch-case](./day03/README.md#switch-case)
            * [switch-case规则](./day03/README.md#switch-case规则)
        * [自动判断是否为闰年 示例](./day03/DateEstimationDays2.java)
    * [循环结构](./day03/README.md#循环结构)
        * [for循环](./day03/README.md#for循环)
        * [while](./day03/README.md#while)
        * [do-while](./day03/README.md#do-while)
        * [特殊流程控制break](./day03/README.md#特殊流程控制break)
            * break语句用于终止某个语句块的执行
            * [break语句出现在多层，嵌套的语句块中时，可以通过标签指明要终止的是哪一层语句块](./day03/README.md#break语句出现在多层嵌套的语句块中时可以通过标签指明要终止的是哪一层语句块)
        * [continue特殊控制](./day03/README.md#continue特殊控制)
        * [return](./day03/README.md#return)
        * [break, continue, return特殊流程控制说明](./day03/README.md#break-continue-return特殊流程控制说明)
</details>


<details>
<summary>day04_基本语法.数组</summary>

* [day04_基本语法.数组](./day04/README.md "day04")
    * [数组](./day04/README.md#数组)
    * [数组声明与初始化](./day04/README.md#数组声明与初始化)
    * [数组元素的默认值](./day04/README.md#数组元素的默认值)
    * [java数据的内存基本结构](./day04/README.md#java数据的内存基本结构)
    * [多维数组](./day04/README.md#多维数组)
        * [数组的不同书写格式](./day04/README.md#数组的不同书写格式)
        * [混合数据类型数组](./day04/README.md#混合数据类型数组)
        
    
</details>


<details>
<summary>day05_面向对象编程</summary>

* [day05_面向对象编程](./day05/README.md "day05")
    * [学习面向对象内容的三条主线](./day05/README.md#学习面向对象内容的三条主线)
    * [面向对象与面向过程](./day05/README.md#面向对象与面向过程)
    * [面向对象的思想概述](./day05/README.md#面向对象的思想概述)
    * [class类结构](./day05/README.md#class类结构)
        * [类的成员构成示例1](./day05/README.md#类的成员构成示例1)
        * [类的成员构成示例2](./day05/README.md#类的成员构成示例2)
    * [创建java自定义类](./day05/README.md#创建java自定义类)
        * [类的成员之一：属性](./day05/README.md#类的成员之一：属性)
        * [类中变量分类：成员变量与局部变量](./day05/README.md#类中变量分类成员变量与局部变量)
            * [成员变量的默认值(类变量、实例变量)](./day05/README.md#成员变量的默认值类变量实例变量)
        * [类的成员之二：方法](./day05/README.md#类的成员之二方法)
        * [对象的创建和使用](./day05/README.md#对象的创建和使用)
        * [类的访问机制](./day05/README.md#类的访问机制)
        * [方法(method)](./day05/README.md#方法method)
            * 方法的调用
        * [方法的重载](./day05/README.md#方法的重载)
        * [可变个数的形参](./day05/README.md#可变个数的形参)
    * [内存划分的结构](./day05/README.md#内存划分的结构)
    * [方法的参数传递](./day05/README.md#方法的参数传递)
    * [面向对象特征之一：封装和隐藏](./day05/README.md#面向对象特征之一封装和隐藏)
        * [信息的封装和隐藏](./day05/README.md#信息的封装和隐藏)
        
</details>

<details>
<summary>day06_面向对象编程</summary>

* [day06_面向对象编程](./day06/README.md "day06")
    * [类的成员之三：构造器(构造方法)](./day06/README.md#类的成员之三构造器构造方法)
        * [构造器的特征](./day06/README.md#构造器的特征)
        * [构造器的作用](./day06/README.md#构造器的作用)
        * [构造器语法格式](./day06/README.md#构造器语法格式)
        * [构造器规则](./day06/README.md#构造器规则)
    * [构造器重载](./day06/README.md#构造器重载)

</details>

<details>
<summary>day07_高级类特性1</summary>

* [day07_高级类特性1](./day07/README.md "day07")
    * [关键字--this](./day07/README.md#关键字--this)
        * [this作用](./day07/README.md#this作用)
        * [this关键字使用注意事项](./day07/README.md#this关键字使用注意事项)
    * [JavaBean](./day07/README.md#JavaBean)
    * [UML图表示类方法](./day07/README.md#UML图表示类方法)
    * [关键字--package](./day07/README.md#关键字--package)
        * [package的使用](./day07/README.md#package的使用)
    * [关键字--import](./day07/README.md#关键字--import)
        * [import语句使用注意事项](./day07/README.md#import语句使用注意事项)
    * [JDK主要的包介绍](./day07/README.md#JDK主要的包介绍)
    * [面向对象特征之二：继承](./day07/README.md#面向对象特征之二继承)
        * [继承基本概念](./day07/README.md#继承基本概念)
        * [继承的作用](./day07/README.md#继承的作用)
        * [继承的规则](./day07/README.md#继承的规则)
    * [方法的重写(overrides)](./day07/README.md#方法的重写overrides)
        * [定义](./day07/README.md#定义)
        * [方法重写规则](./day07/README.md#方法重写规则)
    * [方法重写与方法重载的区别](./day07/README.md#方法重写与方法重载的区别)
</details>


<details>
<summary>day08_高级类特性1</summary>

* [day08_高级类特性1](./day08/README.md "day08")
    * [四种访问权限修饰符](./day08/README.md#四种访问权限修饰符)
    * [super关键字](./day08/README.md#super关键字)
        * [调用父类的构造器](./day08/README.md#调用父类的构造器)
    * [this和super的区别](./day08/README.md#this和super的区别)
        * [super父类与子类的内存结构](./day08/README.md#super父类与子类的内存结构)
        * [子类对象实例化的过程及内存结构](./day08/README.md#子类对象实例化的过程及内存结构)
    * [面向对象特征之三：多态性](./day08/README.md#面向对象特征之三多态性)
        * [虚拟方法调用(Virtual method invocation)](./day08/README.md#虚拟方法调用Virtual-method-invocation)
        * [子类继承父类](./day08/README.md#子类继承父类)
    * [instanceof操作符](./day08/README.md#instanceof操作符)
    * [对象类型转换(Casting)](./day08/README.md#对象类型转换Casting)
    * [Object类](./day08/README.md#Object类)
        * [Object类中的主要方法](./day08/README.md#Object类中的主要方法)
    * [==操作符与equals方法](./day08/README.md#操作符与equals方法)
    
</details>


<details>
<summary>day09_高级类特性1</summary>

* [day09_高级类特性1](./day09/README.md "day09")
    * [toString()方法](./day09/README.md#toString方法)
    * [包装类(Wrapper)](./day09/README.md#包装类Wrapper)
        * [基本数据类型、包装类、String类三者之间的互转](./day09/README.md#基本数据类型包装类String类三者之间的互转)
    * [static关键字](./day09/README.md#static关键字)
        * [类属性、类方法的设计思想](./day09/README.md#类属性类方法的设计思想)
        
</details>


<details>
<summary>day10_高级类特性2</summary>

* [day10_高级类特性2](./day10/README.md "day10")
    * [单例设计模式(Singleton)](./day10/README.md#单例设计模式Singleton)
        * [单例的实现](./day10/README.md#单例的实现)
    * [main方法](./day10/README.md#main方法)
    * [类的成员之四：初始化块](./day10/README.md#类的成员之四初始化块)
        * [代码块分类：static代码块、非satic代码块](./day10/README.md#代码块分类)
    * [final关键字](./day10/README.md#final关键字)
    * [抽象类(abstract class)](./day10/README.md#抽象类abstract-class)
    * [模板方法设计模式(TemplateMethod)](./day10/README.md#模板方法设计模式TemplateMethod)
    * [interfacer接口](./day10/README.md#interfacer接口)
        * [接口用法总结](./day10/README.md#接口用法总结)
</details>


<details>
<summary>day11_高级类特性2</summary>

* [day11_高级类特性2](./day11/README.md "day11")
    * [工厂方法设计模式(factory method)](./day11/README.md#工厂方法设计模式factory-method)
        * 概述
        * [应用场景](./day11/README.md#应用场景)
        * [示例](./day11/README.md#工厂方法设计模式示例)
        * [工厂方法设计总结](./day11/README.md#工厂方法设计总结)
    * [代理模式(proxy)](./day11/README.md#代理模式(proxy))
        * 概述(./day11/README.md#)
        * [示例](./day11/README.md#示例)
    * [接口和抽象类的关系](./day11/README.md#)
    * [类的成员之五：内部类](./day11/README.md#类的成员之五内部类)
        * [内部类示例](./day11/README.md#内部类示例)
    * [匿名内部类](./day11/README.md#匿名内部类)
        * [匿名内部示例](./day11/README.md#匿名内部示例)

</details>


<details>
<summary>day12_异常处理</summary>

* [day12_异常处理](./day12/README.md "day12")
    * [异常的定义](./day12/README.md#异常的定义)
        * [分类](./day12/README.md#分类)
        * Exception
        * 异常解决方法
        * [异常特点](./day12/README.md#异常特点)
        * [java异常类层次](./day12/README.md#java异常类层次)
        * [异常、错误 示例](./day12/README.md#示例)
    * [异常处理机制](./day12/README.md#异常处理机制)
        * [如何处理异常](./day12/README.md#如何处理异常)
    * [异常处理方式一：抓取异常](./day12/README.md#异常处理方式一抓取异常)
        * [注意](./day12/README.md#注意)
    * [异常处理方式二：声明抛出异常](./day12/README.md#异常处理方式二声明抛出异常)
        * [重写方法声明抛出异常的原则](./day12/README.md#重写方法声明抛出异常的原则)
    * [手动抛出异常](./day12/README.md#手动抛出异常)
    * [自定义异常类](./day12/README.md#自定义异常类)
    * [异常处理小结](./day12/README.md#异常处理小结)
        * [java异常处理模型：抓抛模型](./day12/README.md#java异常处理模型抓抛模型)
        * [异常处理5个关键字](./day12/README.md#异常处理5个关键字)
    * 其他
        * [java对象在内存中的结构](./day12/README.md#java对象在内存中的结构)
</details>


<details>
<summary>day13_java 集合</summary>

* [day13_java 集合](./day13/README.md "day13")
    * [java集合概述](./day13/README.md#java集合概述)
        * [Collection接口继承树](./day13/README.md#Collection接口继承树)
        * [Map接口继承树](./day13/README.md#Map接口继承树)
    * [Collection接口](./day13/README.md#Collection接口)
        * [Collection接口方法](./day13/README.md#Collection接口方法)
        * [使用Iterator接口遍历集合元素](./day13/README.md#使用Iterator接口遍历集合元素)
        * [for增强版遍历集合元素--foreach](./day13/README.md#for增强版遍历集合元素--foreach)
    * [List接口](./day13/README.md#List接口)
        * [List接口实现类之一：ArrayList](./day13/README.md#List接口实现类之一ArrayList)
        * [List实现类之二：LinkedList](./day13/README.md#List实现类之二LinkedList)
        * [List实现类之三：Vector](./day13/README.md#List实现类之三Vector)
        * [ListIterator接口](./day13/README.md#ListIterator接口)
        * [Iterator与ListIterator主要区别](./day13/README.md#Iterator与ListIterator主要区别)
    * [Set接口](./day13/README.md#Set接口)
        * [Set要求](./day13/README.md#Set要求)
        * [Set实现类之一：HashSet](./day13/README.md#Set实现类之一HashSet)
        * [hashCode()方法](./day13/README.md#hashCode方法)
        * [Set实现类之二：LinkedHashSet](./day13/README.md#Set实现类之二LinkedHashSet)
        * [Set实现类之三：TreeSet](./day13/README.md#Set实现类之三TreeSet)
        * [Set交集、并集、差集运算](./day13/README.md#Set交集并集差集运算)
    * [Map接口](./day13/README.md#Map接口)
        * [Map常用方法](./day13/README.md#Map常用方法)
        * [Map特点](./day13/README.md#Map特点)
        * [Map接口实现类之一：HashMap](./day13/README.md#Map接口实现类之一HashMap)
            * HashMap特点
            * [Map创建对象时指定初始值](./day13/README.md#Map创建对象时指定初始值)
        * [Map接口实现类之二：LinkedHashMap](./day13/README.md#Map接口实现类之二LinkedHashMap)
        * [Map接口实现类之三：TreeMap](./day13/README.md#Map接口实现类之三TreeMap)
        * [Map接口实现类之四：Hashtable](./day13/README.md#Map接口实现类之四Hashtable)
        * [Map接口实现类之五：Properties](./day13/README.md#Map接口实现类之五Properties)
    * [操作集合的工具类：Collections](./day13/README.md#操作集合的工具类Collections)
    * Enumeration迭代器
    * [其他](./day13/README.md#其他)
        * [Scanner异常处理](./day13/README.md#Scanner异常处理)
        * [List中元素为对象，通过对象中的指定属性进行排序](./day13/README.md#list中元素为对象通过对象中的指定属性进行排序)
        * [List、Set、Map在创建对象时指定初始值](./day13/README.md#ListSetMap在创建对象时指定初始值)
</details>


<details>
<summary>day14_泛型</summary>

* [day14_泛型](./day14/README.md "泛型")
    * [泛型概述](./day14/README.md#泛型概述)
    * [泛型的使用](./day14/README.md#泛型的使用)
    * [泛型的几个重要使用的地方](./day14/README.md#泛型的几个重要使用的地方)
    * [泛型类规则](./day14/README.md#泛型类规则)
        * 自定义泛型类示例
    * [泛型接口](./day14/README.md#泛型接口)
    * [泛型方法](./day14/README.md#泛型方法)
    * [泛型与继承的关系](./day14/README.md#泛型与继承的关系)
    * [泛型通配符](./day14/README.md#泛型通配符)
</details>


<details>
<summary>day14_enmu枚举类</summary>

* [enmu枚举类](./README/枚举类.md "enmu枚举类")
    * [枚举类入门](./README/枚举类.md#)
        * [枚举类的属性](./README/枚举类.md#枚举类的属性)
    * [自定义枚举类](./README/枚举类.md#自定义枚举类)
    * [enum枚举类与普通类的区别](./README/枚举类.md#enum枚举类与普通类的区别)
    * [常用方法](./README/枚举类.md#常用方法)
        * [enum枚举类示例](./README/枚举类.md#enum枚举类示例)
    * [枚举类实现接口](./README/枚举类.md#枚举类实现接口)
        * [实现接口的枚举类示例](./README/枚举类.md#实现接口的枚举类示例)
    * [JDK内置的枚举类示例](./day14/src/com/java/enumerate/enumerate.md)
</details>


<details>
<summary>day14_注解</summary>

* [注解](./README/注解.md "注解")
    * [注解概述](./README/注解.md#注解概述)
    * [三个常用的Annotation](./README/注解.md#三个常用的Annotation)
        * [三个基本注解的使用示例](./README/注解.md#三个基本注解的使用示例)
    * [自定义注解](./README/注解.md#自定义注解)
        * [自定义注解示例](./README/注解.md#自定义注解示例)
    * [元注解](./README/注解.md#元注解)
    * [提取Annotation信息](./README/注解.md#提取Annotation信息)
    * [内置注解源码](./README/注解.md#内置注解源码)

</details>


<details>
<summary>day15_IO流</summary>

* [day15_IO流](./day15/README.md "IO流")
    * [File类](./day15/README.md#File类)
    * [JAVA IO原理](./day15/README.md#java-io原理)
    * [流的分类](./day15/README.md#流的分类)
        * [流的抽象基类](./day15/README.md#流的抽象基类)
        * [IO流体系](./day15/README.md#IO流体系)
        * [节点流和处理流](./day15/README.md#节点流和处理流)
    * [InputStream、Reader](./day15/README.md#inputstreamreader)
    * [OutputStream、Writer](./day15/README.md#outputstreamwriter)
    * [处理流之一：缓冲流](./day15/README.md#处理流之一缓冲流)
    * [处理流之二：转换流](./day15/README.md#处理流之二转换流)
        * [InputStreamReader](./day15/README.md#InputStreamReader)
        * [OutputStreamWriter](./day15/README.md#OutputStreamWriter)
    * [字符集](./day15/README.md#字符集)
    * [字符编码、解码(字节数组与字符数组互转时才需要指定字符集)](./day15/README.md#字符编码解码字节数组与字符数组互转时才需要指定字符集)
    * [处理之三：标准输入输出流](./day15/README.md#处理之三标准输入输出流)
    * [处理流之四：打印流](./day15/README.md#处理流之四打印流)
    * [处理流之五：数据流DataInputStream、DataOutputStream](./day15/README.md#处理流之五数据流DataInputStreamDataOutputStream)
    * [处理流之六：对象流](./day15/README.md#处理流之六对象流)
        * [对象流使用注意，读取时报java.io.EOFException异常](./day15/README.md#对象流使用注意读取时报javaioEOFException异常)
        * 对象的序列化
        * 使用对象流序列化对象
    * [RandomAccessFile类](./day15/README.md#RandomAccessFile类)
    * [流的基本应用小总结](./day15/README.md#流的基本应用小总结)
    
</details>


* [day16_多线程练习](./day16/README.md "")


<details>
<summary>day17_多线程</summary>

* [day17_多线程](./day17/README.md "多线程")
    * [程序、进程、线程概念](./day17/README.md#程序进程线程概念)
    * 多线程使用场景(./day17/README.md)
        * 多线程的创建和启动
    * [Thread类](./day17/README.md#Thread类)
        * [创建线程(类)的两种方法](./day17/README.md#创建线程类的两种方法)
            * [继承Thread类](./day17/README.md#继承Thread类)
            * [实现Runnable接口](./day17/README.md#实现Runnable接口)
         * [继承Thread方式和实现Runnable方法的联系与区别](./day17/README.md#继承Thread方式和实现Runnable方法的联系与区别)
         * [Thread构造器](./day17/README.md#Thread构造器)
         * [Thread常用方法](./day17/README.md#Thread常用方法)
    * [线程的调度](./day17/README.md#线程的调度)
    * [线程的优先级](./day17/README.md#线程的优先级)
    * [使用多线程的优点](./day17/README.md#使用多线程的优点)
    * [线程的分类](./day17/README.md#线程的分类)
        * 守护线程
        * 用户线程
    * [线程的生命周期](./day17/README.md#线程的生命周期)
    * [线程的同步](./day17/README.md#线程的同步)
    * [synchronized线程同步使用方法](./day17/README.md#synchronized线程同步使用方法)
    * [synchronized线程同步机制的两种实现方式](./day17/README.md#synchronized线程同步机制的两种实现方式)
        * 同步代码块
        * 同步方法
    * [互斥锁](./day17/README.md#互斥锁)
    * [懒汉式单例模式线程安全问题修复](./day17/README.md#懒汉式单例模式线程安全问题修复)
    * [释放锁的操作](./day17/README.md#释放锁的操作)
    * [不会释放锁的操作](./day17/README.md#不会释放锁的操作)
    * [线程的死锁问题](./day17/README.md#线程的死锁问题)
    * [线程通信](./day17/README.md#线程通信)
        * 线程通信示例
        * 线程通信应用示例(生产者/消费者问题)
</details>


<details>
<summary>day18_java常用类</summary>

* [day18_java常用类](./day18/README.md "java常用类")
    * [String类](./day18/README.md#String类)
        * 字符串的特性
        * String类的构造器
        * String方法
        * 字符串与基本数据类型、包装类之间转换
        * 字符串与字节数组的相互转换
        * 字符串与字符数组的相互转换
    * [StringBuffer类](./day18/README.md#StringBuffer类)
        * 特点
        * 构造器
        * StringBuffer方法
    * [StringBuilder类](./day18/README.md#StringBuilder类)
        * String、StringBuffer、StringBuilder特点比较
    * 与时间相关的类
        * System.currentTimeMillis();
        * Date：java.util.Date、java.sql.Date
        * SimpleDateFormat
        * Calendar
    * [主要时间标准](./day18/README.md#主要时间标准)
    * [System类的System.currentTimeMillis()方法](./day18/README.md#system类的systemcurrenttimemillis方法)
    * [Date类](./day18/README.md#Date类)
    * [SimpleDateFormat类](./day18/README.md#SimpleDateFormat类)
    * [Calendar类](./day18/README.md#Calendar类)
    * [Math类](./day18/README.md#Math类)
    * [BigInteger类](./day18/README.md#BigInteger类)
    * [BigDecimal类](./day18/README.md#BigDecimal类)
    * [Scanner类](./day18/README.md#Scanner类)
        * [Scanner类](./day18/README.md#next与nextLine区别)
</details>


<details>
<summary>day19_java反射机制</summary>

* [day19_java反射机制](./day19/README.md "java反射机制")
    * [java reflection](./day19/README.md#java-reflection)
        * 反射机制提供的功能
        * 反射相关的主要API
        * Class类主要方法
        * 反射示例
        * 获取类的Class实例的4种方法
        * 示例
    * [JAVA类加载过程](./day19/README.md#JAVA类加载过程)
        * ClassLoader
        *  类加载器一个主要方法
    * [通过反射调用类的完整结构](./day19/README.md#通过反射调用类的完整结构)
        * 获取实现的接口
        * 获取所继承的父类
        * 获取全部的构造器
        * 获取全部的方法
        * 获取全部的属性(Field)
        * 获取注解(Annotation)
        * 泛型相关
        * 获取类所在的包
        * 获取内部类
        * 数字形式修饰符转String修饰符
        * 示例
    * [通过反射调用类中指定的方法、属性、构造器](./day19/README.md#通过反射调用类中指定的方法属性构造器)
        * 调用指定的方法
        * 调用指定的属性
        * 调用指定的构造器
    * [JAVA动态代理](./day19/README.md#JAVA动态代理)
        * 静态代理示例
        * 动态代理示例
    * [动态代理与AOP(Aspect Orient Programming面向切面编程)](./day19/README.md#动态代理与aopaspect-orient-programming面向切面编程)
        * AOP代理示例
    
        
</details>


<details>
<summary>day20_网络编程</summary>

* [day20_网络编程](./day20/README.md "网络编程")
    * [网络编程概述](./day20/README.md#网络编程概述)
    * [通讯要素](./day20/README.md#网络基础)
        * IP和端口
            * InetAddress类(IP地址)、InetSocketAddress(IP、端口)
        * 网络通信协议
    * [TCP socket网络编程](./day20/README.md#基于Socket的TCP编程)
        * ServerSocket类
        * Socket类
        * [TCP socket、WebServer示例](./day20/README.md#TCP-socket示例)
    * [UDP socket网络编程](./day20/README.md#基于socket的UDP编程)
        * DatagramSocket类
        * DatagramPacket类
    * [URL socket网络编程](./day20/README.md#URL编程)
        * URL类
        * URLConnection类
        * HttpURLConnection类
    * [小结](./day20/README.md#小结)
    * [其他](./day20/README.md#其他)
        * [java lambda表达式](./day20/README.md#java-lambda表达式)
        * [InputStream判断数据已经读取结束的解决方法](./day20/README.md#InputStream判断数据已经读取结束的解决方法)

</details>


<details>
<summary>java正则表达式</summary>

* [java正则表达式](./regex/README.md)
    * [正则表达式例子](./regex/README.md#正则表达式例子)
    * [java regex正则](./regex/README.md#javaregex正则)
        * [java.util.regex包结构](./regex/README.md#javautilregex包结构)
        * [Pattern类](./regex/README.md#Pattern类)
            * [Pattern类主要方法](./regex/README.md#Pattern类主要方法)
        * [Matcher类](./regex/README.md#Matcher类)
            * [Matcher类主要方法](./regex/README.md#Matcher类主要方法)
        * [java正则示例](./regex/README.md#java正则示例)
        * [PatternSyntaxException异常类的方法](./regex/README.md#PatternSyntaxException异常类的方法)

</details>


<details>
<summary>经典项目</summary>

* 经典项目
    * [家庭记账软件](./project01/README.md)
    * [客户信息管理系统](./project02/README.md)
    * Bank管理系统
        * [Bank01](./Bank01/README.md)
        * [Bank02](./Bank02/README.md)
        * [Bank03](./Bank03/README.md)
        * [Bank04](./Bank04/README.md)
        * [Bank05](./Bank05/README.md)
        * [Bank06](./Bank06/README.md)
        * [Bank07](./Bank07/README.md)
        * [Bank08](./Bank08/README.md)
   
    * 开发团队调度软件
        * [开发团队调度软件_参考版](./project03_sample/README.md)
        * [开发团队调度软件_改进版](./project03/README.md)
    * [考试管理系统软件](./project04/README.md)
</details>

* other
    * [Java学习线路](./README/java学习线路_ok.md)
    * [廖雪峰Java教程](https://www.liaoxuefeng.com/wiki/1252599548343744)
    * [安装JDK](./README/install_JDK.md "安装JDK")  
    * [IntelliJ_IDEA生成JavaDoc文档](./README/IntelliJ_IDEA生成JavaDoc文档.md)
    * [clone或一个新的Interlij IDE项目到本地如何正常运行](README/Intellij_IDE_open_new_clone_project.md "clone或一个新的Interlij IDE项目到本地如何正常运行")
    * [IntelliJ IDEA的安装、配置与使用](README/images/other/IntelliJ_IDEA的安装、配置与使用.pdf)
        * [IntelliJ_IDE常规设置](./README/IntelliJ_IDE设置.md)
    * [JUnit单元测试--IntelliJ IDEA](./README/JUnit_IntelliJ_IDEA.md)
    * [如何编译和运行包含package的java源文件](./README/Compile_and_run_a_contain_package.md)
    * [JDK API在线文档](./README/java_resources.md)
    * [java方法区以及static的内存分配图](./README/java方法区以及static的内存分配图.md)
    * [URI、URL、URN联系与区别](./README/URI_URL_URN.md)
    * [double数据的内存存储方式](./README/double数据的内存存储方式.md)
    * [Java常用工具类](./README/Java常用工具类.md)
    * java中调用shell脚本
        * [java中调用shell脚本](./README/java中调用shell脚本/java中调用shell脚本.md)
        * [Runtime.exec()执行shell、cmd命令常见陷阱于完善](./README/java中调用shell脚本/Runtime.exec()执行shell、cmd命令常见陷阱于完善.md)
    