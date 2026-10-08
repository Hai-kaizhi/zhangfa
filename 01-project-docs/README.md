# 01-project-docs — 项目级长期基线

当前项目尚未立项，本目录为空模板态；基线文档由提示词在流程中生成，不预置空文档：

| 产出 | 提示词 | 时机 |
|---|---|---|
| `00-inputs/01-原始需求.md` | —（立项输入材料直接写入） | 立项时 |
| `01-concept/01-概念文档（项目）.md` | [01 概念文档](../99-shared/prompts/01-project/01-提示词-概念文档（项目）.md) | 项目级第一步 |
| `02-prd/02-PRD（项目）.md` | [02 PRD（项目）](../99-shared/prompts/01-project/02-提示词-PRD（项目）.md) | 概念定稿后 |
| `03-tech-doc/03-技术文档（项目）.md` | [03 技术文档（项目）](../99-shared/prompts/01-project/03-提示词-技术文档（项目）.md) | PRD 定稿后 |
| `04A-dev-standards/`、`04B-ui/`、`04C-module-design/` | [04A/04B/04C 提示词](../99-shared/prompts/README.md) | 技术文档后可并行；04A 在真实代码交付前必选，04B/04C 按需 |
| `05-roadmap/05-产品路线图（项目）.md` | [05 产品路线图（项目）](../99-shared/prompts/01-project/05-提示词-产品路线图（项目）.md) | 分支基线一致后收口 |
| `术语表.md` | 无独立提示词（各层按命名承接纪律共同维护） | 首个命名定名时创建，只增维护 |

完整示例见[示范项目](../99-shared/prompts/references/README.md)各项目的同名目录。
