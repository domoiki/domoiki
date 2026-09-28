<h1 align="center">I vibe-code things that actually run</h1>

<p align="center">
  The AI writes most of it. I make it work, write the tests, and put it in production.<br>
  Mostly TypeScript on serverless. Six of my projects are live right now.
</p>

<p align="center">
  <a href="https://domoiki.github.io/"><img src="https://img.shields.io/badge/website-domoiki.github.io-3FB950?style=flat-square&logo=github&logoColor=white" alt="website" height="28"></a>
  <a href="https://github.com/domoiki?tab=repositories"><img src="https://img.shields.io/badge/14-public_repos-30363D?style=flat-square" alt="repos" height="28"></a>
</p>

---

## Live right now

These aren't screenshots. Every one of these is deployed and clickable.

| Project | What it does | Try it |
| --- | --- | --- |
| **`telegram-ai-gateway`** | Personal Telegram ⇄ AI gateway with a full ops console. An ordered chain of AI providers with automatic retry and fallback, a three-slot chat allowlist, and a per-request trace you read like a console log. | [telegram-ai-gateway.vercel.app](https://telegram-ai-gateway.vercel.app) |
| **`absensi`** | Attendance app for small teams. One-tap check-in and check-out, leave requests, a donut chart of who made it in today, and an admin traffic dashboard. | [synx-absensi.vercel.app](https://synx-absensi.vercel.app) |
| **`Toko-Joyo-Abadi`** | Point-of-sale and shop management. Transactions, stock, profit-and-loss reports, and a CSV export that opens correctly in Indonesian Excel. Installable as a PWA. | [synx-joyo.vercel.app](https://synx-joyo.vercel.app) |
| **`synx-chat`** | The first iteration: a Telegram bot on OpenRouter with per-chat memory and a usage dashboard, on Vercel KV. | [synx-chat.vercel.app](https://synx-chat.vercel.app) |
| **`synx-world`** <br> **`my-admin-dashboard`** | A card component library, and a plain-HTML admin dashboard. | [synx-world](https://synx-world.vercel.app) · [dashboard](https://my-admin-dashboard-bice.vercel.app) |

Two details worth pointing at: the gateway keeps **115 unit tests** and encrypts every stored credential with **AES-256-GCM**; the POS hides cost price and profit from the cashier role **in the API response**, not by hiding a field in the UI.

Source for all of them is in the [repos tab](https://github.com/domoiki?tab=repositories).

---

## What I build with

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" height="30">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" height="30">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" height="30">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" height="30">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" height="30">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" height="30">
  <img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white" alt="shadcn/ui" height="30">
  <br>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" height="30">
  <img src="https://img.shields.io/badge/Neon-00E599?style=flat-square&logo=neon&logoColor=black" alt="Neon" height="30">
  <img src="https://img.shields.io/badge/Turso-0F172A?style=flat-square&logo=turso&logoColor=white" alt="Turso" height="30">
  <img src="https://img.shields.io/badge/Drizzle_ORM-5A2FD1?style=flat-square&logo=drizzle&logoColor=white" alt="Drizzle ORM" height="30">
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" height="30">
  <img src="https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram Bot API" height="30">
  <img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white" alt="PWA" height="30">
</p>

## On the bench

Things I'm poking at, not things I've shipped yet.

<p>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" height="26">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" height="26">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" height="26">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" height="26">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" height="26">
  <img src="https://img.shields.io/badge/Linux-FFCC02?style=flat-square&logo=linux&logoColor=black" alt="Linux" height="26">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" height="26">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" height="26">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" height="26">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" height="26">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white" alt="Angular" height="26">
</p>

---

## How I work

I'm not going to pretend typing the prompt is the hard part. The parts that actually take time are the boring ones:

- Deciding that a `400` means stop the fallback chain but a `401` means try the next provider
- Making a webhook idempotent so a retry doesn't send two replies
- Hiding a price at the API boundary when the role isn't allowed to see it
- Writing the test after the thing is built, not before

---

<p align="center">
  <sub>Built with a lot of AI, and a lot of fixing the AI's output.</sub>
</p>
