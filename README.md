# 🚪 [项目名称] WebGIS-DoorOrder

> [基于 Leaflet + Turf.js + ECharts 的全国木门订单分布与空间调度可视化平台]

## ✨ 核心功能 (Features)
- 📍 **海量数据聚合**：使用 MarkerCluster 解决密集订单点展示卡顿问题。
- 🔄 **双向图表联动**：地图点击定位图表高亮，图表点击地图视角飞入（基于 EventBus 解耦）。
- 📐 **前端空间分析**：支持多边形/矩形绘制，结合 Turf.js 实时计算球面面积并筛选区域内订单。
- 🎨 **状态可视化**：根据订单状态（待安装、已完成等）动态渲染不同颜色的 Marker。

## 🛠️ 技术栈 (Tech Stack)
- **地图引擎**: Leaflet 1.9.4
- **空间分析**: Turf.js 6.x
- **数据可视化**: ECharts 5.x
- **标绘插件**: Leaflet.draw 1.0.4

## 🚀 快速开始 (Quick Start)
由于涉及本地 `china.json` 文件请求，请勿直接双击 `index.html` 运行。
1. 克隆本项目到本地。
2. 使用 VSCode 并安装 `Live Server` 插件。
3. 右键 `index.html` -> `Open with Live Server` 即可预览。

## 📸 效果展示 (Screenshots)
<img width="1366" height="641" alt="image" src="https://github.com/user-attachments/assets/d96fbe65-98c0-40e9-9793-78b9c0a836b1" />
<img width="1366" height="641" alt="image" src="https://github.com/user-attachments/assets/20b5c215-1031-4226-8bf8-1e1c3acd5ea6" />
<img width="1366" height="641" alt="image" src="https://github.com/user-attachments/assets/2b5fdd2a-8f1f-4afb-9ce5-380b418474bb" />


## 👨‍💻 作者 (Author)
- [MROU]
