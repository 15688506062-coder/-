# Explore Shandong 🗺️

一个基于 Flutter 开发的山东省旅游文化展示应用，通过精美的 UI 设计、城市景点推荐、美食探索、路线规划和 AI 旅行顾问功能，帮助用户深入了解山东特色城市文化。

---

## 📱 项目简介

Explore Shandong 是一个面向旅游爱好者和家乡文化推广的移动应用。

应用围绕山东代表城市展开，整合：

* 城市介绍
* 景点推荐
* 特色美食
* 旅行路线规划
* 城市探索打卡
* AI 智能旅行推荐

目前收录城市：

* 东营（黄河入海口 · 生态之城）
* 烟台（仙境海岸线 · 海滨之城）
* 聊城（江北水城 · 文化之城）

---

## ✨ 功能特色

### 🏠 首页

* 精美轮播 Banner
* 城市推荐卡片
* 探索统计数据
* 快速功能入口
* AI 旅行顾问入口

### 🔍 城市探索

用户可以浏览：

* 城市文化介绍
* 城市特色标签
* 推荐景点
* 推荐美食
* 旅行路线

支持进入城市详情页进行深入探索。

---

### 📍 景点打卡系统

用户可以：

* 浏览景点信息
* 完成景点打卡
* 查看打卡记录
* 累积旅行积分

系统自动统计：

* 已探索城市数
* 已打卡景点数
* 获得积分

---

### 🍜 美食地图

展示山东特色美食：

#### 东营

* 黄河口大闸蟹
* 广饶肴驴肉
* 史口烧鸡

#### 烟台

* 鲅鱼水饺
* 海肠捞饭
* 蓬莱小面

#### 聊城

* 魏氏熏鸡
* 呱嗒
* 高唐驴肉火烧

---

### 🗺️ 路线规划

为每个城市提供旅行路线推荐：

* 一日游
* 两日游
* 经典景点路线
* 美食路线

帮助用户快速制定行程。

---

### 🤖 AI 旅行顾问

通过问答方式分析用户偏好：

* 喜欢自然风光
* 喜欢海滨城市
* 喜欢历史文化
* 喜欢特色美食

智能推荐最适合的山东旅游目的地。

---

### 👤 个人中心

包含：

* 探索进度统计
* 城市完成情况
* 旅行积分
* 成就系统

激励用户持续探索山东文化。

---

## 🎨 UI 设计特点

### Material 3

项目采用：

* Material Design 3
* Flutter 最新设计规范
* 响应式布局

### 视觉风格

特点：

* 大圆角卡片设计
* 渐变色主题
* 城市专属配色
* 动态过渡动画
* 沉浸式图片展示

---

## 🏗️ 项目结构

```text
lib/
│
├── main.dart
│
├── 数据模型
│   ├── CityData
│   ├── Attraction
│   ├── Food
│   ├── RoutePlan
│   └── RouteItem
│
├── 页面
│   ├── SplashPage
│   ├── HomePage
│   ├── ExploreTab
│   ├── ProfileTab
│   ├── CityDetailPage
│   ├── MapPage
│   └── AIQuizPage
│
├── 公共组件
│   ├── SmartImage
│   ├── StarRating
│   └── TagChip
│
└── 状态管理
    └── TravelAppState
```

---

## 🚀 运行项目

### 1. 克隆仓库

```bash
git clone https://github.com/yourname/explore-shandong.git
```

### 2. 进入项目

```bash
cd explore-shandong
```

### 3. 安装依赖

```bash
flutter pub get
```

### 4. 运行项目

```bash
flutter run
```

---

## 🛠 技术栈

* Flutter
* Dart
* Material 3
* StatefulWidget
* AnimationController
* PageView
* CustomScrollView
* Hero UI Design

---

## 🌟 项目亮点

* 丰富的山东文化内容
* 精美现代化 UI
* 动画启动页
* 智能推荐系统
* 打卡积分机制
* 路线规划功能
* 图片加载优化
* 响应式布局设计

---

## 📌 未来规划

计划新增：

* 更多山东城市
* 实时天气查询
* 地图导航
* 收藏功能
* 用户登录
* 云端数据同步
* AI 行程生成
* 多语言支持

---

## 📄 License

This project is licensed under the MIT License.

---

**Explore Shandong · 发现山东之美，探索家乡故事**
