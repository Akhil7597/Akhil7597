- (i)Title Of Project: Home Automation using AI
(ii)Group Members: Akhil Jain, Saunvid Ganbavale, Sagar Sabre
(iii)Brief Description about project implementation:

According to the proposed system, we have designed the system structure shown in the block diagram. We have designed the model in such a way that it can be kept at a safe place inside the house. All programming and components installation are done and tested inside the laboratory and in home. There are a lot of components and wires that we have used for the system. This is done in the easiest and lowest cost possible. However, the system is flexible and can be customized by the user. Changing one of the components setup has to be compatible with the right software available. Every components used in this system was programmed and tested separately for safety measures and matching with the right driver. Each component was programmed separately with both Arduino Mega and Arduino UNO using different Arduino IDE. Also they were run in different computers. Later on all were combined in a single Arduino IDE. It is not possible to run the system without the Wi-Fi and computer.

1)Android Application:
In this system we have the Android application to control all the home appliances.  From Android phone we select any home appliance from the options that appear in the App then we select ON or OFF. 
This can be done only when the user is inside the house. There should be Bluetooth connection for the App. It is related with the Bluetooth module. It allows establishing point-to-point connection with Bluetooth support devices. 
This technology is known by Android’s support for the Bluetooth network stack which permits to exchange data wirelessly.
The Android Software Development Kit (SDK) provides all necessary tools to develop Android Application (API). 
This application is a Java based program. The Android uses .apk file to install the application. The code is written in Android Studio IDE. All appliances buttons list will appear first. 
Then the user has to choose an option. Later the action button ON and OFF appears. There are 2 layouts of the code structure, two Class code and user
permission code. These are written in Android Studio IDE. The code is written according to the appearance of the options in the phone.

2)AI Chat Bot:
The AI chat bot is a sort of proof of concept that will demonstrate the possibility to remote control sensors and actuators (for example a couple of relays) via Telegram.
Telegram is an instant messaging application, similar to the famous Whatsapp. Last June,the Telegram developers announced that a new set of APIs were available to develop bots.My
idea was to develop a bot, running on my Raspberry Pi, that receives commands via Telegram chats. I connected to the Raspberry a solenoid lock and a module with two relays.
The user, through the Telegram app installed on his smartphone, starts a chat with the “bot” account; the messages are delivered to the Telegram servers.
The first step in developing your own bot, is to create it in Telegram. You create new bots or configure existing ones sending the right commands to a “built-in” bot, 
the BotFather:Start the process to create a new bot sending to the BotFather the command /newbot. You’ll be prompted for the name (display name) of your new bot and for its username.
If the process is successful, you’ll receive an authorization token, that is the “password” you must specify in your program to “impersonate” the bot.
