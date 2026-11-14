# Archival notice
This repository is now under [fm01-bot/bot](https://github.com/fm01-bot/bot) for the sake of easier orchestration and project management.

# website

Build: docker build --target build .

Prod: docker build --target prod -t fm01-prod . && docker run -p 3007:3007 fm01-prod

Dev preview: fm01bot.gamrtag.xyz
