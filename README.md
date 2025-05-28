# UWB知识点文档

这是一个专门收集和整理UWB（Ultra-Wideband）技术相关知识点的文档站点。我们致力于为UWB开发者、研究人员和技术爱好者提供全面、准确、实用的技术文档和开发指南。

## 📖 文档内容

### 协议文档
- [控制协议规范](docs/protocol/control-protocol.md) - UWB读卡器控制协议详细说明

## 🛠️ 技术栈

- **[MkDocs](https://www.mkdocs.org/)** - 静态站点生成器
- **[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)** - 现代化的文档主题
- **[PyMdown Extensions](https://facelessuser.github.io/pymdown-extensions/)** - Markdown扩展
- **[GitHub Pages](https://pages.github.com/)** - 文档托管平台
- **[GitHub Actions](https://github.com/features/actions)** - 自动化部署

## 📁 项目结构

```
UwbKnowledgePoints/
├── docs/                          # 文档源文件
│   ├── index.md                   # 首页
│   ├── protocol/                  # 协议文档
│   │   └── control-protocol.md    # 控制协议规范
│   ├── guide/                     # 开发指南
│   │   ├── quick-start.md         # 快速开始
│   │   ├── overview.md            # 技术概述
│   │   └── faq.md                 # 常见问题
│   ├── images/                    # 图片资源
│   └── about.md                   # 关于页面
├── .github/                       # GitHub配置
│   └── workflows/                 # GitHub Actions
│       └── deploy.yml             # 部署工作流
├── mkdocs.yml                     # MkDocs配置文件
├── convert_doc.py                 # 文档转换脚本
├── Control_protocol(20250421).docx # 原始协议文档
└── README.md                      # 项目说明
```

### 文档许可
本项目的文档内容采用 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) 许可协议。


## 🙏 致谢