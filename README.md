# YouTube/SoundCloud Music Downloader Developed By BitSamurai


This Telegram bot is a powerful and user-friendly tool that allows anyone to download audio tracks from YouTube and SoundCloud directly within Telegram. The bot is designed to make the process of obtaining music as simple and convenient as possible.

When a user sends a YouTube or SoundCloud link to the bot, it automatically offers to download the audio in high-quality MP3 format. The bot also supports music search by name. Users can type the /search command or simply send a short query, such as a song title or artist name. The bot will then display a list of tracks found on YouTube, and after the user selects a track, the bot will download and send the audio file.

The bot supports multiple languages, including Russian, English, Spanish, Azerbaijani, Turkish, Ukrainian, and Arabic. When users start the bot or use the /language command, they can easily choose their preferred language from a convenient keyboard. The bot remembers each user's language preference for future sessions.

To ensure compliance with Telegram policies, the bot requires users to be subscribed to a specific Telegram channel before they can use its features. The bot checks the user's subscription status before processing any requests. If the user is not subscribed, the bot sends a polite message asking them to join the channel.

There is a strict file size limit of 50 MB for audio files, in accordance with Telegram's restrictions. If the downloaded file exceeds this limit, the bot notifies the user and does not send the file.

During the download process, the bot keeps the user informed by displaying progress updates. It also provides a button to cancel the download at any time. If the user chooses to cancel, the bot immediately stops the download and informs the user that the process has been cancelled.

The bot is careful to respect copyright law. It displays copyright warnings before and after sending any audio files, reminding users to use the content for personal purposes only. The bot also provides contact information for copyright holders who wish to request removal of content.

All user language preferences are saved and loaded automatically, ensuring a seamless and personalized experience. The bot is built using Python 3 and leverages several powerful libraries, including python-telegram-bot for Telegram integration, yt-dlp for downloading and extracting audio from YouTube and SoundCloud, and ffmpeg for audio conversion and processing. It also uses python-dotenv for secure environment variable management, as well as standard Python libraries such as os, asyncio, tempfile, shutil, json, and logging.

The bot is fully asynchronous, allowing multiple users to download music simultaneously without delays. Each user's download is handled in a separate temporary folder, which is automatically cleaned up after use to ensure privacy and efficient resource management.

This project was created and developed by BitSamurai. The bot is open source, and the code is available on GitHub. For questions, suggestions, or copyright concerns, users can contact the developer via email or Telegram.

Try the bot now: t.me/ytdlpload_bot
GitHub: github.com/BitSamurai23/YTMusicDownloader
Blog: artoflife2303.github.io/miniblog/

This bot is designed to be fast, safe, multilingual, and fully compliant with Telegram's policies and copyright requirements. Enjoy your music experience with just a few taps!


Written by BitSamurai

Last changes: 22.06.2025
