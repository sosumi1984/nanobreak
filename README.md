# nanobreak
Jailbreak-related research for the iPod Nano 6/7 generations. Also includes the files needed to poke around the Nano 6/7 generations' code.
Hello. Thanks for visiting the nanobreak GitHub! This is a dumping ground for all findings relating to the iPod Nano 6/7 that may lead to a jailbreak in the future.
Most people have given up on the prospect of jailbreaking the Nano 6/7 (Last real activity for this stuff seems to be around 2018), but with my recent re-discovery of my Nano 6/7, I'm ready to be the head of the project.
The files currently on the page are as follows: A version of extract2g compiled for Mac, the latest firmware files for the Nano 6/7, and extracted versions of those firmware files. 

# What we know so far
At the moment, there isn't much of use that has been discovered. You can easily manipulate the homescreen of the Nano 6/7 with a simple edit to a plist file, but at the moment, that doesn't have much use. A file within the extracted Nano 6/7 ipsw files contains either 9 or 11 different firmware files, depending on which iPod you are looking at. Out of these 9 or 11, only one is currently openable. All others are encrypted. The only one we have access to is rsrc.fw, which can be mounted as an img file, allowing us to poke through the contents. 

# Extracting Firmware.MSE from the Nano 6/7 IPSW
Extracting the Firmware.MSE file to view the files contained inside is quite easy, thanks to a tool called Extract2G. The github link can be found [here.](https://github.com/win32kbase/extract2g) The compiled version on the linked GitHub page is compiled for Windows and Linux. My GitHub repo has a version compiled for MacOS. After running the extraction command, you should have 9 or 11 firmware files, depending on whether you extracted the Firmware.MSE file for the Nano 6 or 7.
