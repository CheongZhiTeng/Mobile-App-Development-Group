# 宽柔中学 Micro Society 手机 App 开发组
## 软件需求清单（Student & Teacher）

**技术栈**：React Native + Expo  
**更新日期**：2026年9月  
**适用对象**：学生（0基础）、教师（自学中）

---

## 一、学生端软件需求

### 1.1 核心开发工具

| 软件 | 版本要求 | 用途 | 获取方式 |
|---|---|---|---|
| **Expo Snack** | 最新版（浏览器） | 浏览器写代码，零安装入门 | snack.expo.dev |
| **Expo Go** | 最新版 | 手机扫码实时预览 App | App Store / Google Play |
| **Node.js** | LTS 24.x 或更高 | 本地开发环境运行时 | nodejs.org |
| **VS Code** | 最新版 | 代码编辑器 | code.visualstudio.com |
| **Git** | 最新版 | 版本控制 | git-scm.com |

> **说明**：Expo Go 要求 iOS 16.4+ 或 Android 对应版本[reference:0]。React Native 官方要求 Node 22.11.0 或更新版本[reference:1]。Node 24 当前为 Active LTS，建议使用[reference:2]。

### 1.2 浏览器

| 浏览器 | 要求 | 用途 |
|---|---|---|
| **Chrome / Edge / Safari** | 最新版 | Expo Snack、GitHub、Firebase 控制台 |

### 1.3 账号需求（全部免费）

| 平台 | 用途 | 备注 |
|---|---|---|
| **Expo 账号** | Expo Go、EAS Build | 免费注册 |
| **Google 账号** | Firebase、GitHub 登录 | 已有即可 |
| **GitHub 账号** | 代码托管 | 免费 |
| **Firebase 账号** | 云端数据库 | Spark 免费计划 |

> Firebase Spark 免费计划：10K 月活用户、1GB Firestore 存储、50K 读/天[reference:3]。

### 1.4 手机端要求

| 项目 | 要求 |
|---|---|
| **操作系统** | Android 8.0+ 或 iOS 16.4+ |
| **网络** | Wi-Fi，需与电脑同一网络（Expo Go 扫码预览需要） |
| **存储** | 至少 200MB 可用空间 |
| **推荐** | Android 手机（可直接安装 APK） |

> **没有 Android 手机怎么办**：两人一组共用，或使用 Expo Snack 网页预览。

### 1.5 学生不需要安装的软件

- ❌ Android Studio（Expo 托管工作流不需要）
- ❌ Xcode（仅 iOS 原生开发需要）
- ❌ Flutter SDK（第 20 节仅预览，用 DartPad 在线即可）
- ❌ Java JDK（Expo 托管工作流不需要）

---

## 二、教师端软件需求

### 2.1 学生端全部软件 +

### 2.2 额外开发工具

| 软件 | 版本要求 | 用途 | 备注 |
|---|---|---|---|
| **EAS CLI** | 最新版 | 云端打包 APK | `npm install -g eas-cli` |
| **Expo CLI** | 最新版 | 本地项目管理 | `npx expo` |
| **Firebase CLI** | 最新版 | 部署、管理 Firebase | 可选 |
| **Postman / Apidog** | 最新版 | 测试 API | 可选，推荐 |

### 2.3 云端服务（教师配置）

| 服务 | 用途 | 免费额度 |
|---|---|---|
| **Firebase Realtime Database / Firestore** | 云端同步、排行榜 | 1GB 存储，50K 读/天 |
| **Firebase Authentication** | 用户登录 | 10K 月活用户 |
| **EAS Build** | 云端打包 APK | 免费额度（有限次数） |
| **GitHub** | 代码托管、模板 repo | 免费 |

> **安全提醒**：Firebase 安全规则必须设置，不开放 public write。不要收集学生隐私数据。

### 2.4 教学辅助工具

| 工具 | 用途 |
|---|---|
| **Google Slides / PowerPoint** | 20 节 slides |
| **Excalidraw / Figma** | 画 wireframe |
| **Google Sheets** | 成绩登记、作业评分 |
| **GitHub Classroom** | 作业分发、收集（可选） |
| **Discord / WhatsApp** | 课后答疑 |

### 2.5 教师硬件建议

| 项目 | 最低 | 推荐 |
|---|---|---|
| **电脑** | Windows 10 64-bit / macOS 10.15+ | Windows 11 / macOS 13+ |
| **RAM** | 8GB | 16GB（跑模拟器需要） |
| **存储** | 20GB 可用 | 50GB+ |
| **网络** | 稳定 Wi-Fi | 能访问 Google / GitHub |
| **手机** | Android 8.0+ | Android 10+ |
| **外设** | — | 蓝牙键盘 + 鼠标（iPad 开发必备） |

> Android Studio + 模拟器需要 16GB RAM[reference:4]。如果只用 Expo 托管工作流，8GB 即可。

---

## 三、按课程阶段的软件需求

| 节次 | 学生需要 | 教师需要 |
|---|---|---|
| 1–2 | Expo Snack、Expo Go、浏览器 | 同上 + slides |
| 3–5 | Expo Snack 或 VS Code + Node.js | 同上 + 完整/半成品源码 |
| 6–7 | VS Code、Git、GitHub | 同上 + 模板 repo |
| 8–9 | 同上 + AsyncStorage | 同上 + 备用 API 清单 |
| 10 | 同上 + 免费 API | 同上 + 离线 JSON |
| 11–14 | 同上 + Firebase、EAS CLI | Firebase 项目、安全规则 |
| 15–16 | 同上 + EAS Build | EAS Build 账号、APK 测试 |
| 17 | 同上 | 测试题库、评分表 |
| 18–20 | 同上 + DartPad | DartPad、Flutter 示例 |

---

## 四、软件安装清单（学生版）

### 第一天需要装好的：

- [ ] Expo Go（手机）
- [ ] Chrome / Edge / Safari（电脑）
- [ ] Expo 账号注册
- [ ] GitHub 账号注册
- [ ] Google 账号（Firebase 用）

### 第一周需要装好的：

- [ ] Node.js LTS（24.x）
- [ ] VS Code
- [ ] Git
- [ ] 手机与电脑连接同一 Wi-Fi

### 第 11 节前需要装好的：

- [ ] Firebase 项目创建
- [ ] EAS CLI（`npm install -g eas-cli`）
- [ ] Expo 账号登录 EAS

---

## 五、软件安装清单（教师版）

### 课程开始前：

- [ ] 学生端全部软件
- [ ] EAS CLI + Expo 账号
- [ ] Firebase 项目（Spark 计划）
- [ ] GitHub 模板 repo
- [ ] 备用 API 清单 + 离线 JSON
- [ ] 20 节 slides
- [ ] 完整版 + 半成品源码

### 教学过程中：

- [ ] Postman / Apidog（测试 API）
- [ ] Excalidraw / Figma（画 wireframe）
- [ ] Google Sheets（成绩登记）

---

## 六、不需要的软件（避坑）

| 软件 | 为什么不需要 |
|---|---|
| **Android Studio** | Expo 托管工作流不需要本地 Android SDK |
| **Xcode** | 仅 iOS 原生开发需要，Expo 用 EAS Build 云端打包 |
| **Flutter SDK** | 第 20 节仅预览，用 DartPad 在线即可 |
| **Java JDK** | Expo 托管工作流不需要 |
| **Redux / MobX** | 课程用 useState / useContext 足够 |
| **Docker** | 课程不涉及后端部署 |

---

## 七、一句话总结

**学生只需要：Expo Go + 浏览器 + Node.js + VS Code + Git。**  
**教师额外需要：EAS CLI + Firebase + 教学辅助工具。**  
**Android Studio 和 Xcode 都不需要。**