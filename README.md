# proxy.py
A fully functional forward proxy written in python with basic sockets.

## Features
* Blacklisting IPs and domains
* HTTPS tunneling
* Realtime logging
* Fully functional console

## Running
Simply git clone the repo, then compile the script with `python proxy.py` while in the new directory, and voilà, the proxy is now running and can be found on port 10000 of your machine. You can type help to look at the commands, and any help followed by any command for more details on each command. 

You can set firefox to use the proxy by going to General Settings, going down to network settings, clicking on the `Settings...` button, and then selecting `Manual proxy configuration`, and setting the first field of `HTTP Proxy` to be 127.0.0.1 and the `Port` field to be `10000`, and then selecting `Also use this proxy for FTP and HTTPS`. __*Remember*__, when your finished with the proxy, click `Use system proxy settings` or firefox will just do nothing.
