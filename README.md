# OMNI-AI — Free AI Chat

Talk to **real** Claude, GPT, Grok, Gemini, Kimi, DeepSeek, Qwen, and more in the browser. Models are the official OpenRouter IDs (`anthropic/claude-fable-5.1`, `openai/gpt-5.6-luna`, `x-ai/grok-4.6`) — not renamed clones.

Paste a key from [openrouter.ai/keys](https://openrouter.ai/keys) in Settings for your own credits and `:free` models. Puter sign-in stays as a fallback if no key is set.

Add it to your **Home Screen** — it opens as **OMNI-AI**, full screen, with its own icon.

Each model runs **as itself** (Claude is Claude, Grok is Grok) using distilled vendor system prompts — not a shared Omni persona.

## Live

- **https://coolkidhacks.github.io/FREE-AI-CHAT-BOT/**
- **https://coolkidhacks.github.io/**

## Use it

1. Open the live site.
2. Open **Settings** and paste an OpenRouter key (`sk-or-v1-…`), or click **Sign in** for Puter.
3. Pick a **real model** — every catalog model is listed. Auto picks one if you do not know names.
4. Toggle **Think** for slower, more careful answers. Effort: Low → Max.
5. Open **Usage** in the sidebar to see remaining credits.
6. Type a message, press Enter. Replies stream live, with syntax highlighting on code.

Chats stay in this browser (`localStorage`). Your OpenRouter key never leaves the device.

## Features

- Streaming chat through [OpenRouter](https://openrouter.ai) with `provider.allow_fallbacks: false` so a named model is not swapped for a cheaper clone
- Live catalog from `https://openrouter.ai/api/v1/models` — official $ input / $ output per 1M
- `:free` models (Gemma 4, GLM 5.2, Nemotron) when you want $0
- Puter.js fallback when no OpenRouter key is saved
- Automatic **fallback** when a flagship model is rate-limited or out of usage (reroutes to GLM 5.3, GPT-5.6 Luna, or Flash, and labels it in the thread)
- **Usage meter** from OpenRouter credits (or Puter monthly usage)
- Per-model system prompts (Claude Fable 5.1 / Opus / Sonnet, GPT-5.6 Luna/Sol/Terra, Grok 4.6, Gemini, Kimi, DeepSeek, Qwen, GLM)
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

AI runs through [OpenRouter](https://openrouter.ai) (primary) and [Puter.js](https://developer.puter.com) (fallback). Model voices distilled from public archives at [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) (identity + tone only — no vendor tools).
