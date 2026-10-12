# Рысь — Экспеллиармус! — вариант 2

ID: `lynx-026-v002`. Родитель: `lynx-026`. Дата: 2026-10-12.
Генератор: встроенный `image_gen`; `transparent_background: true`.

Файлы варианта: [исходник](source.png), [PNG 512×512](sticker.png), [WebP 512×512](sticker.webp). [Реестр](../../../registry.md).

## Референсы

- [Морда, глаза и лапы](../../../orig/11xf09f9889.webp).
- [Эмоциональная мимика](../../../orig/7xf09f98a0.webp).
- [Полный рост и динамика одежды](../../../orig/10xf09f95ba.webp).

## Точный промпт

```text
Use case: illustration-story. Create ONE new static Telegram sticker: «Рысь — Экспеллиармус!». Input images are references for the EXACT existing lynx character and sticker art style, not edit targets. Image 1: facial design, green eyes, cheeks and paws; image 2: expressive open-mouth fierce comic emotion; image 3: full-body proportions and dynamic dressed pose.
Subject: the same orange spotted lynx as a Gryffindor student from Harry Potter. Black wizard robe with burgundy lining, recognizable Gryffindor lion shield crest on the chest without lettering, red-and-gold striped scarf. Orange spotted paws and fluffy cream chest visible. Preserve original green eyes, large fluffy cheeks, ear tufts and recognizable proportions. Do not redesign the character.
Action: full-body dynamic fighting stance leaning slightly forward. One forepaw thrust forward, firmly gripping a wizard wand aimed diagonally upward. A vivid scarlet-red Expelliarmus burst erupts from its tip, with sparks, luminous curls and small energy lightning bolts. Other forepaw extended backward for balance. Robe and scarf billow from the force of the spell.
Emotion: determined, cheeky, slightly overconfident; bright green eyes wide open, brows furrowed, mouth open as if shouting the spell. Expressive and slightly comical like the original stickers.
Style: closely match reference sticker pack: cartoon 2D illustration, thick dark-brown outlines, warm orange fur palette, soft gradients, expressive face, slightly exaggerated anatomy, clean white outer sticker border. Keep silhouette and face legible at small size. Spell effect red, not blue.
Composition: square 512 x 512 px target, full lynx including ears, paws and tail, complete wand and ALL effects comfortably within the frame with a transparent margin. Exactly two forepaws and two hind paws; coherent grip and connected wand. Genuine transparent alpha background. No background scene, ground, floor, walls, scenery, text, lettering, captions or watermark. Crest uses lion icon only. Clean edges without loose white fragments outside the intentional border. Output PNG; final static sticker will be exported under 512 KB.
Variant 2: alternate full-body action silhouette: low forward lunge, wand and scarlet spell directed toward the upper left, trailing scarf sweeping to the opposite side. More theatrically defiant open-mouth expression, both green eyes fully visible. Keep all costume and character requirements unchanged.
```

## Исправление кадрирования

Первичный результат: [source-initial.png](source-initial.png). Эффект обрезался слева; выполнена отдельная правка встроенным `image_gen` с этим файлом как целью редактирования и `transparent_background: true`. Итог правки: `source.png`.

```text
Edit the provided sticker only to fix its framing. Preserve the exact lynx character, face, costume, colors, paw pose, wand, red spell and illustration style. The spell is cropped off at the upper-left image boundary: reconstruct its complete outer shape, making the red magical burst more compact if needed, and zoom the ENTIRE composition out to occupy at most 85 percent of the square canvas width and height. ALL parts including every red effect, scarf end, ear and foot must be fully contained with a clear transparent margin on every side. Clean white sticker outline, remove isolated accidental tiny edge specks. No text, no background. Actual transparent alpha background. Square image for a 512x512 Telegram sticker.
```

## Подготовка экспорта

Исходник генератора сохраняется без изменений. FFmpeg: масштабирование Lanczos с сохранением пропорций в 496×496, прозрачные поля до 512×512, WebP без потерь. Результаты проверки и статус — в реестре.
