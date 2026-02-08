# 前言

欢迎来到基于微信小程序的校园保修系统SpringBoot项目。该项目旨在为校园师生提供一个便捷、高效的报修平台，通过微信小程序实现报修申请、进度查询等功能，提高校园设施维护的效率与质量。

# 内容介绍

本项目后端采用Spring Boot框架，结合Spring、Spring MVC、MyBatis等技术进行开发，前端则采用JS、Vue、CSS3、Uniapp等技术，实现了一个功能完善、易于使用的校园保修系统。此外，项目还使用了MySQL数据库进行数据存储，保证了数据的安全与稳定。

# 技术介绍

- 语言：Java
- 使用框架：Spring、Spring MVC，MyBatis，微信小程序
- 前端技术：JS、Vue、CSS3，Uniapp
- 开发工具：IDEA/Eclipse，Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下为项目中的一段核心代码，展示了如何实现报修单查询功能：

```java
// 注解方式定义接口
@RestController
@RequestMapping("/api/repair")
public class RepairController {

    @Autowired
    private RepairService repairService;

    // 查询报修单
    @GetMapping("/list")
    public ResponseEntity<List<Repair>> listRepairs(@RequestParam("openid") String openid) {
        List<Repair> repairs = repairService.listRepairsByOpenid(openid);
        return ResponseEntity.ok(repairs);
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/351145/9/2885/203819/68c591ebFa13b3315/8b859a1de7a2656b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/342279/7/3063/31683/68c591c2Fb79e6bf3/70d4e3669efbca8c.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344467/4/3034/18337/68c591c2Fae82871a/e5f2df87977e5062.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/328698/5/19644/80200/68c591c3F329f5bd9/7b7685689c982514.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/339418/14/10470/24635/68c591c3Fed8f415e/11699e5a1620f401.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/345192/14/3046/76546/68c591c3Fe81ba4d0/3958095a69fde467.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326061/18/19406/18066/68c591c3F29a7ad9e/6d4cd7b9fa4bcd9a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325916/9/19748/17030/68c591c3F427b869d/badb4b0ad28438b9.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/344057/29/3049/18372/68c591c3F849af577/c63f5771625ed4c6.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/337385/6/10522/63302/68c591c4Ff8be1589/abd118f4d8f89b4d.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
