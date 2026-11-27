---
name: jiuliang-scenes
description: Plan and create 半斤九两 / 汤九两 article illustrations and cover images in the default 九两微缩实物讲解风, combining the recognizable cartoon Jiuliang with realistic materials, miniature scenes, one explanatory action, sparse typography, and whitespace. Use for 公众号头图、正文配图、社媒文章插图、行业讲解图、观点隐喻图 and presentation visual anchors.
---

# 九两 IP 场景图

## 默认风格：九两 · 微缩实物讲解风

用户于 2026-10-29 确认：今后文章及讲解类配图以柯桥这一版的真实材质、立体微缩场景为主；随行业调整物件、材质、颜色和场景，不套同一构图。除非用户另有指定，直接采用此风格。

```text
卡通九两 + 有真实质感的主题物件 + 一个有意义的动作
+ 一个核心观点 + 简洁文字与充足留白
```

九两是场景中的讲解者。人物保持卡通识别，物件有可感知的纹理、厚度、重量和光影，两者处于同一个立体空间。通过掀开、连接、观察、拆解等动作，把文章里的关系变成一眼能懂的画面。人物大小随叙事变化，封面可以小、正文可以大。

## 按需读取

- [style-dna.md](references/style-dna.md)：默认材质、光影、构图、文字与行业变化。
- [jiuliang-ip.md](references/jiuliang-ip.md)：人物识别及官方角色参考。
- [approved-examples.md](references/approved-examples.md)：本次获认可的柯桥图片；首次使用新版或校准画风时查看。
- [story-extraction.md](references/story-extraction.md)：从正文提炼物件与动作。
- [prompt-template.md](references/prompt-template.md)：封面、正文与其他模式的生图模板。
- [qa-checklist.md](references/qa-checklist.md)：交付前核对。

## 先做图位规划

只做配图规划、写公众号「配图建议」或把方案交给另一个 Agent 时，同样使用此 Skill。先读 [story-extraction.md](references/story-extraction.md) 和 [approved-examples.md](references/approved-examples.md)，打开随仓库提供的一张同用途示例（封面参考封面、正文参考正文），再按原稿设计场景。

- 每个图位先标原稿段落或小节、读者需要看懂的关系，再给出该行业的具体实物和材质、九两对实物做的动作，以及动作后能看到什么。
- 参考图用于校准真实材质、体积、光影与空间。重新选择本篇的物件、视角和人物尺度。去掉标题后仍应看得出动作；把场景挪到别的行业仍然成立时，回到原稿换掉泛用道具或动作。
- 给制作方说明用途、比例、文字（可无字）和用到的参考图。封面负责识别主题，正文各图承担不同的解释任务；图数随内容变化。用户只要方案时，交付可供生图的方案。

## 工作方式

1. 按上一节的图位规划确定一张图的核心观点。已有规划若只有通用场景或道具，先补齐行业实物、物理动作和可见结果，再生成。
2. 按用途确定比例：正文通常 16:9；封面按平台适配，例如公众号宽封面约 2.35:1、LinkedIn 约 1.91:1、X 长文封面约 5:2。标题、人物和动作放在裁切安全区；先查看目标平台实际要求。
3. 使用官方九两人物参考，结合获认可的立体示例校准。`assets/character/jiuliang-cutout-v2.png` 用于身份识别，动作表用于动作参考；把官方角色图与规划时选的获认可图片一起作为 ImageGen 参考图传入（工具支持参考图时），后者只参考质感、光影和空间，不沿用其中的文字与行业物件。不要照搬二维精灵表的画法来限制正文图的材质与体积。
4. 用户要规划时先给场景方案；用户要配图时直接用 ImageGen 输出完整位图。正式图片写入对应外部媒体目录，Vault 留文字规范与链接。
5. 查看生成结果，核对人物识别、动作含义、材质与光影、文字、手机阅读和平台裁切。

## 关键取舍

- 一张图一个核心观点、一个主动作、一组紧密相关的物件；微缩工厂可有合理细节，不机械限制每个零件数量。
- 默认暖白或象牙白背景、柔和棚拍光、自然接触阴影；主题物件决定主色，橙色服装呼应品牌。不要固定每张蓝橙配色。
- 封面可有一个清楚的大标题；正文可有一句短观点、0–3 个短标签，也可无字。默认清晰排字，手写注释仅在适合时使用，不为凑数量加字。
- 不把主体写实化成人像，也不把场景做成平面图标拼贴、塑料玩具展示、密集 PPT 或大段口号海报。
- 生成场景是讲解插画；文章中的真实现场、产品实拍、报告截图按原材料保留。官方 Logo、二维码继续使用原件。
- 按文章已有材料表达事实，不为丰富画面编造数据、认证、客户、日期或成绩。

本 Skill 负责配图与视觉锚点，不替代整套 PPT 排版、发布流程或授权。
