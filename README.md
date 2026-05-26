# 财务管家

个人财务管理网站，包含三个独立模块：记账日记、本月账单、财务总览。

## 目录结构

```
/
├── index.html          # 首页入口
├── diary/
│   └── index.html      # 记账日记（独立）
├── monthly/
│   └── index.html      # 本月账单（独立，联动记账数据）
├── finance/
│   └── index.html      # 财务总览（独立）
└── README.md
```

## 数据说明

- 记账日记数据 key：`bav7`
- 本月账单数据 key：`monthly_v1`
- 财务总览数据 key：`finance_v1`
- 三个模块数据独立存储，互不影响
- 本月账单读取记账日记的支出数据做浮动预算联动

## GitHub Pages 部署

见下方部署步骤。
