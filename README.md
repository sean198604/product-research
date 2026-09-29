<p align="center"><img src="assets/readme-cover.png" alt="Product Research project cover" width="100%" /></p>

# 产品市场调研工具 (Product Research)

外贸产品市场调研辅助工具，帮助分析产品在目标市场的竞争格局和机会。

## 技术栈

- **前端**: 原生 HTML/CSS/JS（紫色主题）
- **部署**: Docker + Nginx
- **端口**: 7005

## 功能

- 📊 **产品调研信息收集** — 结构化表单采集产品调研数据
- 🎯 **目标市场分析** — 产品规格、竞品对比、价格区间
- 📝 **调研报告模板** — 引导式填写，确保调研维度完整
- 🎨 **独立主题色** — 紫罗兰渐变风格

## 目录结构

```
├── product-research.html        # 主页面
├── product-research/
│   ├── Dockerfile
│   ├── docker-compose.yml
│   ├── nginx.conf
│   └── html/
│       └── index.html           # Nginx 托管版本
└── README.md
```

## 快速启动

```bash
cd product-research
docker-compose up -d
```

访问 `http://192.168.1.246:7005`
