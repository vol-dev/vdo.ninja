---
layout:       post
title:        "Two person chat"
date:         2020-12-16 10:00:00 +0000
author:       "Steve Seguin"
categories:   basic
tags:         tag1 tag2
permalink:    2personchat
order:        4

# POSTS LIST
class:       "style3"                         # config bg-color to post list card (1..6)
list-image:  "/assets/images/pic03.jpg"       # config image to post list card (1..6)
description: >                                # config description to post list card
  Get your camera inside OBS.ninja quickly

# POST HEADER
header-image: "/assets/images/pic13.jpg"      # config image to post header
alt-image:    "image description test post a" # config image description to alt att.
---

While you can achieve a multi-person chat with a group room, you can also do it without it.

For example, `https://obs.ninja/?view=xxxxxxx&push=yyyyyy`

You'll notice that here we have the link both PUSHing and VIEWing at the same time. This allows us to view a remote video and publish a video to others, using the same website tab.  This has the advantage over using two-browser tabs as echo-cancellation will work with this approach, while with two-tabs it might not. It also is compatible with mobile-devices, where two-tabs isn't likely feasible.

The downside of this approach is that you'll need to create a custom link for every person. In this case, 

`https://obs.ninja/?view=xxxxxxx&push=yyyyyy`
and
`https://obs.ninja/?view=yyyyyy&push=xxxxxxx`
