# Shuddi
- A smart bot that keeps your Discord channel free of profanity

![shuddhi_smile](https://user-images.githubusercontent.com/46783458/116255987-649be680-a790-11eb-9fa8-abafb00d201e.png)

## Usage:

1. Create a virtual environment
2. Clone this repository
3. Run ```pip install -r requirements.txt``` in your shell
4. Download the [word2vec model](https://github.com/mmihaltz/word2vec-GoogleNews-vectors) and paste it into ```moderation/hate_speech/data/```
5. Get your unique [Discord Bot token](https://www.writebots.com/discord-bot-token/) and save it as ```utils/token.pickle```
6. Invite the bot into your server
7. Run ```python launcher.py```
