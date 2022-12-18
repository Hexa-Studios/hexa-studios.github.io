---
title: Debugging Safari Mobile
date: 2022-03-02T09:08:25.000Z
date_updated: 2022-03-02T09:08:25.000Z
description: Quick steps to debug Safari Mobile using an iOS simulator on Xcode. 
---

I ran into a problem with a react web app that was only failing on iOS devices. I couldn't understand the problem without debugging the issue on a device with safari and it took me a while to find them - so here they are in all their glory.

## Quick steps to debug Safari Mobile using an iOS simulator on Xcode. 

### Pre-requisites
- Xcode
- Simulator
- Safari

## Steps

Full steps including setup

1. Open Simulator and browse to a website on the Safari browser.
2. Open Safari on the desktop
   - If you don't have developer options enabled:
     - Safari > Preferences
     - Click Advanced
     - Check the box > Show Develop Menu
3. Select Develop, your simulator should be available
4. Select the simulator and select the web address of the page from your simulators safari browser.
5. The console and developer tools are now working as if it was a standard web browser

[Here's a YouTube I found with fuller steps](https://www.youtube.com/watch?v=R9PRC8n1Gv4)