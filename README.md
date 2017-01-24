
# Pyload-autoinstaller | Auto Installer | Debian 8.x


Pyload-ass is an Script to fully automate and easy install [pyLoad](https://pyload.net) on an Linux Server!

  - Install [pyLoad](https://pyload.net) from stable git
  - Install all Python dependencies
  - Install all Python dependencies 
  - Install nginx as Reverse Proxy + Let's Encrypt for SSL

What you need:
  - Linux Server with Debian 8.x
  - A subdomain like (pyload.keinnerd.net)
  - Fresh installed Debian

You use the Script on your own risk!

### Installation

Download and give permissions

```sh
$ cd /tmp
$ wget https://raw.githubusercontent.com/STX2k/pyload-autoinstaller/master/pyload-ass.sh
$ chmod +x pyload-ass.sh
$ ./pyload-ass.sh
```
If you get the Error ERROR: The certificate of 'raw.githubusercontent.com' is not trusted
```sh
apt-get install ca-certificates
```
