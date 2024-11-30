# 易码（CodeEase） 中文编程库
# Dev:Spark(火花) 

[![GPL-3.0 License](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Latest Version](https://img.shields.io/github/v/release/Spark-Code-China/codeease)](https://github.com/Spark-Code-China/codeease/releases/latest)

易码（CodeEase）是一个中文函数库，旨在实现在Python平台中文编程。通过易码，开发者可以使用中文来完成编程任务，无需担心英文函数名带来的困扰。

## 目录

- [项目地址](#项目地址)
- [版本简读](#版本简读)
- [更新日志](#更新日志)
- [特点](#特点)
- [安装](#安装)
- [使用示例](#使用示例)
- [许可证](#许可证)

## 项目地址

- GitHub: [Spark-Code-China/CodeEase](https://github.com/Spark-Code-China/CodeEase.git)

## 版本简读

- **1.0.1.2**：修复 [1.0.1.2] `简体到繁体()` `繁体到简体()` 在Mac导致的报错。
- **1.0.1.1**：快速文本类 和 Json类添加了新功能 新增编码转换 简体繁体互换。 
- **1.0.0.2**：添加了json类和快速文本类。
- **1.0.0.1**：第一个版本发布。

# 更新日志
## [1.0.1.2] - 2024-8-15
## [1.0.1.1] - 2024-8-15

### 变更

* `写出到文件()` 之前内存内容 空列表编码，现在将文本参数通过'\n'.join(文本)连接成字符串写入文件。

### 修复
* 修复 [1.0.1.2] `简体到繁体()` `繁体到简体()` 在Mac导致的报错。
* 修复 `写出到文本()` 无法写出文件内容的问题。

### 新增

* 编码转换类-新增 简体繁体互换只支持Win系统。 
* 新增-编码转换类 添加 base64 base64API Rc4 - 加密解密。 
* 快速文本类 添加 读取文本每行。 
* Json类 添加 取成员 取成员文本。

### 优化

* 无。

### 已删除

* 快速文本类的旧函数 - 写出到文本() - 更改了写法 可以使用。

## 特点

- **中文编程**：提供同等函数的中文翻译，让中文开发者更加便捷地使用Python。
- **易于上手**：只需简单导入易码库，即可开始中文编程之旅。
- **兼容性强**：遵循Python编程规范，与现有Python代码无缝对接。

## 安装

使用pip安装易码：

```bash
pip install CodeEase

```

## 使用示例

from codeease import *
调试输出("你好，世界！")

## 许可证

本项目采用GPL-3.0许可证，详细内容请参考LICENSE文件。
