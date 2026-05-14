# bio_vibe

异星适应者是一套面向高中生物课堂的 Vibe Coding 项目材料。学生抽取一个极端外星环境，用自然语言和 AI 协作，设计一种能适应环境的生物，并生成一个可交互的 HTML 图鉴。

## 快速运行

最简单的方式：

1. 打开 `environments/` 文件夹。
2. 双击任意 `.html` 文件，或拖入浏览器。
3. 学生把对应星球基座代码交给 AI，让 AI 在 `creature-stage` 区域加入自己的生物、标注和生存挑战。

如果要给学生发在线链接，推荐开启 GitHub Pages：

1. 进入仓库 `Settings -> Pages`。
2. Source 选择 `Deploy from a branch`。
3. Branch 选择 `main`，目录选择 `/root`。
4. 保存后访问 `https://thomas-mci-21.github.io/bio_vibe/`。

## 项目结构

```text
bio_vibe/
├── index.html
├── environments/
│   ├── wind_rock.html
│   ├── syrup_sea.html
│   ├── ice_fire_wheel.html
│   ├── floating_forest.html
│   └── quicksand_tower.html
├── docs/
│   ├── project_overview.md
│   ├── teacher_guide.md
│   ├── student_mission_card.md
│   └── shooting_plan.md
└── materials/
    ├── preparation_checklist.md
    ├── design_strategy_cards.md
    └── vibe_prompt_workflow.md
```

## 五个星球

| 星球 | 核心挑战 | 环境文件 |
| --- | --- | --- |
| 风吼岩 | 强风、岩石地表、地热弱光 | `environments/wind_rock.html` |
| 糖浆海 | 低重力、高粘度液体、悬浮营养物 | `environments/syrup_sea.html` |
| 冰火轮 | 极大昼夜温差、强紫外、极寒长夜 | `environments/ice_fire_wheel.html` |
| 浮空林 | 稠密大气、弱光、空中森林 | `environments/floating_forest.html` |
| 流沙塔 | 松软流沙、孤立巨柱植物生态岛 | `environments/quicksand_tower.html` |

## 推荐使用顺序

1. 教师阅读 `docs/project_overview.md`。
2. 按 `materials/preparation_checklist.md` 准备设备、打印材料和拍摄资源。
3. 上课时发放 `docs/student_mission_card.md` 与 `materials/design_strategy_cards.md`。
4. 按 `docs/teacher_guide.md` 组织 120 分钟课堂。
5. 按 `docs/shooting_plan.md` 拍摄课堂宣传素材。

## 教学原则

- 不把 AI 当答案机，而把 AI 当可被学生指挥的程序员。
- 不要求学生会写代码，重点训练描述、反馈、迭代和判断。
- 环境基座只提供舞台，生物设计与生存逻辑必须由学生完成。
- 第一版很丑是正常现象，迭代前后对比正是课堂故事的核心素材。
