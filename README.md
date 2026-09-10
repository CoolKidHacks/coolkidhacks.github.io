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
5. Open **Usage** in the sidebar to see remaining Puter allowance, a turn counter, and whether this chat can finish on the current model.
6. Type a message, press Enter. Replies stream live, with syntax highlighting on code.

Chats stay in this browser (`localStorage`).

## Features

- Streaming `puter.ai.chat()` — every option is a real Puter-hosted model ID
- Automatic **fallback** when a flagship model is rate-limited or out of usage (reroutes to GLM 5.3, GPT-5.6 Luna, or Flash, and labels it in the thread)
- **Usage meter** from `puter.auth.getMonthlyUsage()` plus a mid-chat projection: if remaining allowance cannot finish the project on the heavy model, Omni switches to a lighter one so you still get the answer
- Per-model system prompts (Claude Fable 5.1 / Opus / Sonnet, GPT-5.6 Luna/Sol/Terra, Grok 4.6, Gemini, Kimi, DeepSeek, Qwen, Mistral, GLM)
- Live catalog merge from Puter’s model API
- Thinking traces + effort control, shown as they stream
- Syntax-highlighted code, tables, copy / retry
- Recovers replies that some reasoning models only emit in the thinking channel
- Multi-chat sidebar, search, delete, regenerate, image attach
- Mobile-first (safe area, 44px targets)

## If this repo’s Pages 404s

The working site is published from [coolkidhacks.github.io](https://github.com/CoolKidHacks/coolkidhacks.github.io). To also publish **this** repo:

1. Open **[Settings → Pages](https://github.com/CoolKidHacks/FREE-AI-CHAT-BOT/settings/pages)** as CoolKidHacks
2. Source: **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)** · **Save**

## Credit

made by Adrian In Ur Class Rn

AI runs through [Puter.js](https://developer.puter.com). Model voices distilled from public archives at [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) (identity + tone only — no vendor tools).
