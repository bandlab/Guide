# Streaming with Open Broadcaster Software

[Open Broadcaster Software](https://obsproject.com/) is free and open source software for video recording and live streaming, with source code publicly available on [github](https://github.com/jp9000/OBS). 

There are two versions available: 

- OBS for Windows 7/8 (download [here](https://obsproject.com/download#obs1_dl))
- OBS Multiplatform for Mac with Linux and Windows support coming soon (download [here](https://obsproject.com/download#obs2_dl))

OBS is completely free and comes with a range of supported features, including an API on which a number of publicly available (and free!) [plugins](https://obsproject.com/forum/list/plugins.26/) have been created.

OBS' supported features include:

- Encoding using H264 (x264) and AAC
- Support for Intel Quick Sync Video (QSV) and NVENC
- Unlimited number of scenes and sources
- Live RTMP streaming to Twitch, YouTube, DailyMotion, Hitbox and more
- File output to MP4 or FLV
- GPU-based game capture for high performance game streaming
- DirectShow capture device support (webcams, capture cards, etc)
- Windows 8 high speed monitor capture support
- Bilinear or lanczos3 resampling.

The developers behind OBS have fairly in-depth [Help](http://jp9000.github.io/OBS) and [FAQ](http://jp9000.github.io/OBS/general/faq.html) sections on their website. 

You can also find their Support page [here](http://jp9000.github.io/OBS/general/support.html).


## Streaming through OBS Overview

You can watch a brief overview for the Windows version of OBS below:

<iframe width="853" height="480" src="//www.youtube.com/embed/y-L5zhhVuSc?rel=0" frameborder="0" allowfullscreen></iframe>

# Mac Users

1. Create a scene, by right click in the white box below Scenes and click **Add Scene**. Give it an appropriate name and you're ready to set up your Sources.

2. Add your video and audio sources by right clicking in the **Sources** box and selecting the type of source you'd like to add. If you're using a webcam and USB audio, this would be adding:

	- Webcam (either USB or laptop webcam) - this will be called **Video Capture Device**
	- Audio input (called **Audio Input Capture**)

3. Save your input scenes and sources

4. Click on **Settings** (bottom right)

5. Click on **Stream**

6. Select **Custom Streaming Server** from the dropdown

7. Go to Chew and create (if you haven't done already) a new Show

8. Click on the **Advanced** button

9. Copy and paste your **Stream URL** and **Stream Name** details from the Advanced tab into the same fields in the OBS settings panel

10. Click on **Output**

11. Change **Video Bitrate** to the 900 option. This sets your video quality. If you have an upload speed higher than 1MBPS at [speedtest.net](http://speedtest.net) you can set the Video Bitrate option to higher. As a rule of thumb, you always want to be broadcasting a video bitrate and audio bitrate 20% lower than your upload speed. So, for example, if you have a 1MBPS upload, you want to broadcast video and audio bitrates that total 800 or so (audio bitrate of 192 and video of around 600). 

12. Click **OK**

13. Click **Start Streaming**. Congratulations, you're streaming live on Chew!

# PC Users

One of our awesome power users has put together a tutorial for getting to grips with OBS on PC. [Riglow](http://chew.tv/riglow), you're awesome!

<iframe src="http://chew.tv/embed/riglow/advanced-broadcast-settings-for-open-broadcast-software" width="853" height="480" scrolling="no"></iframe>


A huge thank you to [DJ Dead Air](http://twitter.com/djdeadair) for his help in putting the below guide together. We owe you one dude! 

1. Create a scene, by right click in the white box below Scenes and click **Add Scene**. Give it an appropriate name and you're ready to set up your Sources.

2. Add your video and audio sources by right clicking in the **Sources** box and selecting the type of source you'd like to add. If you're using a webcam and USB audio, this would be adding:

	- Webcam (either USB or laptop webcam) - this will be called **Video Capture Device**
	- Audio input (called **Audio Input Capture** - this may not be needed for some versions of Windows) 

3. Save your input scenes and sources

4. Click on **Settings** (bottom right)

5. Click on the **Broadcast Settings** tab on the left side bar

6. Set **Mode** to **Live Stream**, then click the **Streaming Service** dropdown and select **Custom**

7. Go to Chew and create (if you haven't done already) a new Show

8. Click on the **Advanced** button

9. Copy and paste your **Stream URL** into the **FMS URL** and **Stream Name** into **Play Path/Stream Key** from the Advanced tab into the same fields in the **OBS settings panel**

10. Click on the **Encoding** tab on the left side bar

11. Change **Max Bitrate** to the 900 option. This sets your video quality. If you have an upload speed higher than 1MBPS at [speedtest.net](http://speedtest.net) you can set the Video Bitrate option to higher. As a rule of thumb, you always want to be broadcasting a video bitrate and audio bitrate 20% lower than your upload speed. So, for example, if you have a 1MBPS upload, you want to broadcast video and audio bitrates that total 800 or so (audio bitrate of 192 and video of around 600).

12. Click the **Audio** tab on the left side bar

13. Select your **Primary Sound Driver** in the **Desktop Audio Device** dropdown

14. Select your **Primary Audio Source** in the **Microphone/Auxiliary Audio Device** dropdown

15. Click **Apply** & **Ok**

16. **YOU MUST RESTART OBS FOR SETTINGS TO APPLY**

17. Click **Start Streaming** then, once your signal indicator has gone green (i.e. Chew is receiving your broadcast signal from OBS), click the **Go Live** button in the Advanced tab. Congratulations, you're streaming live on Chew!
