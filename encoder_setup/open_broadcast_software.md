# Streaming with Open Broadcaster Software

[Open Broadcaster Software](https://obsproject.com/) is free and open source software for video recording and live streaming. If you're so inclined, you can find its source code on [github](https://github.com/jp9000/OBS). 

There are two free versions available: 

- OBS for [PC](https://obsproject.com/download))
- OBS for [Mac](https://obsproject.com/download#mac)

OBS has a fairly in-depth [Help](http://jp9000.github.io/OBS), [Support](http://jp9000.github.io/OBS/general/support.html) and [FAQ](http://jp9000.github.io/OBS/general/faq.html) sections on their website - but we'll condense what you need to know below.

## Streaming through OBS Overview

# Mac Users

1. [Download](https://obsproject.com/download#mac), install and open OBS

2. Click the + icon below 'Scenes' to create a scene

3. Click the + icon below 'Sources' to add your video and audio sources. If you're using a webcam and USB audio, this would be adding:

	- Webcam (either USB or laptop webcam) - this will be called **Video Capture Device**
	- Audio input (called **Audio Input Capture**)

3. Save your input scenes and sources

4. Open **Settings** and then **Stream**

6. Select **Custom Streaming Server** from the dropdown menu

7. Go to Chew and create (if you haven't done already) [a new Show](http://chew.tv/guide/using_chew/go_live_on_chew)

8. Copy and paste the **Server URL** and **Stream Key** into OBS

9. Click **OK**

10. Click **Start Streaming**. Once Chew's detected your signal, you're live! Nice work. 

# PC Users

One of our awesome power users has put together a tutorial for getting to grips with OBS on PC. [Riglow](http://chew.tv/riglow), you're awesome!

<iframe src="http://chew.tv/embed/riglow/advanced-broadcast-settings-for-open-broadcast-software" width="853" height="480" scrolling="no"></iframe>
<br />
And a huge thank you to [DJ Dead Air](http://twitter.com/djdeadair) for his help in putting the below guide together. We owe you one dude! 

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

## Traktor Users

Big love to [Battleborn](http://chew.tv/battleborn) for putting together this runthrough of Edcast, OBS and Traktor on PC together! You can read the steps Battleborn went through to get Traktor audio below.  

<iframe src="http://chew.tv/embed/battleborn/chewtv-and-traktor-s4-obs-setup-using-edcast" width="853" height="480" scrolling="no"></iframe>
<br />
1. Enable Stereo Mix

2. Setup OBS as Source: Built-in Card / Mic: Default

3. Setup [EdCast Standalone](https://www.fastserv.com/kb/article/edcast_standalone_-_stream_live_audio_to_icecast_or_shoutcast) for Stereo Mix

4. Double check speakers for sound

5. Open Traktor, set Audio to Built-in Card

6. Click **Start Streaming** then, once your signal indicator has gone green (i.e. Chew is receiving your broadcast signal from OBS), click the **Go Live** button in the Advanced tab. Congratulations, you're streaming live on Chew!
