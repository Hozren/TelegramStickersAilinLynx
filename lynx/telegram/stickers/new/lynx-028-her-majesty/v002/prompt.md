# Её Рысье Величество — вариант 2

ID: `lynx-028-v002`. Родитель: `lynx-028`. Дата: 2026-10-12.
Генератор: встроенный `image_gen`; `transparent_background: true`.

Файлы: [исходник](source.png), [PNG 512×512](sticker.png), [WebP 512×512](sticker.webp). [Реестр](../../../registry.md).

## Референсы

- [Сидячая поза и пропорции](../../../orig/5xf09fa4a8.webp).
- [Прищур и высокомерная мимика](../../../orig/16xf09f9892.webp).
- [Пропорции персонажа в одежде](../../../orig/10xf09f95ba.webp).

Параметр `referenced_image_paths`: эти три оригинала в указанном порядке (абсолютные пути внутри проекта). Отдельный вызов для каждого варианта.

## Точный промпт

```text
Use case: illustration-story.
Create ONE new static Telegram sticker titled conceptually «Её Рысье Величество» (NO text in the image).
The three input images are visual REFERENCES only for the exact original lynx identity and sticker drawing style, not edit targets. Image 1 establishes seated rounded feline proportions, spotted orange fur and expressive eyebrow; image 2 establishes haughty half-closed green eyes, cream fluffy cheeks and muzzle; image 3 establishes stylized dressed full-body proportions. Match this existing character as closely as possible.
Subject: the SAME orange spotted FEMALE lynx dressed as British Queen Elizabeth II. Keep her original feline face, orange fur colors, big green eyes, cream fluffy cheeks and chest, large pointed ears with black tufts, short lynx tail and rounded cartoon proportions. No human face or character redesign.
Costume: elegant soft lavender dress in Elizabeth II's style, delicate golden royal crown with gemstones BETWEEN the ears, classic THREE-strand pearl necklace, small gemstone royal brooch on chest, neat white gloves shaped as rounded cartoon cat paws.
Pose and action: seated regally, torso straight and very slightly leaning back, chin slightly raised, shoulders open. One gloved forepaw delicately holds a thin clear crystal wine glass by its LONG STEM, with DARK RED WINE inside. She is actually taking a SMALL PRIM SIP: rim touches lips, glass slightly tilted, wine level physically plausible. Glass must not obscure eyes or most of muzzle. Other gloved forepaw rests aristocratically on her knee, little outer digit conspicuously extended. Exactly two forepaws, coherent glove digits and glass grip. Show seated bent knees under dress, no throne or furniture needed.
EXPRESSION IS MOST IMPORTANT: half-narrowed green eyes, arrogantly raised eyebrows, calm condescending prim expression, a faint smug smile at the visible corner of her mouth while sipping. She glances down her nose at everyone as if judging their manners. British aristocratic restraint, subtle snobbery, comic haughtiness, complete self-satisfaction; not angry, not sad, not broadly laughing.
Art: original pack's bright 2D cartoon, thick dark-brown outlines, warm orange fur with spots, soft shadows and gradients, expressive slightly exaggerated face, clean white outer sticker border. No photorealism, no 3D.
Composition: ONE character filling most of a square image, face large enough to read at sticker size. Full crown, both tufted ears, seated body, paws, tail and entire wine glass all comfortably inside frame with a transparent margin on all sides. Genuine transparent alpha background, no checkerboard painting, no palace, scenery, floor, background, extra decoration, text, captions or watermark. Clean silhouette and edges, no stray fragments. Output PNG; target final export 512x512 pixels, under 512000 bytes.
Variant 2: a distinct more frontal seated pose, face angled slightly toward image left to sip from the glass on image left. Chin a little higher, both green eyes clearly visible in an especially haughty half-lidded sideways glance. Resting gloved paw and extended little digit clearly silhouetted against the lavender knee. Preserve all other requirements.
```


## Уточнение жеста и кадрирования

Первичный результат: [source-initial.png](source-initial.png). Цель правки — этот файл; `transparent_background: true`. Итог: `source.png`.

```text
Edit this sticker with only these targeted corrections. Preserve the exact lynx identity, haughty half-lidded green eyes, facial expression, sipping action, crown, lavender dress, pearls, brooch, wine glass and pose. On the white-gloved paw RESTING ON THE KNEE, extend its outermost little digit out sideways in a clearly visible aristocratic pinky gesture; keep the other digits resting on the knee and feline cartoon anatomy. Zoom the entire composition out so it occupies at most 88 percent of the square canvas height and width. Restore complete ear tuft and white border if clipped; all ears, crown, tail, paws, dress and glass must be fully within the canvas with a generous transparent margin on EVERY side. Clean up stray white specks outside the intentional continuous white sticker outline. Genuine transparent alpha background. No new objects or text.
```

## Экспорт и проверка

Исходники генератора сохранены без перекодирования. Экспорт FFmpeg: `scale=496:496:force_original_aspect_ratio=decrease:flags=lanczos,pad=512:512:(ow-iw)/2:(oh-ih)/2:color=0x00000000,format=rgba`; WebP: `-c:v libwebp -lossless 1 -frames:v 1`.

Размеры 512×512, вес ниже 512 000 байт; проверены прозрачные и непрозрачные пиксели PNG, альфа-канал и один кадр WebP. Выполнен просмотр на [белом](preview-white.png) и [тёмном](preview-0x202020.png) фоне. Статус — ready; выбор пользователя пока не сделан. Подробные параметры в реестре.
