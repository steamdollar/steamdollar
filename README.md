# Lee Seung Jun

Backend engineer in Seoul. I work mostly in Go and TypeScript.

[Portfolio](https://steamdollar.github.io/) · [한국어 프로필](https://steamdollar.github.io/ko/) · [KR / EU / US Résumés](https://steamdollar.github.io/resume/)

For the last two years I built the backend of a maritime ERP: passenger
reservations, cargo, and onboard operations for a Korea–Japan ferry operator.
Before that I wrote Node.js/TypeScript services at a blockchain research lab.

Some of that work:

- rebuilt a legacy PHP/JS passenger reservation system as a Go (Gin) service
- merged two standalone services into the base server, DB migration included.
  This took the ERP from seven services to five, and I did it alone
- built the QR boarding backend for a newly launched vessel, with WebSocket
  state sync between cloud and ship
- set up the company's first cloud/container environment on Azure from scratch,
  and moved deployments from manual CLI runs to shell-script pipelines
- led the four-person backend team: code review as the merge gate, shared
  internal Go packages, implementation direction

## Projects

**[copylingo](https://github.com/steamdollar/copylingo)** — a Telegram bot I
use every day for studying Japanese. Go/Gin, PostgreSQL, Redis, the Gemini API,
Docker Compose. No ORM (sqlx), 50+ test files.

**[browserToolkit](https://github.com/steamdollar/browserToolkit)** — a Chrome
extension with the small tools I kept needing: Base64/JWT decoding, quick HTTP
requests, Mermaid preview, notes.

## Stack

Gin · PostgreSQL · Microsoft SQL Server · MariaDB · Redis · Docker · Azure ·
GitHub Actions

Poking at lately: Kotlin, MCP servers, NestJS, Next.js