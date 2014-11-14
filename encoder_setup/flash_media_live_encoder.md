# Streaming with Flash Media Live Encoder (FMLE)

[Flash Media Live Encoder](http://www.adobe.com/uk/products/flash-media-encoder.html) is "a media encoder that streams audio and video in real time to Adobe Media Server software or Flash Video Streaming Service (FVSS). This software can enable the broadcast of live events ... around the clock."

If you're just getting started with live streaming using a single camera, Flash Media Encoder is a great entry point. It's both robust and free!

<u>Streaming through Flash Media Encoder Overview</u>

1. Setup capture card in the "Video" Section to stream in H.264 format
2. Setup the stream in the "Stream to Flash Media Server" section, matching the stream name and server address found on your Event's Run Page
3. Check "Save to File" to record to disk
4. Set the stream's bitrate to match your connection strength and adjust keyframe interval
4. Connect to the server in the "Stream to Flash Media Server" section
5. Click Start to begin streaming
6. Check your stream's video and audio quality by clicking 'play' on your Run page player. You're good to go!

Adobe offers a guide to using the Flash Media Live Encoder application on their site:

- [Windows and Mac](http://www.adobe.com/devnet/adobe-media-server/articles/webcasting_fme.html#articlecontentAdobe_numberedheader_1)

## Download a Chew Streaming Profile

To make it as easy as possible starting out with Chew we've created a couple of example streaming profiles for you to download and open in Flash Media Live Encoder to get you started. Download one of these xml files, updated the streaming details from those on your Chew Go Live page and you're good to go!

[Flash Media Live Encoder Profile - 720p HD at 1500kbps (fmle_1280_720_1500kbps.xml)](/r/encoder_setup/downloads/fmle_1280_720_1500kbps.xml)

[Flash Media Live Encoder Profile - 1080p HD at 700kbps (fmle_1920_1080_2200kbps.xml)](/r/encoder_setup/downloads/fmle_1920_1080_2200kbps.xml)

## Setup Video Feeds

Flash Media Encoder supports one video input. This can be your computer's webcam or an external HDMI/SDI camera connected though a capture card.

Simply connect your video input source to your computer and you can select the source in Flash Media Encoder under the "Video" section. 

## Setup Audio Feeds

We recommend adding an audio feed to your broadcast for the best quality for your viewers/ listeners. Adding an audio feed to Flash Media Live Encoder is as simple as adding a video feed - simply connect your audio input source to your computer then select the source in Flash Media Live Encoder under the "Audio" section. 

## Bitrate and Keyframe Interval

### Bitrate

The bitrate is the amount of video data that is uploaded to the server per second. Most commonly measured in bits or megabits per second, this is a really important number you should be aware of to ensure a smooth stream. First, run a connection test using something like [Speedtest.net](http://speedtest.net/). Then make sure the bitrate in the Flash Media Encoder "output settings" you're using is at least 25% below the result you got from the speed test.

If the bitrate in Flash Media Encoder is set higher than the upload speed at your venue, you will have issues with the stream stopping and starting - it may not even start at all.

### Keyframe Interval

A video is a sequence of images and each image is called a frame. To compress video data, most encoders take a frame and make it a reference or key. This keyframe is sent as part of the broadcast, and all of the data after that keyframe is relative to it. The benefit of this is that the compressor only needs to send what has changed since the last keyframe.

A short keyframe interval leads to smoother switching between qualities for the user watching your stream.

**The keyframe interval should be set to as low as possible to help the user experience. In Flash Media Live Encoder is should be set to 4 seconds or less. This is 120 frames at 30fps. **

## Stream Details

Your stream details are unique to each of your events run through the Chew platform. These are available from the Encoder Setup section on your Event's Run page.

1. Open Flash Media Encoder and select Output Settings
2. Set your Output Destination to RMTP Server
3. The server's address is shown on the Run page and looks like **rtmp://stream3.chew.tv:1935/live**
4. The stream's name is as shown on the Run page and looks like: **example.d7100ee389849e2640f5cd29de7d5d4e**
5. Select OK and save your settings.