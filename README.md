# 云端天宫 CloudTower 3D

🎮 **在线体验**: [https://0065paula.github.io/cloudtower-3d/](https://0065paula.github.io/cloudtower-3d/)

中国传统天宫风格 + 现代云运维平台的 3D 可视化场景

![CloudTower Preview](https://raw.githubusercontent.com/user-attachments/assets/cloudtower.jpg)

## ✨ 功能特点

### 6 大功能区域
- 🏛️ **ZONE 1** - 角色权限管理 (RBAC) - 牌坊入口
- 🔮 **ZONE 2** - 可观测性平台 - 旋转水晶球浑天仪
- 🔍 **ZONE 3** - 全局搜索 - 脉冲光束发射塔
- 📋 **ZONE 4** - 任务中心 - S形流光传送带
- 📜 **ZONE 5** - 事件审计 - 历史画卷长廊
- 🚀 **ZONE 6** - 升级中心 - 法器发射台

### 视觉效果
- 🎨 配色: 青绿山水 + 金色琉璃 + 天蓝云白
- 💎 材质: 半透明玉石、金属鎏金、发光能量体
- ✨ 后期处理: Bloom 辉光效果
- 🌫️ 氛围: 体积雾、漂浮云层、仙气粒子

### 交互功能
- 🖱️ 鼠标拖拽旋转视角 (OrbitControls)
- 🔍 滚轮缩放
- 👆 点击建筑查看详情

## 🚀 在线预览

**直接访问**: https://0065paula.github.io/cloudtower-3d/

或在本地运行:
```bash
# 克隆仓库
git clone https://github.com/0065paula/cloudtower-3d.git
cd cloudtower-3d

# 用浏览器打开
open index.html

# 或启动本地服务器
python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

## 🛠️ 技术栈

- **Three.js** - 3D 渲染引擎
- **WebGL** - 硬件加速图形
- **ES Modules** - 现代 JavaScript 模块
- **Bloom Post-processing** - 辉光后期效果

## 📁 项目结构

```
cloudtower-3d/
├── index.html          # 主文件 (包含所有代码)
├── README.md           # 项目说明
└── vercel.json         # Vercel 部署配置
```

## 🎯 使用指南

1. **旋转视角**: 按住鼠标左键拖拽
2. **缩放**: 鼠标滚轮
3. **平移**: 按住鼠标右键拖拽
4. **自动旋转**: 场景会缓慢自动旋转展示

## 🔗 相关链接

- **GitHub 仓库**: https://github.com/0065paula/cloudtower-3d
- **设计灵感来源**: 阿里云云原生运维平台概念图

## 📄 License

MIT License
