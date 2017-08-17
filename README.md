# Nemesis - TheChatbot

Nemesis is a chatbot made using Artificial Intelligence Markup Language(AIML).
The bot can be customised to cater to any specific requirement of work.

 # Bot Files Description
 
 ### AIML
 These files are core bot files.Any changes to these files will reflect into the changes of the bot responses.Current AIML file base can be modified to use the bot for any specific use like FAQ bot,etc.
 
 ### Maps
 -  Map files attempts to match the map element’s contents to one of its own properties, returning the property’s value. 
 -  Maps are data structures that provide key-value pairs.
 -  Some of the current map files are taken from ALICE Bot.
 ### Sets
- These files contain values which are unique text strings.Values such as names of birds,animals,etc. are stored in these files.
- Some of the current set files are taken from ALICE Bot.
 ### Substitutions
 - These files are used to modify text strings being passed through your bot in such a way that both the AIML interpreter and your client can parse their meanings.
 - These look for defined sets of characters in text strings, and replace those sets of characters with new values.
 - Depending on the substitution file, this transformation can either occur before the bot attempts to form a match with an input, or in the bot’s response itself.
 - The current bot substitution files are the default files of the PANDORABOTS Platform.These can be changed or used along with the custom substitution files.
 ### System
- These file contain the default properties and characteristics of the bot.
- These can be modified to add more traits for the bot.
# Bot Deployment
 
- The bot can be deployed using the pandorabots api(AIaaS).
