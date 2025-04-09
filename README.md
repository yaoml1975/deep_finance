<h1 align="center">Deep Finance Analysis</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Content-Markdown-0078d7" alt="Format">
  <img src="https://img.shields.io/badge/DeepSeek-LLM-orange" alt="AI">
  <img src="https://img.shields.io/badge/Update-2025--04--08-brightgreen" alt="Update">
</p>
---

## 📚 项目介绍
本仓库是基于DeepSeek大语言模型生成的金融知识库，聚焦以下：
- **AI市场分析**：通过自然语言提问获取实时股债商品趋势解读（案例见[市场洞察](./docs/market_insights)）
- **价值投资策略**：巴菲特护城河理论、格雷厄姆安全边际等经典模型的操作指南
- **财务精读手册**：20+核心指标公式解析与300家上市公司财报案例
- **智能投研笔记**：经人工校验的AI生成投研方法论（DCF/波特五力/SWOT）

> ⚠️ **注意**：所有内容均为信息参考，**严禁作为投资依据**，完整声明见[免责条款](#⚖️-免责声明)

---

## 🗂️ 文档体系
### 核心模块
| 目录                 | 内容说明                            | 数据源                 |
|----------------------|-----------------------------------|-----------------------|
| `/investment`        | 价值/技术/量化投资方法论           | 伯克希尔年报/学术论文 |
| `/financial_metrics` | 财务指标公式库与舞弊识别技巧       | SEC/沪深交易所数据    |
| `/cases`             | 可口可乐/苹果等经典投资案例分析     | 10-K报告/券商研报     |
| `/tools`             | Wind/Choice使用指南与数据模板      | 官方文档/实战经验     |

### 特色内容
- **AI增强学习**：通过`DeepSeek-V3`模型生成的可交互问答

---

## ⚖️ 免责声明
根据《证券法》与《个人信息保护法》要求：
1. **非实时性声明**  
   市场分析基于历史数据生成，存在**最长5个工作日的滞后性**，请以交易所公告为准

2. **非专业指导**  
   所有AI生成内容未经CFA持证人审核，不得替代专业投顾服务

3. **数据脱敏规范**  
   涉及的上市公司数据已通过标准脱敏处理，去除敏感商业信息

4. **第三方责任**  
   引用数据的准确性由Yahoo Finance/东方财富等原始提供方负责

*完整法律文本见* [法律协议](./legal/LEGAL.md)

---

## 🛠️ 使用指南
### 知识检索
1. **本地搜索**  
   使用VSCode的`Todo Tree`插件进行跨文件关键词检索
2. **AI交互**  
   复制问题至[DeepChat](https://github.com/ThinkInAIXYZ/deepchat)客户端获取扩展解读

### 贡献须知
- 财务公式修正请附Wind/Bloomberg数据截图
- 案例分析需注明出处（年报页码/研报日期）
- 严禁上传未脱敏的上市公司内部数据

---

## 📌 参考文献
1. 伯克希尔·哈撒韦公司年度报告（1995-2024）
2. SEC上市公司披露规则《Regulation S-K》
3. DeepSeek大模型金融语义理解白皮书（2025）

---

License: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
