---
layout: post
title: "Linux build updated again"
date: 2017-10-28
catagories: news
---
It is not that long ago that I updated the precompiled Linux build to be using SDL 2.0.6 instead of 2.0.5. Now I have another update. The compiled Linux build is now compiled on Ubuntu 12.04. This was a bit harder as Ubuntu 12.04 has reached end-of-life. However it was necessary as Ubuntu 14.04 is semi broken. At least the ubuntu:14.04 Docker image is broken. libsdl2-dev has been broken in 14.04 for months now. Even though I compiled my own version of SDL2 the build turned out to not work properly on other systems. Most notably the fullscreen support was broken. Well, that is now in the past.
