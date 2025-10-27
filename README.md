# 前言

大家好，今天给大家分享一款大学生平时成绩量化管理系统，这是一款基于Java语言和MySQL数据库开发的项目。该项目适用于毕业设计或实战项目，可以帮助学生和教师更好地管理和量化平时成绩。以下是项目详细介绍。

## 内容介绍

本项目主要实现了大学生平时成绩的录入、修改、查询、统计和排名等功能。系统分为学生端和教师端，学生端可以查看个人成绩和排名，教师端则可以进行成绩的录入和修改。此外，系统还提供了导出成绩功能，方便教师进行成绩的备份和打印。

## 技术介绍

本项目采用以下技术栈进行开发：

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是项目中的一段核心代码，展示了如何使用Java和Spring Boot进行成绩的查询操作：

```java
// 成绩控制器
@RestController
@RequestMapping("/score")
public class ScoreController {

    @Autowired
    private ScoreService scoreService;

    // 查询成绩
    @GetMapping("/getScore")
    public ResponseEntity<Score> getScore(@RequestParam("studentId") String studentId, @RequestParam("courseId") String courseId) {
        Score score = scoreService.getScore(studentId, courseId);
        return ResponseEntity.ok(score);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/328281/34/4672/143386/689ea18fF00d97f25/ea6a09eaf57e368a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/291044/10/26899/73125/689ea175Faa03c58e/80a58cad710b21a2.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/310476/32/26549/92964/689ea175Fa6be1133/1871392c8b92c6f0.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/324603/6/4833/87040/689ea177Fd7e5ee02/c0a4dee750e68ffb.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/320497/19/25227/43976/689ea177F7c37f8f0/8270e2e6770cf87a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/319979/7/25367/79365/689ea177F3f1194a0/80755b9058253821.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/320662/36/24550/84974/689ea178F5a5a6044/1f8dc8e425039d7e.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/287641/14/26430/42428/689ea178F2c6b816d/e22024e599fa2a35.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/288682/13/24279/66148/689ea179F54f33a0b/62c99550aa1b041f.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/314324/35/26402/54103/689ea179F719a54c2/18a71ee21d12e50b.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
