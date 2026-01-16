# Human Judgment System (HJS) Protocol

<p align="center">
  <strong>防止自动化系统中的责任蒸发</strong>
</p>

<p align="center">
  <strong>中文</strong> | <a href="README.md">English</a>
</p>

<p align="center">
  <a href="https://github.com/schchit/Human-Judgment-System">
    <img src="https://img.shields.io/badge/Status-Public%20Proposal-blue" alt="Status">
  </a>
  <a href="https://creativecommons.org/licenses/by-sa/4.0/">
    <img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey" alt="License">
  </a>
  <a href="https://github.com/schchit/Human-Judgment-System/issues">
    <img src="https://img.shields.io/badge/Issues-Welcome-brightgreen" alt="Issues">
  </a>
  <a href="https://github.com/schchit/Human-Judgment-System/stargazers">
    <img src="https://img.shields.io/github/stars/schchit/Human-Judgment-System?style=social" alt="GitHub stars">
  </a>
</p>

---

## 📖 项目简介

**Human Judgment System (HJS)** 是一个旨在解决自动化系统中"责任蒸发"问题的协议框架。当AI系统做出不可逆决策时，如何确保真正的人类判断已经发生？HJS通过引入**判断层（Judgment Layer）**，为自动化系统提供结构化的安全保障。

## 🎯 核心问题

**决策正在被自动化，但不可逆的后果仍由人类承担。**

现代AI系统擅长计算，但缺乏结构化的安全机制来验证在不可逆决策之前是否真正发生了人类判断。

## 🔧 解决方案

HJS引入了一个新的基础设施层——**判断层（Judgment Layer）**，它能够：

- ✅ **识别**不可逆决策节点
- ⏸️ **强制**自动化暂停  
- ✍️ **要求**明确的人类责任接受
- 📝 **记录**判断以供验证

## 🚀 快速开始

### 📚 对于读者

- 📄 **[English Whitepaper (PDF)](docs/whitepaper/en/White%20Paper%20on%20Human%20Judgment%20System%20v1.0%20(English%20Version).pdf)** - 完整的概念框架
- 📖 **[中文白皮书 (PDF)](docs/whitepaper/zh-CN/人类判断系统白皮书%20v1.0（中文版）.pdf)** - 中文版本白皮书
- 🎯 **[核心原则](#-核心原则)** - HJS是什么，不是什么

### 👨‍💻 对于开发者

```bash
# 克隆仓库
git clone https://github.com/schchit/Human-Judgment-System.git

# 进入项目目录
cd Human-Judgment-System

# 查看文档
cd docs
```

## 📋 目录结构

```
Human-Judgment-System/
├── README.md                 # 项目主文档（英文版）
├── README.zh-CN.md           # 中文版项目文档
├── CONTRIBUTING.md           # Contributing guide (English)
├── CONTRIBUTING.zh-CN.md     # 贡献指南（中文版）
├── docs/                     # 文档目录
│   ├── README.md            # 文档索引
│   └── whitepaper/          # 白皮书
│       ├── en/              # 英文版
│       └── zh-CN/           # 中文版
├── assets/                   # 资源文件
│   └── images/              # 图片资源
└── .github/                  # GitHub配置
    └── ISSUE_TEMPLATE/      # Issue模板
```

## 🎯 核心原则

### HJS 是什么

- 🔒 **基础设施层**：在应用层和决策层之间插入判断层
- 📊 **协议框架**：定义标准化的判断流程和验证机制
- 🛡️ **安全保障**：确保不可逆决策前必须有明确的人类判断
- 📝 **可追溯性**：记录所有判断过程，支持审计和验证

### HJS 不是什么

- ❌ **不是AI替代品**：不替代AI的决策能力
- ❌ **不是监管工具**：不是用于监管或控制的工具
- ❌ **不是单一实现**：是一个协议，可以有多种实现方式

## 🔍 核心概念

### 1. 判断层 (Judgment Layer)
在自动化系统中插入的中间层，负责识别需要人类判断的关键节点。

### 2. 不可逆决策 (Irreversible Decisions)
一旦执行就无法撤销或修复的决策，如删除数据、终止服务等。

### 3. 责任接受 (Responsibility Acceptance)
人类明确承认并接受对某个决策的责任。

### 4. 判断记录 (Judgment Record)
记录判断过程的数据结构，包括时间戳、决策者、决策内容等。

## 💡 应用场景

- 🤖 **AI自动化系统**：确保AI决策前有人类审核
- 🏥 **医疗诊断系统**：关键诊断前需要医生确认
- 💰 **金融交易系统**：大额交易前需要人工审批
- ⚖️ **法律决策系统**：重要判决前需要法官审查
- 🚗 **自动驾驶系统**：关键操作前需要人类确认

## 🤝 贡献指南

我们欢迎所有形式的贡献！请查看 [CONTRIBUTING.zh-CN.md](CONTRIBUTING.zh-CN.md) 了解详细信息。

## 📄 许可证

本项目采用 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 许可证。

## 📞 联系方式

- 💬 [GitHub Issues](https://github.com/schchit/Human-Judgment-System/issues) - 讨论、问答和问题追踪

## 🌟 致谢

感谢所有为这个项目做出贡献的思考者和开发者。

---

<p align="center">
  <strong>让自动化系统更负责任，让人类判断更有价值</strong>
</p>
