# vue_project

## 步骤①: 启动后台服务

### 1.初始化数据库

进入`vue_api_server\db`目录, 里面只有一个`mysql.sql`, 这是项目的初始化sql文件. 然后使用一些常见的mysql数据库工具, 把脚本导入进入, 完成**`后台项目的数据库创建`**


### 2.配置后台服务的数据库地址

进入`vue_api_server\config`目录, 修改里面的`default.json`配置文件, 修改里面的mysql数据库地址


> `default.json`配置修改如下
>
> 主要修改`db_config`节点中的`host`、`database`、`user`、`password`字段, 修改为上一步数据库的地址

![image-20211201163731489](https://gitee.com/hliushi/pic-go_-image/raw/master/img/work/image-20211201163731489.png)


### 5.使用 node app.js 运行服务

## 步骤②: 启动前端服务

`clone`或`download`项目后, 直接在对应的目录执行`npm install`, 直接把前端服务所需要的依赖全部安装, 然后在执行对应的`npm run serve`即可启动前端服务

启动服务端  node app.js

