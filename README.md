## Running the bot from your own hardware/vps/etc
* Gather the requirements:
    `python3 -m pip install -r requirements.txt`
* Start EDDNListener and allow to run for 5-10 minutes to generate price histories
* Place your bot token, as well as a file named 'botadmin' containing your message.author.id, in the same directory as the py file with the name `token` and run the bot:
    `python3 EDPriceCheckBot.py`
