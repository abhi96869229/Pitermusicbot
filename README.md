# PeterMusicBot TELEGRAM VC MUSIC BOT - This is a pyrogram bot based on pytgcalls for playing songs or audio files in Telegram group voice chat
[![MusicBot logo](https://telegra.ph/file/accf8bad04684b7687121.jpg)](https://t.me/global_girls_boys_chatting)


-It is inspired from su music project and hamkercat's telegram voice bot.
Neither su music project , nor pytgcalls are stable


<p align="center">
<a href="https://app.codacy.com/gh/utkarsh542/Pitermusicbot?utm_source=github.com&utm_medium=referral&utm_content=utkarsh542/Pitermusicbot&utm_campaign=Badge_Grade_Settings" alt="Codacy Badge">
<img src="https://api.codacy.com/project/badge/Grade/6141417ceaf84545bab6bd671503df51" /> </a>
<a href="https://github.com/utkarsh542/Pitermusicbot" alt="Libraries.io dependency status for GitHub repo"> <img src="https://img.shields.io/librariesio/github/utkarsh542/Pitermusicbot" /> </a>
<a href="http://hits.dwyl.com/utkarsh542/Pitermusicbot" alt="HitCount"> <img src="http://hits.dwyl.com/utkarsh542/Pitermusicbot.svg" /> </a>
</p>
<p align="center">
<a href="https://github.com/utkarsh542/Pitermusicbot" alt="GitHub closed issues"> <img src="https://img.shields.io/github/issues-closed-raw/utkarsh542/Pitermusicbot?style=flat&logo=github&color=success" /> </a>
<a href="https://github.com/utkarsh542/Pitermusicbot" alt="GitHub commit activity"> <img src="https://img.shields.io/github/commit-activity/m/utkarsh542/Pitermusicbot" /> </a>
<a href="https://github.com/utkarsh542/Pitermusicbot/graphs/contributors" alt="GitHub contributors"> <img src="https://img.shields.io/github/contributors/utkarsh542/Pitermusicbot?style=flat&logo=github" /> </a>
<a href="https://github.com/utkarsh542/Pitermusicbot/network/members" alt="GitHub forks"> <img src="https://img.shields.io/github/forks/utkarsh542/Pitermusicbot?label=Forks&logo=github" /> </a>
<a href="https://github.com/utkarsh542/Pitermusicbot" alt="GitHub closed pull requests"> <img src="https://img.shields.io/github/issues-pr-closed-raw/utkarsh542/Pitermusicbot?color=success" /> </a>
<a href="https://github.com/utkarsh542/Pitermusicbot" alt="GitHub issues"> <img src="https://img.shields.io/github/issues-raw/utkarsh542/Pitermusicbot?style=flat&logo=github&color=yellow" /> </a>
</p>
<p align="center">
<a href="https://github.com/utkarsh542/Pitermusicbot" alt="GitHub release (latest by date including pre-releases)"> <img src="https://img.shields.io/github/v/release/utkarsh542/Pitermusicbot?include_prereleases?style=flat&logo=github" /> </a>
<a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg?style=flat&logo=python&color=blue" /> </a>
<a href="https://github.com/utkarsh542/Pitermusicbot" alt="Docker!"> <img src="https://aleen42.github.io/badges/src/docker.svg" /> </a>
<a href="https://github.com/utkarsh542/Pitermusicbot" alt="GitHub repo size"> <img src="https://img.shields.io/github/repo-size/utkarsh542/Pitermusicbot" /> </a>
<a href="https://github.com/utkarsh542/Pitermusicbot/blob/master/LICENSE" alt="GPLv3 license"> <img src="https://img.shields.io/badge/License-GPLv3-blue.svg" /> </a>
</p>
<p align="center">
<a href="https://t.me/AuraUpdates" alt="Telegram!"> <img src="https://aleen42.github.io/badges/src/telegram.svg" /> </a>
<a href="https://github.com/utkarsh542/Pitermusicbot/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" /> </a>
<a href="https://makeapullrequest.com" alt="PRs Welcome"> <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" /> </a>
</p>


## Requirements

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.7+
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)

## Deployment

### Config

Copy `example.env` to `.env` and fill it with your credentials.

### Without Docker

1. Install Python requirements:
   ```bash
   pip install -r requirements.txt
   ```
2. Run:
   ```bash
   python main.py
   ```

### Using Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```

### Heroku
 [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/utkarsh542/Pitermusicbot.git)

### StringSession

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@itzgauravv/AuraXVCBot#main.py) 

## Commands
-The commands and there use is explained here-:
- `/saavn` To search song on jio saavan and play the first result 
- `/ytt` To search the song on Youtube and play the first matching result.
- `/deezer` To search song on deezer and play good quality stream.
- `/song` To download a song from youtube.
- `/play` Reply this in response to a link or any telegram audio file it will be played 
- `/skip` to skip current song 
- `/stop` to stop the streaming of song 
- `/pause` to pause the stream 
- `/resume` to resume the playback. 
- Inline search is also supported.


## Support
- [Channel](https://t.me/AuraXNetwork)
- [Group](https://t.me/global_girls_boys_chatting)

## Credits
- [hamker cat](https://github.com/thehamkercat/Telegram_VC_Bot)
- [Roj](https://github.com/rojserbest)
- [Marvin](https://github.com/BlackStoneReborn)
- [Laky](https://github.com/Laky-64) & [Andrew](https://github.com/AndrewLaneX): PyTgCalls

