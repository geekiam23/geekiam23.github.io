---
layout: post
title: Bloc Jams
thumbnail-path: "img/bloc-jams.png"
short-description: Bloc Jams is a Spotify clone built with jQuery and rebuilt with AngularJS.

---
{:.center}
![]({{ site.baseurl }}/img/bloc-jams.png)

## Explanation

Bloc Jams is a completely practical music player, developed first with JavaScript, then recreated with jQuery and AngularJS. Some of Bloc Jams’ most important features include the ability to replay, skip, and mute songs. Buzz library was used to support music playback (along with a variety of other functions).
 
## Problem
 
Bloc Jams is a browser-only replica of Spotify. The website has three states - landing state for information, a collection state that was used to accumulate available albums on one page to select, and an album state where users could listen to an album. The player bar, located at the bottom of the album page, lets users have total control over the album that is currently playing. 
 
## Solution
 
Bloc Jams’ service does the majority of the heavy lifting in this Angular SPA. Through this (custom) Angular service, songs from the available album are stopped/started, muted/unmuted, and skipped or replayed. The custom Seek-Bar directive allows the user to adjust volume and song playback position from the player bar.
 
## Conclusion
 
Bloc Jams provides a quality user experience with a sample album. It was a lot of fun experimenting with Angular and jQuery. 
