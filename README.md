# Integrating-ChatGPT-into-Discord

### Introduction:

In today's fast-paced world, it is crucial to have quick and efficient access to information. As the consumption of video content continues to grow exponentially, finding a way to extract key information from these videos becomes increasingly important. This guide will explore the innovative integration of ChatGPT with Apple's Siri voice assistant, focusing on the automatic generation of video content summaries. By combining the advanced language processing capabilities of ChatGPT with Siri's user-friendly voice interface, we unlock a powerful solution for streamlining information retrieval.

### Steps for Integrating ChatGPT into Discord

**Step 1 Create an account/login to account** [ChatGPT Website](https://chat.openai.com/auth/login)
1. When using chatGPT for the first time, go to the chatGPT website to create an account

![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrating-ChatGPT-to-siri/blob/f1d2e83ecaab9697e5c99dbefbf21963fa44e586/Image/WX20230324-143335.png)

2. Click on "Sign up" to register account, or "Log in" if you have one.

![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrating-ChatGPT-to-siri/blob/f1d2e83ecaab9697e5c99dbefbf21963fa44e586/Image/WX20230324-143253.png)

**Step 2 Access to ChatGPT API**
1. Once logged in, go to this website for API claims:(https://platform.openai.com/account/api-keys)
2. Login to account and click on "Create New Security Key" to create the API key.

![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrating-ChatGPT-to-siri/blob/4adb3d68c622b29b0963f103fb00953b836b82b0/Image/WX20230324-144724.png)
**Notice:** The key will only be displayed once!!! Remember to keep it safe! If the key is not saved in time, it will have to be recreated!

**Notice:** Every API comes with limited free quota, for details please see [API documentation](https://openai.com/pricing).

**Step 3 To obtain a Discord token:**

1. Log in to the Discord Developer portal. [ChatGPT Website](https://discord.com/developers/applications).
2. Create a new application by clicking "New Application" in the top right corner of the "Applications" section on the left side of the screen. Enter the name of your bot and click "Create" to proceed to the next page.
3. On the next page, click on the "Bot" tab on the left-hand side and then click the "Add Bot" button to create a bot for your application.
4. Copy the token by clicking on the "Copy" button next to the token field.
5. Go to the "Bot" section of your application.
6. Find the bot you just created and click on the "Add Bot" button on the right-hand side.
7.Scroll down to the "Token" section and click on the "View Token" button to reveal the token.
8.If you have already generated a token before, the button will be labeled "Reset Token" instead.
9.Scroll down to the "Privileged Gateway Intents" section and toggle on the "Message Content" intent.
10.Click on the "Save Changes" button to save your changes.

**Step 4 To set up OAuth:**
1. Go to the "OAuth2" section on the left-hand side of your application.
2. Click on the "URL Generator" option.
3. In the "SCOPES" section on the left-hand side, select "bot" and in the "BOT PERMISSIONS" section on the right-hand side, select "Administrator".
4. Copy the URL at the bottom of the page and paste it into your web browser.
5. Select the server you want to add the bot to.
6. Click "Continue" and authorize the bot to join the server.

### Support Me with a Cup of Coffee ☕
If you think this small application useful and would like to show your appreciation, please consider buying me a cup of coffee to support my efforts! Your generosity will not only fuel my motivation to continue working on this project, but also help me cover the costs associated with development and maintenance.

To buy me a coffee, simply scan or clik below:

![Github Octocat mascot](https://github.com/JiaxiongWeng-Conor/Integrating-ChatGPT-to-siri/blob/353dc1ae3fdcc5ca2f2e4a8f8c017fddb3a051b1/Image/IMG_6200.jpg)

[Link of venmo](https://account.venmo.com/u/Jiaxiong-Weng)


Thank you for your support! 🙏
