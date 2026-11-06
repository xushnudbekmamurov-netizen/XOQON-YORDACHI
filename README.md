# XOQON-YORDACHI

Voice-controlled smart phone assistant. It lets you operate your phone
with voice commands when your hands are busy or using the touchscreen
is inconvenient. An AI model is integrated to make commands smarter.

## Status
Early development. Currently in personal testing.

## Why
Hands-free control helps in everyday situations and can improve
accessibility for people who find touchscreens hard to use.

## License
MIT
## How it works
- Basic voice commands work offline, no API key needed.
- Long or complex commands are sent to Gemini, which translates them
  into the app's own command language. This part needs internet and
  a Gemini API key.
- Only the text of the command is sent, nothing else from your phone.
- Risky actions (calls, messages, deletions) ask for confirmation.
