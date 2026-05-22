# Snobby — Snob KI Agent

Animated voice + chat agent for GoSNOB. Deployable on GitHub Pages, testable on mobile.

## Deploy to GitHub Pages

Go to: **Settings → Pages → Source: Deploy from branch → main / root → Save**

Live URL: `https://redhippogit.github.io/Snobby/`

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
- API calls go directly to Anthropic from your browser
- Model: `claude-haiku-4-5` (fast + cheap for testing)
