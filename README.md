# zulip-covid-bot

A chatbot made using Zulip API that gives information related to Covid-19
# Instructions to run locally:
1. [Create a Zulip Realm](https://zulip.com/create_realm/)
2. Goto to settings and create a new generic bot named 'Covid Bot'. (Settings can be found in dropdown of gear icon present in top right corner of zulip realm)
3. Download the zuliprc file for your bot and place it in your home directory as '.zuliprc'.
4. Install all the requirements using ``` pip install -r requirements.txt ```
5. In ``` bot.py ``` , change site in ``` self.client = zulip.Client(site="https://chirag-jain.zulipchat.com/api/") ``` to url of your created zulip realm.Do the same for ``` BOT_MAIL ``` variable.  
6. Run ``` bot.py ``` using python 3. ``` python3 bot.py ```
7. Head over to your created zulip realm and start using the bot.

# Live video demo

Watch at [https://www.youtube.com/watch?v=1PAg6Sf8ZC8&feature=youtu.be](https://www.youtube.com/watch?v=1PAg6Sf8ZC8&feature=youtu.be)

