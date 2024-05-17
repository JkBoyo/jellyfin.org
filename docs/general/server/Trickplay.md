---
uid: server-trickplay
title: Trickplay
---

# Trickplay

These settings relate to the quality, frequency, and delivery with which the server generates trickplay preview images when scrubbing through video. This feature was implemented as of 10.9.0.

## Supported Platforms

Currently Trickplay is only supported for the web, desktop, Android phone, and iOS clients. 

## Hardware Decoding/Acceleration

These options enable hardware decoding/encoding either when files are scanned or when you're parsing them on the client. Acceleration is only avilable with QSV and VAAPI acceleration methods.

# Common Troubleshooting Practices

Currently Trickplay has no way to delete generated images. You can refresh the metadata scan which can replace misgenerated images. 

If you decide you want to delete trickplay images you can go into the cache section of the server and delete the temp and images folder. This will delete most of your images but if you unselect trickplay in your dashboard before the scan completes you will no longer have trickplay images.