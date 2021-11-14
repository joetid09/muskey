# muskey
## Purpose:
  to build a bot for automating and buying stocks/bitcoin based on certain events i.e. Elon Musk's tweets
## Resources to utilize:
  ###Languages:
      C#, SQL, BotNet
  ###Web Resources:
      Github, AzureDevops, Azure
  ###APIS
      tbd
   ###Database:
      Sql Server 
 ##Description:
  This project's primary goal is to attempt to create a bot that is able to view market trends and have the ability to buy and sell stock accordingly. The initial focus will be finding out what APIs to use, learning more about Azure Bots and Botnet, learning about how stocks are supposed to be traded (I'm attempting to use the resource found in this article: https://towardsdatascience.com/how-to-get-started-building-a-stock-cryptocurrency-forex-trading-program-2abbf0a4729f#51f2 , althought I'll be using in a .net/c# environment instead of python), and setting up a database and data warehouse. 
  
  
  Phase two will consist of the majority of coding. I'll be setting up the environment that will allow for real time ticker information. I'll then have to post this information into the database. Based on the information that is passed in, Botnet will contain the logic needed to process the new data and log it's course of action. These logs will be stored in the datawarehouse, which will then be loaded into a power BI report, and the report will reflect the success rates of the bots hypothetical trades. This is certainly the portion I see most of my roadblocks happening, but where I believe I'll learn the most about Azure and reinforce what I already know. 
  
  Phase three will be the payoff period. The bot will gain access to an Ameritrade api which allows it to buy and sale (https://developer.tdameritrade.com/apis). I'll put in the automation, give it access to a small pool of money, and monitor the results
