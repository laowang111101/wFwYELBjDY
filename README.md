# 家政管理系统部署文档 python641

## 项目概述

家政管理系统是一款集成了前后端技术的家政服务管理软件。该系统采用 Python + Django + Vue.js 技术栈开发，旨在提供便捷、高效的家政服务管理解决方案。

## 技术栈

- 后端：Python + Django
- 前端：Vue.js

## 功能模块

- 用户管理：负责用户注册、登录、权限分配等功能
- 服务项目管理：对家政服务项目进行分类、管理
- 服务人员管理：对家政服务人员进行信息录入、排班等管理
- 订单管理：处理订单的创建、支付、派单、完成等流程
- 费用结算：实现服务费用计算、支付等功能

## 系统角色

- 系统管理员：负责整个系统的维护、管理
- 客户：注册并使用家政服务
- 服务人员：提供家政服务
- 财务人员：负责财务结算

## 运行环境

- 后端：
  - Python 3.6+
  - Django 2.2+
  - 数据库：PostgreSQL 11+
- 前端：
  - Vue.js 2.6+

## 部署步骤

1. 安装后端依赖
   ```bash
   pip install -r requirements.txt
   ```
2. 配置数据库
   - 修改 `settings.py` 中的数据库配置信息
3. 初始化数据库
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
4. 运行后端服务
   ```bash
   python manage.py runserver
   ```
5. 编译前端代码
   ```bash
   npm install
   npm run build
   ```
6. 部署前端代码到 Nginx 或其他 Web 服务器

## 目录结构

```
项目根目录/
|-- backend/                # 后端代码目录
|   |-- apps/               # Django 应用目录
|   |-- manage.py           # Django 管理脚本
|   `-- project/            # 项目配置文件目录
|-- frontend/               # 前端代码目录
|   |-- node_modules/       # 前端依赖模块目录
|   |-- src/                # 源码目录
|   `-- package.json        # 前端项目配置文件
`-- deployment/             # 部署脚本和配置文件目录
```

## 核心亮点

- 前后端分离，易于维护与扩展
- 灵活的权限管理，确保系统安全
- 丰富的功能模块，满足不同角色需求
- 高效的订单处理流程，提升工作效率
- 支持多终端访问，方便快捷

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img14.360buyimg.com/ddimg/jfs/t1/343995/30/7301/23122/68d4f381Fcacf015e/8fe85261d249aefe.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/351129/2/7354/25832/68d4f382Fdbebe90f/3f1ec2c873e353fe.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/343420/5/7311/74661/68d4f382F31cef612/e4c03e16348fbb1d.jpg)
