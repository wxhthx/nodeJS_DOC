## 安装Mongodb安装文件
    因为都是傻瓜式操作，不再赘述该内容
## 创建数据库文件的存放位置
    比如d:/mongodb/data/db。启动mongodb服务之前需要必须创建数据库文件的存放文件夹，否则命令不会自动创建，而且不能启动成功。
    打开cmd（windows键+r输入cmd）命令行，进入D:\mongodb\bin目录（如图先输入d:进入d盘然后输入cd d:\mongodb\bin），
    输入如下的命令启动mongodb服务

    mongod --dbpath D:\mongodb\data\db
## 'mongod'不是命令行
    windows上经常会遇到这样的问题，解决办法如下：
    打开mongo的安装目录，复制路径，如：C:\Program Files\MongoDB\Server\3.4\bin
    将该路径添加到系统环境变量Path下，以管理员权限打开cmd即可正常使用
## mongo非正常关闭引发的错误
    打开数据库文件的存放位置，删除*.lock即可
