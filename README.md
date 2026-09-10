# Omni — Free AI Chat Bot

Talk to **real** Claude Fable, GPT, Grok, Gemini, Kimi, DeepSeek, Qwen, and Mistral in the browser. **No API key.** Sign in with a free [Puter](https://puter.com) account.

Each model runs **as itself** (Claude is Claude, Grok is Grok) using distilled vendor system prompts — not a shared Omni persona.

## Live

- **https://coolkidhacks.github.io/FREE-AI-CHAT-BOT/**
- **https://coolkidhacks.github.io/**

## Use it

1. Open the live site.
2. Click **Sign in** — allow the Puter popup.
3. Pick a **verified model**.
4. Toggle **Think** for slower, more careful answers. Effort: Low → Max.
5. Type a message, press Enter.

Chats stay in this browser (`localStorage`).

## Features

- Streaming `puter.ai.chat()` — every option is a real Puter-hosted model ID
- Per-model system prompts (Claude Fable 5.1 / Opus / Sonnet, GPT-5.6 Luna/Sol/Terra, Grok 4.6, Gemini, Kimi, DeepSeek, Qwen, Mistral, GLM)
- Live catalog merge from Puter’s model API
- Thinking traces + effort control
- Multi-chat sidebar, search, delete, regenerate, copy, image attach
- Mobile-first (safe area, 44px targets)

## If this repo’s Pages 404s

The working site is published from [coolkidhacks.github.io](https://github.com/CoolKidHacks/coolkidhacks.github.io). To also publish **this** repo:

1. Open **[Settings → Pages](https://github.com/CoolKidHacks/FREE-AI-CHAT-BOT/settings/pages)** as CoolKidHacks
2. Source: **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)** · **Save**

## Credit

AI runs through [Puter.js](https://developer.puter.com). Model voices distilled from public archives at [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) (identity + tone only — no vendor tools).
