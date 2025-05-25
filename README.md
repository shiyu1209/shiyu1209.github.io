# Shi Yu's Personal Website

🚀 基于Astro构建的多功能个人网站 

[![Astro](https://img.shields.io/badge/Astro-3.0-FF5D01?logo=astro)](https://astro.build)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue)](https://shiyu1209.github.io)

## 🛠️ 技术组成

### 核心架构
- **框架**: Astro 3.0（岛屿架构）
- **样式**: CSS Modules + 自定义变量
- **交互**: 原生JavaScript DOM操作
- **部署**: GitHub Pages

### 关键组件
| 组件 | 功能 |
|------|------|
| `Button.astro` | 可复用3D按钮组件 |
| `Background.astro` | 动态背景粒子系统 |
| `Layout.astro` | 全局页面布局容器 |
| `music.css` | 播放器专属样式模块 |

## 📂 项目结构
```bash
HTMLAPP/
├── public/            # 静态资源
├── src/               # 核心源码
    ├── components/    # 可复用组件
    │   ├── background.astro  # 动态背景组件
    │   ├── button.astro      # 3D按钮组件
    │   └── FishAnimation.astro # 鱼类动画组件
    │
    ├── layouts/       # 布局模板
    └── pages/         # 页面入口
        ├── index.astro      # 主页
        ├── music.astro     # 音乐播放器
        ├── profile.astro   # 个人资料页
        ├── notice.astro    # 通知公告页
        └── search.astro    # 搜索功能页
```

### ✨ 核心功能

### 页面特性
- **响应式布局**：适配移动端与PC端
- **玻璃质感UI**：`backdrop-filter: blur(10px)` 实现毛玻璃效果
- **实时时钟**：秒级更新的时间显示

### 音乐播放器
- 五首歌曲的播放列表
- 进度条拖拽控制
- 专辑封面动态加载
- 播放/暂停/切歌功能

### 个人资料页
- 双邮箱验证展示
- 社交平台直达链接
- 项目卡片悬停动画
- B站/GitHub/邮箱快速入口

## 🪐 未来计划

- [ ] 添加AI语音助手
- [ ] 实现WebAR画廊
- [ ] 添加Three.js 3D模型展示


## 📮 联系方式
​​邮箱​​：2521393424@qq.com 