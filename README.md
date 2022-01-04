# FOX MAIL SUPPORT
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/911217306611372112/927916463841497108/TYest-removebg-preview_1.png"/>
</p>
Fox Mail Support is open-source bot which u can use in your server just follow these steps :- <br>

1. Install `python` if you don't already have it installed. then open your terminal and install `pycord` by typing `pip install -U git+https://github.com/Pycord-Development/pycord` in the console 
2. Clone the repository or download the code.
3. Create a `config.py` file in the same directory (folder) and put the following code in it :-
```py
token='Your Bot token' # Enter your bot's token here
guild_id = guild_id # Enter the guild id of the server u want the mails to be sent to
role_ids = [role_1_id,role_2_id] # Enter the ids of the roles that should be able to view the tickets. You don't need to add the role what have Manage Channels or Adminstrator permissions because they can already see the tickets. You can have None (Leave it like []) or unlimited roles just add them with a comma :) 
```
4. Invite the bot in your server and make sure it has Manage Channel permission. 
5. After u did that run the `main.py`. (You can just click on the file or open your terminal in the directory and type `python main.py`) leave the window open if you close it the bot will stop.
6. And thats it the bots done. :)
