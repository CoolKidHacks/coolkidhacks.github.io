# OMNI-AI — Free AI Chat

Talk to **real** Claude, GPT, Grok, Gemini, Llama, Kimi, DeepSeek, Qwen, Mistral, and more in the browser. Models are official OpenRouter IDs (`anthropic/claude-opus-5`, `openai/gpt-4o`, `openai/gpt-5.6-luna`, `x-ai/grok-4.6`) — not renamed clones.

Tap **Log in** or **Sign up** to connect your OpenRouter account. You are sent to OpenRouter, then returned here. Chat runs as OpenRouter agents on the model you pick — including `:free` models.

Add it to your **Home Screen** — it opens as **OMNI-AI**, full screen, with its own icon.

Each model runs **as itself** (Claude is Claude, Grok is Grok) using distilled vendor system prompts — not a shared Omni persona.

## Live

- **https://coolkidhacks.github.io/FREE-AI-CHAT-BOT/**
- **https://coolkidhacks.github.io/**

## Use it

1. Open the live site.
2. Tap **Log in** or **Sign up**. OpenRouter’s page covers both existing accounts and create-account.
3. Pick a **real model** — every catalog model is listed. Auto picks one if you do not know names.
4. Toggle **Think** for slower, more careful answers. Effort: Low → Max.
5. Open **Usage** in the sidebar to see remaining credits.
6. Type a message, press Enter. Replies stream live, with syntax highlighting on code.

Chats stay in this browser (`localStorage`). Your OpenRouter session never leaves the device.

## Features

- Streaming chat through [OpenRouter](https://openrouter.ai) with `provider.allow_fallbacks: false` so a named model is not swapped for a cheaper clone
- Sticky `session_id` per chat so the same OpenRouter agent stays on one provider
- Live catalog from `https://openrouter.ai/api/v1/models` — official $ input / $ output per 1M
- `:free` models (Gemma 4, GLM 5.2, Nemotron) when you want $0
- Automatic **reroute** when a flagship model is rate-limited or out of usage (retries on GLM 5.3, GPT-5.6 Luna, or Flash, and labels it in the thread)
- **Usage meter** from OpenRouter credits
- Per-model system prompts (Claude Opus / Sonnet / Haiku, GPT-4o, GPT-5.6 Luna/Sol/Terra, Grok 4.6, Gemini, Llama, Kimi, DeepSeek, Qwen, GLM)
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

AI runs through [OpenRouter](https://openrouter.ai). Model voices distilled from public archives at [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) (identity + tone only — no vendor tools).
