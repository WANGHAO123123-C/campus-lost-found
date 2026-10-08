1.项目背景
在校园日常中，学生经常丢失校园卡、耳机、雨伞、书本等物品。当前寻物、招领信息分散在班级群、朋友圈，消息容易被刷屏覆盖，信息传播范围有限，失主与拾物人很难匹配上。
本次设计“校园失物招领小程序”，目标是集中存放寻物、招领信息，支持浏览、发布、关键词搜索，简化校园物品找回流程。本原型仅做基础功能，不开发实名认证、即时聊天、地图定位等复杂模块，为后续代码实现预留空间。

2.用户与用户需求
用户：在校大学生

3.丢失物品：
发布寻物启事，填写物品信息、丢失地点、物品描述

4.捡到物品：
发布招领启事，上传物品描述、捡拾地点

5.浏览：
查看全部寻物、招领信息列表

6.检索：
输入物品名称关键词，快速搜索相关信息

7.查看详情：
点开单条信息，查看完整描述

8.管理：
查看自己发布的记录，物品找到后修改信息状态为【已完成】

9.解决的问题
解决校园失物信息碎片化、消息易被淹没、跨班级信息无法互通的痛点，统一信息发布平台，提升物品找回效率。

二、软件主要功能
1. 浏览失物、招领信息首页列表
2.发布寻物信息
3.发布招领信息
4. 关键词搜索物品信息
5.查看物品详情页面
6.我的发布：查看本人发布记录，修改信息状态（进行中/已完成）
三、原型设计说明
原型工具：墨刀
原型在线链接：https://modao.cc/proto/design/pb2mump1ws8g95mnp?open_access_menu=&curSpaceCid=spmump159ileowmb
原型包含页面：
<img width="490" height="1060" alt="image" src="https://github.com/user-attachments/assets/8f27b742-7898-4fc2-af00-d6690c8657d0" />
<img width="436" height="1009" alt="image" src="https://github.com/user-attachments/assets/4c50154b-6158-4f84-917d-8554f5581d35" />
<img width="499" height="1069" alt="image" src="https://github.com/user-attachments/assets/77dccab4-c9f0-466d-aee1-1c1d1d772eab" />
<img width="538" height="1045" alt="image" src="https://github.com/user-attachments/assets/b0b5c83e-d166-42f5-8ebd-6fb014f5f42c" />
目录结构
campus-lost-found/

├── index.html          # 主页面（单页应用：首页/发布/搜索/详情/我的发布）

├── css/

│   └── style.css       # 全部样式（小程序风格，移动端居中、响应式）

├── js/

│   ├── data.js         # 数据模型 + 示例数据 + localStorage 读写

│   ├── core.js         # 核心业务逻辑（校验/搜索/状态标记/统计，纯函数）

│   └── app.js          # 页面渲染、路由与交互逻辑

├── test/

│   ├── test.html       # 单元测试运行页面

│   └── test.js         # 35 个单元测试用例（白盒为主）

├── docs/               # 博客素材（流程图、截图）

└── README.md           # 目录说明与使用说明



