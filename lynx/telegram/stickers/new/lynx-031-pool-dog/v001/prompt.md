# Рысь и овчарка у бассейна — первый пробный вариант

ID: lynx-031-v001. Родитель: lynx-031. Дата: 2026-10-12.
Генератор: встроенный image_gen; transparent_background: true.
По запросу пользователя создан только один вариант для предварительного просмотра.

## Референсы

1. [Фото мема](reference-meme.png) — композиция и взаимодействие.
2. [Оригинал 5](../../../orig/5xf09fa4a8.webp) — пропорции рыси.
3. [Оригинал 16](../../../orig/16xf09f9892.webp) — внешность и мимика.

referenced_image_paths: абсолютные пути этих трёх изображений в указанном порядке. Фото при генерации передано из C:/Users/Hozre/AppData/Local/Temp/codex-clipboard-ioyQ4Z.png, затем сохранено рядом.

## Точный промпт

```text
Use case: illustration-story. Create ONE static Telegram sticker based on reference image 1, the photo of a tiger in a round pool facing a German shepherd. Replace ONLY the tiger character with the original female orange spotted LYNX established by references 2 and 3. Image 1 guides scene, pose and interaction; images 2 and 3 guide exact lynx identity and cartoon drawing style. On the RIGHT, our lynx sits chest-deep in water inside a compact round rigid-sided pool with a gray-blue rim. Her two forepaws rest together on the near-left pool edge, shoulders slightly hunched, head tilted forward. On the LEFT outside the pool, a German shepherd is shown in side / rear three-quarter view, black-and-tan coat, upright pointed ears, long canine muzzle, turned toward the lynx. Their faces close together, making direct eye contact. Reproduce the photo's awkward funny stillness and spatial relationship. Lynx has a fixed, slightly bewildered and suspicious stare as if trying to understand this dog, closed mouth, NO smile or bared teeth. Dog calm and curious. No fight, fear or aggression. Keep the lynx identity: warm orange spotted fur, green eyes, fluffy cream cheeks and chest, long dark ear tufts, rounded feline paws. It is a LYNX, no tiger stripes. Draw dog in same cartoon style. Exactly TWO animals, one lynx and one German shepherd. Compact composition with LARGE readable faces. Pool water has a few simple glints, no complex reflections. Show sufficient pool rim and water to make the scene immediately recognizable, but don't let pool dominate. Whole dog, ears, paws and pool silhouette safely within square with transparent margins. Bright 2D cartoon in original sticker pack style, dark-brown outlines, soft gradients and shading, clean continuous white outer sticker border. True transparent alpha background outside the animals and pool. No fence, trees, ground, scenery or photographic background. No text, captions, watermark, photorealism or 3D. Target final PNG/WebP export 512x512 under 512000 bytes. Only one image.
```

## Результат

[Первичный результат](source-initial.png) сохранён. По следующему запросу пользователя исправлены лапы и кадрирование, подготовлены экспорты.

## Доработка и экспорт

Первичный результат сохранён как [source-initial.png](source-initial.png). Правка через image_gen, transparent_background: true; referenced_image_paths: первичный результат. Итог — [source.png](source.png).

```text
Edit this sticker with targeted corrections, preserve exact animals, faces, colors and cartoon style. 1. Move the two lynx forepaws onto the pool's FRONT TOP RIM: paws visibly overlap and hang down OUTSIDE the gray metal rim, cream toes covering the outside wall just below rim, forearms lean on rim. Move lynx forward inside pool enough to physically reach that rim. No paws floating in water. 2. Restore whole rounded right end of pool which was cut off, a natural continuous oval pool, and zoom entire composition out to fit within central 85 percent of square canvas, transparent space on ALL sides. 3. Clean all stray white flecks outside silhouette, smooth narrow white sticker outline. Keep German shepherd left looking at lynx right, close eye contact, no extra objects, no text. Actual transparent alpha background.
```

[PNG 512×512](sticker.png), [WebP 512×512](sticker.webp). Экспорт FFmpeg: Lanczos до 496×496 с сохранением пропорций, прозрачные поля до 512×512, WebP без потерь. Проверка и статус — в [реестре](../../../registry.md).
