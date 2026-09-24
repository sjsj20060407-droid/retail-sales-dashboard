# Online Retail Sales Dashboard

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-purple)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 项目简介
基于 Online Retail II 真实电商数据集（80万+条交易记录），使用 Python Plotly
构建包含 8 个模块的交互式销售数据看板，可直接在浏览器中打开交互展示。

## 数据集
- 来源：[Online Retail II - Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
- 清洗后记录：805,549 条
- 时间跨度：2009-12-01 至 2011-12-09

## 看板模块
| 模块 | 内容 |
|------|------|
| KPI 卡片 | 总销售额 · 订单数 · 客户数 · 国家数 |
| 月度趋势 | 销售额折线图 + 订单量柱状图（双轴） |
| 国家排行 | Top 10 国家销售额横向柱状图 |
| 商品排行 | Top 10 热销商品收入排行 |
| 时段分析 | 每小时订单分布 + 星期销售分布 |
| 年度对比 | 年度销售额 + 客单价对比 |
| 客户分析 | 消费金额箱线图 + 分布直方图 |
| 新老客趋势 | 月度新客 vs 复购客堆叠柱状图 |
| 气泡图 | 商品单价 vs 销量（气泡大小=收入） |

## 核心数据
- 总销售额：£17,743,429
- 总订单数：53,628
- 独立客户：5,878
- 覆盖国家：41

## 技术栈
- Python · pandas · Plotly · matplotlib
- 输出格式：交互式 HTML（浏览器直接打开）

## 使用方式
直接下载 `sales_dashboard.html`，用浏览器打开即可查看完整交互看板。

## 项目结构

## 2026-09 更新

- 本看板的 8 模块结构（KPI/趋势/排行/时段/新老客）已复用为「Theory 周报 PPT 自动工作台」的页面规划蓝本
- 后续方向：Plotly 图表规则与 PPT 自动生成管线（PptxGenJS）打通，实现看板 → 周报 PPT 的数据直通
