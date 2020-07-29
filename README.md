# Radar-FB8202475

### Basic Information
#### Please provide a descriptive title for your feedback:
Broken Auto layout constraints in AVPlayerViewController top info bar

#### Which area are you seeing an issue with?
AVKit

#### Environment
Apple TVOS 13.4.8 (17M61)

#### What type of feedback are you reporting?
Incorrect/Unexpected Behavior

### Description
Please describe the issue and what steps we can take to reproduce it:
Auto layout errors appear in the console when the top info bar is presented.

Steps:
- Create an instance of AVPlayerViewController
- Make it play some content
- Swipe down to show the top info bar with audio and subtitles settings

The following auto layout errors appear in the console:
https://gist.github.com/dcordero/3e075345f0fc82a103b343f0aa6f439e
