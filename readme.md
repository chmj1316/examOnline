﻿ # （必填）开发记录（时间倒序排列）
  
### 8/9 03：30
方娇：完成了教师批阅完编程题后的更新分数servlet。对

### 8/9 03：00
柴智：查看自己的全部成绩；新建showStudentgrade 老师查看学生成绩

### 8/9 02：30
方娇：完成了管理员增删教师用户和教师增删学生用户的servlet，精简到一个servlet里。

### 8/9 02：00
柴智：修改ManagerInterfaceImplDao，TeacherfaceImplDao，selftest.java，login.java ；ShowStudentgrade  重命名为showmygrade

### 8/9 01：00
柴智：新建updateselfinfo，新建user；修改student.java，teacher.java，manager.java

### 8/9 00：30
方娇：将教师端单个添加题库和批量添加题库servlet和dao层逻辑补全。完善了教师查看试卷的servlet。

### 8/10 00：00
柴智：新建DoExam.java，修改 PaperInterfaceImplDao与PaperInterfaceDao；修改service 层  paper I与IMPL



### 8/9 14：30
梁净净：修正考试页面，将编程题与选择填空题界面分隔开

### 8/9 14：30
段唯钧：完成教师查看试卷界面

### 8/9 14：00
柴智：修正注册页检查方法中的错误。合并学生页面的前后端。

### 8/9 12：00
方娇：写完了后台的教师出卷查卷的逻辑。

### 8/9 11：30
梁净净：完成教师添加题目界面

### 8/9 10：00
柴智&方娇：修正上传路径的bug,封装了papertopaperstring 方法，批量上传了部分题目。


 ---


### 8/8 16：00
梁净净：完成部分教师出卷界面

### 8/8 16：00
段唯钧：完成部分教师批改试卷界面

### 8/8 15：30
梁净净：完成前端部分学生界面汇总及功能连接
 
### 8/8 15：20
柴智：数据库增加了Bctanswer表，增加对应的javabean以及dao包和数据库操作。封装service层，完成对应的servlet。 
 
### 8/8 15：00
段唯钧：完成教师删除学生界面设计

### 8/8 14：30
方娇： 增加了教师出卷功能的dao层方法，和一部分servlet。

### 8/8 14：00
梁净净：完成学生错题界面

### 8/8 13：30
梁净净：完成学生自测页面

### 8/8 13：00
梁净净：完善试卷页面

### 8/8 12：00
段唯钧：完成教师查询学生成绩页面

### 8/8 11：30
梁净净：完成教师首页页面显示

### 8/8  10.30
段唯钧&梁净净：对教师模块各个界面进行设计

### 8/8 10：00
梁净净：完成管理员首页界面显示

### 8/8 09：45
段唯钧：完善之前页面效果

### 8/8 09：20
柴智：把数据库studentgrade，score字段分为xztscore,tktscore,bctscore,其中bctscore默认值为-1，代表未批阅。同时修改对应的Javabean以及dao包下对应SQL语句。  
  
 ---
 
### 8/7 20：20
方娇：修复了mistakes类的问题，完成了错题集的填空题和编程题。

### 8/7 20：00
段唯钧：管理员管理教师页面

### 8/7 19：50
梁净净：完成主页页面设计和学生登陆后主页显示及并加入js效果。

### 8/7 18：00
柴智：完成登陆页与注册页的js,修复部分bug。

### 8/7 16：00
柴智&方娇：完成登陆页与后台的联系，ajax校验验证码。实现了各种上传文件.

### 8/7 16：00
梁净净：完成管理员发布公告静态页面和js部分效果

### 8/7 16：00
段唯钧：教师个人中心页面和管理员个人中心页面

### 8/7 14：00
段唯钧：完成前端考试查询页面，实现一个页面显示多个不同页面

### 8/7 12：00
梁净净：（数据丢失）解决前一天登陆注册问题

### 8/7 10：00
段唯钧：修改前台页面获取后台数据的脚本

### 8/7 10：00
柴智：利用POI插件实现本地Excel批量上传题目到数据库题库。完成teacher类，管理员类的查看个人信息servlet方法。

### 8/7 9:00
方娇：实现了教师查看学生成绩；把所有的SQL语句修改封装到dao包；修改昨天遗留的错误。

---

### 8/6  20.00
梁净净：完成前端学生考试页面

### 8/6  19.00
段唯钧：完成前端学生考试成绩查询页面

### 8/6 19:00
柴智&方娇：
1. 修改了bean包的缺陷
2. 完善了业务逻辑层和数据访问层之间的调用代码
3. 找到了生成试卷的新思路并写出了：大型构造函数及其封装类
4. 初步完成了学生端功能的（错题集、个人信息查询、个人成绩查询）servlet函数（自测尚未写出）
5. 前后端都实现了登陆注册验证码（红红火火恍恍惚惚）
6. 实现了一半的查看试卷功能
7. 实现了自测题的生成（不随机版）

### 8/6  16.00
梁净净：完成前端注册页面设计，并加入js验证功能

### 8/6 14：00
柴智：补全dao包的增删改查，具体实现。

### 8/6  13.30
方娇：封装好service层服务

### 8/6  13.00
段唯钧：完成前端学生个人信息界面设计

### 8/6  10.30
梁净净：完成前端登陆页面，并与后台进行测试

### 8/6 9:00
柴智：修正昨天项目合并时的错误

---

### 8/5 21:00
方娇：教师类，学生类，管理员三个类 service包和dao包基础的增删改查

### 8/5 20:00
柴智：其类的全部接口，以及实现2个类的实现，还缺4个类的实现。

### 8/5 11:00
柴智：完成db层数据库的连接与关闭方法，连接到远程的MySQL服务器，
配置信息在"db.properties",暂时未实行数据库连接池，采用普通的方法。 

### 8/5 9:00
柴智：修改bean层，增加注释以及构造方法，实现序列化接口。 

### 8/5 8:00
方娇： 完成项目说明文档。 

---

### 8/4 19:00
方娇： 添加bean层的九个Javabean实体类。 

### 8/4 19:00
柴智： 新建项目，完成SQL语句建表，和说明文档。 

