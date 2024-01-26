## Ferramentas para Hacking
Abaixo segue uma pequena lista de ferramentas que poderão te auxiliar em todo o processo do pentest, desde a enumeração à pós exploração em um ambiente, incluindo redes  Active Directory, ambientes mobile, campanhas de phishing e muito mais!
<br>

### :male_detective: Enumeração

> [!IMPORTANT]
> Ferramentas para Enumeração te ajudam a obter informações sobre o ambiente alvo, seja de forma passiva ou ativa.

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [CrossLinked](https://github.com/m8sec/CrossLinked)      | **Python** | `Linux/Windows/macOS` | LinkedIn enumeration tool to extract valid employee names from an organization through search engine scraping. |
| [Nmap](https://github.com/nmap/nmap)      | **C** | `Linux/Windows/macOS` | Nmap - the Network Mapper. |
| [Sublist3r](https://github.com/aboul3la/Sublist3r)      | **Python** | `Linux/Windows/macOS` | Fast subdomains enumeration tool for penetration testers. |
| [Waybackurls](https://github.com/tomnomnom/waybackurls)      | **Go** | `Linux/Windows/macOS` | Fetch all the URLs that the Wayback Machine knows about for a domain. |
| [WhatWeb](https://github.com/urbanadventurer/WhatWeb)      | **Ruby** | `Linux/macOS` | Next generation web scanner. |
| [WafW00f](https://github.com/EnableSecurity/wafw00f)      | **Python** | `Linux/Windows/macOS` | WAFW00F allows one to identify and fingerprint Web Application Firewall (WAF) products protecting a website. |
| [Subfinder](https://github.com/projectdiscovery/subfinder)      | **Go** | `Linux/Windows/macOS` | Fast passive subdomain enumeration tool. |
| [Feroxbuster](https://github.com/epi052/feroxbuster)      | **Rust** | `Linux/macOS` | A fast, simple, recursive content discovery tool written in Rust. |
| [Dnsx](https://github.com/projectdiscovery/dnsx)      | **Go** | `Linux/Windows/macOS` | dnsx is a fast and multi-purpose DNS toolkit allow to run multiple DNS queries of your choice with a list of user-supplied resolvers. |

<br>

### :spider: Web Hacking

> [!IMPORTANT]
>Ferramentas para ataques em aplicações web, facilitando o comprometimento de servidores por meio desses serviços.

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [BurpSuite](https://portswigger.net/burp)      | **Java** | `Linux/Windows/macOS` | Best-in-class software and learning for security engineers and penetration testers. |
| [OwaspZap](https://portswigger.net/burp)      | **Java** | `Linux/Windows/macOS` | The ZAP core project. |
| [Commix](https://github.com/commixproject/commix)      | **Python** | `Linux/Windows/macOS` | Automated All-in-One OS Command Injection Exploitation Tool. |
| [SQLMap](https://github.com/sqlmapproject/sqlmap)      | **Python** | `Linux/Windows/macOS` | Automatic SQL injection and database takeover tool. |
| [Dalfox](https://github.com/hahwul/dalfox)      | **Go** | `Linux/Windows/macOS` | Dalfox is a powerful open-source XSS scanner and utility focused on automation. |
| [Nuclei](https://github.com/projectdiscovery/nuclei)      | **Go** | `Linux/Windows/macOS` | Fast and customizable vulnerability scanner based on simple YAML based DSL. |
| [WPScan](https://github.com/wpscanteam/wpscan)      | **Python** | `Linux/macOS` | WPScan WordPress security scanner. |
| [JexBoss](https://github.com/joaomatosf/jexboss)      | **Python** | `Linux/macOS` | Jboss (and Java Deserialization Vulnerabilities) verify and EXploitation Tool. |

<br>

### :computer: Post-Exploitation

> [!IMPORTANT]
>Após obter acesso em uma rede, é necessário explorar mais a fundo a máquina onde o acesso foi obtido, e após isso, explorar a rede.

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [LinPEAS](https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS)      | **Shell** | `Linux/macOS` | Linux Privilege Escalation Awesome Script. |
| [WinPEAS](https://github.com/carlospolop/PEASS-ng/tree/master/winPEAS)      | **PowerShell** | `Windows` | Windows Privilege Escalation Awesome Script. |
| [Meterpreter](https://github.com/rapid7/metasploit-framework)      | **Ruby** | `Linux/Windows/macOS` | Meterpreter is a Metasploit attack payload that provides an interactive shell from which an attacker can explore the target machine and execute code. |
| [D3m0n1z3dShell](https://github.com/MatheuZSecurity/D3m0n1z3dShell)      | **Shell** | `Linux` | Demonized Shell is an Advanced Tool for persistence in linux. |
| [Mimikatz](https://github.com/gentilkiwi/mimikatz)      | **C++** | `Windows` | A little tool to play with Windows security. |
| [Proxychains](https://github.com/haad/proxychains)      | **C** | `Linux/macOS` | A a tool that forces any TCP connection made by any given application to follow through proxy like TOR or any other SOCKS4, SOCKS5 or HTTP(S) proxy. |
| [Empire](https://github.com/BC-SECURITY/Empire/)      | **Python** | `Linux/Windows/macOS` | Empire is a post-exploitation and adversary emulation framework that is used to aid Red Teams and Penetration Testers. |
| [Evil-winrm](https://github.com/Hackplayers/evil-winrm)      | **Ruby** | `Linux/macOS` | The ultimate WinRM shell for hacking/pentesting. |

<br>

### :key: Ataques em Credenciais

> [!IMPORTANT]
>Abaixo confira algumas ferramentas com foco em quebra de senhas, seja online (serviços web) e offline (hash).

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [Hashcat](https://github.com/hashcat/hashcat)      | **C** | `Linux/Windows/macOS` | World's fastest and most advanced password recovery utility. |
| [PseudoHash](https://github.com/t3l3machus/psudohash)      | **Python** | `Linux/Windows/macOS` | Generates millions of keyword-based password mutations in seconds. |
| [JohnTheRipper](https://github.com/openwall/john)      | **C** | `Linux/macOS` | Advanced offline password cracker, which supports hundreds of hash and cipher types, and runs on many operating systems, CPUs, GPUs, and even some FPGAs. |
| [Hydra](https://github.com/vanhauser-thc/thc-hydra)      | **C** | `Linux/macOS` | Online bruteforce tool. |
| [Trevorspray](https://github.com/blacklanternsecurity/TREVORspray)      | **Python** | `Linux/macOS` | TREVORspray is a modular password sprayer with threading, clever proxying, loot modules, and more. |

<br>

### :book: Wordlist

> [!IMPORTANT]
>Você poderá combinar as wordlists abaixo com ataques focados em quebra de senha e também reconhecimento de usuários/arquivos/diretórios/subdomínios em um ambiente web.

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [Wordlists](https://github.com/kkrypt0nn/wordlists)      | **Txt** | `n/a` | A collection of wordlists for many different usages. |
| [SecLists](https://github.com/danielmiessler/SecLists)      | **Txt** | `n/a` | List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. |
| [RockYou2021](https://github.com/ohmybahgosh/RockYou2021.txt)      | **Txt** | `n/a` | RockYou2021.txt is a MASSIVE WORDLIST compiled of various other wordlists. |

<br>

### :satellite: Wi-Fi Hacking

> [!IMPORTANT]
>Abaixo segue também uma lista de ferramentas com objetivo principal ataques em redes Wi-Fi, que podem ser combinadas com a lista de senhas anterior.

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [Aircrack-ng](https://github.com/aircrack-ng/aircrack-ng)      | **C** | `Linux/macOS` | WiFi security auditing tools suite. |
| [Wifite2](https://github.com/derv82/wifite2)      | **Python** | `Linux/macOS` | Rewrite of the popular wireless network auditor, "wifite". |
| [Bettercap](https://github.com/bettercap/bettercap)      | **Go** | `Linux/macOS` | The Swiss Army knife for 802.11, BLE, IPv4 and IPv6 networks reconnaissance and MITM attacks. |
| [ARPSpoof](https://github.com/smikims/arpspoof)      | **C** | `Linux/macOS` | Performs an ARP spoofing attack using the Linux kernel's raw sockets. |
| [Wifi-Hacking](https://github.com/ankit0183/Wifi-Hacking)      | **Python** | `Linux/macOS` | Cyber Security Tool For Hacking Wireless Connections Using Built-In Kali Tools. |
| [wifipumpkin3](https://github.com/P0cL4bs/wifipumpkin3)      | **Python** | `Linux/Windows/macOS` | Powerful framework for rogue access point attack. |
| [wifiphisher](https://github.com/wifiphisher/wifiphisher)      | **Python** | `Linux/macOS` | The Rogue Access Point Framework. |

<br>

### :nose: Sniffing

> [!IMPORTANT]
>Também são úteis algumas ferramentas para captura e análise de tráfego da rede.

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [Wireshark](https://gitlab.com/wireshark/wireshark)      | **C** | `Linux/Windows/macOS` | Network traffic sniffer and analyzer. |
| [TCPDump](https://github.com/the-tcpdump-group/tcpdump)      | **C** | `Linux/macOS` | Network dissector. |

<br>

### :door: Active Directory

> [!IMPORTANT]
>Principalmente em redes de Active Directory, as ferramentas abaixo podem ser facilmente utilizadas para ataques nesses ambientes.

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [Crackmapexec](https://github.com/byt3bl33d3r/CrackMapExec)      | **Python** | `Linux/macOS` | A swiss army knife for pentesting networks. |
| [Impacket](https://github.com/fortra/impacket)      | **Python** | `Linux/macOS` | Impacket is a collection of Python classes for working with network protocols. |
| [BloodHound](https://github.com/BloodHoundAD/BloodHound)      | **PowerShell** | `Windows` | Six Degrees of Domain Admin. |
| [Responder](https://github.com/lgandx/Responder)      | **Python** | `Linux/Windows/macOS` | Responder is a LLMNR, NBT-NS and MDNS poisoner, with built-in HTTP/SMB/MSSQL/FTP/LDAP rogue authentication server supporting NTLMv1/NTLMv2/LMv2. |
| [PsMapExec](https://github.com/The-Viper-One/PsMapExec)      | **Powershell** | `Windows` | A PowerShell tool that takes strong inspiration from CrackMapExec. |

<br>

### :iphone: Android Pentest

> [!IMPORTANT]
>Hoje qualquer empresa quer ter ou já tem um aplicativo, também existem ferramentas para pentest nesses aplicativos mobile, tanto Android quanto iOS.

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [Frida](https://github.com/frida/frida/)      | **Python** | `Linux/Windows/macOS` | Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers. |
| [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)      | **Python** | `Linux/Windows/macOS` | Mobile Security Framework (MobSF) is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework. |
| [reFlutter](https://github.com/Impact-I/reFlutter)      | **Python** | `Linux/Windows/macOS` | Flutter Reverse Engineering Framework. |

<br>

### :email: Phishing

> [!IMPORTANT]
>Campanhas de phishing são extremamente importante, principalmente visando uma execução de um Red Team.

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [Gophish](https://github.com/gophish/gophish)      | **Go** | `Linux/Windows/macOS` | Open-Source Phishing Toolkit. |
| [Evilgnix2](https://github.com/kgretzky/evilginx2)      | **Go** | `Linux/Windows/macOS` | Standalone man-in-the-middle attack framework used for phishing login credentials along with session cookies, allowing for the bypass of 2-factor authentication. |

<br>

### :bug: C2

> [!IMPORTANT]
>Ferramentas de comando e controle são ótimas para manter acesso em um ambiente, principalmente quando você precisa desenvolver seus próprios beacons/stagers e precisa de uma framework robusta para manter conexão com as máquinas infectadas.

| Ferramenta        | Linguagem           | Suporte  | Descrição    |
| ----------- |-------------------------|----------|----------------|
| [CobaltStrike](https://www.cobaltstrike.com/)      | **Java** | `Linux/Windows/macOS` | Software for Adversary Simulations and Red Team Operations. |
| [BruteRatel](https://bruteratel.com/)      | **C#** | `Linux/Windows/macOS` | A Customized Command and Control Center for Red Team and Adversary Simulation. |
| [Covenant](https://github.com/cobbr/Covenant)      | **.NET** | `Linux/Windows/macOS` | Covenant is a collaborative .NET C2 framework for red teamers. |
