# SQL智能可视化分析助手
基于 Dify 实现「自然语言转 SQL + ECharts 数据分析可视化」的实战项目，适配 SQL Server 环境，聚焦评论情感/关键词分析场景，提供可直接复用的 SQL 脚本、Dify 配置、ECharts 可视化代码。

[![SQL Server Compatibility](https://img.shields.io/badge/SQL%20Server-2017%2B-brightgreen)](https://learn.microsoft.com/zh-cn/sql/sql-server/)
[![Dify Version](https://img.shields.io/badge/Dify-0.6.10%2B-blue)](https://dify.ai/)
[![ECharts Version](https://img.shields.io/badge/ECharts-5.4.0%2B-orange)](https://echarts.apache.org/)


## ✨ 核心功能

| 功能模块 | 说明 | 技术亮点 |
|---------|------|---------|
| 📝 自然语言转 SQL | 用户用中文描述需求，AI 生成标准 SQL | 多轮澄清机制，处理模糊需求 |
| 🔍 SQL 智能纠错 | 自动检测语法错误，给出修复建议 | 对接数据库元数据，精准定位 |
| 📊 ECharts 可视化 | 根据查询结果自动生成图表配置 | 智能图表类型推荐（柱状/折线/饼图等） |
| 💡 数据洞察 | 自动分析数据趋势，生成文字解读 | 结合业务场景的智能摘要 |

## 📋 目录结构

