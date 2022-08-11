# Python Exploit & Tool Database (Under Construction)
___
![Last Commit](https://img.shields.io/github/last-commit/MythicStack/Python-Security-Tool-Database)
___
## Synopsis
 Future home of the world's largest repo of Python exploits and tools. I didn't really find anything great in existence, so making it myself. My table of contents will likely be garbage, so you should probably rely on Ctrl + F.
 
 Really I just want to make something people will use so if you have input, DM me on Twitter: [@MythicStack](https://www.twitter.com/MythicStack). 
 
 If you think a project should be included here I really want to know, but keep in mind that this isn't supposed to be a dictionary. I want to keep the best, covering as many bases as possible while minimizing overlap.

___

### Table of Contents

 - [Adversary Simulation](#adversary-simulation)
 - [Digital Forensics and Incident Response](#digital-forensics-and-incident-response-dfir)
 - [Information  Gathering](#information-gathering)
 - [Penetration Testing]()
 - [Vulnerability Scanning](#vulnerability-scanning)

___


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


##### Penetration Testing

- [EvilTwinFramework](https://github.com/Esser50K/EvilTwinFramework) - Python tool to help penetration testers perform evil twin attacks and some other wifi related exploits.
- [SQL Map](https://github.com/sqlmapproject/sqlmap) - This thing is so cool! Really awesome set of contributors on this project, basically it's an automated detector/exploiter for SQL injection vulnerabilities. This thing kicks ass once you get the hang of it.


##### Vulnerability Scanning

- [Faraday](https://github.com/infobyte/faraday) - Faraday is clean and I love using it, I've messed with it in my home lab a lot. Bottom line is, it's fantastic. It has a clean & intuitive web UI, tracks vulnerability history, aids in remediation efforts, and it's updated as often as you'd expect. All the damn time.