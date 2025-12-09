---
layout: post
title: "Linux build updated"
date: 2017-10-15
categories: news
---
I have updated the standalone Linux build to use SDL 2.0.6 instead of SDL 2.0.5. SDL 2.0.5 apparently has a problem with keyboard input that resulted in some keys being recorded double. This seems to only affect Ubuntu. I have updated the standalone package. While the new one has working keyboard support it appears that there still are some problems with the fullscreen support. It is weird as the version compiled against the distributions version of SDL2 works perfectly. I guess creating a standalone version is just problematic that way... still want to figure it out though.
