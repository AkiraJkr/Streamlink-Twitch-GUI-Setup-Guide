# Streamlink Twitch GUI Setup Guide
A guide for setting up Streamlink Twitch GUI to substitute Twitch's website, with Low Latency support.

<br>This guide was made for Windows.

<br>![A image here](https://raw.githubusercontent.com/AkiraJkr/Streamlink-Twitch-GUI-Setup-Guide/master/data/Streamlink_Twitch_GUI_SS.png)

<br>Requirements:

<br>- A player of your choice(Latest [MPC-HC](https://mpc-hc.org/) recommended, supports [K-Lite MCP](https://www.codecguide.com/download_kl.htm))
<br>- Latest [Streamlink](https://streamlink.github.io/) release.
<br>- Latest [Streamlink Twitch GUI](https://github.com/streamlink/streamlink-twitch-gui) release.

# Setting up Streamlink

<br>This is the most important part, as you may have issues otherwise if you don't set this up in-case you are using it for anything other than Twitch.

<br>1 - After installing Streamlink, go to "%APPDATA%/streamlink"
<br>![Oh hello, a image should be here.](https://raw.githubusercontent.com/AkiraJkr/Streamlink-Twitch-GUI-Setup-Guide/master/data/Streamlink_Setup_1.png)

<br>2 - Open streamlinkrc(Yes, it has no extension) with notepad or Notepad++.
Follow the instructions there to set the directory of your player. In my case where I use MPC-HC, this is how it looks like.
<br>![Oh hello, are you looking for easter eggs?](https://raw.githubusercontent.com/AkiraJkr/Streamlink-Twitch-GUI-Setup-Guide/master/data/Streamlink_Setup_2.png)

<br>Now Streamlink should be set up for general use! I recommend you setup FFMPEG yourself if you're using it for something like YouTube.

<br>To use Streamlink, open CMD, and type "streamlink URL quality".(Of course, switch URL for the stream's link and quality for...the quality. AKA 720p, 720p60, etc) Be aware it only supports several services. Check Streamlink's website for more info.


<br>**==OPTIONAL== ==Low Latency Support==**
<br>3 - Download [this](https://gist.github.com/back-to/8e9ed3c60e5932d8c7a67ccd43b906d0/) plugin here, and back at the %APPDATA%/streamlink folder, create a plugins folder, and extract twitch.py on it. You may need [7-Zip](https://www.7-zip.org/) to open and extract the plugin.
<br>![Nope, no easter eggs here, go home.](https://raw.githubusercontent.com/AkiraJkr/Streamlink-Twitch-GUI-Setup-Guide/master/data/Streamlink_Setup_3.png)
