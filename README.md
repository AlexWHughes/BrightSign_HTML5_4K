# BrightSign_HTML5_4K
This is an example BA Connected project file that allows you to run web pages in 4K on XT3 units (XT243/1143)

## What is this?
This is a working BrightAuthor:Connected project that forces a BrightSign player to actually render HTML5 content at **3840x2160 (4K)**.

I spent way too long figuring this out — not just how to get the device to *output* 4K (which is the easy part), but how to get it to **actually render** the HTML widget at 4K resolution. Most of the time, it says it’s in 4K, but you’re just getting 1080p stretched.

This project is tested on:
- BrightSign XT1144/XT243
- BrightSign OS 8.5.64

## Why does this exist?
Because **nobody else** documented a working, fully functional example project.

Everything I found online was either:
- Outdated
- Vague
- Or ended with "this should work" (spoiler: it didn’t)

So after too many late nights, multiple firmware tests, widget tweaks, and moments of existential doubt — I cracked it. And this file? This is the working example I wish someone else had uploaded.

## What's inside?

- A working BA Connected project file (4K HTML5.bpfx)
- An HTML5 widget with a test URL (`https://screenresolutiontest.com`) to validate rendering resolution
- A 3840x2160 canvas setup that doesn’t scale weirdly
- No weird cropping, no stretched canvas, just real 4K rendering

## Can't I just do this in BA Connected?
Most likely now they've solved their bug, yes. But just in case I want to share these files. 

## Real Talk

I seriously debated gatekeeping this project.
Not out of ego — but because I put in way too many hours of testing, reboots, and cursing at screen resolution tools to hand it over on a silver platter.
But I wouldn’t be able to sleep at night if I didn’t share this. I *needed* this exact project when I started. So here it is, for whoever needs it next.

You're welcome. This simple config cost me a lot more than money. Good luck.
— Alex
