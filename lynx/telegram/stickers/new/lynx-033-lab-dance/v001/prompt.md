# Танцующая рысь в лабораторном халате — вариант 1

ID: lynx-033-v001. Родитель: lynx-033. Дата: 2026-10-12.
Генератор: встроенный image_gen; transparent_background: true.

Запрос: сохранить танцующую рысь оригинала 10, заменить одежду лабораторным халатом, убрать очки, вместо звёздочек — C, H, Ti, Cl, Mo.

## Референсы

1. [Оригинал 10](../../../orig/10xf09f95ba.webp) — основной объект редактирования, поза и эмоция.
2. [Оригинал 1](../../../orig/1xf09f9898.webp) — зелёные глаза и внешность.

referenced_image_paths: абсолютные пути этих файлов в указанном порядке.

## Точный промпт

```text
Use case: precise-object-edit. Edit the FIRST reference sticker, preserve its original character, composition and exuberant dancing pose AS CLOSELY AS POSSIBLE. Second reference supplies the same lynx's green eyes previously hidden behind sunglasses. Original sticker: orange spotted female lynx dancing wildly, one forepaw raised above head, other forepaw lowered, one hind leg kicked high sideways with pink pads facing viewer, other hind paw planted, short tail, head tilted, mouth wide open with red tongue in exuberant joy. Preserve that EXACT dynamic pose, proportions, fluffy cream cheeks and chest, dark ear tufts, orange fur and original 2D cartoon linework. Requested changes ONLY: 1. Replace purple sparkly disco jacket with a WHITE LABORATORY COAT, open at front over cream furry chest, small notched lapels, simple buttons and small lab coat pockets, sleeves following original arms and flaring coat hem following dance motion. No other clothes or new props. 2. REMOVE sunglasses completely. Show expressive joyful GREEN lynx eyes with natural original-pack lashes and brows, consistent with exuberant open-mouth expression. No eyewear anywhere. 3. REMOVE ALL floating stars and sparkle symbols and replace them with exactly FIVE floating chemical element symbols: 'C', 'H', 'Ti', 'Cl', 'Mo'. Exact capitalization: uppercase C; uppercase H; uppercase T plus lowercase i; uppercase C plus lowercase l (letter ell); uppercase M plus lowercase o. Each symbol appears ONCE, separately around lynx in available transparent space, large bold legible upright lettering with dark contour and white sticker edging. These are chemical symbols only, NOT periodic table tiles, not formulas, no atomic numbers, no boxes, no stars. Keep text clear of face, ears and paws. No other written text. Preserve original's bright cartoon 2D, warm orange palette, dark-brown outlines, soft shading, clean white outer sticker outline. No photorealism or 3D. Entire character including raised paw, both ear tufts, kicked hind paw, coat hems, tail and all five symbols safely within square frame with transparent margins on EVERY side. True transparent alpha background, no painted checkerboard. No background, floor, lab scenery, additional characters, glasses, test tubes, equipment or watermark. Final target PNG/WebP 512x512 under 512000 bytes. Variant 1: closest possible match to original dance silhouette and wide-open delighted mouth. Lab coat follows jacket silhouette, coat tails slightly longer. Arrange five chemical symbols around the silhouette in dark teal-blue lettering, sufficiently large to read at sticker size.
```

## Правка кадрирования

Цель: [source-initial.png](source-initial.png). image_gen; referenced_image_paths: первичный результат; transparent_background: true. Итог: source.png.

```text
Edit ONLY framing and edge cleanup. Preserve EXACT dancing pose, face, green eyes, open mouth, white lab coat, fur, colors and all FIVE chemical symbols C, H, Ti, Cl, Mo with their exact lettering, placement and colors. Zoom the ENTIRE composition out so it occupies at most 85 percent of square width and height. Restore full raised top paw and ear tuft that touch/cross top canvas edge; give generous transparent margin above them and on all other sides. Every symbol fully contained. Clean stray flecks outside white sticker border. True transparent alpha background. No other changes, no glasses, no stars, no additional text.
```

## Файлы и экспорт

[Исходник](source.png), [PNG](sticker.png), [WebP](sticker.webp). FFmpeg: Lanczos до 496×496, прозрачные поля до 512×512; WebP без потерь. Исходники без перекодирования. Превью на [белом](preview-white.png) и [тёмном](preview-0x202020.png) фоне. Проверка — в [реестре](../../../registry.md).
