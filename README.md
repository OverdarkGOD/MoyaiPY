# MoyaiPY - Version 0.6
Moyai is a Discord Bot made in Python. The bot interacts with Discord's API called Discord.py. This bot contains more than 40 commands and all are executable through Discord's integration. Their integration allows programmers to synchronize their slash commands to the Discord client. This allows for easier accessibility and quick execution. Below will show an example of the correct syntax of the commands and the parameters of those commands. Below will also show the definitions of these commands and their parameters in their respective categories.

## Main File
The main file does not have commands to execute. It provides communication to the Discord client. It holds the requiste data in order for the bot to communicate properly. Upon running the file, the bot will check it's directory to see if there are other files that need to loaded with the main file. Once the bot loads the other files, the bot will print in the terminal that it is online. 

The main file does listen for members that join a guild. When a member joins a guild, the bot will respond to the user by sending them a message in their direct messages. 

The main file also logs every action that happens to the bot. In the terminal, the bot will print errors if something goes wrong.

## Example
- COMMAND_IS_HERE: THE DEFINITION OF THE COMMAND
   - PARAMETER_IS_HERE: THE DEFINITION OF THE PARAMETER


## Support Commands
   - help: shows the help manager. Help manager shows all of the known commands and defines them. Within the manager, you can submit a report or a ticket Command Works
   - assistant: a helper for reporting and ticketing Command Works 

## Fun Commands 
   - pong: outputs the bot client latency - Command Works
   
   - avatar: enlarges the pinged user's profile picture - Command Works
      - member: define the user you want to enlarge the profile picture of
      
   - ping: ping an IP/DNS Command Works
      - website: define the IP/DNS you would like to ping
   
   - google: google search within discord - Command Works
      - message: define what you're searching for
   
   - rando: the bot will send a random photo - Command Works
      - message: define what you're searching for
 
   - memes: the bot will send a random meme - Command Works
   
## Info Commands
   - info: shows information about the server and the bot - Command Works
   
   - status: shows information about the bot - Command Works
   
   - whois: shows information about an user - Command Works
      - member: define the user you would like information from
 
## Mod Commands
   - captcha: enforces users who join a guild to verify that they are human and not a bot

   - purge: allows users with manage permissions to delete previous messages - Command Works
      - amount: define the amount of messages you would like to delete
   
   - warn: allows users with kick or ban permissions to send warnings to users. - Command is being rewritten
   
   - ban: allows users with ban permissions to ban users within a guild - Command Works
      - member: define the user you would like to ban from your guild
      - reason: define a reason for the ban (optional)
      
   - unban: allows users with ban permissions to unban users within a guild - Command Works 
      - member: define the user you would like to unban from your guild
   
   - kick: allows users with kick permissions to kick users within a guild - Command Works
      - member: define the user you would like to kick from your guild
      - reason: define a reason for the kick (optional)
   
   - lock: allows users with manage channels to lock users from texting, sending attachments, and reactions within a channel - Command Works
      - role: choose a role that users have that you'd like to lock
      
   - unlock: allows users with manage channels to unlock users ability to text, send attachments, and react within a channel - Command Works
      - role: choose a role that users have that you'd like to unlock
      
   - clone: allows users with manage channels to automatically delete and recreate a channel - Command Works
      - channel: choose a channel to clone
   
   - dm: send a message to a user or yourself - Command Works
      - header: the main tile of your message
      - subject: the description of your message
      - body_title: the title of your paragraph
      - body: the paragraph of your message
      - user: the user you're sending this message to.
   
   - thread: create a thread - Command Works
      - title: The title of the thread
      - description: the description of the thread
   
 
## Music Commands
   - join: makes the bot join the voice channel you are currently in - Command Works
   
   - summon: makes the bot join a voice channel you wish - Command Works
      - channel: choose the channel the bot will join 
      
   - leave: makes the bot leave the voice channel - Command Works
   
   - volume: allows users to adjust the volume of the bot's audio output - Command Works
      - volume: adjust the volume using integers
      
   - now: shows the currently playing song - Command Works
   
   - pause: pauses the current song - Command Works 
   
   - resume: resumes the current paused song - Command Works 
   
   - stop: stops playing the song & clears the queue - Command Works 
   
   - skip: vote to skip a song, the requestor can automatically skip. 3 votes needed in order to skip a song - Command Works
   
   - queue: shows the player's queue - Command Works
      - page: queue the song of your choice
      
   - shuffle: randomizes the queue - Command Works
   
   - remove: remove a song from the queue at a given index - Command Works
   
   - loop: loop the currently playing song. Invoke the command again to unloop - Command Works
   
   - play: enter the URL of the song from YouTube and the bot wiull join the voice channel you're in and the bot will automatically start playing the song - Command Works
      - search: choose the song you want to play
   
## SQL Commands
  - create: allows users to create a database table - Command Works
    - table: the name of the table you're creating
    - task:  the task you're creating
    - value1
    - value2 
    - value3
    
  - insert: allows users to insert data by typing in the following parameters - Command Works
    - table: enter the table you're inserting data into
    - task: enter the task you're inserting data into
    - value1
    - value2
    - value3
    
  - delete: allows users to delete a row within a table - Command Works
    - table: enter the table that you're deleting data from
    - task: enter the task you're deleting data from
    - row_x: enter the row you're deleting
    
  - fetch: allows users to fetch all information within a table - Command Works
    - table: enter the table you're fetching
    - task: enter the task you're deleting
    
  - verify: allows users to verify if the table or the SQL module is working correctly - Command Works
    - table: enter the table you're verifying
    
## Fixed Issues
Redone the "user_verify" function by implementing the "captcha" function. Removed code in the main file that may have caused unknown problems. The code in the main file had two variables operating two different but almost identical values. The code has been rewritten and been moved to the config.py file.
  
## Known Issues
SQL commands are not asynchronous. Commands are functional, but will delay the bot from use until commands are executed.
  
## Test Commands
There are other miscellaneous commands that are always being tested. If you are in the support server, you know that there are two Discord bots made in python. One of them being the main bot and the other being a testing bot. The testing bot holds more commands than the main bot. Join our server to get a hands on look at what commands we are creating! https://discord.gg/vgKmCDq6r6




