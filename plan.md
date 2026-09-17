# 宽柔中学 Micro Society
## 手机 App 开发组 详细计划书（React Native + Expo 版）

---

## 0. 一页摘要

- **组名**：手机 App 开发组（Mobile App Development Group）
- **时间**：每周一次，共 20 节
- **总时数**：约 50 小时
- **主线工具**：React Native + Expo
- **开发环境**：Expo Snack（浏览器）或 VS Code + Node.js
- **测试方式**：手机安装 Expo Go，扫码实时预览
- **打包方式**：EAS Build 云构建 APK
- **数据与后端**：AsyncStorage、Firebase、免费 API
- **版本控制**：GitHub
- **进阶预览**：Flutter / Dart、原生开发概念

---

## 1. 总目标与成果

### 1.1 总目标

学生在 20 节内从已有编程基础过渡到移动 App 开发，能够：

1. 掌握 JavaScript 核心：变量、函数、数组、对象、解构、模块、async/await。
2. 理解 React 组件、JSX、props、state、hooks。
3. 使用 React Native 构建跨平台 App。
4. 使用 React Navigation 实现多屏幕导航。
5. 使用 AsyncStorage 做本地存储。
6. 调用免费 API，读取 JSON 数据，处理 loading / error。
7. 使用 Firebase 做云端同步、排行榜、报名等。
8. 使用 Git 管理代码，上传 GitHub。
9. 使用 EAS Build 打包 APK，安装在自己的 Android 手机。
10. 完成一个年度小组项目（校庆作品）。

### 1.2 最终成果

- 4 个作业
- 1 个测试
- 1 个校庆作品（可运行 APK + GitHub repo + README + 演示）

---

## 2. 对象、人数、时间、场地、设备

### 2.1 对象

- 已有 C++ 一年基础，或 Python / HTML / CSS / Lua 基础
- 对手机 App、工具、设计、游戏有兴趣
- 建议优先招 Android 手机用户（方便装 APK）

### 2.2 人数

- 理想：12–18 人
- 最多：20 人
- 分组：2 人一组，校庆项目 2–3 人一组

### 2.3 设备

- 电脑：能开 Chrome 即可；若用 VS Code，需能安装 Node.js
- 手机：Android 优先，安装 Expo Go
- 没有 Android 手机：两人一组，或使用 Expo Snack 网页预览
- 网络：需要能访问 Expo、GitHub、Firebase、免费 API
- Google 账号：Firebase 需要
- Expo 账号：EAS Build 需要（免费）

---

## 3. 工具与平台

### 3.1 主工具

- **React Native + Expo**
  - 一套代码同时生成 Android / iOS App
  - 浏览器可用 Expo Snack，零安装
  - 手机装 Expo Go，扫码即跑
  - 支持相机、音频、传感器、定位、通知等硬件功能
- **JavaScript / TypeScript**
  - 先以 JavaScript 为主，后期可引入 TypeScript
- **React Navigation**
  - 多屏幕导航

### 3.2 进阶工具

- **AsyncStorage**
  - 本地存储，类似 TinyDB
- **Firebase Realtime Database / Firestore**
  - 云端同步、排行榜、报名
  - 不绑信用卡，使用 Spark 免费计划
  - 必须设置安全规则，不开放 public write
- **Google Sheets + Apps Script**
  - 免费后端替代
- **GitHub**
  - 存代码、README、作品
- **EAS Build**
  - 云端打包 APK，无需本地 Android SDK
- **Expo Snack**
  - 浏览器写代码，适合机房快速开始

### 3.3 免费 API 建议

- Open-Meteo：天气，无需 key
- Frankfurter：汇率，无需 key
- Quotable：名言
- JSONPlaceholder：练习用假数据
- 备用 API 一定要准备，避免 API 失效

---

## 4. 20 节总表

| 节 | 主题 | 类型 | 作业 |
|---|---|---|---|
| 1 | Expo 入门：Hello World、Expo Go、Snack | 基础 | — |
| 2 | JavaScript 核心速成 | 基础 | — |
| 3 | React 组件、JSX、props | 基础 | 布置 HW1 |
| 4 | State、事件、表单 | 基础 | — |
| 5 | 样式、Flexbox、UI/UX | 基础 | HW1 截止 |
| 6 | 列表 FlatList、增删改 | 基础 | — |
| 7 | 多屏幕导航 React Navigation | 基础 | 布置 HW2 |
| 8 | 本地存储 AsyncStorage | 基础 | — |
| 9 | 网络、API、JSON、async/await | 基础 | — |
| 10 | 整合小项目：天气 / 待办 | 基础 | HW2 截止 |
| 11 | 项目定题、wireframe、Git 基础 | 项目 | 布置 HW3，年度项目定题 |
| 12 | 项目骨架、导航、数据流 | 项目 | — |
| 13 | 核心功能 1 | 项目 | HW3 截止 |
| 14 | 核心功能 2 + Firebase / API | 项目 | 布置 HW4 |
| 15 | 测试、修 bug、优化 | 项目 | — |
| 16 | 打包 APK、提交，年度项目 ready | 项目 | HW4 截止 |
| 17 | 测试课 | 测试 | 测试 |
| 18 | 进阶 API、错误处理、通知、相机、传感器 | 进阶 | 进阶挑战 |
| 19 | 云端数据库 Firebase / Supabase | 进阶 | 进阶挑战 |
| 20 | Git 进阶 + Flutter / 原生预览 | 进阶 | 衔接明年 |

---

## 5. 每节详细教案

### 第 1 节：Expo 入门

**目标**：认识 Expo、Expo Go、Expo Snack，跑通第一个 App。

**内容**：
- 注册 Expo 账号
- 打开 snack.expo.dev
- 手机安装 Expo Go，扫码预览
- 组件、JSX、Text、View、Button
- 修改文字、颜色、样式

**实作**：
- Hello App
- 自我介绍 App
- 按按钮改变文字和颜色

**产出**：
- 一个可在手机上运行的 Expo App

**作业**：
- 无正式作业，练习修改自我介绍 App

---

### 第 2 节：JavaScript 核心速成

**目标**：用 C++/Python 对照，快速掌握 JS 必备语法。

**内容**：
- 变量：let / const
- 函数：箭头函数、默认参数
- 数组：map、filter、find
- 对象：解构、展开运算符
- 模块：import / export
- 异步：Promise、async/await
- 闭包、this 简单带过

**实作**：
- 用 JS 写计算器逻辑
- 数组过滤与映射练习
- 模拟异步请求

**产出**：
- 能读懂并修改 JS 代码

**作业**：
- 准备 HW1 概念

---

### 第 3 节：React 组件、JSX、props

**目标**：理解 React 组件化思维。

**内容**：
- 函数组件
- JSX 语法
- props 传递
- 组件拆分
- 条件渲染

**实作**：
- 卡片组件
- 用户信息组件
- 简单页面布局

**产出**：
- 多个可复用组件

**作业**：
- 布置 HW1：计数器 + 待办列表（JS + React 基础）
- 截止：第 5 节

---

### 第 4 节：State、事件、表单

**目标**：掌握 useState 和用户交互。

**内容**：
- useState
- 事件处理
- TextInput
- 表单提交
- 状态更新

**实作**：
- 计数器
- 登录表单
- 年龄判断器

**产出**：
- 能输入并显示结果的 App

**作业**：
- 继续 HW1

---

### 第 5 节：样式、Flexbox、UI/UX

**目标**：学会 React Native 样式与基本设计。

**内容**：
- StyleSheet
- Flexbox 布局
- 间距、字体、颜色
- 图标库
- 响应式设计

**实作**：
- 美化 HW1
- 做一个个人主页 UI

**产出**：
- 界面整齐的 App

**作业**：
- HW1 截止
- 检查与展示

---

### 第 6 节：列表 FlatList、增删改

**目标**：处理列表数据。

**内容**：
- FlatList
- map 渲染列表
- 添加、删除、修改
- key 的重要性

**实作**：
- 购物清单
- 简单待办列表
- 列表筛选

**产出**：
- 能用列表的 App

**作业**：
- 准备 HW2

---

### 第 7 节：多屏幕导航 React Navigation

**目标**：学会多屏幕 App 和页面跳转。

**内容**：
- 安装 React Navigation
- Stack Navigator
- 页面跳转
- 传递参数
- 返回按钮

**实作**：
- 多页自我介绍 App
- 菜单页 → 内容页

**产出**：
- 2–3 屏幕 App

**作业**：
- 布置 HW2：多屏幕 + API + AsyncStorage 小 App
- 截止：第 10 节

---

### 第 8 节：本地存储 AsyncStorage

**目标**：学会保存资料，关闭 App 后资料还在。

**内容**：
- AsyncStorage 读写
- 键值对概念
- 存储列表
- 删除数据

**实作**：
- 待办清单
- 笔记 App
- 单词卡

**产出**：
- 能保存资料的 App

**作业**：
- 继续 HW2

---

### 第 9 节：网络、API、JSON

**目标**：学会调用 API 和读取 JSON。

**内容**：
- fetch
- HTTP GET
- JSON 解析
- async/await
- 错误处理初步
- loading 状态

**实作**：
- 读取免费 API
- 显示名言 / 汇率
- 简单 JSON 解析

**产出**：
- 一个能联网的 App

**作业**：
- 继续 HW2

---

### 第 10 节：整合小项目：天气 / 待办

**目标**：完成一个完整小 App。

**内容**：
- 整合 UI + API + AsyncStorage
- 加载中提示
- 错误提示
- 城市输入
- 结果显示

**实作**：
- 天气 App
- 或汇率 App
- 或名言 App

**产出**：
- 完整小 App

**作业**：
- HW2 截止
- 展示与互评

---

### 第 11 节：项目定题、wireframe、Git 基础

**目标**：准备年度项目，学会版本控制。

**内容**：
- UI vs UX
- 配色、字体、间距、图标
- 线框图
- 用户流程
- Git：repo、commit、push
- GitHub README

**实作**：
- 画年度项目 wireframe
- 分组、定题
- 建立 GitHub repo

**产出**：
- 项目提案 + wireframe + GitHub repo

**作业**：
- 布置 HW3：项目 wireframe + 3 屏幕 + 主要数据流
- 截止：第 13 节
- 年度项目必须本节定题

---

### 第 12 节：项目骨架、导航、数据流

**目标**：建立项目骨架。

**内容**：
- 屏幕规划
- 导航设计
- 数据流
- AsyncStorage / API / Firebase 规划
- 分工

**实作**：
- 建立 3–4 个屏幕
- 做基本导航
- 做假数据测试

**产出**：
- 项目骨架

**作业**：
- 继续 HW3
- 开始写项目 README

---

### 第 13 节：核心功能 1

**目标**：完成项目最主要功能。

**内容**：
- 主功能实现
- 调试
- 小组分工
- 进度检查

**实作**：
- 完成主功能 50–70%

**产出**：
- 可运行一半的项目

**作业**：
- HW3 截止
- 继续项目

---

### 第 14 节：核心功能 2 + Firebase / API

**目标**：完成第二个核心功能或整合 Firebase / API。

**内容**：
- Firebase Realtime Database / Firestore
- 读、写、更新、删除
- 安全规则
- API 整合
- 错误处理
- 测试

**实作**：
- 完成项目 80%
- 云端同步或排行榜

**产出**：
- 接近完成的项目

**作业**：
- 布置 HW4：可运行原型 + APK + 3 分钟演示
- 截止：第 16 节

---

### 第 15 节：测试、修 bug、优化

**目标**：让项目稳定。

**内容**：
- 测试清单
- 找 bug
- 修 bug
- UI 优化
- 准备演示

**实作**：
- 同组互测
- 跨组测试
- 收集反馈

**产出**：
- 稳定版项目

**作业**：
- 继续 HW4
- 准备第 16 节提交

---

### 第 16 节：打包 APK、提交，年度项目 ready

**目标**：年度项目必须 ready。

**内容**：
- EAS Build 打包 APK
- 导出源码
- 写 README
- 准备 slides
- 提交

**实作**：
- 每组安装 APK
- 演示 3 分钟
- 提交文件

**产出**：
- APK
- GitHub repo
- README
- 演示 slides
- 年度项目正式 ready

**作业**：
- HW4 截止
- 准备第 17 节测试

---

### 第 17 节：测试课

**目标**：检验学生是否掌握基础。

**内容**：
- 30 分钟笔试
- 90 分钟实作
- 30 分钟口试 / 展示 / 检讨

**笔试范围**：
- JS 基础、React 组件、state、props、导航、AsyncStorage、API、Firebase、Git

**实作**：
- 做一个 2 屏幕小 App

**评分**：
- 笔试 30%
- 实作 50%
- 口试 20%

**产出**：
- 测试成绩
- 升组参考

---

### 第 18 节：进阶 API、错误处理、通知、相机、传感器

**目标**：从“会调用 API”升级到“会处理真实情况”。

**内容**：
- REST API 复习
- 嵌套 JSON
- JSON 里的列表
- 错误处理：404、超时、无网络、API 限制
- 加载中 UI
- 重试按钮
- 多 API 整合
- 简单缓存
- Expo 通知、相机、传感器

**实作**：
- 多来源资讯 App：天气、汇率、名言 / 笑话
- 没网络时显示错误，不崩溃
- 调用相机拍照

**产出**：
- 进阶 API App

---

### 第 19 节：云端数据库 Firebase / Supabase

**目标**：让 App 能同步、共享、排行榜。

**内容**：
- 为什么需要云端
- Firebase Realtime Database / Firestore 基础：读、写、更新、删除
- 或 Supabase
- 安全规则：不要公开写权限
- 不要收集同学隐私数据

**实作**：
选一个：
- 云端待办 App
- 简单排行榜
- 班级活动报名 App

**工具**：
- Firebase Spark 免费计划
- Supabase 免费计划
- GitHub

**注意**：
- 不绑信用卡
- 不开放 public write
- 只做学习用途

---

### 第 20 节：Git 进阶 + Flutter / 原生预览

**目标**：让学生见过明年的进阶路线。

**内容**：
- Git 分支、merge、pull request
- GitHub Actions 简单介绍
- Flutter / Dart 预览
- 原生 Android / iOS 概念
- 明年 Intermediate 组路线

**实作**：
- 用 DartPad 写一个小程序
- 看 Flutter 示例
- 把今年项目的源码、APK、README 整理上 GitHub

**工具**：
- DartPad
- GitHub
- Flutter 文档

**为什么进阶**：
明年如果分 Beginner / Intermediate：
- Beginner：继续 React Native + Expo
- Intermediate：Flutter + Firebase + API + Git

---

## 6. 四个作业详细设计

| 作业 | 布置 | 截止 | 内容 | 评分重点 |
|---|---|---|---|---|
| HW1 | 第 3 节 | 第 5 节 | 计数器 + 待办列表，JS + React 基础 | 功能、逻辑、界面 |
| HW2 | 第 7 节 | 第 10 节 | 多屏幕 + API + AsyncStorage 小 App | 存储、列表、稳定 |
| HW3 | 第 11 节 | 第 13 节 | 项目 wireframe + 3 屏幕 + 主要数据流 | 规划、设计、完整 |
| HW4 | 第 14 节 | 第 16 节 | 可运行 App + APK + 3 分钟演示 | 成品、演示、文档 |

### HW1：计数器 + 待办列表

- 使用 React 组件
- 使用 useState
- 使用 FlatList
- 能添加、删除
- 界面整齐

### HW2：多屏幕 + API + AsyncStorage

- 使用 React Navigation
- 使用 fetch 调用 API
- 使用 AsyncStorage 保存数据
- 有 loading / error 提示
- 关闭 App 后资料还在

### HW3：项目 wireframe + 3 屏幕

- 画 wireframe
- 说明每个屏幕功能
- 说明数据流
- 说明使用 AsyncStorage / API / Firebase
- 小组分工表
- GitHub repo

### HW4：可运行 App + APK

- 能安装
- 主功能可用
- 有 README
- 有 3 分钟演示
- 有 5 页 slides

---

## 7. 校庆项目详细计划

### 7.1 项目范围

- 2–3 人一组
- 3–5 个屏幕
- 1 个主功能
- 1 个本地存储 或 1 个免费 API / Firebase
- 使用 React Native + Expo
- 打包 APK 或提供 Expo 链接

### 7.2 项目时间线

| 节 | 项目进度 |
|---|---|
| 第 11 节 | 定题、分组、wireframe、GitHub repo |
| 第 12 节 | 项目骨架、导航 |
| 第 13 节 | 核心功能 1，HW3 截止 |
| 第 14 节 | 核心功能 2 + Firebase / API |
| 第 15 节 | 测试、修 bug、优化 |
| 第 16 节 | 打包 APK、提交，必须 ready |

### 7.3 项目例子

- 校园工具：时间表、食堂菜单、活动通知、校车时间
- 学习工具：单词卡、测验、公式表、错题本
- 生活工具：喝水提醒、记账、待办、习惯打卡
- 娱乐工具：猜数字、反应测试、记忆翻牌、音乐播放器

### 7.4 交付文件

- APK
- GitHub repo（源码）
- README
- 3 分钟演示视频或现场演示
- 5 页 slides

### 7.5 项目评分表

| 项目 | 分数 |
|---|---|
| 功能完整 | 40 |
| UI/UX | 20 |
| 稳定度 | 20 |
| 文档 README | 10 |
| 展示 | 10 |
| 总分 | 100 |

---

