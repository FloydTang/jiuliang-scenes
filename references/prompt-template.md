# 生图提示词模板

Use these as prompt structures for ImageGen. Replace all braces before generation.

## Standard 16:9 Article Image

```text
Generate one standalone 16:9 Chinese article illustration for the 半斤九两 / 汤九两 personal IP.

Core style:
A clean real-object studio scene with generous whitespace. The active character is 卡通九两, a Q-version young AI mentor with silver-blue-purple fluffy hair, round glasses, orange inner shirt, white/light-gray tech jacket, black pants, and black-white-orange sneakers. He is friendly, smart, energetic, not childish, and must perform the core physical action.

Scene:
Theme: {主题}
Reader situation: {读者处境}
Physical metaphor: {抽象观点变成的一个物理动作}
Real main object: {一个真实主物件或紧凑物件组}
Jiuliang action: {九两具体动作}
Short handwritten Chinese labels: {标签1} / {标签2} / {标签3}

Composition:
16:9 horizontal canvas. Background is {#FFFFFF pure white / warm paper #FAF7F0 / near-white #FBFBFA}. The scene occupies medium-light space, with clear breathing room around objects. Real objects share coherent light, perspective, and soft contact shadows. Use sparse brand-color accents: orange, blue, green, and a tiny red warning/detail only if useful.

Constraints:
No Xiaohei, no black bean mascot, no robot mascot, no animal mascot, no realistic human photo. No PPT, no infographic, no flowchart, no UI screenshot, no app logo, no dense text, no big title, no stock-photo office, no gradient background, no decorative orbs, no overloaded object inventory. Keep one core physical action and at most two small props.
```

## Header Image

```text
Generate one wide Chinese article header illustration for 半斤九两 / 汤九两.

Ratio: {2:1 or 16:9}. Leave safe whitespace for cropping and title overlay. Use 卡通九两 as the recognizable personal-IP actor: silver-blue-purple hair, round glasses, orange inner shirt, white/light-gray tech jacket, black pants, black-white-orange sneakers.

Article offer/category:
{文章主题或栏目}

Core visual:
One real-object scene where Jiuliang {动作} with {真实主物件}. The image should read in 1 second as: {一秒读懂句}.

Labels:
Use 0-2 very short Chinese labels only if readable at thumbnail size: {标签}

Style:
Clean, premium, warm, not marketing-poster heavy. Background {背景}. Sparse orange/blue/green accents. Strong silhouette, enough whitespace, no dense copy.

Negative:
No Xiaohei, no generic anime boy, no animal/robot mascot, no PPT, no big slogan poster, no UI screenshot, no fake logos, no dense paragraphs.
```

## Long-Scroll Story

```text
Generate one ultra-wide long-scroll story image for the 半斤九两 / 汤九两 personal IP.

Ratio about 2.6:1 to 3:1. Near-white or warm-paper background with subtle studio air. A loose hand-drawn route travels from left to right. Along it, 5-8 real-object nodes tell a continuous story. At every node, 卡通九两 performs one physical action with the object. The character remains recognizable: silver-blue-purple hair, round glasses, orange inner shirt, white/light-gray tech jacket, black pants, black-white-orange sneakers.

Main story:
{主线}

Left opening:
{左侧身份 / 起点 / 开场}

Nodes:
- {节点主题} | object: {物件} | Jiuliang action: {动作} | note: {短注释}
- {节点主题} | object: {物件} | Jiuliang action: {动作} | note: {短注释}
- {节点主题} | object: {物件} | Jiuliang action: {动作} | note: {短注释}
- {节点主题} | object: {物件} | Jiuliang action: {动作} | note: {短注释}
- {节点主题} | object: {物件} | Jiuliang action: {动作} | note: {短注释}

Right closing:
{右侧收束 / 当前关注 / 结论}

Layout:
Uneven node spacing, natural vertical rhythm, clear whitespace, no numbered circles, no timeline modules, no cards. Notes appear close to objects as light handwritten annotations. Use sparse colored dots, tape, or underlines only as rhythm accents.

Negative:
No Xiaohei, no black bean character, no robot/animal mascot, no formal timeline chart, no PPT, no dashboard, no UI screenshot, no dense text, no equal-spacing process diagram, no collage chaos.
```

## Cutout / Green-Screen Variant

Use this only when a reusable transparent character or object layer is needed:

```text
Generate a clean full-body 卡通九两 character on a solid chroma-green background. The background color must be clearly different from the hair, clothes, skin, and shoes. Keep the full body visible with safe margin. No shadow touching the edge, no props, no text.

Character: silver-blue-purple fluffy hair, round glasses, orange inner shirt, white/light-gray tech jacket, black pants, black-white-orange sneakers, friendly AI mentor energy, Q-version but not childish.
```

After generation, remove the green background with the ImageGen chroma helper and QA on dark, white, and warm-paper backgrounds.
