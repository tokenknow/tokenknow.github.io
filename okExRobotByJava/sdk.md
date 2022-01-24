# 获取OKEx Api SDK

欧易官方提供了C#、Java、PHP、Python的SDK。

SDK地址：[https://github.com/jane-cloud/Open-API-SDK-V5](https://github.com/jane-cloud/Open-API-SDK-V5)

![alt SDK](images/001.png "SDK")

# 拉取Java的SDK，安装到maven

## 通过Git拉取SDK

![alt SDK](images/002.png "SDK")

## 通过Idea打开Java的SDK

## 在pom文件中加入配置

```java
<properties>
    <maven.test.skip>true</maven.test.skip>
</properties>
```

## 编译安装到Maven

![alt SDK](images/003.png "SDK")

## 创建Java的Maven工程并引入安装的SDK

![alt SDK](images/004.png "SDK")