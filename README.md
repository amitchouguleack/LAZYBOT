🦾💤 LAZYBOT
Amit’s chill-but-smart symptom checker powered by DialogFlow, Flask, and Infermedica API. Built during a Lazy Remix Sprint while sipping chai and dodging burnout.

🧠💬 What is LazyBot?
LazyBot is your friendly health chatbot that checks your symptoms without checking your patience. It uses DialogFlow as the front-end 🗣️ and Infermedica API as the brain 🧠 — like a doctor who doesn’t mind being pinged at 2am 🌙.

⚙️🔁 How It Works
👤 User chats with LazyBot via DialogFlow (or Telegram, or your website).

🧾 DialogFlow sends the message to a Python Flask webhook.

🧪 Webhook calls the Infermedica API with the user’s symptoms.

🧘 Infermedica returns a diagnosis or triage suggestion.

📨 LazyBot formats the response and sends it back to the user.

It’s like having a chill doctor with zero wait time and infinite patience 😌.

🚀🛠️ How to Run
📥 Import the DialogFlow agent into your project.

🔐 Add your Firebase config and Infermedica credentials to lazybot.py.

🧰 Run pip install -r requirements.txt to install dependencies.

🧨 Start the Flask app and plug the webhook URL into DialogFlow’s fulfillment settings.

Boom 💥 You’re live.

💬📲 Where to Use It
🤖 Telegram chatbot

🌐 Website widget

🎙️ Voice assistant (if you’re feeling fancy)

🧪🔗 Built With
🧠 Infermedica Python SDK

📚 Infermedica API Docs

🧵 DialogFlow + Flask + Python

🛠️🧘 Notes
This repo is fully remixed by Amit Chougule as part of his Lazy Remix Sprint 🐢⚡.

If you find a bug 🐞, make a PR or whisper it to LazyBot — it listens 👂.

No warranty, but lots of good vibes ✨.
