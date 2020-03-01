---
layout: post
title: Split screen
date: 2020-03-01 11:04:14
Author: Xiang Li
tags: [surface,screen]
comments: true
# toc: true
---
```
xrandr --output DP-1 --scale 2x2
```
Stop Flicker
```
xrandr --output eDP-1 --scale 0.9999x0.9999
```
```
xrandr --output eDP-1 --auto --output HDMI-2 --auto --scale 2x2 --right-of eDP-1  # Simpler oneliner scaling
xrandr --output eDP-1 --scale 0.9999x0.9999  # Stop flicker
```