# 敦煌历代时空 GIS 演变系统

一个交互式地理信息系统(GIS)项目，通过可视化展示敦煌在不同历史时期的城市、军事、文化及基础设施的演变过程。

## 📍 项目概览

本项目使用 Leaflet.js 和 Esri World Topo Map 等开源技术，将敦煌从**汉代**到**当代**五个时期的历史地理数据进行交互式展示。

## 🎯 核心功能

### 时间轴导航
- **汉代** (Han Dynasty)：气候湿润，绿洲极盛
- **唐代** (Tang Dynasty)：文化繁荣，丝路高峰
- **明清** (Ming-Qing)：衰退与复兴
- **1970s** (Modern 1)：工业化初期
- **当代** (Contemporary)：文旅融合

### 节点类型分类
| 类型 | 颜色 | 示例 |
|------|------|------|
| 郡县治所 / 核心城市 | 🔴 红色 | 敦煌郡城、沙州城 |
| 军事关隘 / 烽燧驿站 | 🟠 橙色 | 玉门关、阳关 |
| 宗教石窟 / 文化遗址 | 🟣 紫色 | 莫高窟、榆林窟 |
| 水利工程 / 基础设施 | 🔵 蓝色 | 党河水库、敦煌机场 |
| 农业乡镇 / 屯田区 | 🟢 绿色 | 效谷县、南湖公社 |

### 环境层
- **河流系统**：疏勒河和党河的历史流量变迁
- **绿洲范围**：各时期绿洲面积的演变

## 🛠️ 技术栈

- **前端框架**：Tailwind CSS 3
- **地图库**：Leaflet.js 1.9.4
- **底图服务**：Esri World Topo Map
- **CDN**：jsDelivr（国内加速）
- **语言**：HTML5 + JavaScript (Vanilla)

## 🚀 快速开始

### 本地运行

1. **克隆仓库**
   ```bash
   git clone https://github.com/unveileap-source/Dunhuang.git
   cd Dunhuang
   ```

2. **启动本地服务器**
   ```bash
   # 使用 Python 3
   python -m http.server 8000
   
   # 或使用 Node.js http-server
   npx http-server
   ```

3. **在浏览器打开**
   ```
   http://localhost:8000
   ```

### GitHub Pages 部署

该项目已配置为可直接通过 GitHub Pages 访问：
- 访问地址：`https://unveileap-source.github.io/Dunhuang`

## 📊 数据说明

项目包含 28 个历史地理节点，涵盖：
- 行政中心（6 个）
- 军事设施（4 个）
- 文化遗址（6 个）
- 基础设施（4 个）
- 农业区域（8 个）

每个节点包含：
- 地理坐标（经纬度）
- 历史时期标签
- 详细描述
- 补充信息（建置时间、人口、特产等）

## 🗺️ 历史地理背景

敦煌作为古代丝绸之路的重镇，其历史演变体现了：
- **气候变化**：从汉代的湿润到当代的干旱
- **水系变迁**：疏勒河与党河的退缩与调控
- **政治兴衰**：从汉唐繁荣到明清衰退再到当代复兴
- **生态挑战**：从绿洲扩张到生态危机再到生态恢复

## 💡 使用建议

- **手机用户**：竖屏时侧栏在地图上方，横屏时在左侧
- **PC 用户**：建议分辨率 ≥ 1024×768
- **国内用户**：所有资源已通过 CDN 国内加速，加载速度优化

## 📖 参考资源

- [Leaflet.js 官方文档](https://leafletjs.com/)
- [Tailwind CSS 官方文档](https://tailwindcss.com/)
- [敦煌研究院官网](https://www.dha.ac.cn/)
- [丝绸之路文献资料库](http://silkroad.mes.ac.cn/)

## 📄 许可证

暂未指定。项目中使用的第三方库（Leaflet, Tailwind CSS, Esri）遵循各自的开源许可协议。

## 👤 作者

- **项目创建人**：unveileap-source

## 📧 联系方式

如有问题或建议，欢迎通过以下方式联系：
- GitHub Issues：[提交问题](https://github.com/unveileap-source/Dunhuang/issues)
- GitHub Discussions：[讨论区](https://github.com/unveileap-source/Dunhuang/discussions)

---

**最后更新**：2026-05-01  
**项目状态**：活跃维护中 ✨