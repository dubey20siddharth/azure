#Lab 1 :Cognitive Services Bot

In this lab, you will build, a cognitive services bot which is used for testing cognitive services.

### Prerequisites
The following software environment is needed for running this bot :

```
1.Node.js
2.Microsoft BotFramework Emulator.
3.SubLimeText Editor.
```

### Collecting the keys

Over the course of this lab, we will collect various keys. It is recommended that you save all of them in a text file, so you can easily access them throughout the workshop.keys:
-Bot Framework App ID.
-Bot Framework App password.
-Text Analytics API.
-Computer Vision API.
-Custom Vision-Url.
-Custom Vision-Prediction-Key.
-Face API. 


### Implementation

To check implementation of this lab please refer to the following file in cognitive_services_bot folder:

```
                             cognitive_services_bot.js
```

###Check implementation through following steps

1. Open HelloBot.js file in SubLime Text Editor and provide Bot Framework App ID and Bot Framework App password in this section of code. (note : If you are working on local then there is no need to specify Bot Framework App ID and Bot Framework App password  ).

![Sample Outcome](photos/HelloBot_0.jpg)

2.open .env file in cognitive_services_bot folder and paste all keys which you already collected and save.

3.Open command prompt (cmd) and set path to Basic Bots folder then run cognitive_services_bot.js file using command below:

                               node cognitive_services_bot.js.

4.Start the Bot Framework Emulator and connect your bot. 
  -Type http://localhost:3978/api/messages into the address bar.(This is the default end point that your bot listens to when hosted locally).Click on “Connect” button.(note : If you are working on local then no need to specify Microsoft App ID and Microsoft App Password ).  
![Sample Outcome](photos/cognitive_services_bot_0.jpg)
  -The following screenshot shows the results of this chatbot running in the Bot Framework Channel Emulator.
   -Menu Output.
   ![Sample Outcome](photos/cognitive_services_bot_03.jpg)
   -OCR Output.
   ![Sample Outcome](photos/cognitive_services_bot_2.jpg)
   -Custom Vision Output.
   ![Sample Outcome](photos/cognitive_services_bot_3.jpg)
   -Face Description Output.
   ![Sample Outcome](photos/cognitive_services_bot_4.jpg)
   -Image Analytics Output.
   ![Sample Outcome](photos/cognitive_services_bot_5.jpg)
   -Text Analytics Output.
   ![Sample Outcome](photos/cognitive_services_bot_6.jpg)

                                    




