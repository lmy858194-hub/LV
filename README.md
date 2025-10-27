# LIVIA 分析平台 移动版

LIVIA 是一个轻量级 DeFi 分析工具，优化为单文件部署，适合手机使用。支持 BSC、ETH、Solana，包含持币分析、价格趋势、交易详情和**貔貅盘检测**。

## 功能
- **多链**：BSC、ETH、Solana。
- **持币分析**：前 100 地址、持仓、占比、鲸鱼（>1%）、风险评分。
- **价格趋势**：显示 20 条价格记录（图表），可导出 PNG。
- **交易详情**：最近 10 笔大额交易（>5% 总供应量）。
- **貔貅盘检测**：
  - 前 10 地址占比 >50% 预警。
  - 流动性锁定 <10% 警告（BSC/ETH）。
  - 大额交易异常检测。
- **PWA**：支持离线访问，添加到主屏幕。

## 快速开始
1. **部署**：
   - 上传 `index.html` 到 `lmy858194-hub/LV` 根目录。
   - 在 **Settings > Pages** 设置 GitHub Pages（`main`, `/ (root)`）。
   - 访问 `https://lmy858194-hub.github.io/LV`。
2. **API 密钥**：
   - BSC: [bscscan.com](https://bscscan.com/register)
   - ETH: [etherscan.io](https://etherscan.io/register)
   - Solana: [solscan.io](https://solscan.io/docs/api/register)
3. **测试**：
   - 链：BSC
   - 合约：`0x55d398326f99059fF775485246999027B3197955`（USDT）
   - 输入 API 密钥，点击“加载数据”。

## 注意
- 不要硬编码 API 密钥，测试后清除浏览器缓存。
- 404 错误：检查 `index.html` 在根目录，确认 GitHub Pages 设置。

## 许可证
MIT License（见 `LICENSE`）。
