<div align="center">

# Code2LlmPrompt [中文](#cn)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![.NET](https://img.shields.io/badge/.NET-8.0-purple)
![Platform](https://img.shields.io/badge/platform-Windows-0078d7)
![Architecture](https://img.shields.io/badge/architecture-MVVM-green)
[Issues & Todo](./Issues&Todo.md)

### A GUI Wrapper for [code2prompt](https://github.com/mufeedvh/code2prompt)  
### Transform Code into LLM-Friendly Prompts – Now with Visual Interface

![Preview](Code2LlmPrompt/Assets/Code2LlmPrompt_Preview.png)

</div>

## 🎯 What It Does

This is a **graphical user interface (GUI) wrapper** around the excellent [code2prompt](https://github.com/mufeedvh/code2prompt) CLI tool by [mufeedvh](https://github.com/mufeedvh).  
It converts source code into AI-ready prompts while preserving:

- Code structure and relationships
- Comments and documentation  
- Directory hierarchy

## ✨ Key Features

- **📁 Multiple Formats**: Markdown, JSON, or XML output (powered by code2prompt)
- **🔧 Smart Filtering**: Include/exclude files and directories
- **📊 Token Counting**: Real-time token estimation with various encodings
- **🌳 Structure Preservation**: Maintains file and folder relationships
- **⚡ One-Click Processing**: Generate prompts instantly without command line
- **💾 Flexible Export**: Copy, save, or preview results

## 🚀 Get Started in 4 Steps

1. **Select Folder** - Choose your project directory
2. **Configure** - Set file filters and output format (uses code2prompt engine)
3. **Generate** - Click to create LLM-optimized prompt
4. **Use** - Copy to your preferred AI model

## 🛠 Requirements

- **OS**: Windows 10/11 (other platforms supported but not packaged)
- **Runtime**: .NET 8 (included in standalone build)
- **Backend**: [code2prompt](https://github.com/mufeedvh/code2prompt) (bundled or required separately – see install notes)

## ⚙️ Configuration

- **File Patterns**: Smart inclusion/exclusion rules
- **Output Templates**: Customizable formatting (same as code2prompt)
- **Token Optimization**: Choose encoding (cl100k, p50k, r50k)
- **Git Context**: Optional version control information

## 📄 License

MIT License - see [LICENSE.txt](LICENSE.txt) for details.

<a id="cn"/>
---
<div align="center">

# Code2LlmPrompt

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![.NET](https://img.shields.io/badge/.NET-8.0-purple)
![Platform](https://img.shields.io/badge/platform-Windows-0078d7)
![Architecture](https://img.shields.io/badge/architecture-MVVM-green)

### 一款为 [code2prompt](https://github.com/mufeedvh/code2prompt) 打造的图形界面包装程序  
### 将代码转换为 LLM 友好的提示词 – 可视化操作，无需命令行

![Preview](Code2LlmPrompt/Assets/Code2LlmPrompt_Preview.png)

</div>

## 🎯 功能简介

本程序是 [code2prompt](https://github.com/mufeedvh/code2prompt) 命令行程式的 **GUI 外壳**，将源代码转换为AI就绪的提示词，同时保留：

- 代码结构和关系
- 注释和文档
- 目录层级

## ✨ 核心特性

- **📁 多格式支持**: Markdown、JSON 或 XML 输出（基于 code2prompt 引擎）
- **🔧 智能筛选**: 包含/排除文件和目录
- **📊 令牌统计**: 实时估算令牌数，支持多种编码
- **🌳 结构保持**: 维护文件和文件夹关系
- **⚡ 一键处理**: 无需命令，即时生成提示词
- **💾 灵活导出**: 复制、保存或预览结果

## 🚀 快速开始

1. **选择文件夹** - 选择项目目录
2. **配置设置** - 设置文件过滤器和输出格式（底层调用 code2prompt）
3. **生成提示词** - 点击创建LLM优化的提示词
4. **使用** - 复制到您偏好的AI模型

## 🛠 系统要求

- **操作系统**: Windows 10/11 (支持其他平台，但未打包)
- **运行时**: .NET 8 (独立版本已包含)
- **后端依赖**: [code2prompt](https://github.com/mufeedvh/code2prompt) （请查看安装说明）

## ⚙️ 配置选项

- **文件模式**: 智能包含/排除规则
- **输出模板**: 可自定义格式（与 code2prompt 一致）
- **令牌优化**: 选择编码方式 (cl100k, p50k, r50k)
- **Git上下文**: 可选的版本控制信息

## 📄 许可证

MIT 许可证 - 详见 [LICENSE.txt](LICENSE.txt)
