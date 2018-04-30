# Infrastructure Setup

This module is for Infrastructure setup to run ChatBot.


### Prerequisites

The following platform Installations should be done before running ChatBot in any system:

```
1.Install Node.js.
2.Install Bot Framework Emulator.
3.Install Sublime Text editor.

```

### 1.Install Node.js

To install node.js use this URL link:https://nodejs.org/en/download/.)  Click on option as per configuration of working system.

![Sample Outcome](photos/infra_setup_node1.jpg)

a) Click on Node.js setup file which is downloaded on your PC then click on next.

![Sample Outcome](photos/infra_setup_node2.jpg)

b)Accept license aggrement and click on next.

![Sample Outcome](photos/infra_setup_node3.jpg)

c) Specify path to install node.js.

![Sample Outcome](photos/infra_setup_node4.jpg)

d) Choose npm package manager for node.js and click on next.
 
![Sample Outcome](photos/infra_setup_node5.jpg)

e)Install packages which are necessary to run chatbot.
  -Open node.js command prompt.
  -create a folder for your bot,cd into it,and run npm init.
  -Install botbuilder and restify module using npm command:
```
npm install –save botbuilder
npm install –save restify
```

### 2.Install  Bot Framework Emulator.

a)To install Microsoft bot framework emulator use this link: https://github.com/Microsoft/BotFramework-Emulator/releases.

![Sample Outcome](photos/infra_setup_node6.jpg)

b)If you're running the Bot Framework Emulator behind a firewall or other network boundary and want to connect to a bot hosted remotely, you will need to install and configure tunneling software.
c)Use this link to download: https://ngrok.com/download.Configure the path to ngrok in the emulator's App Settings dialog.Verify the emulator is able to successfully launch ngrok.

### 3.Install Sublime Text editor.
1.Use this link to download sublime text editor: https://www.sublimetext.com/download.
