# Discord vReddit Converter Bot
Discord bot that will post MP4 videos when Reddit links are posted within chat that contain vReddit videos.

Requires ffmpeg to be installed and in path

Update the .env file to contain your bots token

`pip3 install -r requirements.txt`

# Running with Docker
`cd discord-vreddit-converter/`

Update the .env file to contain your bots token

`docker build . -t discord-vreddit-converter`

`docker run -it -d --restart unless-stopped discord-vreddit-converter:latest`
