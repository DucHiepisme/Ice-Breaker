# 🐧 Ice Breaker Game

A cartoon penguin helps you break the ice. Pick a topic, pull a random question, and get everyone talking.

**Play it:** https://duchiepisme.github.io/Ice-Breaker/

## Topics

| Topic | What it is | Questions |
| --- | --- | --- |
| 🌟 Life | Personal questions to get to know you better | 25 |
| 🎲 Random | Random questions to lighten the mood | 25 |
| 🧠 Deep | Philosophical questions to spark discussion | 24 |
| 🎒 Experiences | Questions about your most memorable moments | 25 |
| 🪄 If you could... | Imaginative "If you could…" scenarios | 25 |
| ⚖️ Would you rather... | Tough "Would you rather…" choices | 25 |

## How to play

1. Click a topic.
2. Read the question aloud and let everyone answer.
3. Press **Next** for another question. Questions are shuffled and won't repeat until you have seen them all.

Keyboard: `→` next, `←` previous, `Esc` back to topics. The snow can be switched off with the button in the top corner, and animations are reduced automatically if your device asks for it.

## Run locally

It is one static file with no build step. Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

## Add or edit questions

Open `index.html` and edit the `questions` object near the top of the `<script>`. Each topic is a list of strings. The question counts on the cards update automatically.

Made with ❤️ for fun conversations.