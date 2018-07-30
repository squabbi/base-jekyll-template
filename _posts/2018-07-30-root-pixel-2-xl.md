---
date: 2018-07-30 21:10:11 +1000
title: Root Pixel 2 (XL)
video_id: M-0NIUUvYI4
description: A video guide on rooting your Pixel 2 (XL) using Magisk & Magisk Manager
categories:
  - pixel-2
resources:
  - name: Magisk Beta
    link: >-
      https://forum.xda-developers.com/apps/magisk/beta-magisk-v13-0-0980cb6-t3618589
type: Video
set: pixel-2
set_order: 2
---

A guide on rooting your Pixel 2 and Pixel 2 XL.

## Pre-requisites

* A computer
* Time
* A brain

## Downloads and Links

1. [Google USB Drivers (for Windows only)](https://dl-ssl.google.com//android/repository/latest_usb_driver_windows.zip){: target="_blank"}
2. [Android SDK Platform Tools (ADB & fastboot)](https://developer.android.com/studio/releases/platform-tools.html){: target="_blank"}

## Before Starting

This procedure will wipe your device's internal storage. Please make a backup of anything you need as unlocking the bootloader will factory reset your phone.

I will not take any responsibility for any damages done by following this guide. However, this guide was written as a complementary item to my video, which worked on my Pixel. Magisk may not be able to bypass SafetyNet in the future, with this cat and mouse game between SafetyNet and Magisk Hide. Be prepared for SafetyNet dependent apps to stop working in the future, and always keep an eye on Magisk releases and SafetyNet news.

Read any newer, more relevant instructions wherever possible as this written guide cannot and may not be 100% up to date, all of the time.

## 👨‍🍳 Preparing your Pixel

We need to enable OEM unlocking before we are able to unlock the bootloader, as a security measure in place since Marshmallow (Android 6.0). For this, we need to enable the Developer options. Start by going to Settings, then navigating to System and selecting About Phone. Scroll down to the bottom and tap on the build number until you enable the developer options, you will need to confirm using your pattern.

Once the developer options are enabled, go back once and select Developer options. Find OEM unlocking and enable (✔️) that, you will need to confirm with your pattern. Also locate USB debugging and enable (✔️) that as well.&nbsp;