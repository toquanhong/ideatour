# create  the first  Java project



## 创建项目

create  a project



启动idea,转到 file >  new > Project ,  选择Java项目和对应的SDK,然后点击next 按钮.

如果要使用main方法创建Java类,请从模板复选框中选择创建项目.

start  idea, go to the file >  new  >  project menu , select  the Java  project  and appropriate (合适的,对应的)  SDK, and  then  click  the  next  button

![image-20210710223716686](C:\Users\Quanhong\Desktop\photo\image-20210710223716686.png)

从下面的对话框中选择命令行应用程序,然后继续.输入项目名称和目录位置,然后单击完成.

 If you want to create a Java class using the main method.  select  the  command-line application  from  the dialog  (对话)  box shown  below  and continue.  enter  the Project  name  Dictionary  location.  click the  finish  button.





## 创建包

create   a  package

包在Java项目下创建,也可以单独创建,也可以在创建类的同时创建,让我们按照以下步骤创建一个包.

packages   are  created  under a Java   project,either  individually   (独自地,逐个地)   or  simultaneously   (同时地)   with  a class, let us  create a  package by the following  these steps

转到项目视角,右键单击Project  选择 new >  module  option

go  to the Project  perspective  (看法,视角) ,   right-click  Project  and  select  new- module  option.







![image-20210710225945849](C:\Users\Quanhong\Desktop\photo\image-20210710225945849.png)









新建块窗口将类似于新项目,选择Java 选项和对应的SDK,然后点击next按钮,输入模块名称.

the  new module  window will  be similar to the new project, select  the  Java   options and  the appropriate   SDK , and  then  click the   next  button. enter the   module  name, click the finish button.



## 创建Java类

可以在Java模块下创建Java类.

转到Project透视图,展开Project并从模块中选择src目录,右键单击他,选择 new >  Java  class 选项

在对话框中输入类名,然后单击确定按钮,他将使用类声明打开editor 窗口.



create Java class, go to  the Project   perspective  ,expand Project  and select  the src   directory  from  the module.   right-click  it, select  the  new Java  class option. enter the class name  in the dialog box, and then click  OK.

it  opens  the  editor  window using  class  declarations.



## 运行Java应用程序

让我们编写一个简单的代码,他将在控制台上打印一条消息,在编辑器窗口输入以下代码

let us  write  a simple code  that  prints a message on  the console. enter  the following code  in the editor window.

```java
public class Helloworld {
	public static  void main （String[]  args）{
		System.out.println ("helloworld")
	}
}
```



转到运行菜单,然后选择运行选项,选择class name,然后单击run,如果没有编译错误,则他将在窗口的底部显示输出.

go  to the   run  menu, and   then  select  the run  option, select  the  class name,and  then  click run. if   there  is  no  compile error, it  displays  the output  at  the  bottom   the   window.







![image-20210710234012442](C:\Users\Quanhong\Desktop\photo\image-20210710234012442.png)