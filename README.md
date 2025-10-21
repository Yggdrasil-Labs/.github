# .github

> Yggdrasil-Labs 组织的共享配置和模板仓库

这个仓库包含了 Yggdrasil-Labs 组织下所有项目的共享配置、工作流、模板和最佳实践。

---

## 📁 仓库结构

```
.github/
├── profile/                     # 组织 Profile README
├── .github/
│   ├── dependabot.yml           # Dependabot 依赖更新配置
│   └── workflows/               # GitHub Actions 工作流
│       ├── ci.yml               # 统一 CI/CD 工作流
│       └── sync-dependabot.yml  # Dependabot 配置同步
├── labels.yml                   # 统一标签配置
└── README.md                    # 本文件
```

---

## 🚀 功能特性

### 🔄 CI/CD 工作流
- **统一 CI**: 支持 Node.js、Python、Go、Java、Flutter 等多语言项目的自动化测试和构建
- **智能发现**: 自动检测项目类型并运行相应的 CI 流程
- **依赖管理**: 通过 Dependabot 自动更新依赖，支持多种包管理器
- **配置同步**: 自动将 Dependabot 配置同步到组织内所有仓库

### 🏷️ 标签系统
- **统一标签**: 基于约定式提交规范的标签配置
- **语义化分类**: 支持功能、Bug、文档、依赖、发布等多种类型
- **自动应用**: 与 Dependabot 和 CI 工作流集成，自动应用相应标签

### 📖 组织标准
- **代码规范**: 遵循 Conventional Commits 提交规范
- **多语言支持**: 统一支持主流编程语言的开发流程
- **自动化运维**: 减少手动配置，提高开发效率

---

## 🛠️ 使用方法

### 为新项目应用配置

1. **复制 CI 工作流**:
   ```bash
   cp .github/workflows/ci.yml your-project/.github/workflows/
   ```

2. **应用 Dependabot 配置**:
   ```bash
   cp .github/dependabot.yml your-project/.github/
   ```

3. **应用标签配置**:
   ```bash
   cp labels.yml your-project/.github/
   ```

### 自动同步配置

- **Dependabot 配置**: 使用 `sync-dependabot.yml` 工作流可以自动将 Dependabot 配置同步到组织内所有仓库
- **CI 工作流**: 建议每个项目都使用统一的 `ci.yml` 工作流，支持多语言项目自动检测

### 自定义配置

每个项目可以根据需要自定义这些配置，但建议保持核心结构的一致性，特别是 CI 工作流和标签系统。

---

## 📚 相关文档

- [组织 Profile](profile/README.md) - Yggdrasil-Labs 组织介绍
- [标签配置](labels.yml) - 统一标签定义和使用说明
- [Dependabot 配置](.github/dependabot.yml) - 依赖更新自动化配置

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