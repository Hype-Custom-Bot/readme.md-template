# How to invite the bot
https://discord.com/oauth2/authorize?client_id=CLIENT_ID&scope=bot+applications.commands&permissions=8

**Please replace CLIENT_ID with your bot's client id**


# How to start the bot

**IMPORTANT: MAKE SURE YOU INSTALLED PYTHON [3.9.7](https://www.python.org/downloads/release/python-397/)**

## Windows
Make sure you install all requirements using the command below

```
pip install -U -r requirements.txt
```

And you can now run the bot using the command below!

```
python bot.py
```

**If you see `Ready!`, then the bot is running!**

## Linux
Make sure you install all requirements using the command below

```
pip3 install -U -r requirements.txt
```

And you can now run the bot using the command below!

```
python3 bot.py
```

**If you see `Ready!`, then the bot is running!**


# How can I host the bot 24/7
## DO NOT use replit to host your bot!
**You should NOT use Repl.it to host your bot.**

While this may seem like a nice and free service, it has a lot more caveats than you might think, such as:

- The machines are super underpowered.
    - This means your bot will lag a lot as it gets bigger.
- You need to run a webserver alongside your bot to prevent it from being shut off.
    - This isn't a trivial task, and eats more of the machines power.
- Repl.it uses an ephemeral file system.
    - This means any file you saved via your bot will be overwritten when you next launch.

- They use a shared IP for everything running on the service.
This one is important - if someone is running a user bot on their service and gets **banned**, everyone on that IP will be banned. **Including you.**

Please avoid using repl.it to host your bot. It's not worth the trouble.

## Need to run your bot 24/7? Get a cheap VPS.
- [Scaleway](https://www.scaleway.com/): EU
- [Linode](https://www.linode.com/): US/EU/Asia
- [DigitalOcean](https://www.digitalocean.com/): US
- [Vultr](https://www.vultr.com/) US
- [OVH](https://www.ovh.co.uk/): EU/Canada
- [Hetzner](https://www.hetzner.com/) Germany/US
- [Time4VPS](https://www.time4vps.eu/) Lithuania.
- **Self-hosting:** Any computer
- **Free hosting:** 
    - [Railway (No credit card required)](https://railway.app)
        - The free plan is not suitable for large bots
    - [Oracle Cloud (Credit card required)](https://www.oracle.com/cloud/)
- **Kinda free:** GCP, AWS have one year free micros.