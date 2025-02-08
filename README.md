# PTCG Check Friend Macro for Macrodroid

This macro have been designed to work with **Arturo's PTCGPB** and works only on **Android**

I tested it with 2 phones with different resolutions so it should work on yours too, [here is a video showing it in action](https://drive.google.com/file/d/1JPXEf0MJKQAhgtauZBxr2hyxhtZEhWAv/view?usp=sharing)

This macro can be used to automatically check for new friends and add them as they appear
To avoid spamming server request the macro refresh the social hub every 4-6 seconds so you should specifiy a waiting time around 10-15s 
It works using random timing variation when clicking buttons to be a bit safer

The variant macro Clean & Check Friends can be used to remove all friends first then accept all profiles, it can be usefull when your requests are full of old bots that are already done removing ppl
It's dependent of the Check Friends macro so you do need to have both installed if you want to use it and **be in the friend request page before you use it**

# Installation

- First you need to install macrodroid
- Download the .macro on the repo on your phone then choose to execute with MacroDroid
- You'll be prompted to change permissions so Macrodroid can do stuff on his own like emulating clicks on your screen, feel free to analyze the code before, it's not that much long
- At this time it requires you to change your device screen resolution (look at the 2 firsts lines when you load the macro)
- On the bottom right you should see a button with a "+", click it until it does not ask you to change permissions anymore
- Start PocketTCG and click the little "Check" icon
- To stop it, increase the volume

# Compatibilities

Known working Screen res :
- 2700x1224
- 2400x1080

# Issues

Feel free to increase the waiting times if your phone is pretty slow when opening menus

If it does not manage to check when a new friend appears, it might not be compatible with you screen resolution

If after pressing the macro, the social hub do not even update every 4-6 seconds, it means that macrodroid do not have the rights to emulate click on your screen, on non-rooted devices it can happens frequently the first time installed, restarting you phone should fix the issue


