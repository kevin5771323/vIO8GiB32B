## 前言

随着新冠疫情的不断发展，抗原自测成为了人们日常生活中必不可少的一部分。为了方便大家进行抗原自测，我们开发了一套新冠抗原自测平台小程序，后端采用Spring Boot技术。在此，我们将项目开源，希望能帮助到更多的人。

## 内容介绍

新冠抗原自测平台小程序主要包括以下功能：用户注册登录、个人信息管理、抗原自测记录、自测结果查询等。通过该小程序，用户可以方便快捷地进行抗原自测，实时掌握自己的健康状况。同时，平台也为用户提供了一个互动交流的空间，让用户可以分享自测心得，共同抗疫。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12/14/16

## 核心代码

以下是项目中的一个核心代码片段，实现了用户自测结果提交的功能：

```java
// UserController.java
@PostMapping("/submitTestResult")
public ResponseEntity<String> submitTestResult(@RequestBody TestResult testResult) {
    try {
        userService.submitTestResult(testResult);
        return new ResponseEntity<>("提交成功", HttpStatus.OK);
    } catch (Exception e) {
        e.printStackTrace();
        return new ResponseEntity<>("提交失败", HttpStatus.INTERNAL_SERVER_ERROR);
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

## 项目截图
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/339247/7/9329/203491/68c63995F3a98c57a/5eb98c9e9dc52617.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/339082/2/10687/35545/68c6396cFe9446c76/0f168e7f74534d9f.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/333747/19/12872/21323/68c6396dFe8d35894/2cba76db57089aac.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/349568/23/3225/7548/68c6396dF5c247820/421a26dea0d49b38.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/333822/29/12936/105874/68c6396dF05fb7be1/b7eaa6adf2242a67.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/350836/11/3232/102256/68c6396dFcd7cdd8d/d400cfee5a2a056b.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/347522/30/3174/40344/68c6396dFc74bdb96/6a41324ec8f62df7.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/337418/37/10607/25703/68c6396dF1424f52b/7d42e448dfa4627f.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/340747/21/10551/33586/68c6396eFe7c45f7d/7a4fd6e481c20199.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334806/40/13116/80467/68c6396eF2aa9b34d/92ee3c0a5650aff0.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
