<div align="center">

# Igor Zatochniy

### Junior Go Backend Developer

**Go · PostgreSQL · REST APIs · Concurrency · Docker · Testing**

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

Створюю практичні backend-сервіси на Go: проєктую REST APIs, працюю з PostgreSQL, concurrency та зовнішніми інтеграціями.

У проєктах роблю акцент на надійності: чітких transaction boundaries, явному error handling, automated tests, graceful shutdown, observability та відновленні після збоїв.

Маю вісім років досвіду в digital marketing та SEO, що допомагає мені пов’язувати технічні рішення з реальними потребами продукту.

## Основні проєкти

| Проєкт | Продукт | Engineering Highlights | Де перевірити |
|---|---|---|---|
| **CryptoPulse Telegram Bot** | Telegram-бот для відстеження цін на криптовалюти й надсилання персональних сповіщень | Durable Telegram inbox · transactional reply outbox · leased/fenced delivery · graceful shutdown | [Live Bot](https://t.me/btc_eth_usdt_bot) · [Runbook](https://github.com/igor-zatochniy/cryptopulse-telegram-bot/blob/main/docs/operations.md) · [Repository](https://github.com/igor-zatochniy/cryptopulse-telegram-bot) |
| **SEO Auditor** | Сервіс для паралельного технічного SEO-аудиту сторінок зі збереженням результатів у PostgreSQL | Bounded worker pool · PostgreSQL leases with `SKIP LOCKED` · SSRF hardening · graceful shutdown | [Example Result](https://github.com/igor-zatochniy/seo-auditor/blob/main/docs/example-result.md) · [Repository](https://github.com/igor-zatochniy/seo-auditor) |
| **Site Checker** | Сервіс за розкладом перевіряє доступність сайтів, зберігає історію перевірок і створює сповіщення в разі збоїв | PostgreSQL job leases/fencing · RabbitMQ confirms/DLQ/retries · transactional alert outbox · Kubernetes manifests with optional KEDA worker scaling | [Interactive API Docs](https://igor-zatochniy.github.io/site-checker/) · [Demo](https://github.com/igor-zatochniy/site-checker/blob/main/docs/demo.md) · [Repository](https://github.com/igor-zatochniy/site-checker) |
| **Audiobook TTS Reader** | Windows-застосунок для озвучення електронних книг із безпечним відновленням прогресу та локальним REST/SSE API | Streaming UTF-8 chunking · token-protected loopback REST/SSE API · coverage-guided fuzzing · validated progress recovery | [API](https://github.com/igor-zatochniy/tts-reader#local-rest-api) · [Fuzz Tests](https://github.com/igor-zatochniy/tts-reader/blob/main/chunk_reader_fuzz_test.go) · [Repository](https://github.com/igor-zatochniy/tts-reader) |

## Ключові навички

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

Розглядаю пропозиції віддаленої роботи на посаді **Junior Go Backend Developer**.

</div>
