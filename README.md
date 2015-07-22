ubuntu-airplay 0.0.23
===

I have always been annoyed about how iOS, Mac OSX, and all of Apples proprietary hardware/software has inhibited so many of us technology savvy people.  

Project Status:
---
I've found multiple other open source projects which can interface with airplay servers, now I need to implement some.  
I know that it's possible to stream video, pictures, and sound is supported from Pulseaudio, but this project won't be complete without screensharing.  

I am currently learning and planning how to move forward.

Project Details:
---
Right now it's Python 3 using the QT system from PyQt4.  
It is designed for Ubuntu/Linux only, but I'm trying to make this thing OS-independent.  
From my last testing, this ran fine on my Dad's Windows 8 laptop, and I've tested 14.04-15.04.

Requirements:
---
See the `dependencies.md` file for installing the needed software.

Why I'm doing this:
---
I go to a school where everyone has iPads as their learning tool, which are horrid for coding/programming and software development, but make a good classroom common tool. As a result, there is an Apple TV in every single room for the students to quickly present whatever is on their screen, and the teachers can show their presentations with their assigned Macbooks.

I am one of two people at this school who use Linux (Ubuntu) and who bring their laptops every day. I use mine for school work fairly often, as I understand how much I can do in Linux and not iOS. But whenever some task comes up where I'd need to airplay my work to an Apple TV, I'm being restrained to my iPad.

What this aims to be:
---
This application is designed to sit in your System Tray just like in OSX, with a drop down list of available Airplay Recievers, and allow you to:
- Stream your desktop
- Send a photo/picture
- Play a video
- Stream Music  
And whatever else the users and developers of this project wish it to be.

Want to help?
---
I'm always looking for contributors, if you can help with any of these I'd love to work with you.  
 * Python network discovery protocols (for finding listings of devices)
 * Airplay/Media protocols
 * Python Qt (thinking about things like screen capture)
 * And developers to help make this work for non-Ubuntu OSs.
