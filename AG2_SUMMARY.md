# AG2 和 AutoGen 的差别总结

## 简要回答

AG2 是 Microsoft AutoGen 的进化版本，由 AutoGen 原创始人和核心贡献者团队于2024年11月11日创建。主要差别包括：

### 1. 治理结构革命性变化
- **AutoGen**: Microsoft 企业主导
- **AG2**: 社区驱动的开放治理（AG2AI 组织）

### 2. 许可证升级
- **AutoGen**: MIT 许可证
- **AG2**: Apache 2.0 许可证（更好的企业保护）

### 3. 愿景扩展
- **AutoGen**: 多智能体对话框架
- **AG2**: 完整的"Open-Source AgentOS for AI Agents"

### 4. 技术架构改进
- 全新的 LLMConfig 配置系统
- MCP (Model Context Protocol) 集成
- 结构化输出支持
- 增强的工具系统和编排模式

### 5. 向后兼容性
- `autogen` 和 `ag2` 是同一个 PyPI 包的别名
- 现有 AutoGen 代码可无缝迁移
- 提供平滑的升级路径

## 核心优势

1. **开放治理**: 从企业主导转向社区驱动
2. **法律保护**: Apache 2.0 提供更好的企业级使用保障
3. **技术升级**: 更现代的架构和更丰富的功能
4. **生态扩展**: 更完整的工具链和集成支持
5. **企业友好**: 增强的安全性和生产环境支持

## 迁移建议

```bash
# 直接升级（无需修改代码）
pip install -U "ag2[openai]"
# 或
pip install -U "autogen[openai]"
```

## 详细文档

完整的对比分析请查看：
- [中文版详细文档](website/docs/faq/ag2-vs-autogen-cn.mdx)
- [English detailed documentation](website/docs/faq/ag2-vs-autogen-en.mdx)

这些文档将在 AG2 官方文档网站 (docs.ag2.ai) 的 FAQ 部分发布。