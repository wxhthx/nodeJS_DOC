## 安装Mongodb安装文件
    因为都是傻瓜式操作，不再赘述该内容
## 创建数据库文件的存放位置
    比如d:/mongodb/data/db。启动mongodb服务之前需要必须创建数据库文件的存放文件夹，否则命令不会自动创建，而且不能启动成功。
    打开cmd（windows键+r输入cmd）命令行，进入D:\mongodb\bin目录（如图先输入d:进入d盘然后输入cd d:\mongodb\bin），
    输入如下的命令启动mongodb服务
  ```Bash
  mongod --dbpath D:\mongodb\data\db
  ```
