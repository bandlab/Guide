#Setting your bitrates

When live streaming, you need to make sure you're broadcasting audio and video content within the limits of your connection (more specifically, its upload capacity). 

As a rule of thumb, you always want to be broadcasting a video bitrate and audio bitrate 20% lower than your upload speed. To find your upload speed, go to [Speedtest.net](http://speedtest.net) and run a speed test. Once you have your upload speed, you can then calculate the correct video and audio bitrates you'll need to use in your encoder.

For example, if you have an upload speed of 1Mbps, you want to broadcast combined video and audio bitrates of about 800kbps (i.e. an audio bitrate of 192kbps and video of around 600kbps).

If your upload speed can support higher bitrates we recommend an audio bitrate of 320kbps (for the best listening experience for your viewers) and ~2,500kbps video for a 720p or 1080p broadcast. Higher video bitrates result in increased CPU usage on your streaming computer, try lowering the resolution or video bitrate if you notice a jumpy picture.

In OBS, if you're using the 'Simple' Output mode in Settings you can update video and audio bitrates in the same section:

![OBS Simple Settings Pane](https://raw.githubusercontent.com/chewcode/Guide/master/encoder_setup/simple.png)

If you're using the 'Advanced' Output mode in Settings, you'll need to update video and audio bitrates in their corresponding tabs:

![OBS Advanced Settings Pane](https://raw.githubusercontent.com/chewcode/Guide/master/encoder_setup/advanced.png)

If you have any queries or issues with setting your bitrates, please [contact Support](mailto:support@chew.tv) or join the [Chew community Slack channel](http://slack.chew.tv) where someone will be able to help! 
