# IMAGES_PROMPTS — изображения для сайта

Все картинки кладутся в `images/`, подключаются в `index.html`.
Компонент для вставки: `<figure class="scene-photo"><img src="images/..." alt="..." /></figure>`.

## Общий стиль (добавлять к каждому промпту)

> Dark charcoal palette (#111–#181818), restrained deep red (#d13521) and mint (#9ee8c1) accent
> lighting, slightly stylized cinematic 3D illustration, matte materials, soft volumetric lighting,
> cinematic depth of field, premium modern portfolio aesthetic, no text, no logos, no watermark.

Характер лиса (единый персонаж во всех сценах):

> A slim male anthropomorphic fox, dark brown-black fur, light gray-white markings,
> white paws and tail tip, subtle deep red markings.

## Статус

| Сцена | Изображение | Статус |
|---|---|---|
| 01 — Приветствие | `images/fox-studio.jpg` | ✅ готово |
| 02 — Работа | `images/work-office.jpg` | ✅ готово |
| 03 — Путь разработчика | — | нужно сгенерировать |
| 04 — Пет-проекты | — | опционально (сцена и так плотно заполнена карточками) |
| 05 — Стриминг | — | нужно сгенерировать |
| 06 — Хобби | — | нужно сгенерировать (7 маленьких картинок для карточек) |
| 07 — Контакты | — | нужно сгенерировать |

---

## Готово (промпты сохранены для переиспользования стиля)

### Scene 01 — `images/fox-studio.jpg`

*(промпт восстановлен по готовой картинке — оригинальный был у тебя)*

> "A cozy dark studio room at night. A slim male anthropomorphic fox with dark brown-black fur
> and light gray-white markings sits at a desk with a computer, surrounded by a coding and
> streaming environment: monitors with code and a live stream interface, warm desk lights,
> headphones. Warm practical lights, subtle red and mint accents, dark charcoal environment,
> slightly stylized cinematic 3D, no text, no logos, no watermark."

### Scene 02 — `images/work-office.jpg`

> "A slim male developer standing by a large window in a modern dark office, city lights outside,
> displays with code nearby. Dark charcoal palette, restrained red and mint accents, cinematic
> soft lighting, slightly stylized, no text, no logos, no watermark."

---

## Нужно сгенерировать

Формат для карточек сцен — альбомный (3:2 или 4:3), вёрстка обрежет под `aspect-ratio: 3/2`.

### Scene 03 — Путь разработчика (таймлайн карьеры)

> "A cinematic miniature railway / road through a dark modern world representing a software
> developer career. A slim male anthropomorphic fox walks beside a sequence of distinct
> stations representing freelance work, smart home engineering, software development,
> analytics, culture and tickets. Each station has its own subtle visual identity while
> remaining in the same dark cozy world. Red and mint accent lights, warm atmospheric
> lighting, stylized 3D diorama, cinematic depth of field, no text, no logos, no watermark."

### Scene 05 — Стриминг

> "A cozy dark streamer room at night. A slim male anthropomorphic fox with dark brown-black
> fur and light markings sits in front of a gaming PC and multiple monitors, wearing a headset
> and streaming. One screen suggests a horror game, another shows a live streaming interface,
> microphone and small desk lights nearby. The mood is relaxed and playful, representing
> streaming as a hobby, recreation and communication practice. Warm dark room, subtle red and
> mint accents, atmospheric cinematic lighting, slightly stylized 3D miniature diorama,
> premium modern aesthetic, no text, no logos, no watermark."

### Scene 07 — Контакты (финал)

> "A quiet cinematic final scene in the same dark cozy miniature world. A slim male
> anthropomorphic fox stands near a warm desk light and a simple communication terminal,
> looking toward an open path leading outside. The atmosphere is calm, creative and welcoming,
> suggesting an invitation to get in touch. Dark charcoal colors, warm lamp light, subtle red
> and mint accents, cinematic depth of field, high-quality stylized 3D diorama, peaceful
> portfolio ending, no text, no logos, no watermark."

### Scene 04 — Пет-проекты (опционально)

> "A cozy dark miniature creative technology workshop filled with personal software projects.
> A slim male anthropomorphic fox works on several projects at once: a glowing Twitch bot
> service hub, a small Unity game on a monitor, an image-resizing machine, open-source code
> displayed on screens, IoT boards, cables and tiny server racks. The scene feels like a
> creative inventor's workshop rather than a corporate office. Dark charcoal palette, red and
> subtle mint accents, cinematic 3D diorama, soft warm lighting, no text, no logos, no watermark."

### Scene 06 — Хобби-карточки (7 маленьких, формат 1:1)

Общий префикс для всех семи:

> "Small square cozy dark illustration for a hobby card, single centered subject,
> dark charcoal palette, red and mint accent lights, slightly stylized cinematic 3D,
> no text, no logos, no watermark."

1. **Стриминг** — "An anthropomorphic fox with a headset in front of a streaming setup with a microphone and monitors."
2. **Рисование и анимация** — "An anthropomorphic fox drawing on a graphics tablet, sketches and framed artworks around."
3. **3D-моделирование** — "An anthropomorphic fox sculpting a glowing 3D holographic model at a desk."
4. **Вкусно поесть** — "An anthropomorphic fox enjoying a beautifully plated meal at a cozy dark table."
5. **Чай** — "An anthropomorphic fox pouring tea from a teapot into a cup, steam rising, tea cans and cups around."
6. **Природа и движение** — "An anthropomorphic fox riding a bicycle through a green park in the evening."
7. **Игры** — "An anthropomorphic fox with a game controller in front of a glowing monitor."

---

## Исходный план: полноэкранные фоны сцен

Промпты выше изначально задумывались как миниатюрные диорамы на весь экран (фон сцены под
текстом). Если захочешь такой вариант вместо карточек — они подходят без изменений, включая
две уже готовые сцены:

- Scene 01: "A dark cozy miniature diorama representing a modern developer's personal workspace,
  slightly stylized 3D, matte materials, cinematic soft lighting. A slim male anthropomorphic fox
  … sitting at a desk with a laptop and two monitors. Tiny hints of code, Twitch interface and
  creative tools around the room. Warm practical lights, subtle red and mint-green accents,
  dark charcoal environment, premium modern portfolio aesthetic, cinematic depth of field,
  no text, no logos, no watermark."
- Scene 02: "A dark futuristic miniature city representing backend engineering. A slim male
  anthropomorphic fox developer walks through a tiny city made of server buildings and glowing
  data routes. Docker containers represented as modular buildings, Kafka as flowing streams of
  light, APIs as interconnected roads, Python and FastAPI suggested through abstract visual
  motifs. Dark charcoal palette, restrained red and mint accents, cinematic soft volumetric
  lighting, sophisticated 3D diorama, matte materials, no text, no logos, no watermark."
- Scene 06 (общая, если карточки не понравятся): "A stylish cozy personal hobby room presented
  as a miniature gallery. A slim male anthropomorphic fox moves between small visual scenes
  representing his hobbies: streaming, digital drawing, 3D modeling, video editing, gaming,
  cycling, swimming, nature and enjoying good food. Include small framed artworks, a 3D model
  on a desk, a bicycle helmet, game controller, sketchbook, headphones and a window looking
  onto greenery. Dark charcoal palette, warm lighting, subtle red and mint accents, cinematic
  depth of field, high-quality stylized 3D diorama, personal and inviting, no text, no logos,
  no watermark."
