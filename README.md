# Classic Brawl v20

Brawl Stars v20 server emulator written in Python.

![ScreenShot](https://media.discordapp.net/attachments/932573964918747139/981500951972184064/Screenshot_2022-05-28-21-24-29-592_com.brawlstars.server.jpg) 

### Requirements:
- Python 3.7 or higher
- pymongo
- dnspython
- colorama

### MongoDB configuration
First you'll need to put your MongoDB connection string in `config.json`. If you don't know how to get it here's a quick tutorial: https://imgur.com/a/oXI34dA

### Running the server
In a terminal, type __`pip install -r requirements.txt`__ then __`python main.py`__

### Configuring the client app
To connect to your server, a **patched client** is required. 
Download this [base APK](https://drive.google.com/file/d/1GYtNvucblPgtsHanN8T2eAKXzGQFa5i6/view?usp=drivesdk) and change the IP in `libsb9838.config.so`

### Need help?
Open an issue or contact me on **Discord**: vanya_dev#2814
