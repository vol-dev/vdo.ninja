---
layout:       post
title:        "High-def camera"
date:         2020-12-16 10:00:00 +0000
author:       "Steve Seguin"
categories:   hd
tags:         tag1 tag2
permalink:    high-def-camera
order:        3

# POSTS LIST
class:       "style2"                         # config bg-color to post list card (1..6)
list-image:  "/assets/images/pic02.jpg"       # config image to post list card (1..6)
description: >                                # config description to post list card
  Get your camera inside OBS.ninja quickly

# POST HEADER
header-image: "/assets/images/pic13.jpg"      # config image to post header
alt-image:    "image description test post a" # config image description to alt att.
---

You can customize the playback of videos by added parameters to the OBS.Ninja URL links, along with many other aspects. OBS.Ninja is highly flexible in this regard, letting you achieve your desired outcome without needing to code and without additional software.

For example, `https://obs.ninja/?view=xxxxxxx`, could be amended to `https://obs.ninja/?view=xxxxxxx&bitrate=500`, which will target a video bitrate of 500kbps.

Multiple parameters can be appended together by using the separating charater "&".

`http://obs.ninja/?view=xxxxxxx&bitrate=500&stereo=1`

The default publishing video bitrate of most modern browsers is around 2500-kbps, but we can achieve higher quality if we manually set this to something higher.

`http://obs.ninja/?view=xxxxxxx&bitrate=6000`

You'll notice that we added &bitrate=6000 to the viewer's side and not the publishing side.  The viewer gets to control the bitrate; every viewer can set their own custom video bitrate in fact.

On the publishing side, the default target resolution will be 1280x720 @ 60-fps, but we can set this higher by adding &quality=0 to the push link.
`http://obs.ninja/?push=xxxxxxx&quality=0`

For 1080p60 gaming, you'll want to set the video bitrate to 12000-kbps or higher, as lower bitrates might cause the frame rate to be quite low otherwise.  Otherwise, for talking head-type videos, the default video bitrate is often going to be adequate.
