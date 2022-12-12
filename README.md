# 博客园Flutter

使用Flutter编写的博客园客户端，支持iOS及Android。

基于[博客园开放API](https://api.cnblogs.com/help)开发；受制于API，部分功能可能并不完善。

## 框架

- `GetX` 状态管理、路由管理、国际化
- `Dio` 网络请求
- `Hive` 数据存储

## 目录结构

- `app` 一些通用的类及样式
- `services` 提供数据存储等服务
- `requests` 请求的封装
- `generated` 生成的国际化文件,使用 `get generate locales`生成
- `modules` 模块，每个会有两个文件，view及controller
- `widgets` 自定义的小组件
- `routes` 路由定义
- `models` 实体类

## Todo

- 博客
    - [ ] 检查博文收藏状态(API似乎有问题)
- 新闻
    - [ ] 新闻评论(博客园已关闭新闻评论)
- 博问
    - [ ] 获取单个回答的评论
    - [ ] 删除回答
    - [ ] 修改回答
    - [ ] 提问
    - [ ] 回答
    - [ ] 评论
    - [ ] 删除评论
    - [ ] 更新评论

