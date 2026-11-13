# hatch-pet · Agent Skill

hatch-pet：Create, repair, validate, visually QA, and package Codex-compatible v2 animated pets from character art, generated images, company or prospect brand。

GitHub：[eli-ovops/skill-hatch-pet](https://github.com/eli-ovops/skill-hatch-pet)

## 内容

本次公开副本包含 29 个来源文件。

- [`LICENSE.txt`](LICENSE.txt)
- [`SKILL.md`](SKILL.md)
- [`agents/openai.yaml`](agents/openai.yaml)
- [`references/animation-rows.md`](references/animation-rows.md)
- [`references/codex-pet-contract.md`](references/codex-pet-contract.md)
- [`references/qa-rubric.md`](references/qa-rubric.md)
- [`scripts/assemble_extended_atlas.py`](scripts/assemble_extended_atlas.py)
- [`scripts/combine_direction_blind_verdicts.py`](scripts/combine_direction_blind_verdicts.py)
- [`scripts/compose_atlas.py`](scripts/compose_atlas.py)
- [`scripts/compose_cardinal_anchor_strip.py`](scripts/compose_cardinal_anchor_strip.py)

文件类型：.py（23）、.md（4）、.txt（1）、.yaml（1）。

## Skill 入口

技能名称：hatch-pet。
- 入口：[`SKILL.md`](SKILL.md)；脚本和参考文件按原包结构保留。

使用前先阅读技能正文、依赖和权限要求；本次发布没有安装或执行这些技能。

## 来源与许可

保留原有上游许可证和署名；相关源码按仓库内既有许可使用。新增发布介绍的许可单独列在 LICENSE.publication-notes。

上游仓库地址尚未可靠核实，保留为待核事项。

## 当前状态与验证边界

- 本次完成公开副本整理和静态检查；没有运行来源代码、构建 App、安装 Skill 或启动服务。
- 项目可能处于原型、实验或研究阶段；没有将其表述为生产交付、客户验收或经过验证的投资收益。
- 图片、视频、数据库、真实账户记录及未确认可公开的附件没有随本次文本/源码副本上传。
- 部分相对链接、运行依赖或素材可能仍需补齐；原始快照中的静态引用缺口数为 0，该数字不是运行失败数。
- [本次来源文件清单](SOURCE_MANIFEST.csv)
