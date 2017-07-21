---
title: Shutter, a Snipping Tool for Ubuntu
date: 2017-07-14 23:05:25
tags: [snipping-tool, windows, linux, ubuntu, productivity]
---

Lately I've been trying to fire up Ubuntu more frequently on my trusty Thinkpad T540p at home instead of Windows 10 and I have also been playing around with Elementary OS on Virtual Box at work, instead of Windows 7.

From time to time while using Linux I'll run into a task I perform as second nature on Windows that I have no clue of performing in Linux.

Today I wanted to share a quick screen grab of something with a friend via WhatsApp web and my usual workflow is to hit the Windows key and type `snippin`, for the _Snipp_ing Tool and then wack enter, grab the pic, `ctrl+c` then `ctrl+v` into the browser window and away goes my pic. As I was running Linux at the time I had to google what to do, I wasn't really interested in hitting `PrtSc` and my whole screen.

Google lead me here: https://ubuntuforums.org/showthread.php?t=2115956 and I finally achieved my screen grab using Shutter, which works in a similar fashion to the Windows' Snipping Tool. To install run the following commands from the terminal:

```
sudo add-apt-repository ppa:shutter/ppa
sudo apt-get update
sudo apt-get install shutter
```

Credit to [slickymaster](https://ubuntuforums.org/member.php?u=1753126) for the commands to install shutter.

As much as I was pleased with being able to perform my screen grab and share after installing Shutter, I definitely prefer the Windows' Snipping Tool. In Shutter I had to save the image, open the containing folder, then finally drag and drop into the WhatsApp web browser window. When using the Snipping Tool in Windows it's a simple `ctrl+c` of your screen grab then `ctrl+v` into the browser window. One nice feature I did find though was that Shutter supported undo via `ctrl+v` when editing the screen grab, something the Windows' Snipping Tool doesn't offer.

I think Windows probably wins this round til I can find a better way. I could be missing something here so hopefully I can replicate my old workflow in Linux.