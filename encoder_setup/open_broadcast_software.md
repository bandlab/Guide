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

1. Create a scene, by right click in the white box below Scenes and click 'Add Scene'. Give it an appropriate name and you're ready to set up your sources. You can right-click the scene in this list to change its position for organisation purposes as well as setting a hotkey for it.

2. Add your video and audio sources by right-click in the Sources box and select which type to add. Source types [include](http://jp9000.github.io/OBS/general/overview.html):
	
	- Window or monitor capture

	- Image or Image slideshow

  	- Text

	- Video Capture Device

3. Save your input scenes and sources and click Preview Stream to check everything's working as you want it to

4. Start broadcasting and check your stream's video and audio quality by clicking 'play' on your Run page player. You're good to go!

## Stream Details

Your stream details are unique to each of your events run through the Chew platform. These are available from the Encoder Setup section on your Event's Run page.

1. Open OBS and click Settings
2. Click Stream settings and pick 'Custom Streaming Server' from the dropdown
3. The server's address is shown on the Run page and looks like **rtmp://stream3.chew.tv:1935/live**
4. The stream's name is as shown on the Run page and looks like: **example.d7100ee389849e2640f5cd29de7d5d4e**
5. Select OK and save your settings.