# What is this?
Bunch of bash scripts to help you manage your v2ray server.

# What does it do?
To elaborate:
- Add, view, delete users to/from your config file
- Assign number of devices a user can use 
- Tells you if a user exceeds the assigned number of devices (by checking the logs and IP addresses)
- Supports servers that are load balanced

# How do I use it?

```
mkdir /root/v2ray
cd /root/v2ray
git clone https://github.com/aMir733/v2ray_tools
mkdir -p /etc/v2ray
cp [your v2ray config file] /etc/v2ray/config.json
command -v v2ray || cp [your v2ray binary] /usr/local/bin/v2ray
```

It's not a program. It's just a bunch of bash scripts. YOU NEED TO READ EVERY SINGLE FILE IN THIS REPOSITORY BEFORE RUNNING THEM ON YOUR SERVER. Check what argument each script takes and run them accordingly. Do not expect a plug-and-play experience. I didn't have time to make a manual page or a help message for each script. They're all simple enough to understand even as a new-bie.

TL;DR: Learn how to use it by reading it.

# What does it need?
- You need to install `jq` and `qrencode` to be able to run most of the scripts
- Config file is set separately in each script. Change it if it's somewhere else
- v2ray binary should be in your PATH

# Last words
![last-words](https://i.imgur.com/wM4U85h.jpg)
