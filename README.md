# Omni — Free AI Chat Bot

Talk to **real** Claude Fable, GPT, Grok, Gemini, Kimi, DeepSeek, Qwen, and Mistral in the browser. **No API key.** Sign in with a free [Puter](https://puter.com) account.

Each model runs **as itself** (Claude is Claude, Grok is Grok) using distilled vendor system prompts — not a shared Omni persona.

## Fix the 404 (required, one minute)

GitHub will not publish `*.github.io` until Pages is switched on **by the repo owner**. I cannot do this from an API token.

1. Open **[Settings → Pages](https://github.com/CoolKidHacks/FREE-AI-CHAT-BOT/settings/pages)** while logged in as **CoolKidHacks**
2. **Build and deployment → Source:** `Deploy from a branch`
3. **Branch:** `main` · **Folder:** `/ (root)`
4. **Save**

Wait ~60 seconds, then hard-refresh:

**https://coolkidhacks.github.io/FREE-AI-CHAT-BOT/**

If GitHub still shows “There isn’t a GitHub Pages site here”, you haven’t clicked Save on that page yet.

## Use it

1. Open the live site (after Pages is on).
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

## Credit

AI runs through [Puter.js](https://developer.puter.com). Model voices distilled from public archives at [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) (identity + tone only — no vendor tools).
