# 生图提示词模板

根据行业填入场景。先参考官方九两人物，再查看 approved-examples.md 中的获认可图片，保留身份与质感，不照搬布料、蓝橙配色或固定站位。

## 正文配图 / 讲解图

```text
Create one complete {aspect ratio, normally 16:9} article illustration for 半斤九两 / 汤九两.
Style: 九两微缩实物讲解风 — a refined 3D cartoon guide integrated into a tactile, realistic physical scene. Warm ivory studio background, soft diffused lighting, natural contact shadows, coherent perspective, and generous intentional whitespace.

Core idea: {one article viewpoint}
Industry: {industry}
Main object or coherent object group: {objects naturally belonging to this industry}
Material details: {weave / brushed metal / glass refraction / wood grain / paper edges, as appropriate}
One explanatory action: Jiuliang {physical action} to make {relationship} visible.
Scale treatment: {miniature / cutaway / magnified detail / ordinary scale, whichever clarifies this idea}
Composition: {viewpoint, focal point, character scale, reserved text space}

Character: preserve the supplied official Jiuliang identity — fluffy silver-blue-lavender hair, round glasses, orange inner shirt, white/light-gray tech jacket, black trousers, black-white-orange sneakers. Friendly, clever, recognizable, with dimensional cartoon rendering. He physically participates in the action and shares the scene's lighting. No realistic human face, generic mascot, or flat pasted sticker.

Typography: {exact short sentence OR 0–3 exact labels OR no text}. Use crisp, readable typeset lettering. Text supports the scene; do not add extra labels. Do not default to handwriting.
Color: use the real materials' appropriate colors with a calm neutral background; the orange clothing carries brand continuity. No mandatory blue-orange palette.
Avoid dense diagrams, icon collages, unrelated props, glossy plastic everywhere, dramatic neon, decorative gradients, and stock office scenes. Do not invent certificates, reports, numbers, logos, or QR codes. Produce a conceptual illustration rather than fabricated documentary evidence.
```

## 封面

在正文模板基础上，用一个更容易辨认的主体轮廓和动作，保留足够的标题区域。加入：

```text
Cover format: {target platform and actual aspect ratio}.
Exact title: {short title}.
Optional subtitle or series line: {exact wording or none}.
Use strong, clean editorial typography with a clear hierarchy and breathing room. Keep the title, Jiuliang, and the meaningful action within the platform's crop-safe area. One visual idea, no poster-like block of sales copy. Jiuliang may be small when the main physical scene should dominate.
```

不要让每张图都复制“左字右人”。中文、英文封面分别组织字数与版面；公众号、LinkedIn、X 长文按各自裁切需求适配。

## 长卷与演示文稿视觉

沿用相同材质、人物和灯光。长卷按故事需要设置少量场景，各场景一个动作；PPT 插图为标题或讲解留出空间。不要把整段文章、所有节点或整页幻灯片内容塞入生图提示词。

## 透明角色层

仅在需要复用角色图层时生成单独 cutout。直接要求透明背景，保留全身和边缘安全距离。它是身份与动作素材，不替代最终立体实物场景。
