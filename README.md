# 模块化封套宣传册

**Modular Brochure System · `modular-brochure-system`**

一套封套承载品牌，一张双面插页介绍一项业务，用颜色区分，用组合适配客户。

这个 Skill 将“通用封套＋A4 双面插页”的宣传方式整理为可持续维护的设计与制作方法，适用于拥有多产品、多业务或多种解决方案的企业及组织。

## 核心方法

- **封套通用**：承载稳定品牌信息，适合在确认后集中制作。
- **版式统一**：固定品牌位置、页眉页脚、网格、字体与视觉语言。
- **业务分色**：正反两面主题色一致，配合名称和编号识别。
- **整张组合**：每个模块是一张双面纸，按客户需要选取和排序。
- **分别更新**：独立管理封套和各业务模块的版本与补印。

统一品牌的同时，可以为不同客户提供不同的内容组合。无需因一项业务更新而重做整套资料。

## 使用

把仓库中的 [`modular-brochure-system/`](modular-brochure-system/) 文件夹完整放入 Codex 的技能目录（通常为 `~/.codex/skills/`）。入口是 [`SKILL.md`](modular-brochure-system/SKILL.md)。

可以这样提出任务：

> 使用 $modular-brochure-system，根据我的品牌资料和业务清单，规划统一封套、业务配色及 A4 双面插页，并为三类客户提供组合建议。

> 使用 $modular-brochure-system，在现有母版下新增一张解决方案插页，保持顶部、底部和品牌风格一致，同时更新模块登记表。

## 包含内容

| 文件 | 用途 |
| --- | --- |
| [`SKILL.md`](modular-brochure-system/SKILL.md) | 任务入口、工作方法与交付规则 |
| [`设计系统`](modular-brochure-system/references/design-system.md) | 母版、配色与内容组织 |
| [`来源观察`](modular-brochure-system/references/source-patterns.md) | 原始设计的可借鉴结构和适配边界 |
| [`印刷与装配`](modular-brochure-system/references/production-and-assembly.md) | 印前检查、双面配对、客户组合与版本管理 |
| [`正面母版`](modular-brochure-system/assets/module-front.svg) / [`背面母版`](modular-brochure-system/assets/module-back.svg) | 可编辑的 A4 结构示意 |
| [`模块登记表`](modular-brochure-system/assets/module-register.csv) | 维护业务、颜色、正反文件、版本与库存 |

SVG 为 RGB、无出血的结构母版，需替换占位内容并按实际印刷规格制作输出文件。封套尺寸与收纳量依照纸张、结构和印厂刀模确定。

## 方法来源

由真实历史宣传册的结构和使用方式提炼：保留品牌统一、双面模块、业务分色和灵活装配的思路，增加模块编号、版本配对、客户组合与制作检查。原资料中的横向展开稿作为适配例外处理。

仓库仅发布抽象方法、原创母版及虚构示例，不附原宣传册图片、PSD、人物资料、联系方式或历史客户标志。
