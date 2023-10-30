# uml
类图,它既用于应用程序的系统分类的一般概念建模,也用于详细建模,将模型转换成编程代 码。同时也可用于数据建模。
类图显示出类、接口以及它们之间的静态结构和关系;它用于描述系统的结构化设计。最基本 的元素是类或者接口。在类图中常用的关系有:继承,关联,依赖,实现。在画类图时,需要有类的 名称,属性和方法。类的名称是必须要写的,属性中有公有,受保护,私有,实现四种。
我本来划分管理员,操作员和一般用户,是从范围由大到小来划分的,这样的话,一般用户范 围最广,其次是操作员,最后是管理员,所以一般用户是父类,操作员是其子类,管理员是操作员的 子类。前几天和涛哥交流的时候,他说管理员应该是父类,因为从权限上来说,管理员的权限最大, 其次是操作员,最后是一般用户。感觉也很有道理,所以在这个理解之上,机房收费系统的类图应该 是这个样子的:
![image](https://github.com/10924126/uml/blob/main/uml.png)


![image](https://github.com/10924126/uml/blob/main/%E6%9C%9F%E4%B8%AD.drawio.png)



參考網址:https://blog.csdn.net/zll_0405/article/details/78898597
