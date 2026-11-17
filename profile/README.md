![OssPinchana](https://github.com/user-attachments/assets/ee3adc45-b909-4ef2-acd8-14eaaa467a27)

# Пінчана 🐈 (OSS)

**Пінчана** — відкрита платформа для завантаження медіа з TikTok, Instagram, YouTube Shorts, YouTube Music, Spotify, SoundCloud, Deezer, Threads, Twitter/X та інших сервісів. Тут зібрані офіційний вебклієнт, API та документація Пінчани.

## Головні проєкти

### [pinchana-web](https://github.com/Pinchana/pinchana-web)

Офіційний мінімалістичний AMOLED-вебклієнт Пінчани. Працює з Pinchana API, підтримує попередній перегляд і завантаження медіа, Cloudflare Turnstile та захищені браузерні сесії.

**Спробувати:** [pinchana.cc](https://pinchana.cc)

### [pinchana-api](https://github.com/Pinchana/pinchana-api)

Монорепозиторій Пінчани зі шлюзом FastAPI, скраперами, спільним кодом, DLP і конфігурацією Docker Compose. Шлюз визначає платформу та викликає відповідний скрапер у своєму процесі. Усі компоненти API зберігаються як звичайні каталоги, тому для отримання всього коду достатньо `git clone`.

**API:** [api.pinchana.cc](https://api.pinchana.cc)

## Документація

[pinchana-docs](https://github.com/Pinchana/pinchana-docs) — офіційна документація для Pinchana Web і Pinchana API, побудована на Astro Starlight.

**Доступна на:** [docs.pinchana.cc](https://docs.pinchana.cc).

## Компоненти API

- [Шлюз FastAPI](https://github.com/Pinchana/pinchana-api/tree/main/pinchana-server) маршрутизує запити та віддає медіа з кешу.
- [Спільний код](https://github.com/Pinchana/pinchana-api/tree/main/pinchana-core) містить моделі, кешування, музичні утиліти та керування VPN.
- [Скрапери](https://github.com/Pinchana/pinchana-api#supported-modules) встановлюються в один образ зі шлюзом. У списку наведені підтримувані джерела та маршрути.
- [DLP](https://github.com/Pinchana/pinchana-api/tree/main/pinchana-dlp) — додатковий сервіс приватних завантажень з ізольованими воркерами.

[pinchana-pinterest](https://github.com/Pinchana/pinchana-pinterest) — окремий сервіс для завантаження медіа з Pinterest-пінів.

Дякуємо кожному, хто підтримує проєкт фінансово, користується ним і допомагає робити Пінчану кращою 💚

<div align="center">

[ [Пінчана 🐈](https://s.co.ua/pinchana) ] [ [Задонатити](https://xxanqw.pp.ua/donate) ] [ [Patreon](https://www.patreon.com/xxanqw/membership) ]

</div>
