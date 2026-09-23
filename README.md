# Reversible Context Memory / Обратимая память контекста

Концепция обратимого селективного сжатия истории ИИ-чата: полная история остаётся канонической, а перед каждым запросом из отправляемой копии детерминированно исключаются наименее релевантные разрешённые фрагменты. Исключённый текст можно точно восстановить по адресным указателям через MCP-инструменты того же чат-приложения.

The concept of reversible selective compression for AI chat history: the full history remains canonical, while the least relevant permitted fragments are deterministically omitted from the outgoing copy before each request. Omitted text can be recovered precisely through addressable pointers and MCP tools provided by the same chat application.

## Статьи / Articles

- [Русская версия — оригинал](articles/ARTICLE_RU.md)
- [Русская версия v3 — литературная редакция концепции](articles/ARTICLE_RU_V3.md)
- [English version — translation](articles/ARTICLE_EN.md)

Русский текст является исходным. Английская версия — только перевод; при смысловых расхождениях приоритет имеет русская версия.

The Russian text is the original. The English version is a translation only; if meanings diverge, the Russian version is authoritative.

## Статус / Status

Новая архитектура находится на стадии технического проектирования. Бенчмарки и экспериментальное подтверждение её эффективности пока отсутствуют; опубликованный `ARTICLE_RU.md` сохранён как предыдущая версия.

The new architecture is in technical design. Benchmarks and experimental validation of its effectiveness are not yet available; the published `ARTICLE_RU.md` remains the previous version.

Обсуждение, замечания и результаты независимых экспериментов: [GitHub Issues](https://github.com/talgatiko/reversible-context-memory/issues).

Discussion, objections, and independent experimental results: [GitHub Issues](https://github.com/talgatiko/reversible-context-memory/issues).

## Авторы / Authors

Алексей Добрый, Талгат Зайниев, кот Вервульф и человечество через GPT-5.6 Sol.

## Лицензия / License

Материалы распространяются по лицензии [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).

The materials are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).
