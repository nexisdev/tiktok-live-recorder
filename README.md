<div align="center">


<h1> TikTok Live Recorder🎥</h1>

<em>TikTok Live Recorder is a tool for recording live streaming tiktok.</em>

[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

The TikTok Live Recorder is a tool designed to easily capture and save live streaming sessions from TikTok. It records both audio and video, allowing users to revisit and preserve engaging live content for later enjoyment and analysis. It's a valuable resource for creators, researchers, and anyone who wants to capture memorable moments from TikTok live streams.

<img src="https://i.ibb.co/YTHp5DT/image.png" alt="image" border="0">

</div>

<div align="left">


  <h1> How To Use </h1>

- [Install on Windows & Linux 💻](#install-on-windows--linux-)
- [Install on Android 📱](#install-on-android-)

</div>

<br>

## Install on Windows & Linux 💻

To clone and run this application, you'll need [Git](https://git-scm.com) and [Python3](https://www.python.org/downloads/) installed on your computer. From your command line:

<!-- <img src="https://i.ibb.co/8DkzXZn/image.png" alt="image" border="0"> -->

<be>

</div>

  ```bash
# Clone this repository
$ git clone https://github.com/Michele0303/tiktok-live-recorder
# Go into the repository
$ cd tiktok-live-recorder
# Go into the source code
$ cd src
# Install dependencies
$ pip install -r requirements.txt
# Run the app on windows
$ python main.py -h
# Run the app on linux
$ python3 main.py -h
  ```

## Install on Android 📱

<b>Install Termux from F-Droid:</b> <a href="https://f-droid.org/packages/com.termux/">HERE</a> - Avoid installing from Play Store to prevent potential issues.

From termux command line:

<be>

</div>

  ```bash
# Update packages
$ pkg update
$ pkg upgrade
# Install git, python3, ffmpeg
$ pkg install git python3 ffmpeg
# Clone this repository
$ git clone https://github.com/Michele0303/tiktok-live-recorder
# Go into the repository
$ cd tiktok-live-recorder
# Go into the source code
$ cd src
# Install dependencies
$ pip install -r requirements.txt
# Run the app
$ python main.py -h
  ```

<div align="left">


## To-Do List 🔮

- [x] Automatic Recording: Enable automatic recording of live TikTok sessions.
- [x] Authentication: Added support for cookies-based authentication.
- [x] Recording by room_id: Allow recording by providing the room ID.
- [x] Recording by TikTok live URL: Enable recording by directly using the TikTok live URL.
- [x] Using a Proxy to Bypass Login Restrictions: Implement the ability to use an HTTP proxy to bypass login restrictions in some countries (only to obtain the room ID).
- [x] Implement a Logging System: Set up a comprehensive logging system to track activities and errors.
- [ ] Add Feature to Send Recorded Live Streams to Telegram.
- [ ] Add Feature to Save the Chat in a File.
- [ ] Implement Auto-Update Feature: Create a system that automatically checks for new releases.

## Legal ⚖️

This code is in no way affiliated with, authorized, maintained, sponsored or endorsed by TikTok or any of its affiliates or subsidiaries. Use at your own risk.
