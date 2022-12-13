# AutoInstall-McServer
---------------------------------------------------
Automatic installation of an minecraft server Linux
---------------------------------------------------
HOW TO INSTALL:

1. Download the file
2. Open the terminal
3. Run by writing ./autoMcServer

----------------------------------------------------
HOW TO USE:

1. Once you're done with the installation, you'll need to agree the EULA by running the following commands:
	1a. java -Xms1024M -Xmx1024M -jar server.jar nogui #NOTE: This will cause an error
	1b. nano eula.txt
	1c. (this isn't a command) in the file, you change the eula to "false" instead of "true"
	1d. STRG + X for leaving, then y for yes and then press enter
2. You will need to open port 25565 on your router, this can be different for each router, so the best would be
   to google how it's done for yours
3. start the server with: java -Xms1024M -Xmx1024M -jar server.jar nogui
IMPORTANT HERE: 1024M stands for the amount of RAM you want to use, here it is 1024 MB, or 1GB, you can change
this depending on how much you want to use and how much you are able to give 

