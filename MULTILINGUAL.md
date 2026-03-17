# 🌐 多语言支持功能说明

**版本：** v4.0  
**发布日期：** 2026-03-17  
**支持语言：** 中文（简体）/ English

---

## 🎉 功能概述

人类历史网站现已支持完整的中英文双语切换功能！用户可以根据自己的语言偏好，一键切换网站的所有文本内容。

---

## ✨ 核心特性

### 1️⃣ **一键语言切换**
- 🇨🇳 中文（简体）
- 🇺🇸 English
- 左上角语言切换按钮
- 即时切换，无需刷新页面

### 2️⃣ **完整翻译覆盖**
- ✅ 所有界面元素（按钮、标签、统计）
- ✅ 所有历史事件（标题、描述、详情、影响）
- ✅ 搜索和过滤功能
- ✅ 图表标签和图例
- ✅ 弹窗和提示信息
- ✅ 收藏面板

### 3️⃣ **本地存储偏好**
- 💾 自动保存语言选择
- 🔄 下次访问自动应用
- 📱 跨设备独立保存

### 4️⃣ **双语事件数据**
- 📚 35 个历史事件的完整双语数据
- 🌍 每个事件包含中英文标题、时间、描述、详情、影响
- 📍 地理位置名称双语显示

---

## 🎯 使用方式

### 方法 1：点击语言按钮
1. 查看页面左上角
2. 点击 🇨🇳 中文 或 🇺🇸 English 按钮
3. 网站立即切换语言

### 方法 2：自动检测
- 首次访问自动使用中文
- 之后访问自动使用上次选择的语言

---

## 📋 翻译对照表

### 界面元素

| 中文 | English |
|------|---------|
| 🌍 人类历史发展进程 | 🌍 Timeline of Human History |
| 📜 时间线视图 | 📜 Timeline View |
| 🗺️ 地图模式 | 🗺️ Map Mode |
| 🔖 收藏 | 🔖 Bookmarks |
| 🔍 搜索历史事件... | 🔍 Search historical events... |
| 全部时间 | All Time |
| 千年尺度 | Millennium |
| 世纪尺度 | Century |
| 年代尺度 | Decade |
| 全部 | All |
| 🎨 文化 | 🎨 Culture |
| ⚙️ 科技 | ⚙️ Technology |
| 🏛️ 政治 | 🏛️ Politics |
| 🔬 科学 | 🔬 Science |
| 💰 经济 | 💰 Economy |
| ⚔️ 军事 | ⚔️ Military |

### 时代分类

| 中文 | English |
|------|---------|
| 🪨 史前时期 | 🪨 Prehistoric |
| 🏛️ 古代文明 | 🏛️ Ancient |
| 🏰 中世纪 | 🏰 Medieval |
| ⛵ 近代早期 | ⛵ Early Modern |
| 🚀 现代 | 🚀 Modern |

### 统计标签

| 中文 | English |
|------|---------|
| 历史事件 | Historical Events |
| 古代文明 | Ancient Civilizations |
| 年历史跨度 | Years of History |
| 分类领域 | Categories |
| 📊 事件时代分布 | 📊 Events by Era |
| 🏷️ 事件分类统计 | 🏷️ Events by Category |

### 弹窗内容

| 中文 | English |
|------|---------|
| 事件描述 | Description |
| 详细信息 | Details |
| 历史影响 | Historical Impact |
| 分类标签 | Tags |
| 📍 位置 | 📍 Location |
| (点击查看地图位置) | (Click to view on map) |
| 📌 相关事件 | 📌 Related Events |
| 暂无收藏事件 | No bookmarks yet |

---

## 📊 事件数据示例

### 示例 1：人类起源

**中文：**
- 标题：人类起源
- 时间：约 300 万年前
- 描述：最早的人类祖先出现在非洲东部
- 详情：南方古猿是最早的人科动物之一，能够直立行走
- 影响：开启了人类进化历程

**English：**
- Title: Origin of Humans
- Time: c. 3 million years ago
- Description: Earliest human ancestors appeared in East Africa
- Details: Australopithecus was one of the earliest hominids, capable of bipedal locomotion
- Impact: Marked the beginning of human evolution

### 示例 2：工业革命

**中文：**
- 标题：工业革命开始
- 时间：公元 1760 年
- 描述：人类进入机械化生产时代
- 详情：工业革命以蒸汽机的改良为标志
- 影响：彻底改变了人类的生产生活方式

**English：**
- Title: Industrial Revolution Begins
- Time: 1760 CE
- Description: Humanity entered mechanized production era
- Details: Industrial Revolution marked by steam engine improvement
- Impact: Completely transformed human production and lifestyle

---

## 🔧 技术实现

### 数据结构

```javascript
// 双语事件数据
const historicalEvents = [
  { 
    id: 1, 
    era: "prehistoric", 
    title: { 
      zh: "人类起源", 
      en: "Origin of Humans" 
    },
    time: { 
      zh: "约 300 万年前", 
      en: "c. 3 million years ago" 
    },
    location: { 
      zh: "非洲东部", 
      en: "East Africa" 
    },
    description: { 
      zh: "最早的人类祖先出现在非洲东部", 
      en: "Earliest human ancestors appeared in East Africa" 
    },
    details: { 
      zh: "南方古猿是最早的人科动物之一...", 
      en: "Australopithecus was one of the earliest..." 
    },
    impact: { 
      zh: "开启了人类进化历程", 
      en: "Marked the beginning of human evolution" 
    },
    tags: ["science", "culture"]
  }
  // ... 更多事件
];
```

### 翻译对象

```javascript
const translations = {
  zh: {
    title: '🌍 人类历史发展进程',
    subtitle: 'Timeline of Human History - From Origins to Present',
    searchPlaceholder: '🔍 搜索历史事件、文明、人物...',
    timelineView: '📜 时间线视图',
    mapView: '🗺️ 地图模式',
    bookmarks: '🔖 收藏',
    // ... 更多翻译
  },
  en: {
    title: '🌍 Timeline of Human History',
    subtitle: 'From Origins to Present - 人类历史发展进程',
    searchPlaceholder: '🔍 Search historical events, civilizations, figures...',
    timelineView: '📜 Timeline View',
    mapView: '🗺️ Map Mode',
    bookmarks: '🔖 Bookmarks',
    // ... 更多翻译
  }
};
```

### 切换函数

```javascript
function switchLanguage(lang) {
  currentLang = lang;
  localStorage.setItem('historyLang', lang);
  
  // 更新语言按钮状态
  document.getElementById('langZh').classList.toggle('active', lang === 'zh');
  document.getElementById('langEn').classList.toggle('active', lang === 'en');
  
  // 更新 HTML lang 属性
  document.documentElement.lang = lang === 'zh' ? 'zh-CN' : 'en';
  
  // 更新所有 i18n 元素
  document.querySelectorAll('[data-i18n]').forEach(el => {
    const key = el.getAttribute('data-i18n');
    if (translations[lang][key]) {
      el.textContent = translations[lang][key];
    }
  });
  
  // 重新渲染时间线和图表
  renderTimeline();
  renderCharts();
}
```

### HTML 标记

```html
<!-- 语言切换按钮 -->
<div class="lang-switcher">
  <button class="lang-btn active" onclick="switchLanguage('zh')" id="langZh">
    🇨🇳 中文
  </button>
  <button class="lang-btn" onclick="switchLanguage('en')" id="langEn">
    🇺🇸 English
  </button>
</div>

<!-- 使用 data-i18n 属性的元素 -->
<h1 data-i18n="title">🌍 人类历史发展进程</h1>
<input data-i18n-placeholder="searchPlaceholder" placeholder="🔍 搜索...">
```

---

## 📱 响应式设计

### 桌面端
- 语言按钮固定在左上角
- 与主题切换按钮对称布局
- 悬停动画效果

### 移动端
- 语言按钮自动缩小
- 调整位置避免遮挡内容
- 触摸友好的按钮尺寸

---

## 🎨 视觉设计

### 语言按钮样式
- 🇨🇳 🇺🇸 国旗 emoji 标识
- 圆角按钮设计
- 活动状态高亮显示
- 渐变背景（选中时）

### 状态指示
- **未选中：** 半透明背景，灰色边框
- **选中：** 金色渐变背景，黑色文字
- **悬停：** 边框高亮，轻微上移

---

## 💾 本地存储

### 存储键值
```javascript
// 语言偏好
localStorage.setItem('historyLang', 'zh'); // 或 'en'

// 主题偏好（独立存储）
localStorage.setItem('historyTheme', 'dark'); // 或 'light'

// 收藏数据（与语言无关）
localStorage.setItem('historyBookmarks', '[1,2,3]');
```

### 加载逻辑
```javascript
// 页面加载时
let currentLang = localStorage.getItem('historyLang') || 'zh';
switchLanguage(currentLang);
```

---

## 🔍 搜索功能

### 多语言搜索
- 搜索框自动使用当前语言
- 搜索内容匹配当前语言的事件
- 中英文搜索独立进行

### 示例
**中文模式：**
- 搜索 "工业革命" → 匹配相关事件
- 搜索 "孔子" → 匹配相关事件

**英文模式：**
- Search "Industrial Revolution" → Match related events
- Search "Confucius" → Match related events

---

## 📊 图表本地化

### 柱状图（时代分布）
- **中文：** 🪨 史前 | 🏛️ 古代 | 🏰 中世纪 | ⛵ 近代 | 🚀 现代
- **English：** 🪨 Prehistoric | 🏛️ Ancient | 🏰 Medieval | ⛵ Early Modern | 🚀 Modern

### 饼图（分类统计）
- **中文：** 文化 | 科技 | 政治 | 科学 | 经济 | 军事
- **English：** Culture | Technology | Politics | Science | Economy | Military

---

## 🌍 地图标注

### Popup 内容
地图标记的弹窗也支持多语言：

**中文模式：**
```
人类起源
时间：约 300 万年前
地点：非洲东部
最早的人类祖先出现在非洲东部
```

**English Mode：**
```
Origin of Humans
Time: c. 3 million years ago
Location: East Africa
Earliest human ancestors appeared in East Africa
```

---

## 🎯 使用场景

### 场景 1：中文用户
1. 访问网站（默认中文）
2. 浏览中文历史事件
3. 使用中文搜索和过滤
4. 收藏感兴趣的事件
5. 查看中文统计图表

### 场景 2：英文用户
1. 访问网站
2. 点击右上角 🇺🇸 English
3. 全站切换为英文
4. 浏览英文历史事件
5. 使用英文搜索和过滤

### 场景 3：语言学习
1. 先使用中文浏览
2. 切换到英文查看相同内容
3. 对比学习历史术语
4. 提升双语阅读理解

### 场景 4：国际分享
1. 中文用户创建内容
2. 切换到英文验证翻译
3. 分享链接给国际友人
4. 自动适配对方语言偏好

---

## 📈 性能优化

### 加载性能
- 翻译数据内嵌在 JavaScript 中
- 无需额外 API 请求
- 切换延迟 < 100ms

### 内存优化
- 翻译对象共享引用
- 事件数据按需渲染
- LocalStorage 轻量存储

---

## 🔮 未来扩展

### 计划支持的语言
- 🇯🇵 日本語（Japanese）
- 🇰🇷 한국어（Korean）
- 🇫🇷 Français（French）
- 🇩🇪 Deutsch（German）
- 🇪🇸 Español（Spanish）
- 🇵🇹 Português（Portuguese）
- 🇷🇺 Русский（Russian）
- 🇸🇦 العربية（Arabic）

### 扩展功能
- 🌐 自动语言检测（基于浏览器）
- 📖 术语表（专业词汇对照）
- 🔊 语音朗读（TTS 多语言）
- 📝 用户贡献翻译（社区化）

---

## 📝 Git 提交记录

```
commit bfb948f - feat: 添加中英文多语言支持（i18n）
  - 完整双语切换功能
  - 35 个事件的中英文数据
  - 界面元素完整翻译
  - 本地存储语言偏好
  - 图表和地图本地化
```

---

## 🌐 访问链接

**网站地址：** https://magicengine-ai.github.io/human-history/

**切换语言：** 点击左上角 🇨🇳 中文 / 🇺🇸 English 按钮

---

## 📚 相关文档

- [功能说明](FEATURES.md) - 完整功能列表
- [v3.0 更新日志](CHANGELOG-v3.md) - 之前的更新内容
- [README](README.md) - 项目说明

---

**维护者：** Jason Huang  
**GitHub：** https://github.com/magicengine-ai/human-history  
**反馈：** 欢迎提交 Issue 和 PR
