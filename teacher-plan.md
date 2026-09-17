# 宽柔中学 Micro Society 手机 App 开发组
## 教师自学计划书（React Native + Expo 版）

---

## 0. 前提与心态

- 你是老师，不是工程师。
- 目标不是“精通 React Native”，而是：
  - 能示范
  - 能讲解
  - 能排错
  - 能带学生做出可安装的 App
- 建议周期：**8 周**
- 每周投入：**6–8 小时**
- 总时数：约 **50 小时**
- 设备建议：
  - iPad 可应急，但强烈建议借一台 Windows / Mac 笔记本
  - 配蓝牙键盘 + 鼠标
  - 手机安装 **Expo Go**
  - 注册：Expo、GitHub、Google / Firebase
- 核心原则：
  - 先跑通，再理解
  - 先做小项目，再学理论
  - 每学一个概念，立刻在 Expo Snack 实作

---

## 1. 教师最终能力清单

完成本计划后，你应能：

1. 用 Expo Snack 做出 Hello World、计数器、待办、天气 App。
2. 用 React Navigation 做 3 屏幕导航。
3. 用 AsyncStorage 保存本地数据。
4. 用 fetch 调用 API，处理 loading / error。
5. 用 Firebase 读写数据，设置安全规则。
6. 用 EAS Build 打包 APK。
7. 用 Git commit / push 到 GitHub。
8. 讲解并批改 HW1–HW4。
9. 处理学生常见错误：环境、网络、JSON、权限、打包。
10. 独立带学生完成校庆项目。

---

## 2. 八周学习阶段总表

| 周 | 阶段 | 学习目标 | 实作产出 |
|---|---|---|---|
| 1 | JavaScript 核心 | 掌握 JS 必备语法 | 计算器逻辑、数组练习、模拟异步 |
| 2 | React 核心 | 组件、JSX、props、state | 井字棋、计数器、待办列表 |
| 3 | React Native + Expo 基础 | 手机 UI、样式、列表 | Hello、个人主页、购物清单 |
| 4 | 导航 + 存储 + API | 多屏幕、AsyncStorage、fetch | 多屏幕待办、天气 App |
| 5 | Firebase + 打包 | 云端读写、EAS Build | 云端待办、排行榜、APK |
| 6 | 项目流程 + 教学演练 | wireframe、Git、评分 | 校庆项目 Demo、教案 |
| 7 | 进阶预览 | 通知、相机、Supabase、Flutter | 进阶 Demo、FAQ |
| 8 | 教材制作 | 20 节 slides、源码、评分表 | 完整教学包 |

---

## 3. 每周详细计划

### 第 1 周：JavaScript 核心

**目标**：用最少时间掌握教 React Native 所需的 JS。

**学习内容**：
- 变量：let / const
- 函数：箭头函数、默认参数
- 数组：map、filter、find
- 对象：解构、展开运算符
- 模块：import / export
- 异步：Promise、async / await
- 闭包、this 简单带过

**实作**：
- 用 JS 写计算器逻辑
- 数组过滤与映射练习
- 模拟异步请求

**资源**：
- javascript.info（第 1–6 章）
- freeCodeCamp JavaScript 基础

**检查标准**：
- 能读懂并改写简单 JS
- 能解释 `async/await` 的作用

---

### 第 2 周：React 核心

**目标**：理解组件化思维和状态管理。

**学习内容**：
- 函数组件
- JSX 语法
- props 传递
- useState
- 事件处理
- 条件渲染
- 列表渲染

**实作**：
- 井字棋
- 计数器
- 待办列表

**资源**：
- react.dev 官方教程

**检查标准**：
- 能拆分组件
- 能用 state 管理数据
- 能解释 props 和 state 的区别

---

### 第 3 周：React Native + Expo 基础

**目标**：能在手机上跑出真实 App。

**学习内容**：
- Expo Snack
- Expo Go
- View、Text、TextInput、Button
- StyleSheet、Flexbox
- FlatList
- 图标库

**实作**：
- Hello App
- 自我介绍 App
- 购物清单
- 简单待办列表

**检查标准**：
- 能用 Expo Go 扫码预览
- 能做出 2 个屏幕以内的 App

---

### 第 4 周：导航 + 存储 + API

**目标**：做出接近 HW2 的完整小 App。

**学习内容**：
- React Navigation
- Stack Navigator
- 页面跳转、传参
- AsyncStorage 读写
- fetch、HTTP GET、JSON 解析
- loading / error 处理

**实作**：
- 多屏幕待办 App
- 天气 App
- 汇率 App

**检查标准**：
- 能独立完成 2 屏幕 + API + 本地存储
- 能处理无网络情况

---

### 第 5 周：Firebase + 打包 APK

**目标**：让 App 能云端同步，并能安装到手机。

**学习内容**：
- Firebase 项目创建
- Realtime Database / Firestore
- 读、写、更新、删除
- 安全规则
- EAS Build
- APK 安装测试

**实作**：
- 云端待办 App
- 简单排行榜
- 打包 APK

**检查标准**：
- 能生成 APK 并安装
- 能设置 Firebase 安全规则，不开放 public write

---

### 第 6 周：项目流程 + 教学演练

**目标**：能带学生做校庆项目。

**学习内容**：
- Wireframe
- 用户流程
- README 写法
- Git：repo、commit、push
- 项目评分表
- 出题技巧

**实作**：
- 做一份完整校庆项目 Demo
- 写一份教案
- 建立 GitHub 模板 repo

**检查标准**：
- 能讲解项目流程
- 能批改 HW3、HW4
- 能处理学生 Git 常见问题

---

### 第 7 周：进阶预览

**目标**：见过明年 Intermediate 组的内容。

**学习内容**：
- Expo 通知
- Expo 相机
- Supabase 基础
- Flutter / Dart 预览
- 原生 Android / iOS 概念

**实作**：
- 调用相机拍照
- 用 DartPad 写一个小程序
- 看 Flutter 示例

**检查标准**：
- 能演示进阶功能
- 能回答学生“下一步学什么”

---

### 第 8 周：教材制作

**目标**：把 20 节课的教材全部准备好。

**产出**：
- 20 节 slides
- 每节完整版源码
- 每节半成品源码
- 常见错误 FAQ
- 备用 API 清单
- 作业评分表
- 测试题库

**检查标准**：
- 随便抽一节，都能直接上课
- 学生卡住时，你有备用方案

---

## 4. 每周时间表模板

| 时间 | 任务 |
|---|---|
| 周一 1h | 看文档、教程 |
| 周三 2h | 实作小项目 |
| 周六 3h | 做完整项目、整理笔记 |
| 周日 1h | 复习、写 FAQ、准备教材 |

> 如果只有 4 周：把第 1–2 周合并，第 3–4 周合并，第 5–6 周合并，第 7–8 周只做预览。
> 如果有 12 周：每周只专注一个主题，多做项目。

---

## 5. 每节课备课清单

| 节次 | 老师要提前会 |
|---|---|
| 1 | Expo Snack、Expo Go、Hello World |
| 2 | JS 核心语法 |
| 3 | React 组件、JSX、props |
| 4 | useState、事件、表单 |
| 5 | StyleSheet、Flexbox、UI/UX |
| 6 | FlatList、增删改 |
| 7 | React Navigation |
| 8 | AsyncStorage |
| 9 | fetch、JSON、async/await |
| 10 | 天气 / 待办整合 |
| 11 | wireframe、Git 基础 |
| 12 | 项目骨架、导航、数据流 |
| 13 | 核心功能 1 |
| 14 | Firebase / API 整合 |
| 15 | 测试、修 bug |
| 16 | EAS Build、APK、README |
| 17 | 出题、评分 |
| 18 | 进阶 API、错误处理、通知、相机 |
| 19 | Firebase / Supabase |
| 20 | Git 进阶、Flutter 预览 |

---

## 6. iPad 学习建议

- **可以**：用 Safari 打开 `snack.expo.dev` 学 React Native。
- **可以**：用 Expo Go 扫码测试。
- **可以**：用 Swift Playgrounds 学编程思维（选修）。
- **不建议**：用 iPad 做 Git、EAS Build、VS Code 开发。
- **强烈建议**：借一台笔记本，或至少配蓝牙键盘 + 鼠标。

---

## 7. 常见坑

- 不要先学 Flutter，会死。
- 不要跳过 JS 异步。
- 不要教 class components，直接函数组件 + hooks。
- 不要用 Redux，先用 useState / useContext。
- 不要公开 Firebase 写权限。
- 不要第 16 节才第一次打包 APK。
- 不要收集学生隐私数据。
- API 会失效，一定要有备用。
- 模拟器很慢，能真机就真机。
- 学校网络可能挡 Google，提前测试。

---

## 8. 教师自测清单

- [ ] 能独立做出 Hello、计数器、待办、天气 App
- [ ] 能解释 props vs state
- [ ] 能处理 fetch error
- [ ] 能用 AsyncStorage 保存数据
- [ ] 能用 Firebase 读写数据
- [ ] 能打包 APK
- [ ] 能教 Git commit / push
- [ ] 能批改 HW1–HW4
- [ ] 能带学生完成校庆项目
- [ ] 有备用 API 和离线 JSON

---

## 9. 资源清单

- Expo Snack：https://snack.expo.dev
- Expo 文档：https://docs.expo.dev
- React 官方教程：https://react.dev
- JavaScript 教程：https://javascript.info
- React Navigation：https://reactnavigation.org
- Firebase：https://firebase.google.com
- EAS Build：https://docs.expo.dev/build/introduction
- GitHub：https://github.com
- DartPad：https://dartpad.dev
- Flutter：https://flutter.dev

---

## 10. 一句话总结

**你不是要变成 React Native 工程师，你是要变成能带学生做出真实 App 的教练。**
先自己跑通 5 个小 App，再按 20 节提前一周备课，就够了。