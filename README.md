# IoT_MIPS
Retrieval Internet of Thing for MIPS Malware Analysis

## Commercial Antivirus Limitation

Technically, the modus operandi for the identification of malicious files and servers refers to consult in named blacklist databases. The VirusTotal platform issues the diagnoses regarding malignant characteristics related to files and web servers.

When it comes to suspicious files, VirusTotal issues the diagnostics provided by the world's leading commercial antivirus products. Regarding suspicious web servers, VirusTotal uses the database responsible for sensing virtual addresses with malicious practices.

VirusTotal has Application Programming Interface (APIs) that allow programmers to query the platform in an automated way and without the use of the graphical web interface. The proposed paper employs two of the APIs made available by VirusTotal. The first one is responsible for sending the investigated files to the platform server. The second API, in turn, makes commercial antivirus diagnostics available for files submitted to the platform by the first API.

Initially, the executable malwares are sent to the server belonging to the VirusTotal platform. After that, the executables are analyzed by the 71 commercial antiviruses linked to VirusTotal. Therefore, the antivirus provides its diagnostics for the executables submitted to the platform. VirusTotal allows the possibility of issuing three different types of diagnostics: malware, benign and omission.

Then, through the VirusTotal platform, the proposed paper investigates 68 commercial antiviruses with their respective results presented in Table 2. We used 1020 malicious executables for MIPS obtained from our database. The goal of the work is to check the number of virtual pests cataloged by antivirus. The motivation is that the acquisition of new virtual plagues plays an important role in combating malicious applications. Therefore, the larger the database of malwares blacklisted, the better it tends to be the defense provided by the antivirus.

As for the first possibility of VirusTotal, the antivirus detects the malignity of the suspicious file. In the proposed experimental environment, all submitted executables are public domain malwares. Therefore, in the proposed study, the antivirus hits when it detects the malignity of the investigated executable. Malware detection indicates that the antivirus provides a robust service against cyber-intrusions. As larger the blacklist database, better tends to be the defense provided by the antivirus.

In the second possibility, the antivirus attests to the benignity of the investigated file. Therefore, in the proposed study, when the antivirus attests the benignity of the file, it is a case of a false negative – since all the samples are malicious. That is, the investigated executable is a malware; however, the antivirus attests to benignity in the wrong way.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

Table 1 shows the results of the evaluated 71 antivirus products. Only three of these antiviruses scored above 99%. These antiviruses are: MicroWorld-eScan, Ad-Aware, and Tencent. Malware detection indicates that these antivirus programs provide an efficient service against cyber-intrusions.

A major adversity in combating malicious applications is the fact that antivirus makers do not share their malware blacklists due to commercial disputes. Through Table 2 analyse, the proposed paper points to an aggravating factor of this adversity: the same antivirus vendor does not even share its databases between its different antivirus programs. Note, for example, that McAfee and McAfee-GW-Edition antiviruses belong to the same company. Their blacklists, though robust, are not shared with each other. Therefore, the commercial strategies of the same company hinder the confrontation with malware. It complements that antivirus vendors are not necessarily concerned with avoiding cyber-invasions, but with optimizing their business income.

Malware detection ranged from 0% to 99.51%, depending on the antivirus being investigated. On average, the 71 antiviruses were able to detect 53.36% of the evaluated virtual pests, with a standard deviation of 44.68%. The high standard deviation indicates that the detection of malicious executables may suffer abrupt variations depending on the antivirus chosen. It is determined that the protection, against cybernetic invasions, is due to the choice of a robust antivirus with a large and updated blacklist.

As for the false negatives; VBA32, VIPRE, Yandex, CMC, K7GW, K7AntiVirus, Panda, Bkav, and Baidu antiviruses, wrongly stated that malware was benign in more than 99% of cases.
On average, antiviruses attested false negatives in 32.67% of the cases, with a standard deviation of 41.80%. Tackling the benignity of malware can lead to irrecoverable damage. A person or institution, for example, would rely on a particular malicious application when, in fact, it is malware.

VirIT, Babable, F-Prot, Trustlook, CrowdStrike, APEX, and Cybereason antivirus companies hardly omitted opinion on any of the 1,020 malicious samples.
On average, the antiviruses were missing in 13.97% of the cases, with a standard deviation of 32.93%. The omission of the diagnosis points to the limitation of these antiviruses that have limited blacklists for detection of malware in real time.

It is included as adversity, in the combat to malicious applications, the fact of the commercial antiviruses do not possess a pattern in the classification of the malwares as seen in Table 2. We choose 3 of 1,020 malwares samples in order to exemplify the miscellaneous classifications of commercial antiviruses. The chosen malware are VirusShare_00598c4fedb6b6d22472a53c044c680b, VirusShare_009c4e3c30673aed0025b59e8b1581e4 and VirusShare_01296be44c6c7ffbc00b500a2ae28257. In this way, the time when manufacturers react to a new virtual plague is affected dramatically. As there is no a pattern, antiviruses give the names that they want, for example, a company can identify a malware as "Trojan.Linux.Mirai.4!c" and a second company identify it as "ELF:Mirai-HU [Trj]". Therefore, the lack of a pattern, besides the no-sharing of information among the antivirus manufacturers, hinders the fast and effective detection of a malicious application.

###### Table 1 Results of 71 commercial antiviruses:

Antivirus |	Deteccion (%) |	False Negative (%) |	Omission (%)
--------- | ------------- | ------------------ | -------------
MicroWorld-eScan|99,51|0,49|0|
Ad-Aware|99,31|0,49|0,2|
Tencent|99,12|0,78|0,1|
BitDefender|98,92|0,88|0,2|
FireEye|98,73|0,39|0,88|
Emsisoft|98,63|1,18|0,2|
NANO-Antivirus|98,33|1,67|0|
DrWeb|98,24|1,57|0,2|
AVG|97,94|0|2,06|
Kaspersky|97,55|1,67|0,78|
GData|97,25|0,59|2,16|
McAfee|96,96|2,55|0,49|
McAfee-GW-Edition|96,18|2,16|1,67|
Avira|96,08|3,92|0|
Avast|95,88|2,45|1,67|
Cynet|95,78|4,12|0,1|
ClamAV|95,49|3,92|0,59|
Ikarus|94,41|0,29|5,29|
Symantec|94,31|3,53|2,16|
Microsoft|93,92|5,1|0,98|
Zillya|93,53|5,59|0,88|
ESET-NOD32|93,53|6,47|0|
Fortinet|92,35|7,65|0|
ALYac|91,37|0,78|7,84|
TrendMicro|91,27|8,43|0,29|
ZoneAlarm|91,18|8,14|0,69|
MAX|90,98|8,53|0,49|
Avast-Mobile|90,98|9,02|0|
Rising|90|9,8|0,2|
TrendMicro-HouseCall|89,9|10|0,1|
AhnLab-V3|89,12|10,88|0|
Arcabit|88,04|11,96|0|
Qihoo-360|85,1|12,65|2,25|
BitDefenderTheta|80,39|18,63|0,98|
Sophos|78,63|21,27|0,1|
Lionic|77,65|21,67|0,69|
Comodo|74,12|25,49|0,39|
Antiy-AVL|73,14|16,96|9,9|
F-Secure|72,84|26,57|0,59|
Cyren|69,8|30,1|0,1|
Jiangmin|68,33|0,49|31,18|
MaxSecure|43,33|55,29|1,37|
Sangfor|12,25|85,69|2,06|
CAT-QuickHeal|9,8|90,2|0|
Gridinsoft|4,02|95,49|0,49|
ViRobot|2,35|97,65|0|
VBA32|0,78|99,02|0,2|
VIPRE|0,59|99,22|0,2|
Elastic|0,29|1,76|97,94|
VirIT|0,2|0|99,8|
Yandex|0,1|99,9|0|
CMC|0,1|99,9|0|
K7GW|0,1|99,9|0|
K7AntiVirus|0,1|99,8|0,1|
Panda|0,1|99,71|0,2|
eGambit|0|5|95|
Babable|0|0,1|99,9|
F-Prot|0|0,2|99,8|
Trustlook|0|0,2|99,8|
CrowdStrike|0|0,49|99,51|
APEX|0|0,1|99,9|
Bkav|0|99,9|0,1|
Zoner|0|98,73|1,27|
Acronis|0|99,9|0,1|
Kingsoft|0|97,55|2,45|
TACHYON|0|100|0|
SUPERAntiSpyware|0|100|0|
Baidu|0|99,61|0,39|
Malwarebytes|0|99,8|0,2|
TotalDefense|0|85,49|14,51|
Cybereason|0|0,1|99,9|

###### Table 2 Miscellaneous classifications of commercial antiviruses:

Antivírus |	VirusShare_001627d61a1bde3478ca4965e738dc1e |	VirusShare_075efef8c9ca2f675be296d5f56406fa |	VirusShare_0dab86f850fd3dafc98d0f2b401377d5
--------- | ------------------------------------------- | ------------------------------------------- | --------------------------------------------
Bkav	|	False Negative	|	False Negative	|	False Negative	|
Lionic	|	Trojan.Linux.Mirai.4!c	|	Trojan.Linux.Mirai.4!c	|	Trojan.Linux.Agent.4!c	|


## Materials and Methods

This paper proposes a database aiming at the classification of Android benign and malware executables. There are 1,020 malicious executables, and 1,020 other benign executables. Therefore, our datasaet is suitable for learning with artificial intelligence, since both classes of executables have the same amount.

For the construction of a pattern recognition AI (artificial intelligence), the conventional method used for its training is the use of classes and counter classes of a certain filetype. The designation chosen to refer to the categories was "benign files" for serious and safe applications and "malignant files" for applications that can be a threat to the user. The malwares samples are executables files for MIPS. The virtual plages were extracted from databases made avaiable by enthusiastic groups about the study of malwares through the digital plataform VirusShare. It should be noted that all benign executables were submitted to VirusTotal and all were its benign attested by the main commercial antivirus worldwide. The diagnostics, provided by VirusTotal, corresponding to the benign and malware executables are available in the virtual address of our database.

The construction of the test environment for the experiment was performed using the free software emulator QEMU[https://www.qemu.org/]. Unlike other more popular virtualization solutions, such as VirtualBox[https://www.virtualbox.org/], the emulator is able to install operating systems, such as the IoT MIPS and RISC-V architectures, on machines with divergent host processors , such as the desktop-oriented architectures. The guest system, 32-bit MIPS architecture, was configured and the GNU/Linux Debian and Fedora distributions installed on it for compilation and obtaining samples for analysis in sandbox.

The benign samples were extracted from GNU/Linux Fedora for MIPS architecture, on website official Fedora for linux devices. In addition, databases from others plataforms of benign executables were also used: GNU/Linux Debian for MIPS and compiled samples. To avoid repeat the samples, were used authoral scripts coded in python. The script read the files fetched and delete its copies.


## Dynamic Feature Extraction

The features of 32-bit MIPS files originate through the dynamic analysis of suspicious files. Therefore, in our methodology, the malware is executed in order to infect, intentionally, the GNU/Linux audited, in real time (dynamic), by the Cuckoo Sandbox. In total, 2,793 features are generated of each 32-bit MIPS file, regarding the monitoring of the suspect file in the proposed controlled environment. Next, the groups of features are detailed.

######	Features related to Code Injection, a technique used by an attacker to introduce code into vulnerable programs and change their behavior. The auditory checks whether the tested file try to:
-	execute a process and inject code while it is uncompressed;
-	injecting code into a remote process using one of the following functions: CreateRemoteThread or NtQueueApcThread.
	
######	Features related to Keyloggers, programs that record all user-entered keyboard entries, for the primary purpose of illegally capturing passwords and other confidential information. Checks whether the file being investigated tries to:
-	create mutexes of Ardamax or Jintor keyloggers.
	
######	Features related to the search for other possibly installed programs. The goal is to verify that the audited file searches for:
-	discover where the browser is installed, if there is one in the system.
-	discover if there is any sniffer or a installed network packet analyzer.

######	Features related to disable GNU/Linux components.

######	Features related to packing and obfuscation. The proposed digital forensic verifies if the suspect file:
-	has packet or encrypted information indicative of packing
-	creates a slightly modified copy of itself (polymorphic packing);
-	is compressed using UPX (Ultimate Packer for Executables) or VMProtect (software used in order to obfuscate code and virtualize programs).
-	
######	Features related to persistence, functionality of backup information in a system, without the need to register them before. Our Sandbox audit if suspicious file tries to:
-	create an ADS (Alternate Data Stream), NTFS feature that contains information to locate a specific file by author or title, used maliciously because as the information that is present in it does not change the characteristics of the file associated with it, transform them into an ideal option for building rootkits, because they are hidden (steganography);
-	install a self-executing in startup (autorun);
-	install a native executable to run at the beginning of GNU/Linux boot.

######	Features related to native GNU/Linux programs. It is audited, during its execution, if the suspicious file tries to:
-	allocate write and read memory for execution, usually for unpacking;
-	identify analysis tools installed by the location of the installation of said tool;
-	check for known devices or GNU/Linux from forensic tools and debuggers;
-	detect the presence of the Wine emulator;
-	install yourself on AppInit to inject into new processes;

######	Features related to GNU/Linux boot. Audit if suspicious file tries to:

-	modify boot configurations;
-	install a bootkit (malicious files for the purpose of changing and infecting the master boot record of the computer) through modifications to the hard disk;
-	create a executable file on the system;
-	create or configure registry with a long string of bytes, most likely to store a binary file or configure a malware;
-	create a service;
-	use the APIs to generate a cryptographic key;
-	erase your original disk binary;
-	load a device driver;
-	release and execute a binary file;
-	remove evidence that a file has been downloaded from the Internet without the user being aware of it;
-	create files related to Fakerean Fraudtool malware;
-	connect to an IP BitTorrent Bleepchat (encrypted chat service and P2P from BitTorrent);
-	connect to IP's related to Chinese instant messaging services, such as QQ, used by hackers maliciously;
-	access Bitcoin/ALTCoin portfolios, which can be used to transfer funds into illegal transactions.

######	Features that seek to disable features of GNU/Linux and other utilities. The audit checks to see if the file can:

-	modify system policies to prevent the launch of specific applications or executables;
-	disable browser security warnings;
-	disable GNU/Linux security features and properties;
-	disable google SPDY network protocol support in Mozilla Firefox browsers to increase the ability of an internet malware to gain access to sensitive information;
-	disable system restore;

######	Features related to executable files. The proposed digital forensic verifies that the suspect file tries to:

-	use the BITSAdmin tool (command line tool originally used to download and upload files, as well as track the progress of this transfer, but which malicious hackers use) to download any file;
-	halt at least one process during its execution;
-	execute the WaitFor statement (it has originally the function of synchronizing events between networked computers, but which evildoers use in harmful ways), possibly to synchronize malicious activities.

######	Features related to memory dump, process in which the contents of RAM memory is copied for diagnostic purposes. The proposed digital forensics audits if the application tries to:
-	find malicious URL’s in memory dump processing;
-	find evidence of the presence and use of the yara program, used to perform memory dump's.

######	Features related to crypto-coin mining:
-	It is audited if the suspect application tries to connect to mining pools, the goal is to generate virtual currencies without the cognition (and not benefiting) the computer owner.

######	Features related to system modifications:
-	It is audited if the suspect application tries to create or modify system certificates, security center warnings, user account control behaviors, desktop wallpaper, or ZoneTransfer.ZoneID values in the ADS(Alternate Data Stream).

######	Feature related to POS (point of sale), type of attack that aims to obtain the information of credit and debit cards of victims. It is investigated if the audited file tries to:
-	create files related to malware POS Alina;
-	contact servers related to malware POS Alina;
-	contact botnets related to malware POS blackpos;
-	create mutexes related to malware POS decebel;
-	create mutexes and registry keys related to POS Dexter malware;
-	create mutexes and registry keys related to malware POS jackpos;
-	contact botnets related to malware POS jackpos;
-	contact servers related to POS poscardstealer malware.

######	Features related to shell code injectors. Our Sandbox checks if the tested file:
-	is a shell malware of powerfun type;
-	is a shell malware powerworm type;
-	attempts to create a suspicious shell process;
-	attempts to create log entries via shell scripts.

######	Features related to processes. Checks if the tested file:
-	is interested in some specific process in execution;
-	repeatedly searches for a process not found;
-	tries to fail some process.

######	Features related to ransomwares, cyber-attacks that turn the computer data inaccessible, requiring payment in order to restore the user access. Our Sandbox verifies that the audited server tries to:
-	create mutexes of ransomware named chanitor;
-	execute commands in bcdedit (command-line tool that manages boot configuration data) related to ransomware;
-	add extensions of files known to be ransomwares related to files that have been encrypted;
-	perform drives on files, which may be indicative of the data encryption process seen in an ransomware attack;
-	create instructions on how to reverse encryption made in an ransomware attack or attempt to generate a key file;
-	write a rescue message to disk, probably associated with an ransomware attack;
-	empty the trash;
-	remove or disable shadow copy, which is intended to speed up data restoration in order to avoid system recovery.

######	Features related to the use of sandboxes. The digital forensics examines if the tested file tries to:
-	detect if the sandboxes: Cuckoo, Joe, Anubis, Sunbelt, ThreatTrack/GFI/CW or Fortinet are being used, through the presence of own files used by them;
-	search for known directories where a sandbox can run samples;
-	check if any human activity is being performed;
-	install a procedure that monitors mouse events;
-	disconnect or restart the system to bypass the sandbox;
-	delay analysis tasks;
-	shut down GNU/Linux functions monitored by the cuckoo sandbox.

######	Features related to Trojans (malicious program that enters a computer masked as another program, legitimate) of remote access, or RAT (Remote Access Trojans). Our Sandbox verifies if the tested server tries to create files, registry keys, and/or mutexes related to RATs: 
- Adzok, bandook, beastdoor, beebus, bifrose, blackhole/schwarzesonne, blackice, blackshades, bladabindi, bottilda, bozokrat, buzus, comrat, cybergate, darkcloud, darkshell, delf trojan, dibik/shark, evilbot, farfli, fexel, flystudio, fynloski/darkcomet, ghostbot, hesperbot, hkit backdoor, hupigon, icepoint, jewdo backdoor, jorik trojan, karakum/saharabot, koutodoor, aspxor/kuluoz, likseput, madness, madness, magania, minerbot, mybot, naid backdoor, nakbot, netobserve spyware, netshadow, netwire, nitol/servstart, njrat, pasta trojan, pcclient, plugx, poebot/zorenium, poison ivy, pincav/qakbot, rbot, renos trojan, sadbot, senna spy, shadowbot, siggen, spynet, spyrecorder, staser, swrort, travnet, tr0gbot bifrose, turkojan, urlspy, urx botnet, vertexnet, wakbot, xtreme, zegost.

######	Features related to the banking threats (Trojan horses):

-	Find out if the test file tries to create registry keys, Mutexes or Trojan files, and/or try to contact HTTP servers of the known threats. Banking Banking, Banking, Prinyalka Banking, SpyEye, Tinba Banking, Zeus, Zeus P2P, Dridex, Emotet and Online Banking.

######	Features related to payload in network. Checks if the server tested tries to:
-	verify if the network activity contains more than one unique useragent;
-	create Remote Desktop Connection Protocol (RDP) mutexes;
-	check the presence of mIRC chat clients;
-	install Tor (the onion router, open source software with the ability to securely and anonymously create online connections in order to safeguard the user's right to privacy), or a hidden Tor service on the machine;
-	connect to a Chinese URL shorter with malicious history;
-	create mutexes related to remote administration tools VNC (Virtual Remote Computer).

######	Features associated with network traffic hint GNU/Linux 7 OS in PCAP format. Audit if suspicious document attempts to:
-	connect with an IP which is not responding to requests;
-	resolve a suspicious top domain;
-	start listening (socket) with some server;
-	connect to some dynamic DNS domain;
-	make HTTP requests;
-	generate ICMP traffic;
-	connect to some IRC server (possibly part of some BotNet);
-	make SMTP requests (possibly sending SPAM);
-	connect to some hidden TOR service through a TOR gateway;
-	generate IDS or IPS alerts with Snort and Suricata (network monitoring and management tools).

######	Features related to DNS servers (Domain Name System, servers responsible for the translation of URL addresses in IP). It is investigated the audited file tries to:
-	connect to DNS servers of dynamic DNS providers;
-	connect to the expired malicious site 3322.org, or its related domain, 125.77.199.30;
-	resolve some Free Hosting domain, possibly malicious.

######	Features related to file type.

-	It is audited if the suspect server the suspect file is a SSH, Telnet, SCP and / or FTP-style FTP client with its files, registry keys and mutexes;
-	It is investigated whether the suspect file is a suspect downloader (download manager);
-	It is investigated if the file has in it a path to a pdb extension file, which contains information given directly to the system compiler.

######	Features related to malware. Checks whether the audited file tries to:

-	create Mutexes (single name files, with a function to set a lock / unlock state, which ensures that only one process at a time uses the resources);
-	create Advanced Persistent Threat (APT) files, or connect to IP addresses and URLs of known threats: Carbunak/Anunak, CloudAtlas, Flame, Inception, Panda Putter, Sandworm, Turla Carbon and Turla/Uroboros.

######	Features related to Backdoors:

-	It is audited if the suspect file tries to create Backdoor files, registry keys or Mutexes of the known threats LolBot, SDBot, TDSS, Vanbot and Schwarzesonne.

######	Features related to bots (machines that perform automatic network tasks, malicious or not, without the knowledge of their owners):

-	It is audited if the suspect file tries to contact HTTP servers and / or tries to create Mutexes associated with Athena, Beta, DirtJumper, Drive2, Kelihos, Kotver, Madness, Pony, Ruskill, Solar, VNLoader, and Warbot Bots.

######	Features related to browsers. Checks if the suspect file tries to:

-	install a Browser Helper object (usually a DLL file that adds new functions to the browser) in order to let the navigation experience be impaired in some way;
-	modify browser security settings;
-	modify the browser home page;
-	acquire private information from locally installed internet browsers.

######	Features related to Bitcoin:

-	It is examined if the suspect file attempts to install the OpenCL library, Bitcoins mining tool.

######	Features related to Ransomware (type of malware that by means of encryption, leaves the victim's files unusable, then request a redemption in exchange for the normal use later of the user's files, a redemption usually paid in a non-traceable way, such as bitcoins) .

-	It is monitored if the suspect file tries to show, generate, or is an hta file (HTML Application), common extension type in situations involving ransomware.

######	Features related to exploit-related features which constitute malware attempting to exploit known or unackaged vulnerabilities, faults or defects in the system or one or more of its components in order to cause unforeseen instabilities and behavior on both your hardware and in your software. The proposed digital forensic verifies whether the audited file attempts to:

-	contact the HTTP server of the Blackhole Exploit Kit (a threat that had its peak of performance in 2012, aims to download malicious content on the victim's computer);
-	create mutexes of the Sweet Orange EK exploit;
-	create mutexes from other known exploits;
-	use the technique known as heapspray, where memory is completely filled, causing the computer to experience crashes.

######	Features related to Infostealers, malicious programs that collect confidential information from the affected computer. Digital forensics checks if suspicious file tries to:

-	create files related to infostealer Derusbi;
-	collect credentials and software information from locally installed FTP clients;
-	collect information and credentials related to locally installed Instant Messenger clients;
-	create a program that monitors keyboard inputs (possibly a keylogger);
-	collect credentials and information from locally installed e-mail clients.


######	Features related to virtual machines. The goal is to verify that the audited file searches for:

-	detect whether Bochs, Sandboxie, VirtualBox, VirtualPC, VMware, Xen or Parallels virtual machines are being used through the presence of registry keys (regedit), files, instructions, and device drivers used by them;
-	find the computer name;
-	find the disk size and other information about the disk, which may indicate the use of a virtual machine with small and fixed disk size, or dynamic allocation;
-	discover the BIOS version, which may indicate virtualization;
-	discover the CPU name in the registry, which may indicate virtualization;
-	detect a virtual machine through the firmware;
-	detect the presence of IDE drives in the registry, which may indicate virtualization;
-	detect the presence of SCSI disks;
-	enumerate services, which may indicate virtualization;
-	detect Hyper-V through registry keys (regedit);
-	check the amount of memory in the system in order to detect virtual machines with little available memory;
-	check adapter addresses that can be used to detect virtual network interfaces;
-	detect a virtual machine by using pseudo devices (parts of the kernel that act as device drivers but do not actually match any hardware present on the machine);
-	detect whether it is running in a GNU/Linux, indicative of VirtualBox usage.

######	Features related to Firewall. The proposed digital forensics audits if the file tries to:

-	modify local firewall policies and settings.

######	Features related to cloud computing. The file is audited when you try to:

-	connect to storage services and / or files from Dropbox, Google, MediaFire, MegaUpload, RapidShare, Cloudflare and Wetransfer.

######	Features related to DDoS (Dynamic Danial of Service) attacks:

-	It is audited if the suspect file create mutexes, other files and bots known as DDoS of the IPKiller, Dark-DDoS, Eclipse and Blackrev types.

######	Features related to Infostealers, malicious programs that collect confidential information from the affected computer. Digital forensics checks if suspicious file tries to:

-	create files related to infostealer Derusbi;
-	collect credentials and software information from locally installed FTP clients;
-	collect information and credentials related to locally installed Instant Messenger clients;
-	create a program that monitors keyboard inputs (possibly a keylogger);
-	collect credentials and information from locally installed e-mail clients.
