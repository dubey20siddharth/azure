#Lab 4 :QnaMaker Bot

In this lab, you will build, a QnaMaker bot.

### Prerequisites
This following software environment is needed for running this bot :

```
1.Node.js
2.Microsoft BotFramework Emulator.
3.SubLimeText Editor.
```

### Collecting the keys

Over the course of this lab, we will collect various keys. It is recommended that you save all of them in a text file, so you can easily access them throughout the workshop.keys:
-Bot Framework App ID.
-Bot Framework App password.
-knowledgeBaseId.
-subscriptionKey.


### Implementation

To check implementation of this lab please refer to the following file in QnaMaker_Bot folder:

```
                             QnaMakerBot.js
```

###Check implementation through following steps

1. Open QnaMakerBot.js file in SubLime Text Editor and provide Bot Framework App ID and Bot Framework App password in this section of code. (note : If you are working on local then there is no need to specify Bot Framework App ID and Bot Framework App password  ).

![Sample Outcome](photos/qnamakerbot_0.jpg)

2.Open .env file in QnaMaker_Bot folder and paste knowledgeBaseId key and subscriptionKey collected from the QnaMaker services.

3.Open command prompt (cmd) and set path to Basic Bots folder then run QnaMakerBot.js file using command below:

                               node QnaMakerBot.js.

4.Start the Bot Framework Emulator and connect your bot. 
  -Type http://localhost:3978/api/messages into the address bar.(This is the default end point that your bot listens to when hosted locally).Click on “Connect” button.(note : If you are working on local then no need to specify Microsoft App ID and Microsoft App Password ).  
![Sample Outcome](photos/qnamakerbot_1.jpg)
  -The following screenshot shows the results of this chatbot running in the Bot Framework Channel Emulator.
![Sample Outcome](photos/qnamakerbot_2.jpg)
                                    




