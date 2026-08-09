# VortexCollab
Vortex Studio Collab is a fan-made project that is supposed to replicate Team Create before it gets added. :D
**VortexCollab is currently an early version. Back up your Vortex projects before using it!**

# REQUIREMENTS
Windows
Internet Connection
Vortex Studio

# HOW TO INSTALL
Simply download it through the releases and extract it. Keep in mind you obviously require Vortex Studio to use this.

# HOW TO USE
Boot up the application. You are supposed to see your client ID and this:

1. Create room
2. Join room
3. Exit

So this depends on what you want to do.

**Hosting:**

To host, type 1 in the console app and press enter.
It will give you a room code and will ask you for your project path. Vortex Studio saves your files inside the Documents folder. That means you need to type 
"C:\Users\YOUR_USER\Documents\Vortex Studio\testing.json"
**DO NOT REMOVE THE QUOTES!!** AND REPLACE YOUR_USER WITH YOUR WINDOWS USER NAME

Send the room code to the people you want to collaborate with. Then boot up the file in Vortex Studio and press CTRL + S to save the file and send it to everyone else in the room. To see the progress of other people in the room, restart Vortex Studio and boot up the file again

*I recommend saving it every time you build something big, not after you move 1 part.*

**Joining:**
To join, type 1 in the console app and press enter.
It will ask you for a room code, enter the room code you have received.
Type 4 in the console app and press enter, it would ask you how to save the project file. Type in the name file you want it to be called
Example: "testing". It would save in C:\Users\YOUR_USER\Documents\Vortex Studio

Then boot up the file in Vortex Studio and press CTRL + S to save the file every time and sent it to everyone else in the room. To see the progress of other people in the room, restart Vortex Studio and boot up the file again

*I recommend saving it every time you build something big, not after you move 1 part.*

# SERVER LIMITS
Maximum rooms ------------ 100
Maximum users per room ---- 16
Message size -------------- 1 MB
Message rate -------------- 20/s
Burst limit --------------- 100

# KNOWN LIMITATIONS

**No Vortex Studio Part ID'S:**
Halo hasn't included part ID's for every part, that means the app replaces ID'S with part names. So before you save, make sure there are no parts with the same name.
For example:
`Part
Part
Part`
isn't treated as
`Part
Part1
Part2`
So please do not keep the parts with the same name.

**Simultaneous edits**
Vortex Collab currently doesn't have a full conflict-resolution system.
If two users modify the same property at nearly the same time, the result may depend on which change reaches the other clients first.

**Project format changes**
Vortex Collab relies on Vortex Studio JSON save files.
If Vortex changes the JSON format, some synchronization features may stop working until VortexCollab is updated.

# ROADMAP

**Planned features:**
- Better part identification when Vortex adds IDs
- Improved UI
- Better error handling
- Improved conflict handling
- Improved servers

**Feedback/bug:**
(The best way to report bugs is the discord server)
If you encounter a bug, please include:
- What you were doing
- What you expected to happen
- What actually happened
- Any error shown by Vortex Collab
- Your Vortex Studio version

# THANK YOU FOR USING VORTEX STUDIO AND VORTEX COLLAB!
