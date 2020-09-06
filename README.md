# DarkPi_001
A collection of PiHole Blocklists

RasPiHole Blocklists for my network.

---

## Copyright

License: MIT License

---

My personal installation guide:

https://raw.githubusercontent.com/Darktorizo/DarkPi_001/master/Raspi.TFT.PiHole.PADD.unbound%20Install.txt

*Note: Compiled from various sources

---

## Default PiHole Lists:

##StevenBlack's list
https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts

##MalwareDomains
https://mirror1.malwaredomains.com/files/justdomains

##Cameleon
http://sysctl.org/cameleon/hosts

##Disconnect.me Tracking
https://s3.amazonaws.com/lists.disconnect.me/simple_tracking.txt

##Disconnect.me Ads
https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt

---

### DISCLAIMER

**I AM NOT RESPONSIBLE FOR ANY NETWORK CONNECTIVITY ISSUES AS A RESULT OF USING THE ABOVE MENTIONED LISTS, USE AT YOUR OWN RISK**

Also, if I used your list and forgot to mention you, please contact me and I will correct this.

---

## Found a false positive, but don't know which list contains it?

Run `pihole -q blockeddomain.com`, and it will return the URL of the block list.

---

##### Credits:

- The Raspberry Pi team @ https://www.raspberrypi.org/
- The PiHole Team @ https://pi-hole.net/
- The Unbound Team @ https://nlnetlabs.nl/projects/unbound/about/
- StevenBlack
- MalwareDomains
- Cameleon
- Disconnect.me
- *WaLLy3K* over at https://firebog.net
- All the good people at https://blocklist.site/app
