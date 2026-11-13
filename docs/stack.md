# Стек и инструменты

Только открытые и бесплатные инструменты.

## Скиллы для Claude Code (лежат в `.claude/skills/`)

Агент подхватывает их сам, когда работает в этом репозитории.

| Набор | Откуда | Для чего | Папки |
|---|---|---|---|
| **Impeccable** (главный) | github.com/pbakaus/impeccable @ c4cd192 | типографика, цвет, сетка, UX-аудит | `impeccable` |
| **Hallmark** (главный) | github.com/Nutlope/hallmark @ 04977e1 | новые страницы без «ИИ-вида», линтер шаблонных приёмов (sloplint) | `hallmark` |
| Unslop | github.com/heydamir/unslop @ 97daa3e | чистит готовый интерфейс от фиолетовых градиентов, свечения, эмодзи | `unslop` |
| Emil Kowalski skills | github.com/emilkowalski/skills @ f7ce8c0 | анимации и полировка интерфейса | `animate`, `improve-animations`, `review-animations`, `choreograph`, `gestures`, `emil-design-eng` и др. |
| Superpowers | github.com/obra/superpowers @ 22f0b46 | дисциплина: план → реализация → проверка | `brainstorming`, `writing-plans`, `executing-plans`, `verification-before-completion` и др. |
| Karpathy guidelines | github.com/multica-ai/andrej-karpathy-skills @ 2c60614 | меньше лишнего кода, точечные правки | `karpathy-guidelines` |

Обновить: заново скопировать папку скилла из репозитория автора.

Что не ставили: хуки (Impeccable design hook, Hallmark lint hook, SessionStart-хук Superpowers). Скиллы работают и без них.

## Стек

- Простые сайты и КП: чистый HTML + CSS + JS, без фреймворков.
- Продукты и кабинеты: React + Vite.
- 3D и эффекты: Three.js.
- Ролики про продукт: Remotion (видео собирается кодом).

## Оформление

- Шрифты из Google Fonts с кириллицей: Manrope, Unbounded, Onest, Golos.
- Иконки: Lucide, Hugeicons, Phosphor.
- Картинки: Higgsfield (Nano Banana, GPT Image).

## Проверка

- Playwright: скриншоты на телефоне и компьютере, проверка ссылок и форм.
- PageSpeed Insights: скорость.
