# QA Checklist

## Pass Criteria

The image is acceptable only if all core checks pass:

- Character: clearly recognizable as 卡通九两, not Xiaohei, robot, animal mascot, or generic anime.
- Action: one core physical action is visible within 3 seconds.
- Object: one real main object or tight object group anchors the metaphor.
- Labels: 0-4 short Chinese labels, readable and not explanatory paragraphs.
- Layout: enough whitespace for article use.
- Style: coherent light, perspective, and soft shadows; no pasted collage edges.
- Brand fit: works with 半斤九两 warm paper, white article background, and restrained orange/blue/green accents.
- Fact safety: no invented dates, achievements, company names, user counts, or personal claims.

## Failure Signals

Regenerate or edit if any appears:

- Jiuliang's hair, glasses, orange shirt, or white/gray jacket disappears.
- The character becomes too realistic, too young, too toy-like, or too generic.
- The image uses Xiaohei or a black capsule/bean character.
- The scene becomes a PPT, workflow diagram, dashboard, UI screenshot, or poster slogan.
- Too many objects appear because the prompt copied every article noun.
- Text is too long or unreadable.
- The background is a heavy gradient, dark tech scene, office stock photo, noisy paper texture, or decorative blob field.
- The metaphor needs a long explanation to understand.

## Common Fixes

### Character drift

```text
Keep the scene and objects similar, but revise the character only. Make him clearly 卡通九两: silver-blue-purple fluffy hair, round glasses, orange inner shirt, white/light-gray tech jacket, black pants, black-white-orange sneakers. Do not use Xiaohei, robots, animals, or generic anime styling.
```

### Scene overloaded

```text
Regenerate with the same theme but reduce complexity. Keep one real main object, one Jiuliang action, at most two small props, and 2-3 short Chinese labels. Remove extra objects that do not serve the core physical action.
```

### Text too dense

```text
Remove long text and keep only 2-3 short handwritten Chinese labels. Each label should be 2-6 Chinese characters and should feel like real article-reader language.
```

### Weak metaphor

Return to story extraction and rewrite:

```text
who is being moved by what force, through which physical action, toward what consequence?
```

Then generate again with a simpler object-action pair.
