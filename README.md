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

<br>I recommend that right after you're done, do [this](https://streamlink.github.io/cli.html#cmdoption-twitch-oauth-token).

<br>Now Streamlink should be set up for general use! I recommend you [setup FFMPEG yourself](https://streamlink.github.io/cli.html#cmdoption-ffmpeg-ffmpeg) if you're using it for something like YouTube.

<br>To use Streamlink, open CMD, and type "streamlink URL quality".(Of course, switch URL for the stream's link and quality for...the quality. AKA 720p, 720p60, etc) Be aware it only supports several services. Check Streamlink's website for more info.


<br>**==OPTIONAL== ==Low Latency Support for Streamlink Twitch GUI== ==OPTIONAL==**
<br>3 - Download [this](https://gist.github.com/back-to/8e9ed3c60e5932d8c7a67ccd43b906d0/) plugin here, and back at the %APPDATA%/streamlink folder, create a plugins folder, and extract twitch.py on it. You may need [7-Zip](https://www.7-zip.org/) to open and extract the plugin.
<br>![Nope, no easter eggs here, go home.](https://raw.githubusercontent.com/AkiraJkr/Streamlink-Twitch-GUI-Setup-Guide/master/data/Streamlink_Setup_3.png)

# Setting Streamlink Twitch GUI

<br>1 - Once you start it, you'll be instantly greeted with an pop-up to configure the app, go ahead, this shall take a while.

<br>Go to the "Streaming" tab in the Settings. You'll have to set the paths for a Python executable and a Streamlink python script. This guide only covers the default path and  the latest version of Streamlink, so do not create an Issue on GitHub if you don't have both.

<br>Python
<br>![The cake is a lie.](https://raw.githubusercontent.com/AkiraJkr/Streamlink-Twitch-GUI-Setup-Guide/master/data/Twitch_GUI_SS_Python.png)

<br>Streamlink
<br>![The cake is a lie.](https://raw.githubusercontent.com/AkiraJkr/Streamlink-Twitch-GUI-Setup-Guide/master/data/Twitch_GUI_SS_Streamlink.png)

<br>After you're done, please make sure these specific settings are exactly as in the image below.
<br>![I'm out of easter eggs, could you give me some?](https://raw.githubusercontent.com/AkiraJkr/Streamlink-Twitch-GUI-Setup-Guide/master/data/Twitch_GUI_SS_Streaming.png)

<br>2 - On the "Player" tab, pick the preset that matches your player, and then select it's executable. If you're this far, I don't need to guide you with that. The rest of the settings is up to you.
<br>![I'll gift candy if you do.](https://raw.githubusercontent.com/AkiraJkr/Streamlink-Twitch-GUI-Setup-Guide/master/data/Twitch_GUI_SS_Player.png)

# The End

You're now ready to use Streamlink Twitch GUI to use Twitch and not worry about performance issues, just make sure your PC isn't THAT bad and your network can handle the streams you're watching. Remember, the app is VERY customizable.

<br>![Oh wow. This was a very epic journey, I am very content that you went all this way for such an heartwarming text. Here I am thinking a wall of text to write as an easter egg for the fanatics, but well, there is nothing to write. Not even a recipe. That wouldn't be original. So, uh, yeah. Please don't sue me Nintendo for this image okay?](https://raw.githubusercontent.com/AkiraJkr/Streamlink-Twitch-GUI-Setup-Guide/master/data/The_End.png)