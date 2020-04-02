前后端完全分离--服务端基于thinkphp5+mysql 接口解决方案

体验地址 http://api.hardphp.com/vue-admin/index.html 账号admin 密码123456

接口测试地址：http://api.hardphp.com/api.html


代码结构：

![image](https://github.com/hardphp/tp5-api/blob/master/%E4%BB%A3%E7%A0%81%E7%BB%93%E6%9E%84.png)

```
部署步骤：

第一步（已安装，可略过）：安装git ,下载地址：https://git-scm.com/download/win，然后把C:\Program Files\Git\bin设置环境变量path

第二步（已安装，可略过）：https://nodejs.org/en/blog/release/v9.11.2/

第三步（已安装，可略过）：安装npm install -g @vue/cli，参考https://cli.vuejs.org/zh/guide/installation.html

第四步：下载tp5-api 代码，下载地址：https://github.com/hardphp/tp5-api

第五步：配置config/database.php 数据库信息

第六步：本地hosts文件配置域名api.hardphp.com（域名根据自己喜好，与vue-admin对应即可），然后指向/public目录即可。

第七步：下载vue-admin 代码，下载地址：https://github.com/hardphp/vue-admin

第八步：进入vue-admin 目录，依次npm install

第九步：开发模式 npm run serve

第十步：生产模式 npm run build ，把生成的代码放到/public 下，更名为vue-admin , 浏览器输入 api.hardphp.com/vue-admin ,账号admin，密码123456 即可。

```
```
QQ交流群 :488148501
微信交流群：（由于群二维码有效期太短，加我微信，拉你入群,备注tp5-vue）
```
![image](https://github.com/hardphp/tp5-api/blob/master/895310371197138665.jpg)


