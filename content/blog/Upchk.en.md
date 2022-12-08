---
title: "Upchk - Python script for monitoring host online/offline status"
date: 2022-12-08T13:32:45+02:00
tags: ['python','coding']
draft: false
---
I wrote a Python script that pings hosts and reports the changes in their online/offline status via email. It works on it's own built-in times as opposed to cron and uses Python built-in smtp lib, removing dependency on postfix/sendmail. It's also cross-platform (Linux/Windows/Mac), although I mainly tested it on Linux, because that's what I use.

Code's [here](https://github.com/moondownr/upchk).
