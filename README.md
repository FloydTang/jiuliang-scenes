# jiuliang-scenes

九两 IP 场景图 Skill：把中文文章观点、读者处境、课程故事或演示文稿观点，转成带 **卡通九两** 的微缩实物讲解图：人物保持卡通识别，物件和场景有偏真实的材质、体积与光影。

核心公式：

```text
卡通九两 + 有真实质感的主题物件 + 一个有意义的动作
+ 一个核心观点 + 简洁文字与充足留白
```

2026-10-29 已确认为文章配图默认风格。材质、物件、主色与场景随行业变化，不固定蓝橙配色、手写标签数量或人物站位。

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
assets/examples/keqiao/
references/
```

主要参考：

- `references/jiuliang-ip.md`：角色 DNA 与守则
- `references/style-dna.md`：风格、留白、物件选择
- `references/story-extraction.md`：从文章提炼场景
- `references/prompt-template.md`：ImageGen 提示词模板
- `references/qa-checklist.md`：验收与修正清单
- `references/approved-examples.md`：本次认可的四张柯桥风格参考图（随仓库提供）

---

<!-- jiuliang-about-start -->

## 关于半斤九两 / About EVEN BETTER

半斤九两科技（EVEN BETTER）专注“外贸 + AI”的真实落地。我们希望帮助外贸企业把产品、客户、渠道和团队流程，沉淀成客户看得懂、渠道跑得动、团队留得下的系统。

我们主要提供：

- 外贸 AI 落地方法：围绕 Build / Traffic / Team，判断企业该先建资产、放流量，还是建系统。
- 企业表达与内容增长：把产品、案例、FAQ、老板经验和信任证据，整理成海外客户看得懂的内容资产。
- 主动开发流程：从客户画像、线索搜索、客户背调到开发信和跟进复盘，跑出可复用闭环。
- 团队 AI 工作流：把经验写进 AGENTS.md、SOP、模板库、检查清单和可复用 Skill。

更多内容可以查看我们整理的 [《外贸人 Codex 蓝皮书》](https://github.com/FloydTang/waimaoren-codex-bluebook)。

### 找到我们

- 官网：[tang92.com](https://tang92.com)
- 公众号：半斤九两
- GitHub：[@FloydTang](https://github.com/FloydTang)

扫码关注公众号，领取后续模板、案例和更新；也可以通过公众号后台留言联系九两。

<p>
  <img src="https://raw.githubusercontent.com/FloydTang/waimaoren-codex-bluebook/main/assets/wechat-qr.png" alt="半斤九两公众号二维码" width="180">
</p>

<!-- jiuliang-about-end -->
