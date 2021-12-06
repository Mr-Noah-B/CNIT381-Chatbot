# CNIT381-Chatbot
A Chatbot created for the CNIT 381 final project

This file is also used to help setup the bot, and run it off of your own computer. 

Prerequisites:   
Visual Studio Code: For editing the commands, as well as running the bot  
Webex Account, Webex teams: For interacting with the bot, as well as creating new bots, if desired  
A Web Hook using Ngrok: For the bot to be able to send and receive messages through Webex Teams. the command to get your webhook is **ngrok http 5000** 
Bots Email & Teams Token: To fill out the necessary fields in the 381Bot.py and useless_skills.py files 

Step 1: Download all of the Bots files, and put them in a directory that can be accessed by Visual Studio Code.

Step 2: Open the 381Bot.py file in Visual Studio Code, and fill out the bot_email, teams_token, and bot_url fields, with your bots Email, Webex Teams access token, and Webhook address respectively. Then, in the useless_skills.py file, put the bots Teams access token in the teams_token field.  
<pre>
--The fields to fill out in 381Bot.py
<img align="left" width="401" height="127" src="https://github.com/Mr-Noah-B/CNIT381-Chatbot/blob/main/Img/Image-1.JPG"> 
 </pre>
 <pre>
--The field to fill out for useless_skills.py  
<img align="left" width="374" height="68" src="https://github.com/Mr-Noah-B/CNIT381-Chatbot/blob/main/Img/Image-2.JPG">  
</pre>
Step 3: Update the routers.py file with your routers IP address

Step 4: In Visual Studio Code, open a terminal in the directory where you put the files for the bot, and run the command **python3 381Bot.py**, which should run the bot in the terminal.
<pre>
--When the bot is running, it should look similar to this  
<img align="left" width="1437" height="375" src="https://github.com/Mr-Noah-B/CNIT381-Chatbot/blob/main/Img/Image-3.JPG">   
</pre>
Step 5: Open up Webex Teams, find your bot, and begin chatting with it  
<pre>
--An example of The bot being run
 <img align="left" width="1437" height="375" src="https://github.com/Mr-Noah-B/CNIT381-Chatbot/blob/main/Img/GenieBotIntro.png">  
</pre>
And that is how, using the provided files, you can have a Webex Teams Chatbot running.
