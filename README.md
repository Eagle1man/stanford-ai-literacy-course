# Введение в искусственный интеллект — преподавательский пакет

Курс из **пяти лекций по 90 минут**, по материалам [Stanford CS221 Autumn 2025](https://stanford-cs221.github.io/autumn2025/).

Аудитория — практики без подготовки по машинному обучению; преподаватель тоже не обязан быть специалистом по ML: по каждому слайду есть готовый текст, а по каждому механизму — объяснение, аналогия и схема для доски.

## Лекции

| № | Тема | Слайдов | Материалы |
|---|---|---|---|
| 1 | Поиск, планирование и принятие решений | 23 | [папка](lecture-01/) · [слайды PDF](lecture-01/presentation.pdf) · [игра](lecture-01/game.html) |
| 2 | Как модели учатся и рассуждают при неполной информации | 24 | [папка](lecture-02/) · [слайды PDF](lecture-02/presentation.pdf) · [игра](lecture-02/game.html) |
| 3 | Большие языковые модели, трансформеры и объяснимость ИИ | 26 | [папка](lecture-03/) · [слайды PDF](lecture-03/presentation.pdf) · [игра](lecture-03/game.html) |
| 4 | Игры: состязательный поиск и стратегии | 22 | [папка](lecture-04/) · [слайды PDF](lecture-04/presentation.pdf) · [игра](lecture-04/game.html) · [викторина](lecture-04/test.html) |
| 5 | Логика: знание, вывод и рассуждение | 22 | [папка](lecture-05/) · [слайды PDF](lecture-05/presentation.pdf) · [игра](lecture-05/game.html) · [викторина](lecture-05/test.html) |

## PDF

**Для студентов** — презентации в PDF, читаются с телефона без сторонних приложений:

[lecture-01](lecture-01/presentation.pdf) · [lecture-02](lecture-02/presentation.pdf) · [lecture-03](lecture-03/presentation.pdf) · [lecture-04](lecture-04/presentation.pdf) · [lecture-05](lecture-05/presentation.pdf)

**Для преподавателя** — конспекты в PDF:

[lecture-01](lecture-01/conspect.pdf) · [lecture-02](lecture-02/conspect.pdf) · [lecture-03](lecture-03/conspect.pdf) · [lecture-04](lecture-04/conspect.pdf) · [lecture-05](lecture-05/conspect.pdf)

PDF пересобираются вместе с лекциями (шаг сборки `gen_pdfs.ps1`): если меняется `presentation.pptx` или `conspect.docx`, PDF нужно пересобрать.

## Что в папке каждой лекции

| Файл | Назначение |
|---|---|
| `presentation.pptx` | Слайды на 90 минут, показываются на занятии |
| `presentation.pdf` | Те же слайды в PDF — для чтения с телефона |
| `slide-script.docx` | Что говорить по каждому слайду |
| `conspect.docx` | Конспект для подготовки: механизм, ограничения, «почему это важно» |
| `conspect.pdf` | Конспект в PDF |
| `diagrams.docx` | Схемы для доски: что рисовать, в каком порядке, какой вывод |
| `analogies.docx` | Аналогии с границами применимости |
| `interview-qa.docx` | Вопросы интервью с эталонными ответами |
| `common-mistakes.docx` | Типичные заблуждения и как их исправить |
| `bridge-next.docx` | Связка со следующей лекцией (в пятой — завершение курса) |
| `game.html` | Мини-игра на 10–11 сценариев с разбором каждого ответа |
| `test.html` | Викторина на 10 вопросов (лекции 4 и 5) |

Корневые документы: [README.docx](README.docx), [CURRICULUM_MAP.docx](CURRICULUM_MAP.docx) (сверка с программой CS221), [SOURCES.docx](SOURCES.docx), [ROADMAP.docx](ROADMAP.docx), [STATE.docx](STATE.docx), [REPORT.docx](REPORT.docx), [TASK.md](TASK.md).

## Как открыть

HTML-файлы (`game.html`, `test.html`) открываются двойным щелчком в любом браузере, **интернет не нужен**. Документы Word и презентации — в Microsoft Office или совместимых редакторах, а `.pptx` с телефона без такого приложения откроется как каша символов — поэтому для чтения с телефона есть `presentation.pdf` и `conspect.pdf`: они открываются любым встроенным просмотрщиком.

## Самопроверка

У каждого HTML-файла есть режим автопроверки: откройте файл с хешем `#selftest` в адресной строке,

```
lecture-05/game.html#selftest
```

и он пройдёт себя сам, а в конце напечатает строку вида `SELFTEST score=2200 correct=11 total=11`. Для всех пяти игр и двух викторин этот режим прогнан в headless Chrome: все вопросы отвечены, счёт максимальный.

## Источники

Основа — официальные материалы Stanford CS221 Autumn 2025, ветка `autumn2025`, коммит `d5752037fd67c0824f7330ad1a7b40bd1d992807`. Полный перечень с датами доступа — в [SOURCES.docx](SOURCES.docx).
