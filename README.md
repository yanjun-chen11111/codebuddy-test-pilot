# CodeBuddy Skill: test-pilot

工程级测试技能。当你实现完功能、讨论如何验证，或要求"真正的测试"时，它会：

- 用五大测试设计技术（等价类划分、边界值分析、决策表、状态迁移、属性测试）从功能规格推导测试用例；
- 按对的层级写测试（单元 / 集成 / E2E）；
- 生成带真实断言（oracle）的用例，并用项目实际的测试框架运行（自动识别语言，不强绑 pytest）；
- 强制自检并报告漏测。

## 安装
把 SKILL.md 与 references/ 复制到：
- 项目级：.codebuddy/skills/test-pilot/
- 用户级：~/.codebuddy/skills/test-pilot/

刷新/重启对话后即自动触发，无需额外配置。
