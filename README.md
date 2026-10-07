<div align="center">

# Igor Zatochniy

### SEO Automation Engineer · Go Developer

**Technical SEO · SEO Automation · Go · Web Crawling · PostgreSQL · REST APIs**

<p>
  <a href="https://igor-zatochniy.github.io/portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-00ADD8?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://t.me/zatochniy">
    <img src="https://img.shields.io/badge/Telegram-229ED9?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>
  <a href="mailto:igor.zatochniy@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

</div>

---

## Про мене

Поєдную вісім років досвіду в digital marketing та SEO з розробкою на Go. Створюю інструменти для технічного SEO-аудиту, web crawling, аналізу даних і автоматизації повторюваних перевірок.

Мій фокус — перетворювати SEO-завдання на зрозумілі workflows: зібрати дані, виявити технічні проблеми й підготувати звіт для подальших рішень. Розумію потреби SEO-команди та можу втілити їх у власному інструменті.

У розробці приділяю увагу надійності: automated tests, явному error handling, graceful shutdown, observability та відновленню після збоїв.

## SEO automation у дії

У [SEO Auditor](https://github.com/igor-zatochniy/seo-auditor) вже реалізовано:

- **Технічний аудит:** Site Crawl або список URL, HTTP-статуси, redirects, metadata, canonical, robots directives та structured data.
- **Аналіз структури:** XML sitemaps, граф внутрішніх посилань, click depth, broken links та orphan candidates у межах зібраного crawl.
- **Звіти для роботи:** browser UI з пошуком і фільтрами, історія запусків у PostgreSQL та HTML/CSV export для подальшого аналізу.

[Можливості та запуск](https://github.com/igor-zatochniy/seo-auditor#швидкий-старт-windows) · [Site Crawl](https://github.com/igor-zatochniy/seo-auditor#site-crawl) · [Межі статичного аналізу](https://github.com/igor-zatochniy/seo-auditor#межі-статичного-аналізу)

## Основні проєкти

| Проєкт | Завдання / користь | Engineering Highlights | Де перевірити |
|---|---|---|---|
| **CryptoPulse Telegram Bot** | Telegram-бот для відстеження цін на криптовалюти й надсилання персональних сповіщень | Durable Telegram inbox · transactional reply outbox · leased/fenced delivery · graceful shutdown | [Live Bot](https://t.me/btc_eth_usdt_bot) · [Runbook](https://github.com/igor-zatochniy/cryptopulse-telegram-bot/blob/main/docs/operations.md) · [Repository](https://github.com/igor-zatochniy/cryptopulse-telegram-bot) |
| **SEO Auditor** | Локальний інструмент технічного SEO-аудиту: Site Crawl, аналіз посилань, browser UI та HTML/CSV reports | Bounded worker pool · PostgreSQL leases/fencing · atomic crawl persistence · robots.txt policies · SSRF hardening | [Quick Start](https://github.com/igor-zatochniy/seo-auditor#швидкий-старт-windows) · [Site Crawl](https://github.com/igor-zatochniy/seo-auditor#site-crawl) · [Repository](https://github.com/igor-zatochniy/seo-auditor) |
| **Site Checker** | Сервіс за розкладом перевіряє доступність сайтів, зберігає історію перевірок і створює сповіщення в разі збоїв | PostgreSQL job leases/fencing · RabbitMQ confirms/DLQ/retries · transactional alert outbox · Kubernetes manifests with optional KEDA worker scaling | [Interactive API Docs](https://igor-zatochniy.github.io/site-checker/) · [Demo](https://github.com/igor-zatochniy/site-checker/blob/main/docs/demo.md) · [Repository](https://github.com/igor-zatochniy/site-checker) |
| **Audiobook TTS Reader** | Windows-застосунок для озвучення електронних книг із безпечним відновленням прогресу та локальним REST/SSE API | Streaming UTF-8 chunking · token-protected loopback REST/SSE API · coverage-guided fuzzing · validated progress recovery | [API](https://github.com/igor-zatochniy/tts-reader#local-rest-api) · [Fuzz Tests](https://github.com/igor-zatochniy/tts-reader/blob/main/chunk_reader_fuzz_test.go) · [Repository](https://github.com/igor-zatochniy/tts-reader) |

## Ключові навички

**Technical SEO:** `Crawling` · `HTTP & Redirects` · `Canonical` · `robots.txt` · `XML Sitemaps` · `Metadata` · `Internal Link Analysis` · `Structured Data`

**Automation:** `HTML Parsing` · `API Integrations` · `Scheduled Jobs` · `HTML/CSV Reports`

**Backend:** `Go` · `net/http` · `REST APIs` · `context.Context` · `Concurrency` · `PostgreSQL` · `SQL`

**Reliability & Quality:** `Unit Testing` · `Integration Testing` · `Race Detector` · `Error Handling` · `Structured Logging` · `Graceful Shutdown`

## Технології

**Applied in Projects:** `Docker` · `RabbitMQ` · `Kubernetes` · `KEDA` · `Prometheus` · `OpenAPI` · `Testcontainers` · `GitHub Actions`

**Tools:** `Git` · `Linux` · `CLI`

## Контакти

- Portfolio: [igor-zatochniy.github.io/portfolio](https://igor-zatochniy.github.io/portfolio/)
- Telegram: [@zatochniy](https://t.me/zatochniy)
- Email: [igor.zatochniy@gmail.com](mailto:igor.zatochniy@gmail.com)

---

<div align="center">

Відкритий до віддаленої роботи у **SEO Automation**, **Technical SEO** та **Go Development** для SEO-інструментів і marketing automation.

</div>
