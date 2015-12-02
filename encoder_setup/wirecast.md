# Streaming with Telestream's Wirecast

###_While Chew is built to work with most RTMP encoders, we recommend you broadcast to Chew using [OBS](http://chew.tv/Guide/encoder_setup/how_to_use_open_broadcast_software)._

[Wirecast](http://www.telestream.net/wirecast/overview.htm) is the "only cross-platform, all-in-one live streaming production software that enables capture, live production, and encoding of live streams for broadcast to multiple servers and platforms simultaneously".

It is one of the best encoders we've used - with a huge range of [features](http://www.telestream.net/wirecast/features.htm) - but does (unfortunately for those of you on a budget!) come at a price. Wirecast licenses start at $495 and goes up to $1,194. You can find out more [here](http://www.telestream.net/wirecast/store.asp). 

<u>Streaming through Wirecast Overview</u>

1. Add video and audio feed inputs via 'Add Source'
2. Setup each stream in Output Settings, matching the stream name and server address found on your Event's Run Page
3. Set the stream's bitrate to match your connection strength and adjust keyframe interval
4. Save your settings and click 'Stream' to start broadcasting 
5. Check your stream's video and audio quality by clicking 'play' on your Run page player. You're good to go!

Telestream offer a brief Wirecast tutorial on their website, which is available to download here:

- [Windows](http://www.telestream.net/pdfs/user-guides/Wirecast-5-Tutorial-Windows.pdf)
- [Mac](http://www.telestream.net/pdfs/user-guides/Wirecast-5-Tutorial-Mac.pdf)

You can watch a brief overview of setting up Wirecast below:

<iframe width="853" height="480" src="//www.youtube.com/embed/ITVX8Er_Klk?rel=0" frameborder="0" allowfullscreen></iframe>

## Setup Video Feeds

Wirecast supports an unlimited number of video inputs ranging from webcams (via USB or Firewire), DV/HDV, SDI cameras (via capture cards), as well as IP and web-based sources and Wireless devices. 

Simply connect your video input sources to your computer and Wirecast will recognise them as live feeds. In some cases, you may need to add the inputs manually via the 'Add Source' functionality.

The number of source inputs you can add to a broadcast is only limited by your hardware and processing power.

For more information on how to setup your video feeds, please see the Wirecast user guide here: 

- [Windows](http://www.telestream.net/pdfs/user-guides/Wirecast-5-User-Guide-Windows.pdf)
- [Mac](http://www.telestream.net/pdfs/user-guides/Wirecast-5-User-Guide-Mac.pdf)


## Setup Audio Feeds

We recommend adding an audio feed to your broadcast for the best quality for your viewers/ listeners. Adding an audio feed to Wirecast is as simple as adding a video feed - simply connect your audio input sources to your computer and Wirecast will recognise them as live feeds. In some cases, you may need to add the inputs manually via the 'Add Source' functionality. Often on the Mac, for devices that input via USB, this will be called 'USB Audio Codec'.

__If you are using a separate audio interface with a camera that has an in-built microphone then you must disable the camera's microphone to prevent both audio sources from being streamed.__ 

Once you've setup your audio interface, right click on each camera and, in the audio menu, uncheck all audio sources on that camera shot. Leave the audio interface you want to stream checked.

For more information on how to setup your audio feeds, please see the Wirecast user guide here: 

- [Windows](http://www.telestream.net/pdfs/user-guides/Wirecast-5-User-Guide-Windows.pdf)
- [Mac](http://www.telestream.net/pdfs/user-guides/Wirecast-5-User-Guide-Mac.pdf)


## Bitrate and Keyframe Interval

### Bitrate

The bitrate is the amount of video data that is uploaded to the server per second. Most commonly measured in bits or megabits per second, this is a really important number you should be aware of to ensure a smooth stream. First, run a connection test using something like [Speedtest.net](http://speedtest.net/). Then you should make sure the bitrate in Wirecast's "output settings" that you're using is at least 25% below the result you got from the speed test.

If the bitrate in Wirecast is set higher than the upload speed at your venue then you will have issues with the stream stopping and starting or it may not start at all.


### Keyframe Interval

A video is a sequence of images and each image is called a frame. To compress video data, most encoders take a frame and make it a reference or key. This keyframe is sent as part of the broadcast, and all of the data after that keyframe is relative to it. The benefit of this is that the compressor only needs to send what has changed since the last keyframe. 

The main drawback of this is that over time it becomes harder for the encoder to distinguish the frame-difference information, especially if there is a lot of motion in the video. Another drawback is if your viewer’s computer misses a keyframe, the video is distorted until the next keyframe is sent. 

However, you can control how often the encoder makes a new keyframe by setting the number of keyframes. The more keyframes you broadcast, the more bandwidth required and less your video is compressed, but higher keyframes result in better quality video. 

**The keyframe interval should be set to as low as possible to help the user experience. In Wirecast, should be set to 4 seconds or less. This is 120 frames at 30fps. **
