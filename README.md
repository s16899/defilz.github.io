# Discord bot

Welcome to my github page, so today I will teach you some simple discord.js V12 commands
So if you are excited, lets get started

if you need any help, DM me in discord. my discord ID : NotDec#1631

# FAQ(S)

First question : What is discord.js?
Discord.js is a coding language which is for coding discord bots in JavaScript.

Second question : What will you learn today?
What you will learn today : 
- Printing simple text in javascript
- How the bot will be launched
- How to create your first command in discord.js (DELETED)

Third question : What is easier coding language to code discord bots in general, JavaScript or Python?
Well to answer this question, lets first see how it works.

This is how you print in JavaScript : 
``
console.log("Hello world!");
``

What it does here is that the console will sends message of "Hello world!" to the console.

now This is how you print in python : 
``
print("Hello world!")
``
So what it does here is that this code prints in Hello world! in the console.

Overall, JavaScript is a bit more advanced than python

lets now get into how to code discord bot!

# Lesson 1 : how to create a bot || Difficulty : Easy

First of all, to create a discord bot, you first need to go to Discord dev applications, or click [here](https://discord.com/developers/applications/)

After that click New Application, as shown below

![img](https://cdn.discordapp.com/attachments/945514486041821227/975311807432503296/unknown.png)

Then name your bot something you want and press Create

![img](https://cdn.discordapp.com/attachments/945514486041821227/975313374491586600/unknown.png)

For this tutorial I will name it "Test Bot"

Then click on Bot > Add bot

![img](https://cdn.discordapp.com/attachments/945514486041821227/975313876730138704/unknown.png)

Then press "Yes, do it!"

Now, after that, press OAuth2 > URL Generator

![img](https://cdn.discordapp.com/attachments/945514486041821227/975314228070203392/unknown.png)

Then copy the settings I have below

![img](https://cdn.discordapp.com/attachments/945514486041821227/975314546489184306/unknown.png)

Then copy the generated link and thats how you create the bot application!

# Lesson 2 : Coding || Difficulty : Really difficult

So you will be needing atom or Visual Studio Code, etc. to proceed this step.

If you have notepad it will be really difficult to code with

Anyways, you will also need Node.js, to install it, click [here](https://nodejs.org/) and then install the LTS version because that is the version it is most working in. Then install it.

Now here is atom or Visual Studio Code download link : 

atom : https://atom.io/
Visual Studio Code : https://code.visualstudio.com/

Now it should be all of it.

When you finished, create a folder in desktop and then type cmd into the folder you created. Make sure you rename your folder and doesn't have any spaces between your folder name

Then type in `cmd` into the folder. If you don't know what I mean, this is what I mean.

![img](https://cdn.discordapp.com/attachments/945514486041821227/975315953669783582/unknown.png)

then press enter.

This is what it should pop up with

![img](https://cdn.discordapp.com/attachments/945514486041821227/975316557796376636/unknown.png)

type in `npm init -y`

then this is what it should pop up with. It should be something like this or you didn't follow the first part of this Lesson.

![img](https://cdn.discordapp.com/attachments/945514486041821227/975316901033017385/unknown.png)

if you see this then you're doing correctly.

Now type in `atom .` if you have atom || or type `code .` if you have Visual Studio Code.

your code editor should pop up at this point.

for me I use Visual Studio Code so this is what it popped up for me

![img](https://cdn.discordapp.com/attachments/945514486041821227/975317745061199902/unknown.png)

now, back to the cmd, type in `npm i discord.js@12.5.3`

the reason I put `@12.5.3` at the end of discord.js is because we're gonna code in version 12

Since version 13 you will need to learn about intents, and it is really hard so I don't want to make it hard for you guys. so we're using version 12 today

anyways, after you installed it there should be more files installed.

back to Visual Studio Code, create a new file called `index.js`. To create files, right click on the file menu and press create file and name it `index.js` and that should be all.

Next, type in the code below : 

```
const Discord = require("discord.js");
const client = new Discord.Client();

client.once('ready', () => {
  console.log("Ready!");
});

client.login(token)
```

At this point, go back to discord developer application, then go to Bot section and press reset token, then copy the token you got.

DISCLAIMER : MAKE SURE YOU KEEP YOUR TOKEN SAFE AND PRIVATE! IT IS LIKE A PASSWORD TO YOUR BOT IF YOU USE IT YOU CAN LOGIN TO THE BOT AND MAKE SURE TO RESET YOUR BOT TOKEN EVERY DAY TO PREVENT GETTING YOUR DISCORD BOT HARMED!

anyways, resetting discord bot token resets the token and the old token will be unusable.

after you got your token, type this below the `const client` line.

`const token = ""`

then paste your token in the "" in the `const token` line. That puts your token into the bot so the code will know what the code will be execute in what bot.

After that, you're done.

Go back to your cmd and type this in to start the bot : `node .`

Wait for some time and it should say "Ready!"

If it doesn't say it : 

- Make sure to check that everything is correct

after the cmd sends the word "Ready!", check the server you add your bot in, it should make the bot online

If the bot was online, congratulations, you completed this Lesson!
