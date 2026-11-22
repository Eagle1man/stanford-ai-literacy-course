# Введение в искусственный интеллект — преподавательский пакет

Курс из **двух дополнительных тем** к основным пяти лекциям: **обучение с подкреплением** (лекция 6) и **RAG и агенты** (лекция 7). По материалам [Stanford CS221 Autumn 2025](https://stanford-cs221.github.io/autumn2025/), [Stanford CS234 Winter 2026](https://web.archive.org/web/2026/https://web.stanford.edu/class/cs234/) и [Stanford CS224N Winter 2026](https://web.archive.org/web/2026/https://web.stanford.edu/class/cs224n/).

## Лекция 6 — Обучение с подкреплением

[Презентация (PPTX)](lecture-06/presentation.pptx) · [Конспект для преподавателя (PDF)](lecture-06/conspect.pdf) · [Проверочный тест](lecture-06/test.html)

Темы: агент и среда, MDP, Q-learning, исследование против использования, reward hacking, RLHF. Примеры из материалов CS221 (ненадёжный трамвай) и CS234.

## Лекция 7 — RAG и агенты

[Презентация (PPTX)](lecture-07/presentation.pptx) · [Конспект для преподавателя (PDF)](lecture-07/conspect.pdf) · [Проверочный тест](lecture-07/test.html)

Темы: эмбеддинги, нарезка документов, гибридный поиск, цикл агента, инструменты, оценка качества RAG, ИИ-судья. Основа — CS224N Winter 2026 (лекции 10–11).

## Формат

- **Презентация PowerPoint** — 22 слайда, без кода и формул. В заметках докладчика (speaker notes) — подробное объяснение того, что говорить, куда показывать и на что обращать внимание.
- **Конспект PDF** — те же заметки по слайдам: можно читать рядом с презентацией.
- **Тест HTML** — 10 вопросов на понимание с самопроверкой. Открывается в браузере двойным щелчком, интернет не нужен. Режим автопроверки: открыть с хешем `#selftest`.

Самопрогон: все тесты проверены в headless Chrome — 10 из 10 на каждой лекции.

## Источники

- Stanford CS221 Autumn 2025 — исполняемые материалы `reinforcement_learning.py`, `policy_gradient.py`
- Stanford CS234 Winter 2026 (снимок от 05.11.2026) — расписание обучения с подкреплением
- Stanford CS224N Winter 2026 (снимок от 05.11.2026) — лекции 10 (Agents, Tool Use, and RAG) и 11 (Benchmarking and Evaluation)
- Sutton & Barto, *Reinforcement Learning: An Introduction* (2-е издание)