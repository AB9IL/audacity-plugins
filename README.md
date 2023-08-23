# audacity-plugins
Analysis plugins for the Audacity audio editor (and its forks  Audicium, Tenacity, etc)

## Audio Analysis Tools for Content Creators

Podcasters, audiobook narrators, and vloggers - don't get your uploads rejected or forcibly adjusted by YouTube, SoundCloud, ACX, Amazon, or other media platforms! Use these nyquist plugins to evaluate your audio levels for podcasts, audiobooks, or other uploads. I have created specific analysis plugins which tell you your peak and average loudness (dB LUFS), and whether they meet the applicable technical standards. They also indicate the residual background noise level, which is a quality factor on certain platforms. ACX is especially strict about levels and background noise.

#### Supported Services
```
Amazon Alexa          Sony Entertainment
Amazon Music          SoundCloud
Apple Music           Spotify
Apple Podcasts        Spotify Loud
Club Play             Tidal
Deezer                YouTube
Netflix Streaming
```

#### Dependencies

These audio analysis plugins are Nyquist scripts which are usable in Audacity and its forks (Audicium, Tenacity, etc).

#### Installation 

1. Clone this git repository.
2. Use the built-in installer in **Tools > Nyquist Plug-in Installer**
3. If not using the installer, manually copy the plugins into the proper directory used by Audacity.
```
Linux:
/usr/share/audacity/plug-ins

Windows:
Users\<username>\AppData\Roaming\audacity\Plug-Ins
```

4. Open Audacity; navigate to the menu **Tools** > **Add / Remove Plug-Ins**
5. Select and **Enable** the desired plugins (i.e. ACX-Check, YouTube-Check).

#### Usage 

To check your file's audio levels, select the audio, then pick the desired analyzer from the menu.

**Analyze > Spotify-Check**

The plugin will report peak and average (RMS) levels, plus the background noise level. For each level, there will be a PASS / FAIL / WARNING message to indicate whether the audio meets requirements of the associated streaming platform.
