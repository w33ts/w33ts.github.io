---
title: 'WWHF Badge Wardriving for Fun and Laziness'
date: 2025-02-07
permalink: /posts/2025/02/wwhf-wardriving-laziness/
tags:
  - conference
  - security
  - wifi
---

I'm both lazy and awkward. So when I learned that the badge challenge at WWHF in Denver would require me to find the scanners and scan my badge, I said "hell no, I don't wanna talk to people!"

The Infrastructure
======
After enumerating the badge, dumping the firmware, and giving it a little kiss goodnight, I figured out how the RFID and reporting system works to count badges for the leaderboard when scanned by a scanner. It's all based around MAC addresses.

The Big Funny
======
Well, these devices are all using WiFi because... well of course they are. I just so happened to have my Hak5 WiFi Pineapple with me. Who doesn't bring their entire kit to a security conference knowing that it'll collect dust?

I walked around during the conference, collected all of the MAC addresses in the air, and fed them to the scoring server. Plenty of failed attempts, of course. However, I eventually figured out the manufacturer range that was in use and narrowed down my attempts. This took me most of the way into 3rd place for the badge competition.

Also, I got reset for enumerating and brute forcing the MAC addresses before the conference started during the training days. Oops. Sorry.
