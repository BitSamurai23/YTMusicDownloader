# YouTube/SoundCloud Music Downloader

This Telegram bot allows users to download audio from YouTube and SoundCloud directly in Telegram. When a user sends a YouTube or SoundCloud link, the bot offers to download the audio in MP3 format. The bot also supports searching for music by name: users can type /search or simply send a short query, and the bot will show a list of tracks found on YouTube. After the user selects a track, the bot downloads and sends the audio file.

The bot supports multiple languages, including Russian, English, Spanish, Azerbaijani, Turkish, Ukrainian, and Arabic. Upon starting the bot or using the /language command, users can choose their preferred language from a keyboard.

To use the bot, users must be subscribed to a specific Telegram channel. The bot checks the user's subscription status before processing any requests. If the user is not subscribed, the bot sends a message asking them to subscribe.

There is a file size limit of 50 MB for audio files, in accordance with Telegram's restrictions. If the downloaded file is too large, the bot notifies the user and does not send the file.

During the download process, the bot displays progress updates and provides a button to cancel the download. If the user cancels, the bot stops the download and informs the user.

The bot also includes copyright warnings before and after sending any audio files, reminding users to use the content for personal purposes only and providing contact information for copyright holders.

All user language preferences are saved and loaded automatically. The bot uses yt-dlp for downloading media and supports cookies and ffmpeg for better compatibility and audio conversion.

The bot is designed to be user-friendly, multilingual, and compliant with Telegram's policies and copyright requirements.

Created and developed by BitSamurai.
