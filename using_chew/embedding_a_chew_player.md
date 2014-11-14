# Embedding the Chew Player

#### ** Only available for Studio and Tour subscribers **

If you have a website or blog and want to embed the Chew player into it, we've made the process super simple for you. You'll find your Episode's unique embed code on the Run page. From there, simply copy and paste the iframe embed code into the HTML view of your CMS or into the site code in your website. If you don't manage your website directly yourself then your content editor or website administrator will be able to do this for you.

## Embedding Over SSL/HTTPS

**We currently don't support SSL/HTTPS connections by default on all accounts.** If you attempt to embed a Chew player on an https page you may find the player is blank.

To enable ssl on your account contact [Chew Support](support@chew.tv).

## Responsive Embedding

The Chew player embed code is now fully responsive. When you copy the embed code you will see that it includes some CSS which keeps the player at the correct dimensions regardless of the width of the page.

_You can also try sharing the Chew watch page. It's already responsive and supports both desktop and mobile devices._

## Embed Code Parameters

The Chew player embed code can be customised with a combination of GET parameters passed to the embed code URL.

**countdown** (true) Show or hide the event countdown before an event starts. If set to false, the player will show a simple spinner while waiting for the stream to start.

**archive** (false) Show or hide archive content after an event finishes. **Please note, this is an alpha feature and may not work as expected in all cases.**

**autoplay** (true) Autoplay when the player loads.

**pause** (true) Allow the user to pause playback.

**fullscreen** (true) Allow the user to go fullscreen.

**mute** (false) Mute the audio. Please note that if combined with controls=false there will be no way to unmute the audio.

**scrubbing** (true) Disable the footage scrubber. This also disables access to the live DVR archive.

**loop** (false) Loop archive or live DVR content.

**rebroadcast** (false) Rebroadcast the live event once the broadcast is over. 
**Please note, this is a Studio or Tour feature and will not be applicable to Free or Studio users.**

**color** (f05a35) Set the background colour of the control bar.

**iconcolor** (000000) Set the icon colour on the control bar.

**controls** (true) Show the player controls.

**bandwidthdetection** (true) Disable automatic bandwidth detection.

**forcebandwidth** (source|360|160) Force the player to take a specific bandwith stream. **Please note, not all bandwidths are available on all plans.**

**scaling** (fit) Change how the video scales to to its container:

 - 'fit': fit to window by preserving the aspect ratio encoded in the file's metadata
 - 'half': half-size (preserves aspect ratio)
 - 'orig': use the dimensions encoded in the file; if the video is too big for the available space, the video is scaled preserving the aspect ratio
 - 'scale': scale the video to fill all available space; ignores the dimensions in the metadata