# Error detection video series

Copyright 2018 Ben Eater

This code is [MIT licensed](http://en.wikipedia.org/wiki/MIT_License).

## What is this?

This repo contains the code to accompany a YouTube mini-series on reliable communication, error detection, and correction. To have any idea what's going on here, you should watch the videos:


## Reliable data transmission

[<img src=https://img.youtube.com/vi/eq5YpKHXJDM/maxresdefault.jpg width=360/>](https://www.youtube.com/watch?v=eq5YpKHXJDM)

This is the first video in the series and covers mostly setup for the future videos. In the video we build a simple transmitter and receiver:

 * [`/transmitter`](/transmitter)
 * [`/receiver`](/receiver)


## Parity checking

[<img src=https://img.youtube.com/vi/MgkhrBSjhag/maxresdefault.jpg width=360/>](https://www.youtube.com/watch?v=MgkhrBSjhag)

Parity checking is a basic technique for detecting errors in data transmission. This video explains how it works and walks through building hardware to compute and check parity. The receiver code is identical to the previous video. The transmitter is only slightly different:

 * [`/transmitter-parity`](/transmitter-parity)
 * [`/receiver`](/receiver)


## More?

The rest of the videos are coming soon!
