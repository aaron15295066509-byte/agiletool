# Agiletool - 随身工具包

一个轻量级网页工具，包含：
1. **汇率转换** — 默认人民币↔美元，可切换其他主要货币
2. **尺寸转换** — 默认厘米↔英寸，可切换其他长度单位

## 目录结构

```
agiletool/
├── index.html     # 主页面（单文件，所有CSS/JS内嵌）
└── README.md      # 本文件
```

## 技术方案

- 纯前端单页应用（HTML + CSS + JavaScript）
- 汇率用免费API：`https://open.er-api.com/v6/latest/USD`
- 尺寸换算用固定换算表（不需要联网）
- 无外部依赖，打开即用
- 响应式设计，手机/电脑都可看
