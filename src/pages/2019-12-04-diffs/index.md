---
title: Diffs
path: /2019-12-04-diffs
category: Code
date: 2019-12-04
image: ./screen_shot_2019-12-05_at_12_04_55_am.png
---
I played today with [pixelmatch](https://github.com/mapbox/pixelmatch). I want to be able to detect difference between screens from day to day.

One of the challenges of using pixelmatch is the difference in sizes when you are capturing full screen websites. If the images don't match in size, the script raises an error. I have been writing some code to overcome that problem.