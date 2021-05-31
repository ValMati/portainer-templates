# Pi-hole + Cloudflared

[Pi-hole](https://github.com/pi-hole/pi-hole) is a DNS sinkhole than protects your devices from unwanted content, without installing any client-side software.

Additionally in the *docker-compose.yml* a container [docker-cloudflared](https://github.com/crazy-max/docker-cloudflared) container that acts as a proxy-dns is raised to made the reaquets to Cloudflared via HTTPS.

## Lists

These are the lists I currently use:

* Default: [https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts]
* Firebog AddguardDNS: [https://v.firebog.net/hosts/AdguardDNS.txt]
* Firebog Threat-Intel: [https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt]
* Firebog SmartTV: [https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV.txt]
* Firebog AndroidTrack: [https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/android-tracking.txt]
* Firebog AmazonFireTV: [https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/AmazonFireTV.txt]
* DeveloperDan TrackingAggressive: [https://github.com/lightswitch05/hosts/blob/master/docs/lists/tracking-aggressive-extended.txt]
* OISD Full: [https://dbl.oisd.nl/]
