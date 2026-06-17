---
name: jiuliang-scenes
description: Generate or plan Chinese article and presentation illustrations for 半斤九两 / 汤九两 using the Jiuliang cartoon IP, real-world objects, one physical action, short Chinese labels, and strong whitespace. Use when the user asks for 公众号头图、公众号正文配图、PPT章节视觉、演示文稿配图、九两卡通人像配图、半斤九两个人 IP 插画、主题 IP 场景图、文章观点隐喻图、长卷故事图, or wants to adapt ian-xiaohei-scenes / 小黑场景图 into the Jiuliang personal-IP style.
---

# 九两 IP 场景图

## Core Idea

Turn article ideas, reader situations, project stories, and brand viewpoints into a small scene:

```text
卡通九两 + 真实物件 + 一个物理动作 + 2-4 个短中文标签 + 留白叙事
```

This skill inherits the useful scene-thinking from `ian-xiaohei-scenes`, but the active IP is always 卡通九两. Do not use Xiaohei, Xiaohei assets, black bean characters, generic robots, or unrelated mascots.

## Read First

Load only what the current request needs:

- `references/jiuliang-ip.md`: character DNA, asset paths, and IP guardrails.
- `references/style-dna.md`: visual rules, formats, object choices, color, and whitespace.
- `references/story-extraction.md`: how to convert article text into reader situations, actions, and labels.
- `references/prompt-template.md`: ImageGen prompt templates for standard, cover, and long-scroll modes.
- `references/qa-checklist.md`: acceptance checks and iteration fixes.

Use `assets/character/jiuliang-cutout-v2.png` as the primary character reference when a single clean portrait is needed. Use `assets/character/jiuliang-spritesheet-expanded-v3-clean.png` when action variety or desktop-pet continuity matters.

## Workflow

1. Identify the output mode:
   - Standard article image: 16:9, best for 公众号正文图.
   - Header image: 2:1 or 16:9, best for 公众号头图 or channel cover.
   - Presentation visual: 16:9, best for PPT 封面、章节页、观点页插图、课件过渡页.
   - Long-scroll story: 2.6:1 to 3:1, best for personal journey, project review, product evolution, or course narrative.

2. Extract the scene:
   - Reader: who should feel seen?
   - Conflict: what is pulling, pressing, filtering, blocking, sorting, or accelerating them?
   - Physical action: express the abstract idea as one visible action.
   - Real object: choose one object or one tight object group that naturally belongs to the reader's world.
   - Labels: write 2-4 short Chinese phrases from real usage, not concepts.

3. Build a shot list first when the user asks for planning, comparison, or direction. Include:
   - theme
   - reader situation
   - physical metaphor
   - real object
   - Jiuliang action
   - labels
   - why it is worth drawing

4. Generate directly when the user asks to output, see results, make images, or produce article assets. Use ImageGen with the prompt template, one image per concept.

5. Keep the Jiuliang IP stable:
   - silver-blue-purple hair
   - round glasses
   - orange inner shirt
   - white/gray tech jacket
   - black pants
   - black/white/orange sneakers
   - friendly but not childish

6. QA every generated image before delivery:
   - does it still look like Jiuliang?
   - is there exactly one core physical action?
   - do the objects feel real and coherent?
   - is the text sparse and readable?
   - does it fit the 半斤九两 brand palette and article use case?

## Defaults

- Default background: clean white or warm paper near `#FAF7F0`, depending on article tone.
- Default standard ratio: 16:9.
- Default header ratio: 2:1 when the platform needs a wide cover; otherwise 16:9.
- Default presentation ratio: 16:9 with extra safe space for slide titles or bullet overlays.
- Default label count: 3.
- Default object count: 1 main object plus up to 2 small props.
- Default mood: clear, light, intelligent, a little strange, not poster-like.

## Output Discipline

Do not turn the image into a PPT, diagram, dashboard, dense UI screenshot, office scene, or motivational poster. The picture should feel like a physical little moment that carries the article's meaning.

For PPT work, use this skill to create the visual scenes that go into slides: cover images, chapter openers, metaphor illustrations, and single-point visual anchors. Do not use it as the whole deck generator, slide layout engine, or PPTX exporter. Pair it with a presentation-building workflow when the user needs an actual `.pptx`.

When facts are involved, use only facts from the user, the article, or provided materials. Do not invent achievements, dates, company names, user counts, or personal history to make the image look complete.
