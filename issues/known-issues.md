---
layout: article
title: Known Issues
published: true
---

##Known Issues
###A list of known issues and resolutions. Updated weekly.

####Login Credentials Not Remembered (Windows)

There is an issue where the Windows desktop client will ask a user to login upon startup, even if the Remember Password option has been enabled. Our developers are aware of this issue, and are working on creating a permanent fix. In the meantime, below are instructions for a workaround:

1. Uninstall Bitcasa
Click *Start* and then click *Control Panel*.
Click *Uninstall a program* under Programs.
Select Bitcasa and then click *Uninstall*.
2. Delete the Configuration File
Click *Start*, type *%appdata%* in the Start Search box, and then click *Roaming* in the list.
Locate and delete the folders named *com.bitcasa.Bitcasa* and *Bitcasa*.
3. Download the most recent version of Bitcasa here: <https://www.bitcasa.com/download>
4. Reinstall Bitcasa.
5. Enter your login credentials and close Bitcasa. Bitcasa will then bypass the login screen upon opening the application.

####Files are grey in the desktop application; 1984 date (Mac)

Users of the Mac Desktop App have reported that some image files and PDF files which have been dragged into the Infinite Drive or a subfolder become greyed out. These files appear to be locked by Finder, and the “Date Modified” reads “xx/xx/1984.” We're working on a fix! See the instructions below for a current workaround to unlock these files:

1. Open the Terminal and type: **"xattr -c"**
2. Drag the greyed out files from Finder into the Terminal window.
Hit “Enter.”
3. The greyed out files should appear black again, and be accessible to the user.

We know, it's not [1984](http://www.youtube.com/watch?v=KvkKX035484). 

####Bitcasa Infinite Drive "ejects", appears to be empty (Mac)

The Bitcasa Infinite Drive may at times "eject" arbitrarily, and then appear as empty. When this happens, users will see that the green Bitcasa icon has changed to a blue, generic folder icon. Furthermore, when looking in the console log, users may see eject errors associated with the Bitcasa Infinite Drive. We're working on a fix. 

####Slowness, timing out when sharing a Bitcasa link

When clicking a Bitcasa shared link containing a large amount of data, then selecting *Add to Bitcasa*, some users may experience slowness with the content being added to the Bitcasa Infinite Drive. In some instances, users may receive an error message that reads *Something went wrong* after approximately 30 minutes, indicating that the share has timed out. We're working to resolve this issue. 

####Finder restarts upon exiting the Bitcasa desktop application (Mac)

When you exit the Bitcasa desktop application for Mac, you will see that if Finder is open, it will close and restart. This is to remove the Bitcasa contextual menu from Finder. We're working to make sure that in a future update, Finder doesn't restart after exiting Bitcasa.





