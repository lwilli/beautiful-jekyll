---
layout: post
title: How to Transfer Mac Notes to Evernote
subtitle: Automatically export notes from Mac Notes and import them into Evernote.
---

I recently switched from an iPhone to an Android and realized that I no longer had easy access to all my iCloud notes. Evernote seemed like a good cross-platform alternative, so I decided to make the switch, but there didn't seem to be an easy way to import my notes from Mac Notes into Evernote. 

After some research, I came across a [forum thread](https://discussion.evernote.com/topic/4046-importing-from-apple-mailapps-notes/) with an AppleScript script to copy notes from Notes to Evernote. Although [d.b.walker's script](https://discussion.evernote.com/topic/4046-importing-from-apple-mailapps-notes/?do=findComment&comment=236445) works great, it doesn't maintain the folder structure of the notes. So, I extended d.b.walker's solution to copy the folders with the notes from Notes to Evernote with the AppleScript script below.

**To import your Mac Notes into Evernote, follow the steps under "How to run" in the script below.**

{% gist dbdc6b350bc1005e6d0852c538c6e767 %}