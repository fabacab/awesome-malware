# Awesome Malware [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated collection of awesome malware, botnets, and other post-exploitation tools.

[Malware](https://en.wikipedia.org/wiki/Malware) is software intentionally designed to cause damage or provide unauthorized access to a computer, server, or computer network. While not exclusive, this list is heavily biased towards [Free Software](https://www.gnu.org/philosophy/free-sw.html) projects. For pre-exploitation TTPs, see [awesome-pentest](https://github.com/fabacab/awesome-pentest). For defenses, see [awesome-cybersecurity-blueteam](https://github.com/fabacab/awesome-cybersecurity-blueteam).

Your contributions and suggestions are heartily♥ welcome. (✿◕‿◕). Please check the [Contributing Guidelines](CONTRIBUTING.md) for more details. This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

> :warning: :memo: **Please note** that this compilation is intended for educational and demonstration purposes only.

# Contents

- [Analysis and reverse engineering](#analysis-and-reverse-engineering)
- [Banking trojans](#banking-trojans)
- [Botnets](#botnets)
- [Command and Control](#command-and-control)
- [Credential Stuffing Account Checkers](#credential-stuffing-account-checkers)
- [Data stealers](#data-stealers)
- [Evasion](#evasion)
- [Phishing kits](#phishing-kits)
- [Keyloggers](#keyloggers)
- [RAM scrapers](#ram-scrapers)
- [Ransomware](#ransomware)
- [Remote Administration Tools (RATs)](#remote-administration-tools-rats)
- [Rootkits](#rootkits)
- [Web Shells](#web-shells)

# Analysis and reverse engineering

See [awesome-malware-analysis](https://github.com/rshipp/awesome-malware-analysis).

- [theZoo](https://thezoo.morirt.com/) - Repository of live malwares for your own joy and pleasure, created to make the possibility of malware analysis open and available to the public.

# Banking trojans

> :construction: TK-TODO

# Botnets

- [Idisagree](https://github.com/UndeadSec/Idisagree) - Control remote computers using Discord bot and Python 3.

# Command and Control

(Also known as *C2* and *C&C*.)

- [Browser Exploitation Framework (BeEF)](https://github.com/beefproject/beef) - Command and control server for delivering exploits to commandeered Web browsers.
- [Merlin](https://github.com/Ne0nd0g/merlin) - Cross-platform post-exploitation HTTP/2 command and control server and agent written in golang.
- [SILENTTRINITY](https://github.com/byt3bl33d3r/SILENTTRINITY) - Asynchronous, collaborative post-exploitation agent powered by Python and .NET's DLR.

# Credential Stuffing Account Checkers

Also known as *Account Takeover (ATO)* or *account cracking*.

* Black Bullet - Single-threaded account checker with captcha bypass features and Selenium WebDriver support, sold for about $30 to $50. ([Reference](https://www.recordedfuture.com/credential-stuffing-attacks/#black-bullet))
* [Private Keeper](https://www.deival909.ru/) - Russian language account checker and takeover tool, sold at prices starting from approximately $1 USD.
* [SNIPR](https://snipr.gg/) - Windows toolkit for credential stuffing across Web (HTTP/S) and email (IMAP) attack surfaces with the ability to encrypt and re-sell ATO configurations, sold for about $20.
* STORM - Flexible account checker with Cloudflare protection bypass features written in C#. ([Reference](https://www.netacea.com/blog/storm-cracker-tool))
* [Sentry MBA](https://sentry.mba/) - Among the oldest and longest in-use account checkers, using OCR for captcha bypass but unable to pass JavaScript anti-bot challenges, sold for between $5 and $20 per configuration file. ([Reference](https://www.recordedfuture.com/credential-stuffing-attacks/#sentry-mba))
* Woxy - Email account checker with built-in support for automating password reset and searching email content for valuable information, now cracked and available free of charge. ([Reference](https://www.recordedfuture.com/credential-stuffing-attacks/#woxy))

# Data stealers

> :construction: TK-TODO

# Evasion

- [CheckPlease](https://github.com/Arvanaghi/CheckPlease) - Sandbox evasion modules written in PowerShell, Python, Go, Ruby, C, C#, Perl, and Rust.

# Keyloggers

* [TechNowLogger](https://github.com/Technowlogy-Pushpender/technowlogger) - Windows/Linux keylogger generator which sends key-logs via email with other juicy target info.

# Phishing kits

(Also known as *phishkits*, one word.)

* [ActorExpose/PhishKits](https://github.com/ActorExpose/PhishKits) - Collection of phishing kits provided to the public to make the Internet a safer environment.

# RAM scrapers

> :construction:
>
> See [RamScraper](https://github.com/joren485/RamScraper) for now.

# Ransomware

> :construction: TK-TODO

# Remote Administration Tools (RATs)

Some [Command and Control](#command-and-control) tools also overlap with RAT software.

(Also known as *Remote Access Trojan* or *post-exploitation agent*.)

- [Bella](https://github.com/kdaoudieh/Bella) - Pure Python post-exploitation data mining and remote administration tool for macOS.
- [Empire](https://www.powershellempire.com/) - Pure PowerShell post-exploitation agent built on cryptologically-secure communications and a flexible architecture.
- [EvilOSX](https://github.com/Marten4n6/EvilOSX) - Modular RAT that uses numerous evasion and exfiltration techniques out-of-the-box.
- [Pupy](https://github.com/n1nj4sec/pupy) - Low-footprint, cross-platform (Windows, Linux, macOS, Android) RAT featuring all-in-memory execution guideline written in Python.
- [RedPeanut](https://github.com/b4rtik/RedPeanut) - Small RAT developed in .Net Core 2 and its agent in .Net 3.5/4.0, weaponized with several additional utilities.
- [Slackor](https://github.com/Coalfire-Research/Slackor) - Golang implant that uses Slack as a command and control server.
- [Twittor](https://github.com/PaulSec/twittor) - Stealthy Python based backdoor that uses Twitter (Direct Messages) as a command and control server.

# Rootkits

- [Adore-NG](https://github.com/trimpsyw/adore-ng) - Rootkit adapted for the 2.6 and 3.x Linux kernels.
- [AdoreForAndroid](https://github.com/juxing/AdoreForAndroid) - Adore rootkit ported to Android.
- [Diamorphine](https://github.com/m0nad/Diamorphine) - LKM rootkit for Linux Kernels 2.6.x, 3.x, and 4.x.
- [Masochist](https://github.com/squiffy/Masochist) - Framework for creating XNU based rootkits useful in OS X and iOS security research.
- [Vector-EDK](https://github.com/hackedteam/vector-edk) - Commercial UEFI rootkit illegally sold by Hacking Team to numerous governments, leaked by hacker Phineas Phisher in 2015, and the basis of the [MosaicRegressor rootkit](https://securelist.com/mosaicregressor/98849/).
- [vlany](https://github.com/mempodippy/vlany) - Linux `LD_PRELOAD` rootkit.

# Web Shells

(Also known as *webshells*, one word.)

- [BlackArch Webshells Collection](https://github.com/BlackArch/webshells) - Various webshells that can be installed as a package on BlackArch Linux.
- [DAws](https://github.com/dotcppfile/DAws) - Advanced Web shell.
- [PHP-backdoors](https://github.com/bartblaze/PHP-backdoors) - Collection of PHP backdoors, for educational and/or testing purposes only. 
- [PHP Exploit Scripts](https://github.com/mattiasgeniar/php-exploit-scripts) - Collection of PHP exploit scripts (often but not necessarily always backdoors or web shells), found when investigating hacked servers.
- [PHP WebShells collection](https://github.com/JohnTroony/php-webshells) - Repository of common PHP Web shells, somewhat dated.
- [PhpSploit](https://github.com/nil0x42/phpsploit) - Remote control framework, aiming to provide a stealth interactive shell-like connection over HTTP between client and web server.
- [SharPyShell](https://github.com/antonioCoco/SharPyShell) - Tiny and obfuscated ASP.NET webshell for C# web applications.
- [SecLists Web Shells](https://github.com/danielmiessler/SecLists/tree/master/Web-Shells) - Examples of core Web shell functionality in PHP, JSP, ASP(X), ColdFusion, and more.
- [Weevely](https://github.com/epinna/weevely3) - Extensible PHP Web shell with numerous out-of-the-box modules.

# License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
