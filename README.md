# jiuliang-scenes

九两 IP 场景图 Skill：把中文文章观点、读者处境、课程故事或演示文稿观点，转成带 **卡通九两** 的干净场景图。

核心公式：

```text
卡通九两 + 真实物件 + 一个物理动作 + 2-4 个短中文标签 + 留白叙事
```

## 适合做什么

- 公众号头图、正文配图
- 汤九两 / 半斤九两个人 IP 插图
- 文章观点隐喻图
- PPT 封面、章节页、观点页插图
- 课程、产品、项目演化的长卷故事图

## 不适合做什么

- 直接生成完整 PPTX
- 做密集信息图、流程图、仪表盘或 UI 截图
- 做泛机器人、动物、黑豆角色、小黑风格图
- 用长标题解释画面，而不是让动作本身表达意思

如果要做 PPT，这个 Skill 负责“每一页的视觉锚点/插图”。真正的版式排版、页码、母版和 `.pptx` 导出，建议配合单独的 presentation workflow。

## 安装

复制本仓库到 Codex skills 目录：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/FloydTang/jiuliang-scenes.git ~/.codex/skills/jiuliang-scenes
```

然后在 Codex 中请求类似：

```text
用 jiuliang-scenes 给这篇文章做一张公众号正文配图。
```

或：

```text
用九两 IP 场景图给这页 PPT 做一个章节视觉。
```

## 资产与授权

本仓库公开可见，但不等于开放授权。卡通九两形象、半斤九两 / 汤九两相关品牌资产与角色设定保留权利。未经授权请勿用于第三方商业项目、衍生 IP、转售素材包或与半斤九两无关的品牌传播。

## 目录

```text
SKILL.md
agents/openai.yaml
assets/character/
references/
```

主要参考：

- `references/jiuliang-ip.md`：角色 DNA 与守则
- `references/style-dna.md`：风格、留白、物件选择
- `references/story-extraction.md`：从文章提炼场景
- `references/prompt-template.md`：ImageGen 提示词模板
- `references/qa-checklist.md`：验收与修正清单
