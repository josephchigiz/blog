---
title: Weather Report Viewing On The Command Line
date: 2024-01-30T12:19:20+05:30
tags: ["Weather", "Command-line", "Linux", "Curl"]
---

I discovered a handy command-line tool for checking the weather report while watching [Mischa's video](https://youtu.be/bzkrmkGDQJA).
To check the weather, you should have [curl](https://curl.se/download.html) installed and then run the following in your command-line

```shell
$ curl wttr.in
```

This will show a weather report based on your location. You can also view other locations e.g

```shell
$ curl wttr.in/Tokyo
```

Find more in their Github - link given below.

Have fun with it!

### Links

https://github.com/chubin/wttr.in
