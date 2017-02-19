# onepower
基因报告解读平台的开发，使用Spring+Spring MVC+MyBatis+MySql；目前主要用于信息浏览、报告解读和信息咨询。

# 概述 
1、为医生和病人（客户）之间提供沟桥梁。用户的基因原始材料，经过公司专门实验室检测并得出分析报告后，由平台提供基因咨询和报告解读。
2、采用的是Spring+Spring MVC+MyBatis+MySql，AOP方面是自定义了CheckPathInterceptor、MinidaoInterceptor、CheckUserLogin等方式进行权限的拦截与校验。
3、缓存方面自定了LRUCache。
4、项目第一版实现了信息浏览、报告解读和信息咨询；未来会增加通讯和付费模块。

#技术点
1、使用开源方案MiniDao。MiniDao是Jeecg自己的持久化解决方案，集成了hibernate实体维护和Mybaits SQL分离的两大优势
2、代码生成器工具类 P3CodeGenerateUtil
3、区分app端和后台模块

#备注
暂不能用于商业行为
