# 技能清单（Git 地址版）

> 生成时间：2026-11-05　|　来源：本机 `~/.skills-manager` 中央库　|　共 **47** 个技能：**33** 个可从 GitHub 拉取（11 个仓库），**14** 个无上游需另行备份。

## 一、仓库总览

| # | 仓库地址 | 分支 | 技能数 | License | ⭐ |
|---|---|---|---|---|---|
| 1 | https://github.com/obra/superpowers | main | 14 | MIT | 312,756 |
| 2 | https://github.com/DietrichGebert/ponytail | main | 6 | MIT | 184,916 |
| 3 | https://github.com/wshobson/agents | main | 4 | MIT | 42,229 |
| 4 | https://github.com/anthropics/skills | main | 2 | 无 LICENSE 文件 | 187,611 |
| 5 | https://github.com/mattpocock/skills | main | 1 | MIT | 314,286 |
| 6 | https://github.com/MiniMax-AI/skills | main | 1 | MIT | 13,790 |
| 7 | https://github.com/currents-dev/playwright-best-practices-skill | main | 1 | MIT | 419 |
| 8 | https://github.com/fastapi/fastapi | master | 1 | MIT | 104,426 |
| 9 | https://github.com/QingYunA/answer-me-with-html | main | 1 | MIT | 5,329 |
| 10 | https://github.com/xingkongliang/skills-manager | main | 1 | MIT | 7,289 |
| 11 | https://github.com/alchaincyf/nuwa-skill | main | 1 | MIT | 37,574 |

**一键克隆全部仓库：**

```bash
mkdir -p ~/skills-src && cd ~/skills-src
git clone --depth 1 https://github.com/obra/superpowers.git
git clone --depth 1 https://github.com/DietrichGebert/ponytail.git
git clone --depth 1 https://github.com/wshobson/agents.git
git clone --depth 1 https://github.com/anthropics/skills.git
git clone --depth 1 https://github.com/mattpocock/skills.git
git clone --depth 1 https://github.com/MiniMax-AI/skills.git
git clone --depth 1 https://github.com/currents-dev/playwright-best-practices-skill.git
git clone --depth 1 https://github.com/fastapi/fastapi.git
git clone --depth 1 https://github.com/QingYunA/answer-me-with-html.git
git clone --depth 1 https://github.com/xingkongliang/skills-manager.git
git clone --depth 1 https://github.com/alchaincyf/nuwa-skill.git
```

## 二、按仓库展开（含技能子路径）

### obra/superpowers

- 地址：https://github.com/obra/superpowers
- 分支：`main`　License：MIT　⭐ 312,756
- 说明：方法论主干：头脑风暴 → 计划 → 子代理执行 → 评审 → 验证的完整开发闭环

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `brainstorming` | `skills/brainstorming` | `2ce8aa15` | coding |
| `dispatching-parallel-agents` | `skills/dispatching-parallel-agents` | `2ce8aa15` | coding |
| `executing-plans` | `skills/executing-plans` | `2ce8aa15` | docs、coding |
| `finishing-a-development-branch` | `skills/finishing-a-development-branch` | `2ce8aa15` | coding |
| `receiving-code-review` | `skills/receiving-code-review` | `2ce8aa15` | coding |
| `requesting-code-review` | `skills/requesting-code-review` | `2ce8aa15` | coding |
| `subagent-driven-development` | `skills/subagent-driven-development` | `2ce8aa15` | coding |
| `systematic-debugging` | `skills/systematic-debugging` | `2ce8aa15` | coding |
| `test-driven-development` | `skills/test-driven-development` | `22f0b463` | coding |
| `using-git-worktrees` | `skills/using-git-worktrees` | `22f0b463` | coding |
| `using-superpowers` | `skills/using-superpowers` | `22f0b463` | coding |
| `verification-before-completion` | `skills/verification-before-completion` | `22f0b463` | coding |
| `writing-plans` | `skills/writing-plans` | `22f0b463` | coding |
| `writing-skills` | `skills/writing-skills` | `22f0b463` | coding |

### DietrichGebert/ponytail

- 地址：https://github.com/DietrichGebert/ponytail
- 分支：`main`　License：MIT　⭐ 184,916
- 说明：「偷懒型资深工程师」风格：最小改动、拒绝过度设计，含审计/评审/技术债子技能

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `ponytail` | `skills/ponytail` | `96608e07` | coding |
| `ponytail-audit` | `skills/ponytail-audit` | `96608e07` | coding |
| `ponytail-debt` | `skills/ponytail-debt` | `96608e07` | coding |
| `ponytail-gain` | `skills/ponytail-gain` | `96608e07` | coding |
| `ponytail-help` | `skills/ponytail-help` | `96608e07` | coding |
| `ponytail-review` | `skills/ponytail-review` | `96608e07` | coding |

### wshobson/agents

- 地址：https://github.com/wshobson/agents
- 分支：`main`　License：MIT　⭐ 42,229
- 说明：大型插件合集，本次只取 4 个 Python / FastAPI / E2E 相关技能

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `e2e-testing-patterns` | `plugins/developer-essentials/skills/e2e-testing-patterns` | `7e2fb559` | — |
| `fastapi-templates` | `plugins/api-scaffolding/skills/fastapi-templates` | `7e2fb559` | — |
| `python-design-patterns` | `plugins/python-development/skills/python-design-patterns` | `7e2fb559` | — |
| `python-testing-patterns` | `plugins/python-development/skills/python-testing-patterns` | `7e2fb559` | — |

### anthropics/skills

- 地址：https://github.com/anthropics/skills
- 分支：`main`　License：无 LICENSE 文件　⭐ 187,611
- 说明：Anthropic 官方技能库，本次取 skill-creator 与 frontend-design

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `frontend-design` | `skills/frontend-design` | `ca45fc49` | coding |
| `skill-creator` | `skills/skill-creator` | `ca45fc49` | coding |

### mattpocock/skills

- 地址：https://github.com/mattpocock/skills
- 分支：`main`　License：MIT　⭐ 314,286
- 说明：取 grill-me（方案追问打磨）

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `grill-me` | `skills/productivity/grill-me` | `4ae2317d` | coding |

### MiniMax-AI/skills

- 地址：https://github.com/MiniMax-AI/skills
- 分支：`main`　License：MIT　⭐ 13,790
- 说明：MiniMax 官方技能库，取 docx 排版技能

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `minimax-docx` | `skills/minimax-docx` | `60aaae52` | docs |

### currents-dev/playwright-best-practices-skill

- 地址：https://github.com/currents-dev/playwright-best-practices-skill
- 分支：`main`　License：MIT　⭐ 419
- 说明：Playwright 测试最佳实践单技能仓库

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `playwright-best-practices` | `playwright-best-practices` | `283d5cbc` | coding |

### fastapi/fastapi

- 地址：https://github.com/fastapi/fastapi
- 分支：`master`　License：MIT　⭐ 104,426
- 说明：从 FastAPI 官方仓库的 .agents/skills 目录取 fastapi 技能（注意默认分支是 master）

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `fastapi` | `fastapi/.agents/skills/fastapi` | `5cb6272e` | — |

> 注意：该仓库默认分支为 `master`，且技能埋在 `fastapi/.agents/skills/fastapi`，克隆后路径不要拼错。

### QingYunA/answer-me-with-html

- 地址：https://github.com/QingYunA/answer-me-with-html
- 分支：`main`　License：MIT　⭐ 5,329
- 说明：把回答渲染成一页可视化 HTML 解释页

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `answer-me-with-html` | `skills/answer-me-with-html` | `2d39c334` | 人物角色 |

### xingkongliang/skills-manager

- 地址：https://github.com/xingkongliang/skills-manager
- 分支：`main`　License：MIT　⭐ 7,289
- 说明：Skills Manager 自身，内置 manage-skills 技能（用 CLI 管理技能库）

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `manage-skills` | `skills/manage-skills` | `d30530c0` | coding |

### alchaincyf/nuwa-skill

- 地址：https://github.com/alchaincyf/nuwa-skill
- 分支：`main`　License：MIT　⭐ 37,574
- 说明：人物视角写作（花叔女娲），当前库里是 import 版本，建议换源后纳入

| 技能 | 仓库内子路径 | 本地记录 commit | 归属 preset |
|---|---|---|---|
| `huashu-nuwa` | （仓库根目录） | `—` | writing、人物角色 |

> 注意：本地库里 `huashu-nuwa` 仍是 import 版本（尚未换源）。在新机器上直接用这个仓库装即可，比本机更干净。

## 三、不在 GitHub 上的 14 个

这些没有公开仓库，靠上面 11 个地址拉不全，需要单独打包（直接压缩 `~/.skills-manager/skills/<名称>` 目录即可）。

**自建（9 个）**

- `apipost-test-report` — Apipost 接口测试报告，按 docx 模板出结构化自测报告
- `cn-docx-finalize` — docx 收口成中文正式公文风格（黑体标题 / 宋体正文 / 目录域）
- `code-simplifier` — 代码简化原则与重构指导
- `deployment-plan-review` — 生产变更 / 上线方案文档审核（表格 + 🔴🟡 严重度）
- `drawio-annotate` — 在 drawio 导出 PNG 上做分类高亮标注，并回写 .drawio
- `jiajing-emperor-perspective` — 嘉靖皇帝视角思考框架
- `pozhenzil-perspective` — 破阵子视角思考框架
- `tech-proposal-generator` — 技术方案生成，对齐既定模板格式
- `tech-proposal-review` — 技术方案评审

**技能市场安装（2 个）**

- `markitdown-skill` — 市场包，底层是微软 markitdown CLI；上游 github.com/microsoft/markitdown 是工具本体，不是技能包
- `weekly-report` — 市场包，无公开仓库

**平台发布版（3 个）**

- `superpowers` — OpenClaw 平台发布版（ownerId/slug 元数据），内容与 obra/superpowers 重叠
- `superpowers-overview` — 同上，超能力套件的入口导航
- `superpowers-verification` — 同上，完成声明前的验证要求

## 四、新机器恢复步骤

**方式 A：用 Skills Manager CLI（推荐）**

```bash
# 1. 装 CLI（技能库本体）
git clone --depth 1 https://github.com/xingkongliang/skills-manager.git

# 2. 按清单逐个安装，owner/repo@技能名 会自动定位子目录
skills-manager-cli skills install obra/superpowers@brainstorming
skills-manager-cli skills install DietrichGebert/ponytail@ponytail-review
# …其余按第二节表格替换
```

> `@技能名` 定位失败时（个别仓库目录层级较深），改用克隆后 `skills adopt <本地路径>` 纳管。

**方式 B：纯 clone + 手动拷贝**

```bash
git clone --depth 1 https://github.com/obra/superpowers.git
cp -r superpowers/skills/brainstorming ~/.workbuddy/skills/
```

装完后按 preset 归组（本地现有分组，供参考）：

| preset | 技能数 | 说明 |
|---|---|---|
| `coding` | 29 | 编码能力：方法论主干 + 代码审查 + 技能工程 |
| `docs` | 9 | 文档产出：Word/docx 排版、技术方案、测试报告、格式转换 |
| `人物角色` | 8 | 人物视角角色包 |
| `writing` | 4 | 写作：周报、人物视角与文风 |
| `diagram` | 1 | 图表：架构图生成与标注 |

```bash
skills-manager-cli presets create coding --description "编码能力"
skills-manager-cli presets add-skill coding <技能id...>
skills-manager-cli presets deploy coding --agent workbuddy
```

## 五、两点注意

1. **中文备注不会跟着 git 走。** 本地这 33 个技能的 `description` 已被改写成中文，但从上游拉下来是英文原版。想要中文备注，需要在新机器上重跑一次改写脚本（`_cn_desc.py` + `_cn_block.py` + `_db_sync.py`，见上次整理记录）。
2. **部分技能未归入 preset。** 上表「归属 preset」为 `—` 的 4 个（`e2e-testing-patterns`、`fastapi-templates`、`python-design-patterns`、`python-testing-patterns`）本地装了但没进任何 preset，新机器上按需自行归组。

---

完整机器可读清单见同目录 `skills-manifest.json`（含每个技能的描述、来源 commit、preset 归属）。
