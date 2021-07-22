# Security knowledge-base 

## Cheat Sheet's

| Name | Description |
| ---- | ----------- |
| **Basic Tools** |
| [vim](https://vimsheet.com/)| A Great Vim Cheat Sheet |
| [tmux](https://tmuxcheatsheet.com/)| Tmux Cheat Sheet & Quick Reference |
| [netcat](sans/netcat.pdf)| NetCat Cheat Sheet |
| [tcpdump](packetlife/tcpdump.pdf)| Tcpdump Cheat Sheet |
|  |  |
| **Exploits** |
| [exploitdb](https://www.exploit-db.com/) | Exploit Database - Exploits for Penetration Testers, Researchers, and Ethical Hackers |
|  |  |
| **Reverse Shells** |
| [swisskyrepo](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md)| Reverse Shell Cheat Sheet |
| [pentestmonkey](https://web.archive.org/web/20200901140719/http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet)| Reverse Shell Cheat Sheet |
| | |
| **Cryptography** |
| [password crackers](https://www.unix-ninja.com/p/A_cheat-sheet_for_password_crackers)| A cheat-sheet for password crackers |
|  |  |
| **OWASP** |
| [cheatsheet series](https://cheatsheetseries.owasp.org/index.html) | OWASP Cheat Sheet Series |
|  |  |
| **PortSwigger academy** |
| [sql-injection](https://portswigger.net/web-security/sql-injection/cheat-sheet) | SQL injection cheat sheet |
|  |  |
| **HTB academy** |
| [cheatsheet-77](htb-academy/cheatsheet-77.md) | HTB Academy - Getting started |
| [cheatsheet-35](htb-academy/cheatsheet-35.md) | HTB Academy - Web Requests |
| [cheatsheet-54](htb-academy/cheatsheet-54.md) | HTB Academy - Attacking Web Applications with Ffuf |
|  |  |

## Introduction's and manuals
| Author | Name | Description |
| ------ | ---- | ----------- |
| Ashley Taylor | [bit & bytes](https://web.stanford.edu/class/cs101/bits-bytes.html) | CS101 - Introduction to Computing Principles: Bits and Bytes |
| ippsec | [tmux](https://www.youtube.com/watch?v=Lqehvpe_djs) | Introduction to tmux video |
| Simon Bennetts | [ZAP in Ten](https://www.alldaydevops.com/zap-in-ten) | ZAP in Ten is a series of short form videos; where each video highlights a specific feature or resource for ZAP |
| OWASP | [ZAP User Guide](https://www.zaproxy.org/docs/desktop/ui/) | OWASP ZAP Desktop User Guide |
|  |  |

## Tools & Resources
Name | Description
---- | ----
| **Operating Systems**|
| [jq](https://github.com/stedolan/jq) | Command-line JSON processor |
| [bat](https://github.com/sharkdp/bat) | A cat(1) clone with wings |
| [command-not-found](https://command-not-found.com/) | Install any command on any operating system |
| | |
| **Cryptography** |
| [CyberChef](https://gchq.github.io/CyberChef/)| The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis |
| [Ciphey](https://github.com/Ciphey/Ciphey) | Automatically decrypt encryptions without knowing the key or cipher, decode encodings, and crack hashes  |
| [CrackStation](https://crackstation.net/) | Free Password Hash Cracker |
| [John the Ripper](https://github.com/openwall/john) | John the Ripper jumbo - advanced offline password cracker, which supports hundreds of hash and cipher types, and runs on many operating systems, CPUs, GPUs, and even some FPGAs |
| [hashcat](https://hashcat.net/hashcat/) | Advanced Password Recovery |
| [kali hash-identifier](https://tools.kali.org/password-attacks/hash-identifier) | Software to identify the different types of hashes used to encrypt data and especially passwords |
| [hash_identifier](https://hashes.com/en/tools/hash_identifier) | Identify and detect unknown hashes using this tool. This page will tell you what type of hash a given string is. If you want to attempt to Decrypt them, click this link instead. [Decrypt Hashes](https://hashes.com/en/decrypt/hash/) |
| [Hash Analyzer](https://www.tunnelsup.com/hash-analyzer/) | Tool to identify hash types |
| [RsaCtfTool](https://github.com/Ganapati/RsaCtfTool) | RSA attack tool (mainly for ctf) - retreive private key from weak public key and/or uncipher data |
| [GnuPG Handbook](https://www.gnupg.org/gph/en/manual/x56.html) | The GNU Privacy Handbook |
|  |  |
| **Shells** |
| [rlwrap](https://github.com/hanslub42/rlwrap) | A readline wrapper |
| [msfvenom](https://www.offensive-security.com/metasploit-unleashed/msfvenom/)| MSFvenom - Metasploit Unleashed |
| [evil-winrm](https://github.com/Hackplayers/evil-winrm)| The ultimate WinRM shell for hacking/pentesting  |
| [socat binary](https://github.com/andrew-d/static-binaries/blob/master/binaries/linux/x86_64/socat?raw=true)| socat static compiled binary |
| [revshells](https://www.revshells.com/)| Reverse Shell Generator |
|  |  |
| **Privilege Escalation** |
| [GTFOBins](https://gtfobins.github.io/) | GTFOBins is a curated list of Unix binaries that can be used to bypass local security restrictions in misconfigured systems |
|  |  |
| **SecLists** |
| [SecLists](https://github.com/danielmiessler/SecLists) | SecLists is the security tester's companion. It's a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more.  |
|  |  |
| **Payloads** |
| [XSS Payloads](http://www.xss-payloads.com/) | The wonderland of JavaScript unexpected usages, and more |
| [msfvenom payloads](https://www.offensive-security.com/metasploit-unleashed/binary-payloads/)| Binary Payloads - Metasploit Unleashed |
|  |  |
| **HTTP clients** |
|  [curl](https://curl.se/)| command line tool and library for transferring data with URLs |
|  [Wget](https://www.gnu.org/software/wget/)| GNU Wget is a free software package for retrieving files using HTTP, HTTPS, FTP and FTPS, the most widely used Internet protocols |
| [Invoke-WebRequest](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/invoke-webrequest?view=powershell-7.1)| Microsoft.PowerShell.Utility - Gets content from a web page on the internet |
| **APIs** |
|  [Hoppscotch](https://github.com/hoppscotch/hoppscotch)| Open source API development ecosystem |
|  [Beeceptor](https://beeceptor.com/)| Rest API mocking and intercepting in seconds |
|  [Httpreq.com](https://httpreq.com/)| A free service that allows you to record http requests. This can be useful to debug webhooks, chat-bots or other head-less interactions. |
|  |  |
| **Add-ons & Extentions** |
| [FoxyProxy](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/)| FoxyProxy is an advanced proxy management tool that completely replaces Firefox's limited proxying capabilities |
| [Wappalyzer](https://www.wappalyzer.com/apps/)| Wappalyzer is a browser extension that uncovers the technologies used on websites.  |
| [HUNT](https://github.com/bugcrowd/HUNT)| HUNT Suite is a collection of Burp Suite Pro/Free and OWASP ZAP extensions |
| [PwnFox](https://github.com/yeswehack/PwnFox)| PwnFox is a Firefox/Burp extension that provide usefull tools for your security audit |
| [YesWeBurp](https://github.com/yeswehack/YesWeBurp)| YesWeBurp is an extension for BurpSuite allowing you to access all your https://yeswehack.com/ bug bounty programs directly inside Burp |
| [zap-extensions](https://github.com/zaproxy/zap-extensions)| OWASP ZAP Add-ons |
|  |  |
| **Deliberately vulnerable Applications** |
|  [Juice Shop](https://owasp.org/www-project-juice-shop/)|  Juice Shop encompasses vulnerabilities from the entire OWASP Top Ten along with many other security flaws found in real-world applications |
|  |  |
| **Pwning boxes**
|  [pwn-machine](https://github.com/yeswehack/pwn-machine)| PwnMachine is a self hosting solution based on docker aiming to provide an easy to use pwning station for bug hunters.  |
|  [parrotsec container](https://hub.docker.com/r/parrotsec/security)| Official Parrot Security container image pre-loaded with pentest tools |
|  [parrotsec VM](https://www.parrotsec.org/download/)| Parrot OS, the flagship product of Parrot Security is a GNU/Linux distribution based on Debian and designed with Security and Privacy in mind |
|  |  |
| **File sharing** |
| [Lufi](https://upload.disroot.org/)| Lufi is a free (as in free speech) file hosting software |
|  |  |
| **Other** |
| [pyWhat](https://github.com/bee-san/pywhat) | Identify anything. pyWhat easily lets you identify emails, IP addresses, and more. Feed it a .pcap file or some text and it'll tell you what it is! |
| [static-binaries](https://github.com/andrew-d/static-binaries) | Various *nix tools built as statically-linked binaries  |
|  |  |


## Examples & HowTo's
| Name | Description |
| ---- | ---- |
| **Basic Tools** |
| [tcpdump](https://danielmiessler.com/study/tcpdump/) | A tcpdump Tutorial with Examples — 50 Ways to Isolate Traffic |
|  |  |
| **Shell's** |
| [TryHackMe - Intro to shells](https://tryhackme.com/room/introtoshells)| What the Shell? An introduction to sending and receiving (reverse/bind) shells when exploiting target machines |
| [upgrading shells](https://blog.ropnop.com/upgrading-simple-shells-to-fully-interactive-ttys/#method-2-using-socat) | Upgrading a shell to a fully interactive TTY |
|  |  |



