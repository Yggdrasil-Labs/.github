# .github

> Yggdrasil-Labs 组织的共享配置和模板仓库

这个仓库包含了 Yggdrasil-Labs 组织下所有项目的共享配置、工作流、模板和最佳实践。

---

## 📁 仓库结构

```
.github/
├── profile/           # 组织 Profile README
├── workflows/         # GitHub Actions 工作流
├── ISSUE_TEMPLATE/    # Issue 模板
├── PULL_REQUEST_TEMPLATE/  # PR 模板
├── CODEOWNERS         # 代码所有者配置
├── CONTRIBUTING.md    # 贡献指南
├── SECURITY.md        # 安全政策
└── README.md          # 本文件
```

---

## 🚀 功能特性

### 🔄 CI/CD 工作流
- **自动化测试**: 统一的测试流程和代码质量检查
- **自动部署**: 标准化的部署流程
- **依赖更新**: 自动化的依赖管理和安全更新
- **发布管理**: 统一的版本发布和变更日志生成

### 📋 模板系统
- **Issue 模板**: 标准化的 bug 报告和功能请求模板
- **PR 模板**: 统一的代码审查和合并流程
- **项目模板**: 快速创建新项目的标准化模板

### 📖 文档标准
- **贡献指南**: 详细的贡献流程和代码规范
- **安全政策**: 安全漏洞报告和处理流程
- **代码所有者**: 自动化的代码审查分配

---

## 🛠️ 使用方法

### 为新项目应用配置

1. **复制工作流文件**:
   ```bash
   cp .github/workflows/* your-project/.github/workflows/
   ```

2. **应用模板**:
   ```bash
   cp .github/ISSUE_TEMPLATE/* your-project/.github/ISSUE_TEMPLATE/
   cp .github/PULL_REQUEST_TEMPLATE/* your-project/.github/PULL_REQUEST_TEMPLATE/
   ```

3. **配置代码所有者**:
   ```bash
   cp .github/CODEOWNERS your-project/.github/
   ```

### 自定义配置

每个项目可以根据需要自定义这些配置，但建议保持核心结构的一致性。

---

## 📚 相关文档

- [贡献指南](CONTRIBUTING.md) - 如何为项目做贡献
- [安全政策](SECURITY.md) - 安全漏洞报告流程
- [组织 Profile](profile/README.md) - Yggdrasil-Labs 组织介绍

---

## 🤝 贡献

欢迎为这个配置仓库贡献改进建议！

1. Fork 这个仓库
2. 创建你的功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交你的更改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 打开一个 Pull Request

---

## 📞 支持

如果你在使用这些配置时遇到问题：

- 创建 [Issue](https://github.com/Yggdrasil-Labs/.github/issues)
- 参与 [Discussions](https://github.com/Yggdrasil-Labs/.github/discussions)
- 查看 [组织 Profile](profile/README.md) 了解更多信息

---

<div align="center">
  <sub>© 2025 Yggdrasil-Labs. 保留所有权利。</sub>
</div>