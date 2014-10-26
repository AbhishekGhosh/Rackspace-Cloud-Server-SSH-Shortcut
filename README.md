Rackspace-Cloud-Server-SSH-Shortcut
===================================

![Add SSH Shortcut on Mac OS X to Rackspace Cloud Server](https://thecustomizewindows.com/wp-content/uploads/2014/10/Add-SSH-Shortcut-on-Mac-OS-X-to-Rackspace-Cloud-Server.png)

Plain HTML File to Create a list of Devices to SSH. Intented for Mac and Linux. Probably will work after huge work on Micro & Soft Windozzzzz (read OpenVMS) with puTTY. How to use? Copy paste that HTML file on your Desktop and save with any name and with `html` extension. Double click opens the file.

But you need edit the file t change `ssh://user@host.com` to working one, may be add some inline CSS to make it look better. You do a simple curl or wget on Mac :

```sh
 # you possibly should be at your home 
cd Desktop && wget https://raw.githubusercontent.com/AbhishekGhosh/Rackspace-Cloud-Server-SSH-Shortcut/master/my-rackspace-cloud-servers.html
nano my-rackspace-cloud-servers.html
# ^ + W
# user@host.com
# change
# ^ + O
# ^ + X
```

