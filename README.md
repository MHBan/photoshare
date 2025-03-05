# photoshare
图片分享网站。SpringBoot3+Vue3
# 前言

本项目名为MHBan,是一个简单的图片分享展示网站，如果有机会，我会继续更新。(虽然这个项目很垃圾，但**禁止商用**！)

# 技术栈

## 后端：

SpringBoot

redis

mybatis

minio

mail

数据库：Mysql

## 前端：

VUE3（node.js v20.18.0，npm 10.8.2)

Element-plus

# 项目大体展示

登录

![login](https://github.com/user-attachments/assets/4000b69d-796b-49d5-b00b-64f5f999753a)


注册：需要真实的邮箱地址，获取验证码后才可以登录，一个邮箱地址只能对应一个账号

![register](https://github.com/user-attachments/assets/4efb70a0-d9fa-4a1b-a9bc-306b8a215e31)


首页

![home](https://github.com/user-attachments/assets/611bc6dc-4db1-4290-8e30-43fe5190f79a)


上传图片

![upload](https://github.com/user-attachments/assets/fa36bc00-7b16-4f62-b185-067e4463217a)


除此之外，还包含图片搜索、基本资料修改、头像更换、密码更改等功能

# 需要修改的配置

![watchout](https://github.com/user-attachments/assets/bc9ea854-3707-479e-92ba-0b6cf9a5e23a)


需要对application.yml进行更改

包括：重新配置Mysql数据库，redis服务，minio服务，mail服务

# 注意

前端，我只上传了src文件夹
