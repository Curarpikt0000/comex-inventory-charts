# COMEX & SHFE/SGE 贵金属库存每日图表

每日自动更新的贵金属库存图（Gold / Silver / Platinum）。

- **COMEX 库存**：Notion CME 库存库日频（oz → 吨换算）
- **SHFE/SGE 库存**：每周库存 DB + CME Activity Note `[SHFE]` 日频注解（2026-06-05 起）
- **Pt**：无上海库存数据，仅 COMEX

数据源由 `Comex-Daily-AI-Report` 项目每日采集，本 repo 由 cron 每日更新 `index.html`。

访问：https://curarpikt0000.github.io/comex-inventory-charts/
