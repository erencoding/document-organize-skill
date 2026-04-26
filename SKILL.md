---
name: document-organize
description: Create a document folder structure with project and practice subdirectories. Use when user asks to organize documents, create folder structure for projects, or set up work/practice directories.
version: "1.0"
author: Judy (朱迪)
license: MIT
---

# Document Organization Skill

Create a document folder structure with `project` and `practice` subdirectories.

## Usage Keywords

```
创建 document 文件夹
整理项目
建立练习目录
帮我整理文档
创建文件夹结构
```

## Workflow

### Step 1: Create Folder Structure

```bash
mkdir -p ~/document/project ~/document/practice
```

### Step 2: Reply

告诉用户创建完成：

```
✅ 文件夹已创建！

~/document/
├── project/   — 正式项目
└── practice/  — 练习代码

可以开始使用啦 🐰
```

## Folder Guidelines

| Folder | Usage |
|--------|-------|
| `project/` | 正式项目、生产项目 |
| `practice/` | 演示代码、实验、学习项目 |

## Examples

- "创建 document 文件夹" → 创建 document/project + document/practice
- "帮我整理一下项目" → 创建文件夹结构
- "建立练习目录" → 创建 practice 文件夹

## Notes
- 简单命令，无需认证
- 创建在用户主目录 ~/document/ 下
