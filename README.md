# Supermarket Management System

**观看演示视频**
https://live.csdn.net/v/399479

-     这里是一个基于 ***SQL Server*** 和 ***C#*** 设计的一个管理系统，仅用于学习。<br>

1. 前端:
    - 技术栈: C# (使用Windows Forms)
    - 功能: 用户界面，包括员工登录、商品查询、销售记录等。
2. 后端:
    - 技术栈: C# (使用.NET Framework)
    - 功能: 处理业务逻辑，包括商品管理、库存管理、用户管理、销售记录等。
3. 数据库:
    - 类型: Microsoft SQL Server
    - 功能: 存储所有的数据，包括用户信息、商品信息、库存信息、销售记录等。
4. 员工销售管理:
    - 功能: 员工可以通过前端界面登录，查询商品信息，记录销售数据。
5. 管理员库存管理:
    - 功能: 管理员可以通过前端界面登录，管理商品信息，更新库存数据。


说明:关键的窗口设计代码请查看 ***.cs*** 后缀文件。
> - **.cs**
>> .cs文件是C#源代码文件，包含了用C#编写的代码。它们可以包含类、接口、结构、枚举、委托和方法等。
>> 典型的C#项目会有许多这样的文件，每个文件通常定义一个或多个相关的类或其他类型。
> - **.resx**
>> .resx文件是XML格式的资源文件，通常用于存储与应用程序相关的资源，如字符串、图像、图标等。
>> 它们被设计用于支持应用程序的本地化和全球化，使资源可以根据文化区域（语言和区域设置）进行适配。
> - **.designer**
>> .Designer.cs文件是自动生成的C#代码文件，通常与Windows Forms或其他设计器工具一起使用。
>> 它们包含由设计器生成的代码，用于初始化用户界面组件或其他设计时元素。

## 要求：
> - 根据课程设计任务，针对具体的实际应用进行需求分析，制定出数据库系统的设计方案。
> - 完成中小型数据库系统的开发、管理和维护。
    
## 课设选题与分组:
> - 课设选题：超市销售管理系统
> - 学生分组成立模拟开发项目组：
> - 关系数据库系统开发过程及规范：选用 Microsoft SQL Server 进行数据库管理。 选用 C# 进行窗口UI开发。
    
## 数据库需求分析:
> - 概念结构设计
> - 视图设计
> - 数据库访问权限设计
> - 登录模块设计

具体参考： <https://blog.csdn.net/m0_74242407/article/details/139446649?spm=1001.2014.3001.5501> 更新中（2024/6/13）

![业务流程](https://img-blog.csdnimg.cn/direct/e4ca43e249554c61bbd5c8fafaebc4f6.png)
![销售E-R](https://img-blog.csdnimg.cn/direct/2ade3634d654424a8187d3b6d4b117ea.png)
![登录E-R](https://img-blog.csdnimg.cn/direct/7663bee0f76c4572a28759e4e12f7949.png)