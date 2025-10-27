# LIVIA 分析平台 移动版
轻量级 DeFi 分析工具，单文件部署，手机友好。支持 BSC、ETH、Solana。
## 功能
- 多链：BSC、ETH、Solana。
- 持币分析：前 100 地址、持仓、占比、鲸鱼（>1%）、风险评分。
- 价格趋势：20 条记录图表，可导出 PNG。
- 交易详情：最近 10 笔大额交易（>5% 总供应量）。
- 貔貅盘检测：持仓集中/流动性低/异常交易预警。
- PWA：离线访问，添加到主屏幕。
## 快速开始
1. 上传 `index.html` 到根目录。
2. 设置 GitHub Pages（`main`, `/ (root)`）。
3. 访问 `https://lmy858194-hub.github.io/LV`.
4. 测试：链 BSC，合约 `0x55d398326f99059fF775485246999027B3197955`（USDT），API 密钥（BscScan/Etherscan/Solscan）。
## 注意
- 不要硬编码 API 密钥，测试后清缓存。
- 404：检查 `index.html` 和 GitHub Pages 设置。
## 许可证
MIT License（见 `LICENSE`）。
