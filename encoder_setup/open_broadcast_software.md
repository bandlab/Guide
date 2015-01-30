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

11. Change **Video Bitrate** to the 900 option. This sets your video quality. If you have an upload speed higher than 1MBPS at [speedtest.net](http://speedtest.net) you can set this higher the Video Bitrate option to higher.

12. Click **OK**

13. Click **Start Streaming**. Congratulations, you're streaming live on Chew!
