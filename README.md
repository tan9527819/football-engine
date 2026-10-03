# Jarvis Football AI V3

真实数据驱动的 GitHub Pages 前端。

## 已接入
- 用户历史 CSV：威廉数据库_逐场泊松校准明细
- 65,525 条历史记录
- 市场概率归一化
- 初盘/终盘赔率变化
- 相似盘型索引
- 历史实际胜平负
- 校准概率
- 风险闸门：平局/冷门/置信度
- 证据链与最近匹配样本

## 使用
保持 `index.html` 和 `history_index.json` 在同一目录，然后通过 GitHub Pages 发布。

## 下一步
API-Football 和实时盘口应由 GitHub Actions/后端安全调用，不能把 API 密钥写进浏览器前端。
