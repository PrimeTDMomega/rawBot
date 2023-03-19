### Minecraft 1.12.2 Simple bot API
Can be used to create a basic bot for 1.12.2 servers, performing actions by simply receiving and sending the right packets to the server.

#### Build the API
You will need maven: ```$ mvn clean package```  
The jar will be created in the ```target``` folder.

#### Create a bot
Create a class extending ```rawbot.bot.Bot``` and implement the abstract methods.  
Run it by calling ```run``` on your bot from your main method.  

Check ```rawbot/bot/examples/ChatDumpBot.java``` & ```Example.java``` for an example.

#### Run the example
Run the chat dump bot.  

Compile it: ```$ javac Example.java -cp target/rawBot-1.0.jar```  
Run it on a server: ```$ java -cp target/rawBot-1.0.jar:. Example <host> [port]```  

After authentication your tokens will be saved in ```token.txt``` for future uses.

### CREDITS

PrimeTDMomega - Developer
<br>
KaaskopThomas - Existing

### Note
 - This is not the same bot used for the TDMBOT/ValorBot on 8b8t 
 - Updates likely won't happen as this is just a simple bot written while making one for TDMBOT/ValorBot
 - For support don't DM me because its just a simple bot and if you can't get it to work use something like MineFlayer it isn't easier but it recieves updates so do that
 
 scanBot can be found here - https://github.com/PrimeTDMomega/rawBot/tree/main/scanBot
