# 📱 Telegram Mini App Development Skill

> A comprehensive, framework-agnostic guide for building Telegram Mini Apps — designed as an **AI agent skill** for coding assistants.

[![Telegram](https://img.shields.io/badge/Telegram-Mini%20Apps-26A5E4?logo=telegram&logoColor=white)](https://core.telegram.org/bots/webapps)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🤔 What Is This?

This repository contains a **skill file** (`SKILL.md`) — a structured knowledge document that AI coding assistants (like Gemini, Claude, Copilot, etc.) can consume to gain deep expertise in **Telegram Mini App development**.

When an AI agent loads this skill, it becomes capable of:

- 🏗️ Scaffolding new Telegram Mini Apps from scratch
- 🎨 Applying proper Telegram theming with native CSS variables
- 🔒 Implementing secure data validation (HMAC-SHA256)
- 📱 Using native Telegram UI components (MainButton, BackButton, popups, haptic feedback)
- 🧩 Integrating with **any** JavaScript framework (React, Vue, Svelte, Angular, vanilla JS)

---

## 📖 What Does the Skill Cover?

The `SKILL.md` file is an **1,100+ line** comprehensive guide organized into 18 sections:

| #   | Topic                         | Description                                              |
| :-- | :---------------------------- | :------------------------------------------------------- |
| 1   | What is a Telegram Mini App?  | Overview of Mini Apps and launch methods                 |
| 2   | Loading the SDK               | Script tag, npm packages, and framework-specific loading |
| 3   | The WebApp Object             | All properties, methods, and sub-objects                 |
| 4   | Initialization Lifecycle      | `ready()`, `expand()`, and startup flow                  |
| 5   | Theming & CSS Variables       | Complete CSS variable reference and best practices       |
| 6   | Navigation Components         | BackButton, SettingsButton                               |
| 7   | Bottom Buttons                | MainButton & SecondaryButton API                         |
| 8   | Haptic Feedback               | Impact, notification, and selection feedback             |
| 9   | Popups & Alerts               | Native dialogs (alert, confirm, custom popup)            |
| 10  | Data Validation & Security    | HMAC-SHA256 validation and Ed25519 signatures            |
| 11  | Storage APIs                  | CloudStorage, DeviceStorage, SecureStorage               |
| 12  | Full-Screen Mode              | Requesting and managing full-screen display              |
| 13  | Safe Areas                    | System and content safe area handling                    |
| 14  | Available Events              | Complete event reference table                           |
| 15  | Framework Integration Recipes | Ready-to-use code for Vanilla JS, React, Vue, and Svelte |
| 16  | Design Guidelines             | Official Telegram design principles and UI patterns      |
| 17  | Testing & Debugging           | Dev environment setup, debugging per platform            |
| 18  | Common Pitfalls               | Known issues and their solutions                         |

---

## 🚀 Getting Started

### Installation

Add this skill to any project with a single command:

```bash
npx skills add Rithprohos/telegram-mini-app-skills
```

This will install the skill into your project's `.agent/skills/` directory, making it immediately available to your AI coding assistant.

```
your-project/
├── .agent/
│   └── skills/
│       └── telegram-mini-app-skill/
│           └── SKILL.md        ← installed here
├── src/
└── ...
```

### For AI Coding Assistants

Once installed, the agent will automatically reference this skill whenever it encounters a Telegram Mini App task — no extra configuration needed.

### For Developers

You can also use `SKILL.md` directly as a **standalone reference guide**. It reads like comprehensive documentation with:

- ✅ Copy-paste code snippets for every feature
- ✅ Comparison tables for quick lookups
- ✅ Framework-specific recipes (React, Vue, Svelte, vanilla JS)
- ✅ A quick-reference cheat sheet at the end

---

## 🧩 Framework Support

This skill is **framework-agnostic** — it covers universal SDK concepts and provides integration recipes for:

| Framework            | Covered Topics                              |
| :------------------- | :------------------------------------------ |
| **Vanilla JS**       | Full working example with HTML, CSS, and JS |
| **React/Next.js**    | Custom `useTelegram` hook, layout setup     |
| **Vue 3/Nuxt**       | Composable pattern, page integration        |
| **Svelte/SvelteKit** | Helper module, page component, layout       |
| **Angular**          | Loading via `angular.json` scripts array    |

---

## 📂 Repository Structure

```
telegram-mini-app-skills/
├── SKILL.md       # The main skill file (comprehensive guide)
└── README.md      # You are here
```

---

## 🔗 Resources

- [Official Telegram Mini Apps Documentation](https://core.telegram.org/bots/webapps)
- [@BotFather](https://t.me/BotFather) — Create and manage your bots
- [@telegram-apps/sdk](https://www.npmjs.com/package/@telegram-apps/sdk) — Community TypeScript SDK
- [@twa-dev/sdk](https://www.npmjs.com/package/@twa-dev/sdk) — Lightweight wrapper

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the skill:

1. **Fork** this repository
2. **Edit** `SKILL.md` with your improvements
3. **Submit** a pull request with a clear description of changes

### Contribution Ideas

- Add integration recipes for additional frameworks (Solid, Qwik, etc.)
- Add more real-world code examples
- Document new Telegram Bot API features as they're released
- Add troubleshooting scenarios and solutions

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  Made with ❤️ for the Telegram Mini App developer community
</p>
