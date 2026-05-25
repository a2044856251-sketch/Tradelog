# TradeLog

加密货币交易日志工具。单文件、纯前端，打开 `index.html` 即用。

## 功能

- **离线可用** — 数据通过 IndexedDB（Dexie.js）存储在本地浏览器，不联网、不上传
- **统计面板** — 胜率、盈亏、R 倍数、期望值等
- **图表** — 净值曲线、盈亏分布、日历热力图（Chart.js）
- **截图附件** — 支持为每笔交易附加图表截图，自动压缩
- **备份/恢复** — JSON 格式导出导入全部记录
- **自定义品种和形态** — 可编辑的下拉选项，持久化在 localStorage
- **暗色 UI** — 毛玻璃 + Morandi 配色

## 技术栈

| 层 | 选型 |
|---|------|
| 数据库 | [Dexie.js](https://dexie.org/)（IndexedDB 封装） |
| 图表 | [Chart.js](https://www.chartjs.org/) |
| UI | 原生 HTML/CSS/JS，除两个 CDN 脚本外零依赖 |
| 部署 | GitHub Pages（单文件 `index.html`） |

## 为什么做这个

自己做交易，需要一款离线、快速、无框架依赖的日志工具。同时作为 Crypto × AI 方向的实践项目，展示交易 + 技术交叉领域的产品能力。

## 使用

```
git clone https://github.com/a2044856251-sketch/Tradelog.git
cd Tradelog
open index.html
```

或部署到 GitHub Pages：Settings → Pages → Source: `main`，根目录。

## 作者

**浅海** — 加密货币交易者，AI 工具实践者。

- 关注 Crypto × AI Agent 方向
- 正在寻找 Crypto × AI 领域的产品或运营岗位
