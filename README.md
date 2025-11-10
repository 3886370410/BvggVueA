# 基于SSM的美食推荐平台

## 前言

随着互联网技术的飞速发展，各类信息化的美食推荐平台应运而生，为广大美食爱好者提供了极大的便利。基于此，我们开发了一套基于SSM（Spring、SpringMVC、MyBatis）框架的美食推荐平台，为广大用户提供丰富的美食信息及个性化推荐。

## 内容介绍

本平台致力于打造一个全面、便捷的美食推荐系统。用户可以根据自己的口味喜好、地理位置等信息，轻松地找到周边的美食。此外，平台还提供了美食评论、收藏、点赞等功能，让用户可以互相交流、分享美食心得。

## 技术介绍

- **语言：** Java
- **使用框架：** Spring、SpringMVC、MyBatis
- **前端技术：** JS、Vue、CSS3
- **开发工具：** IDEA/Eclipse
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

## 核心代码

以下是本项目中的部分核心代码：

```java
// 美食推荐Service层代码
public List<Food> recommendFoods(int userId, int limit) {
    // 查询用户喜好标签
    List<Tag> userTags = tagMapper.selectTagsByUserId(userId);
    
    // 根据喜好标签推荐美食
    List<Food> recommendFoods = foodMapper.selectFoodsByTags(userTags, limit);
    
    return recommendFoods;
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

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/328007/30/18663/92237/68c29571F10a27f33/092ba6c19733b0b9.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/333453/26/12017/32314/68c29549F5dd74c9d/3cb95d5494a899dc.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/344262/22/2152/83411/68c29549Fded134cc/84f6d2452fb770ba.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/323542/8/18884/29632/68c2954aF6d49fd11/58b91f7f7901fa15.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/347693/20/2054/94564/68c2954aF3720ae34/3839cbe3efd558d7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327017/4/18813/49115/68c2954bF70ff1d4e/a84d501f6eb7153d.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/324750/14/18812/76339/68c2954bFa16abf42/d09331fdbd46a9a1.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/337673/37/9633/32108/68c2954bFfc3cb6f1/d9565cf8c817e480.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/330471/14/11984/30765/68c2954cF4e385b95/8652e7bb8125de1f.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/339827/30/9534/33134/68c2954cF4455769b/03e2a32c9cbdf510.jpg)

