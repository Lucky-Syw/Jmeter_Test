# Jmeter_Test_Git(作者：Lucky)

脚本git存放地址：

https://github.com/Lucky-Syw/Jmeter_Test

目的：

用来做测试iBer 2.0的所有模块接口轮询

操作流程：

1、clone到本地git上的20_Interface_New.jmx脚本

2、本地进行修改等

3、提交到原git路径下。

4、Jenkins执行点击Jmeter_Test_Git立即构建即可。

5、运行完毕，进入打包机对应的路径下查看测试报告（并根据邮件中给定的路径查看测试报告即可）


注意点：

1、打包机上脚本自动拉取存放的路径：Jenkins/workspace/Jmeter_Test_Git/。即使删除此目录，每次运行Jenkins也会重新建。

2、目前git上存放的路径为个人账号目录下

3、20_Interface_New.jmx 定义的脚本名称不可随意更改，更改后需要修改build.xml文件


