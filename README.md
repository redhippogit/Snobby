# Snob KI Agent

Animated voice + chat agent for GoSNOB. Deployable on GitHub Pages, testable on mobile.

## Deploy to GitHub Pages

```bash
# 1. Create a new GitHub repo (e.g. "snob-agent")

# 2. Push this folder
cd /Users/henry/snob-agent
git init
git add .
git commit -m "initial snob agent"
git remote add origin https://github.com/DEIN-USERNAME/snob-agent.git
git push -u origin main

# 3. Enable GitHub Pages
# GitHub → Settings → Pages → Source: "Deploy from branch" → main / root → Save
```

The live URL will be: `https://DEIN-USERNAME.github.io/snob-agent/`

## Setup on mobile

1. Open the URL above on your phone
2. Enter your **Anthropic API Key** (`sk-ant-...`) → get one at [console.anthropic.com](https://console.anthropic.com/account/keys)
3. The key is saved locally on your device only

## Features

- Animated Snob face (blinks, mouth moves when speaking)
- Voice mode: tap "Ruf Snob an!" → speak → Snob answers out loud
- Chat mode: type messages, Snob responds via text + voice
- Thinking animation (dots) while waiting for API
- Works on mobile Chrome (Android) and Safari (iOS)

## Notes

- Voice recognition requires **Chrome on Android** or **Safari on iOS**
- API calls go directly to Anthropic from your browser (uses `anthropic-dangerous-direct-browser-access` header)
- Model used: `claude-haiku-4-5` (fast + cheap for testing)
