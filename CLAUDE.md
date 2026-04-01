# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目概述

这是一个 VS Code 主题扩展项目，将 Solarized Dark 配色与 Monokai 语法高亮风格结合。

## 常用命令

- **打包扩展**: `vsce package` - 生成 .vsix 安装文件
- **本地安装**: 将扩展复制到 `~/.vscode/extensions/` 目录，或使用 VS Code "开发扩展"功能调试

## 项目结构

- `package.json` - 扩展配置，定义主题元数据和入口
- `themes/solarized-dark-monokai.json` - 主题颜色定义（UI 颜色 + 语法高亮规则）

## 开发说明

修改主题后，使用 "Developer: Reload Window" 命令刷新查看效果。无需构建步骤，纯配置文件项目。

## 发布

- 发布者: linjing
- 引擎要求: VS Code ^1.70.0
