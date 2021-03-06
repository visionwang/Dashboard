# Dashboard

0. [软件设计综合实验要求Check List](documents/check_list.md)
1. [About（项目规划）](documents/about.md)
2. [Team profile（团队组建）](documents/team_profile.md)
3. [Investigation（项目前期调研）](documents/competitor_analyze.md)
4. [Vision（项目愿景）](documents/Baoleme_Project_Proposal.md)
5. [Product Backlog（产品特性）](documents/product_backlog.md)
6. Requirement specification(需求规格说明)
	- 6.1 [Usecase Diagram（用例图）](UseCases/README.md#用例图)
	- 6.2 [Use Cases（用例+活动图）](UseCases/README.md#用例文本与活动图)
	- 6.3 [Domain Model（领域模型）](image/%E9%A2%86%E5%9F%9F%E6%A8%A1%E5%9E%8B.png)
	- 6.4 [State Model（状态模型）](image/订单状态图.png)
	- 6.5 [System Sequence Diagram（功能模型）](SSD/README.md)
	- 6.6 [Supplementary Requirements（补充需求）](documents/Supplementary_Requirements.md)
7. Design(设计)
	- 7.1 UI design
		- [PC端登录注册流程UI设计](UI/login&register)
		- [小程序移动端全部UI](UI/移动端全部)
		- [PC端剩余全部UI](UI/PC端除登录注册)
	- 7.2 Database design
		- 7.2.1 [用户及权限系统数据库设计](ER)
		- 7.2.2 [扫码点餐系统数据库设计](ER/ER.png)
		- 7.2.x [第三方数据评审结果](https://github.com/Baoleme/Dashboard/issues?q=is%3Aissue+is%3Aclosed)
	- 7.3 [API 设计](https://baoleme.github.io/API-document/)
	    - [API说明书](documents/API_Manual.md)
	- 7.4 [Software Architecture Document](documents/Software_Architecture_Document.md)
	- 7.5 Usecase Design
		- 7.5.1 [点餐用例设计](DetailDesign/make_order.md)
		- 7.5.2 [商家注册登录用例设计](DetailDesign/register_login.md)
		- 7.5.3 [商家管理菜品用例设计](DetailDesign/manage_dish.md)
8. 生产规范与指南
	- 8.1 代码规范
		- [后端代码规范](https://github.com/Baoleme/Server/blob/master/Code%20Style.md)
		- [餐厅前端代码规范](https://github.com/Baoleme/Client-Restaurant/blob/master/development_specification.md)
		- [小程序端代码规范](https://github.com/Baoleme/Client-Consumer/blob/master/CODE_STYLE.md)
	- 8.2 [REST API 设计规范](https://baoleme.github.io/API-document/)
	- 8.3 [逻辑架构到应用程序映射指南(BCE)](documents/BCE.md)
	- 8.4 [物理架构云上部署 dock-compose.yml 文件编写与使用(容器编排)](documents/8.4.md)
9. 测试
    - 9.1 [测试方案](documents/测试方案.md)
    - 9.2 [后端API测试报告](documents/后端api测试报告.md)
    - 9.3 [综合测试报告](documents/综合测试报告.md)
    - 9.4 [回归测试报告](documents/回归测试报告.md)
10. [产品效果演示](documents/display.md)

X1. Meet Records
  - [inception meeting（3/22/2018）](https://github.com/Baoleme/Dashboard/blob/master/meet_records/KickOff_Meeting_Record(3-22-2018).md)
  - [iteration1 meeting（3/29/2018）](https://github.com/Baoleme/Dashboard/blob/master/meet_records/meeting_record_of_iteration1(3-29-2018).md)
  - [initial design meeting（4/10/2018-4/11/2018）](https://github.com/Baoleme/Dashboard/blob/master/meet_records/meeting_record_of_initial_design(4-10-2018-4-11-2018).md)
  - [meeting record of detail design（4/17/2018）](https://github.com/Baoleme/Dashboard/blob/master/meet_records/meeting_record_of_detail_design(4-17-2018).md)
  - [sprint meeting（4/28/2018）](https://github.com/Baoleme/Dashboard/blob/master/meet_records/sprint_meeting_for_developing_round2(4-28-2018).md)
  - [iteration2 meeting（5/25/2018）](https://github.com/Baoleme/Dashboard/blob/master/meet_records/meeting_record_of_iteration2(5-25-2018).md)
  - [* 线上小会议（3/25/2018）](meet_records/3.25线上小会议.md)
  - [* 需求小会议（4/1/2018）](meet_records/4.1需求小会议.md)

X2. Tech/Work Report
  - [15331365 - Git恢复之前版本的两种方法reset、revert（图文详解）](https://blog.csdn.net/yxlshk/article/details/79944535)
  - [15331169 - 用例建模小结](https://humanlee1011.github.io/2018/04/14/usecase/#)
  - [15331274 - 在Vue项目中使用Vuex](https://blog.csdn.net/shujh_sysu/article/details/79947418)
  - [15331446 - 小程序原型搭建](https://blog.csdn.net/crystal_zhuyupei/article/details/79948647)
  - [15331436 - axios入坑指北](https://blog.zyuco.com/2018/04/08/axios%E5%85%A5%E5%9D%91%E6%8C%87%E5%8C%97/)
  - [15331435 - 使用Travis进行持续集成（js）](https://blog.andiedie.cn/2018/04/04/%E4%BD%BF%E7%94%A8Travis%E8%BF%9B%E8%A1%8C%E6%8C%81%E7%BB%AD%E9%9B%86%E6%88%90/)
  - [15331432 - 初为产品经理的心理障碍](https://blog.csdn.net/qq_33559972/article/details/79934411)
  - [15331432 - 交互设计那些小纠结](https://blog.csdn.net/qq_33559972/article/details/80877316)
  - [15331169 - Jmeter测试详记](https://humanlee1011.github.io/2018/07/07/Jmeter%E6%B5%8B%E8%AF%95%E8%AF%A6%E8%AE%B0/)

X3. Final Report
  - [团队成员自我总结](documents/Final_Report.md#团队成员自我总结)
  - [PSP-2.1统计表](documents/Final_Report.md#psp-21统计表)
  - [Git统计报告](documents/Final_Report.md#git统计报告)
  - [劳苦清单](documents/Final_Report.md#劳苦清单)
  - 团队成员相关博客清单见X2

XX. 建模练习
  - XX.1 [奇妙清单业务文档](ModelingExercise/业务文档.md)
  - XX.2 [建模要求](ModelingExercise/README.md#建模要求)
  - XX.3 [建模者答案与评价](ModelingExercise/README.md#建模者答案与评价)
