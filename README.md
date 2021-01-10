<h3 align="center">GIT SEU</h3>
<p align="center">项目实训--实现一个基础的github</p>
<p align="left">
  <a href=""><img src="https://img.shields.io/badge/license-MIT-brightgreen" alt="License">
  </a>
</p>



## 项目准备

### 👌项目实现
考虑使用的实践工具、技术、理念（未分类，先罗列出来）：

vue、springboot、docker、mysql、CICD、关于服务器方面如果条件允许考虑go

项目尽可能充分使用github（比如modules、action、dicuess...）,也是不断熟悉自己项目的一个过程。

#### CICD实践
使用dockerfile、docker-compose、github action
#### 代码规范
组内协商
+ 变量、接口
+ 文档、注释
....

### 项目目录

├── docs
├── git_fronter
├── git_server
└── logs

目前主要分为两个module

+ git_fronter 前端
+ git_server 后端

<p style="color:red;">重要重要重要:</br>
git submodule的使用
如果要push主项目，即git_seu，一定要确保本地的子模块（git_fronter, git_server）和gi thub保持一致。
</p>

其他目录

+ logs开发日志
+ docs 开发过程中的文档、资料之类

