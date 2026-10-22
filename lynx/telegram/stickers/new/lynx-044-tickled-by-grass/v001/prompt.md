# Рысь бежит по траве и хохочет — вариант 1

ID: lynx-044-v001. Родитель: lynx-044. Дата: 2026-10-22.
Генератор: встроенный image_gen; transparent background.
Референс: [оригинал lynx-001](../../../orig/1xf09f9898.webp), внешность и стиль.

## Точный промпт генерации

```text
Use case: illustration-story
Asset type: static Telegram sticker, variant 1
Primary request: Create ONE sticker of the SAME female orange spotted lynx from the reference running joyfully through soft meadow grass and laughing uncontrollably because the grass tickles her fluffy belly and the underside near her rear haunches. No text.
Input image: reference image defines the lynx identity, face, fur colors, linework, proportions and polished cartoon style.
Scene/backdrop: only a compact curved strip of fresh green grass with several long flexible blades reaching upward under the moving lynx; genuine transparent alpha everywhere else, no rectangular landscape.
Subject: warm orange spotted fur, large green eyes, cream fluffy cheek ruffs, cream muzzle and pale fluffy belly, triangular ears with dark tufts, short lynx tail. The lynx runs on all four paws in a buoyant side-profile gallop from left to right, body stretched slightly in midair. Long grass blades visibly bend and brush the pale belly and the lower fur just in front of the short tail, making the tickling action unmistakable but innocent and nonsexual.
Expression: huge spontaneous laugh, eyes squeezed into happy crescents, mouth open in delighted laughter with small tongue and tiny feline teeth, cheeks lifted, ears cheerful.
Motion: lively bouncing stride, paws clearly separated, small clean motion strokes around the paws and at the two grass contact points; no words or laughter lettering.
Style/medium: bright polished 2D cartoon matching the original Telegram sticker pack, warm dark-brown outlines, soft gradients, expressive mildly exaggerated pose, clean continuous white die-cut sticker border.
Composition/framing: compact dynamic horizontal-diagonal silhouette, whole lynx, tail, paws and grass fully visible, centered within central 85 percent, generous transparent margins, readable at 512 px.
Constraints: exactly one lynx, four anatomically clear paws, one short natural lynx tail, grass touches belly and rear underside without hiding anatomy, no clothing, no other characters, actual transparency outside the sticker silhouette.
Avoid: text, letters, logos, watermark, flowers, insects, scenery, sky, ground rectangle, trees, extra limbs, extra tails, human anatomy, sexualized pose, cropped ears, cropped paws, random sparkles.
```

## Правка прозрачности и кадрирования

Цель: первичный результат генерации. Встроенный image_gen.

```text
Edit only the background transparency, canvas framing, and stray edge artifacts of this exact sticker. Preserve the exact same single orange spotted lynx, joyful laughing face, running side-profile pose, four paws, short bobtail, pale fluffy belly, grass blades and their contact with belly and rear underside, colors, linework and composition. Remove every gray haze, shadow field, speck, fleck, or disconnected fragment outside the continuous white die-cut sticker silhouette. Make the outside genuinely fully transparent alpha, with a clean smooth white sticker border. Fit the entire lynx, ear tufts, paws, tail and grass strip comfortably inside a square canvas with generous transparent margin on every side, occupying at most 88 percent of width and height. No text, no new objects, no changes to anatomy or expression.
```

## Файлы и обработка

[Первичный результат](source-initial.png), [очищенный исходник](source.png), [PNG](sticker.png), [WebP](sticker.webp).
После правки остаточная низкоальфовая крошка удалена пороговой очисткой альфа-канала. Экспорт FFmpeg: Lanczos до 496×496, прозрачные поля до 512×512; WebP без потерь, compression_level=6.
Превью на [белом](preview-white.png) и [тёмном](preview-dark.png) фоне. Проверка в [реестре](../../../registry.md).
