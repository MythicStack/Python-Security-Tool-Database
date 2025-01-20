# Python Exploit & Tool Database
___
![Last Commit](https://img.shields.io/github/last-commit/MythicStack/Python-Security-Tool-Database)
___
## Synopsis
 I didn't really find a good Python toolkit online and I just want to make something people will use so if you have input, DM me on Twitter: [@MythicStack](https://www.twitter.com/MythicStack). 
 
 If you think a project should be included here I really want to know, but keep in mind that this isn't supposed to be a dictionary. I want to keep the best, covering as many bases as possible while minimizing overlap.


___

### Table of Contents

 - [Not Python](#not-python)
 - [Adversary Simulation](#adversary-simulation)
 - [Digital Forensics and Incident Response](#digital-forensics-and-incident-response-dfir)
 - [Information  Gathering](#information-gathering)
 - [Networking](#networking)
 - [Penetration Testing](#penetration-testing)
 - [Social Engineering](#social-engineering)
 - [Vulnerability Scanning](#vulnerability-scanning)
 - [Wireless Security](#wireless-security)

___


##### Not Python

- [Metasploit](https://github.com/rapid7/metasploit-framework) - Alright so this thing isn't even close to being mostly Python, but cmon it's Metasploit. This has to be in here because I love this thing so much. This makes my life easier every single day.



##### Adversary Simulation

- [Caldera](https://github.com/mitre/caldera) - Mitre's adversary emulation tool. It's not entirely python, but it's mostly python and so sick that it has to be included here.
- [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire) - Old, on Python2, and no longer maintained. That being said, it's got a lot of reference material if you're interested. I messed around with it for an hour or two and all the modules I played with worked without too much finagling (No clue about the OSX stuff though, let me know).
- [Infection Monkey](https://github.com/guardicore/monkey) - Attack simulation tool with self-propagation functionality and a web portal that provides mini security write-ups after attack is complete. Several exploits to chose from + it's a very clean tool.
- [Splunk Attack Data](https://github.com/splunk/attack_data) - Allows you to replay attacks generated from logs, lots of datasets to chose from have already been included in the repo. 
- [FakeNet-NG](https://github.com/mandiant/flare-fakenet-ng) - Simulate legitimate network services while redirecting specified traffic. This is also an older project that is no longer maintained, but I could not find something that provided the same functionality and this still works.


##### Digital Forensics and Incident Response (DFIR)

- [Cold Disk, Quick Response](https://github.com/orlikoski/CDQR) - CDQR is a disk parser and artifact collector. Their readme explains all. This is one of the few on my list that I've never personally used. I also couldn't easily set up a situation in order to use it effectively to test it, but it's been in a bunch of DFIR kits I've been around so I feel comfortable including it here.
- [Cuckoo Modified(+Sandbox)](https://github.com/spender-sandbox/cuckoo-modified) - This is deprecated, but the one I'm familiar with. Never used the new one, but it's [here](http://www.cuckoosandbox.org/). This is a really excellent automated malware analyzer, highly recommend.
- [Image Mounter](https://github.com/ralphje/imagemounter) - CLI mounting tool for virtual and non-virtual images.
- [Loki (IOC Scanner)](https://github.com/Neo23x0/Loki) - Loki is an absolutely sick IOC scanner. Supports: hashes, yara, filenames, and C2 IOCs. 
- [Malware CAPE](https://github.com/kevoreilly/CAPEv2) - This is the Malware Configuration and Payload Extractor, hence the name CAPE. It's phenomenal and there's an [online instance](https://capesandbox.com/).
- [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) - First, how great is that name?! Second, this is the best Python based live memory acquisition tool. Done and dusted. It's a bit old, but still kicking.
- [OSSEM](https://github.com/OTRF/OSSEM) - This is the Open Source Security Events Metadata. Weird name, but great idea. Event log analysis + documentation + standardized framework = win in my book. I'm not a DFIR expert, so can't say for sure how useful this is in a corportate setting, but I appreciate what's going on here.


##### Information Gathering

- [Anubis](https://github.com/jonluca/Anubis) - Subdomain enumerator actively maintained by [jonluca](https://github.com/jonluca). It's a good tool and it works well. Has the added benefit of having a nice README with clear examples. Every issue (at the time of writing) has been resolved. The dude has some pretty cool projects on his blog too.
- [BlackBird](https://github.com/p1ngul1n0/blackbird) - Another OSINT tool! I seem to have a favorite category at this point.
- [DaProfiler](https://github.com/daprofiler/DaProfiler) - This a person profiler and covers bases that others on this list do not. It's fairly in-depth, updated regularly, and has a clean UI. Easy to use and works well, some false positives.
- [holehe](https://github.com/megadose/holehe) - Simple mail checker for popular websites. Clean and to the point, updated by [megadose](https://twitter.com/palenath) as needed. They also have a lot of other interesting projects.
- [IntelOwl](https://github.com/intelowlproject/IntelOwl) - It's a cool malware/malspam threat intel tool. It's mostly Python, but it's pretty JS heavy. I've used it and my thoughts on it are: "Clean/Functional/Well Documented, but it smells like a corporate project."
- [Metagoofil](https://github.com/laramies/metagoofil) - This is an oldie, but a goodie from the days of Python 2. This tool helps obtain files and metadata from target websites using Google.
- [Moriarty Project](https://github.com/AzizKpln/Moriarty-Project) - Checks for provided phone number on popular websites, performs searches, and provides ownership information.
- [Osintgram](https://github.com/Datalux/Osintgram) - Instagram is a wealth of data for those that look, it's maintained by a lot of folks, but Instagram changes may break functionality. It's a well organized project and lots of forks to take a look at.
- [Recon-ng](https://github.com/lanmaster53/recon-ng) - The OSINT equivalent to the Metasploit Framework. Could be updated more often, but it's well respected and there's decades of content on the internet to help you get familiar with it. 
- [sherlock](https://github.com/sherlock-project/sherlock) - Best broad social media hunter I've used by far. So simple a caveman could do it. 
- [SpiderFoot](https://github.com/smicallef/spiderfoot) - Easily the coolest OSINT tool on the list, it would be first if I wasn't trying to keep this thing alphabetical. Its perks are too numerous to outline here, go to their page.
- [theHarvester](https://github.com/laramies/theHarvester) - Jack of Most Trades OSINT tool maintained by a bunch of people. Often Updated and might as well be a household name. It's well-rounded and efficient. What more could you ask for?
- [whoisrecon](https://github.com/MythicStack/whoisrecon) - Shameless self-plug, this is a pretty useful tool I cooked up that lets you use CLI to query a WHOIS archive for historical data and find related domains from wildcard support searches of emails, organizations, and more!


##### Networking

- [Impacket](https://github.com/fortra/impacket) - Impacket is a flexible toolkit for crafting, manipulating, and analyzing network protocols. Never leave home without it.
- [Scapy](https://github.com/secdev/scapy) - Python packet manipulation tool for a really solid number of protocols.
- [NetworkX](https://github.com/networkx/networkx) - Incredibly thourough network mapping and analysis tool for small and large networks.


##### Password Cracking

- [Patator](https://github.com/lanjelot/patator) - All in one brute forcer. This is built as an alternative to Hydra (near and dear to me, but definitely not Python anymore, mostly C) and some other tooling built into Kali by default. It's a sick multi-threaded application that's super flexible and inclusive.


##### Penetration Testing

- [EvilTwinFramework](https://github.com/Esser50K/EvilTwinFramework) - Python tool to help penetration testers perform evil twin attacks and some other wifi related exploits.
- [SQL Map](https://github.com/sqlmapproject/sqlmap) - This thing is so cool! Really awesome set of contributors on this project, basically it's an automated detector/exploiter for SQL injection vulnerabilities. This thing kicks ass once you get the hang of it.
- [CrackMapExec](https://www.kali.org/tools/crackmapexec/) - CrackMapExec (CME) is a post-exploitation tool to automate the assessment of large Active Directory networks. I think there's some drama here between [byt3bl33d3r](https://github.com/byt3bl33d3r/CrackMapExec) and Kali, but I don't know so I'm linking primarily to the Kali one since it's maintained and byt3's is archived. 


##### Social Engineering

- [King Phisher](https://github.com/rsmusllp/king-phisher) - May look reduntant since the SET has a set of modules for phishing, but worry not this is definitely meant to be here. SET has a broad set of tooling in it, but King Phisher focuses on one thing and it does it really well. SMS alerts, MFA bypass, detailed email building, and a lot more are cooked into this tool.
- [Social Engineering Toolkit](https://github.com/trustedsec/social-engineer-toolkit) - Built by one of my favorite people [@HackingDave](www.twitter.com/HackingDave), this Python toolkit (so it's built with more than just Python, sue me) is a modular piece of art with 15+ built in tools that work well out of the box. Plus for new folks to the tool it also has a extremely easy to digest User Manual.


##### Vulnerability Scanning

- [Faraday](https://github.com/infobyte/faraday) - Faraday is clean and I love using it, I've messed with it in my home lab a lot. Bottom line is, it's fantastic. It has a clean & intuitive web UI, tracks vulnerability history, aids in remediation efforts, and it's updated as often as you'd expect. All the damn time.
- [Bandit](https://github.com/PyCQA/bandit) - Slight change up to the rest of the tools in this list, but Bandit is still pretty useful. It's a static code analysis tool for Python scripts. Can be helpful for finding vulnerabilities in home brew applications and it's just a nice tool to have around if you're going to be building anything on your own with Python so you're not making any egregious slip ups.
- [Raccoon](https://github.com/evyatarmeged/Raccoon) - Raccoon is pretty sweet, very helpful, and a must have in your toolkit. It's not super well maintained, but it's open source and works perfectly out of the box for external attack surface scanning and information gathering.


##### Wireless Security

- [Wifite2](https://github.com/derv82/wifite2) - Whatever description isn't going to do the wifite rewrite any justice. WEP, WPS, and WPA/2 attacks galore. Must have if you're doing anything with wireless access points. I don't use any other Python tooling for wireless stuff, that's probably because I don't do much with wireless stuff in the first place so let me know what I missed!
- [BetterCAP](https://github.com/bettercap/bettercap) - BetterCAP is a powerful, flexible, and portable tool designed for performing various types of MITM attacks against networks along with general network recon.


