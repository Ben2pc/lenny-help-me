# Lenny Help Me

基于 [Lenny's Podcast](https://www.lennyspodcast.com/) 86 个专家级 skill 的 AI 顾问，涵盖产品、增长、销售、领导力、招聘、组织变革、创业、职业发展、AI 等领域。

## 结构

```
├── CLAUDE.md          # 顾问配置（角色定义、skill 使用规则、输出规范）
├── AGENTS.md          # -> CLAUDE.md 软链接
├── lenny-skills/      # 知识库（git submodule，来自 RefoundAI/lenny-skills）
└── workspace/         # 每次咨询的产出，按 YYYY-MM-DD-<主题> 归档
```

## 使用

```bash
git clone --recurse-submodules git@github.com:pangcheng1849/lenny-help-me.git
```

在项目目录下启动 Claude Code / Codex 等 AI 编码工具，直接提问即可。
