[README.md](https://github.com/user-attachments/files/24307592/README.md)
# 神影视频 - Bootstrap实训项目

## 项目概述

神影视频是一个基于Bootstrap框架开发的现代化视频流媒体网站实训项目，提供电影、电视剧、综艺和动漫等多种视频内容的在线观看体验。项目采用深色主题设计，具有响应式布局，可在各种设备上流畅运行。

## 项目特点

### 🎨 视觉设计
- **深色主题**：采用现代化深色配色方案，提供舒适的观影体验
- **响应式布局**：完美适配桌面、平板和移动设备
- **流畅动画**：添加了平滑的过渡效果和悬停动画
- **自定义组件**：基于Bootstrap扩展的自定义UI组件

### 📺 核心功能
- **首页轮播**：展示热门电影和推荐内容
- **分类浏览**：电影、电视剧、综艺、动漫等分类导航
- **搜索功能**：支持关键词搜索视频内容
- **电影详情**：查看电影简介、评分、演员等信息
- **用户系统**：登录、注册功能（前端界面）
- **管理员后台**：内容管理功能（前端界面）

### 🔧 技术实现
- **Bootstrap 5**：响应式布局和UI组件
- **Font Awesome**：图标库
- **jQuery**：JavaScript库支持
- **CSS变量**：便于主题定制
- **Flexbox/Grid**：现代化布局方式

## 项目结构

```
Bootstrap实训项目/
├── dist/                 # 第三方资源文件
│   ├── css/             # Bootstrap CSS文件
│   ├── font-awesome-4.7.0/  # Font Awesome图标库
│   └── js/              # Bootstrap JavaScript文件
├── image/               # 图片资源
│   ├── 01.png - 13.jpg  # 电影海报和图片
│   └── 明星照片.jpg     # 演员照片
├── index.html           # 首页
├── login.html           # 登录页面
├── register.html        # 注册页面
├── movie-details.html   # 电影详情页
├── admin-index.html     # 管理员首页
├── admin-movies.html    # 电影管理页
├── link-test.html       # 链接测试页
├── test-function.html   # 功能测试页
└── the_wandering_earth_2.html # 流浪地球2详情页
```

## 技术栈

| 技术 | 版本 | 用途 |
|------|------|------|
| HTML5 | - | 页面结构 |
| CSS3 | - | 样式设计 |
| JavaScript | ES6+ | 交互逻辑 |
| Bootstrap | 5.x | 响应式框架 |
| jQuery | 3.6.0 | JavaScript库 |
| Font Awesome | 4.7.0 | 图标库 |

## 快速开始

### 1. 克隆或下载项目

将项目文件下载到本地目录。

### 2. 运行项目

由于是纯前端项目，直接使用浏览器打开即可：

1. 找到 `index.html` 文件
2. 右键点击选择「打开方式」
3. 选择您常用的浏览器（推荐 Chrome、Firefox、Safari）

### 3. 访问管理员页面

管理员页面位于 `admin-index.html`，可以直接在浏览器中打开访问。

## 主要页面功能

### 首页 (index.html)
- 顶部导航栏：分类导航和搜索功能
- 轮播图：展示热门电影
- 电影分类区：按类型展示电影列表
- 特色内容：重点推荐内容
- 页脚：网站信息和联系方式

### 登录页 (login.html)
- 用户登录表单
- 密码找回链接
- 注册入口

### 注册页 (register.html)
- 用户注册表单
- 验证输入字段
- 注册协议

### 电影详情页 (movie-details.html)
- 电影海报和信息
- 剧情简介
- 演员列表
- 评分和评论
- 播放按钮

### 管理员页面 (admin-*.html)
- 内容管理
- 用户管理
- 数据分析

## 自定义主题

项目使用CSS变量定义主题颜色，可以轻松定制：

```css
:root {
    --primary-color: #6366f1;
    --primary-dark: #4f46e5;
    --primary-light: #818cf8;
    --secondary-color: #8b5cf6;
    --bg-dark: #0f1117;
    --bg-medium: #16181d;
    --bg-light: #1e2029;
    --text-primary: #f8f9fa;
    --text-secondary: #a1a1aa;
    --border-color: #2d2d3a;
    --shadow-color: rgba(0, 0, 0, 0.5);
}
```

## 浏览器支持

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 开发说明

### 实训目标
- 掌握Bootstrap框架的使用
- 学习响应式网站开发
- 理解前端项目结构设计
- 实践HTML、CSS、JavaScript综合应用

### 扩展建议
- 添加后端API接口
- 实现用户认证系统
- 添加视频播放功能
- 实现评论和评分系统
- 添加收藏和历史记录功能

## 许可证

本项目仅供学习和实训使用，请勿用于商业用途。

## 致谢

- Bootstrap团队：提供优秀的前端框架
- Font Awesome：提供丰富的图标资源
- 所有开源项目的贡献者

---

**神影视频 - 高品质电影、电视剧在线观看平台**

*本项目为Bootstrap实训项目，旨在帮助开发者学习前端开发技术*
