<a href="https://github.com/TencentCloudBase/cloudbase-templates"><img src="https://main.qcloudimg.com/raw/20510a20be999a59458204afcf0fe205.png"></a>

# Java 应用示例

这个目录是基于云开发的一个 [Java](https://www.Java.net/manual/zh/index.Java) 应用示例，包含 Java + 云函数，可以基于 **[CloudBase Framework](https://gitee.com/TencentCloudBase/cloudbase-framework)** 框架将项目一键部署到云开发环境

## 线上演示地址

点击下方按钮使用 [CloudBase Framework](https://gitee.com/TencentCloudBase/cloudbase-framework) 可以在云端一键部署本项目到自己的云开发账号上。

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&tdl_anchor=gitee&tdl_site=0&appUrl=https%3A%2F%2Fgitee.com%2FTencentCloudBase%2Fcloudbase-templates&workDir=java-starter&appName=java-starter)

## 部署一个 Java 应用

### 步骤一. 准备工作

具体步骤请参照 [准备云开发环境和 CloudBase CLI 命令工具](https://gitee.com/TencentCloudBase/cloudbase-framework/blob/gitee/CLI_GUIDE.md)

### 步骤二. 初始化应用示例

在命令行执行

```
cloudbase init --template java-starter
```

### 步骤三. 一键部署

进入到项目目录，在命令行执行

```
cloudbase framework:deploy
```

## 开发命令及配置

### 本地开发

```
npm run dev
```

### 上线部署

```
npm run deploy
```

### CloudBase Framework 相关开发配置

查看 [CloudBase Framework 配置](https://gitee.com/TencentCloudBase/cloudbase-framework).

### Java 开发文档

查看 [starter](https://docs.oracle.com/en/java/javase/14/docs/api/index.html).
