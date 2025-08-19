# 基于JAVA+Springboot的OA人事管理系统

- <b>完整代码获取地址：从戎源码网 ([https://armycodes.com/](https://armycodes.com/))</b>
- <b>技术探讨、资料分享，请加QQ群：692619798</b> 
- <b>作者微信：19941326836  QQ：952045282</b> 
- <b>承接计算机毕业设计、Java毕业设计、Python毕业设计、深度学习、机器学习</b>
- <b>选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 一条龙服务</b>
- <b>所有选题地址 ([https://github.com/YuLin-Coder/AllProjectCatalog](https://github.com/YuLin-Coder/AllProjectCatalog)) </b>


## 一、系统介绍

- 用户模块 日志模块 考勤模块 工作流模块 请假 岗位 会议申请 菜单 
- 定时任务月末统计考勤状况 等功能
- 管理员输入登录账号和密码，登录成功后，可以进行自身信息的修改，还有员工管理、部门管理、角色管理、菜单管理、岗位管理、公告管理、个人便签、通讯录、签到签退、个人信息管理、会议室管理、会议管理等功能。
- 员工输入登录账号和密码，登录成功之后，可以对个人信息修改，进行每天上班的签到签退，个人便签管理，也可以查询公司的通讯录可以方便联系到公司所有人。

## 二、所用技术

- springboot+mybatis+ shiro +mvc + activiti+thymeleaf+quartz


## 三、环境介绍

基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7及以上,Maven

源码+数据库脚本

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)


## 五、浏览地址

http://localhost:8880/oa/index

管理员账号密码  admin admin

领导角色演示账号/密码：manager、123456

员工账号密码 ： employee  123456

## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
   若为maven项目，导入成功后请执行maven clean;maven install命令，然后运行；
3. 修改application.yml 里面的数据库配置
4. 启动项目后端项目 
5. 访问  http://localhost:8880/oa/index
