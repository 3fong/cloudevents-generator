
 
quicktype

js实现:

需要自己扩展mavenjava支持java环境集成quicktype;
获取表定义,生成json
json转对应语言文件
生成java目录结构和文件,并导入生成文件
生成java包

swagger

下面是实例命令，列举出常用参数。

-i : 指定swagger描述文件的路径, url地址或路径

-l: 指定生成客户端代码的语言,该参数为必须

-o: 指定生成文件的位置(默认当前目录)

-t: 指定模版文件所在目录 （可选，代码生成基于jmustache,可以指定自定义模板文件）

-c: json格式的配置文件的路径;文件为json格式,支持的配置项因语言的不同而不同		  

https://swagger.io/docs/open-source-tools/swagger-codegen/


实现方式2:
插件方式
https://blog.csdn.net/liyifan687/article/details/103403127


实现方式3:

直接基于java执行command命令方式:

https://cloud.tencent.com/developer/article/1472639



