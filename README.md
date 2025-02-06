# Mediyes
Retrieval for Mediyes Malware Analysis

## Commercial Antivirus Limitation

Technically, the modus operandi for the identification of malicious files and servers refers to consult in named blacklist databases. The VirusTotal platform issues the diagnoses regarding malignant characteristics related to files and web servers.

When it comes to suspicious files, VirusTotal issues the diagnostics provided by the world's leading commercial antivirus products. Regarding suspicious web servers, VirusTotal uses the database responsible for sensing virtual addresses with malicious practices.

VirusTotal has Application Programming Interface (APIs) that allow programmers to query the platform in an automated way and without the use of the graphical web interface. The proposed paper employs two of the APIs made available by VirusTotal. The first one is responsible for sending the investigated files to the platform server. The second API, in turn, makes commercial antivirus diagnostics available for files submitted to the platform by the first API.

Initially, the executable malwares are sent to the server belonging to the VirusTotal platform. After that, the executables are analyzed by the 80 commercial antiviruses linked to VirusTotal. Therefore, the antivirus provides its diagnostics for the executables submitted to the platform. VirusTotal allows the possibility of issuing three different types of diagnostics: malware, benign and omission.

Then, through the VirusTotal platform, the proposed paper investigates 80 commercial antiviruses with their respective results presented in Table 1. We used 1,865 malicious executables for 32-bit architecture. The goal of the work is to check the number of virtual threats cataloged by antivirus. The motivation is that the acquisition of new virtual plagues plays an important role in combating malicious applications. Therefore, the larger the database of malwares blacklisted, the better it tends to be the defense provided by the antivirus.

As for the first possibility of VirusTotal, the antivirus detects the malignity of the suspicious file. In the proposed experimental environment, all submitted executables are public domain malwares. Therefore, in the proposed study, the antivirus hits when it detects the malignity of the investigated executable. Malware detection indicates that the antivirus provides a robust service against cyber-intrusions. As larger the blacklist database, better tends to be the defense provided by the antivirus.

In the second possibility, the antivirus attests to the benignity of the investigated file. Therefore, in the proposed study, when the antivirus attests the benignity of the file, it is a case of a false negative – since all the samples are malicious. That is, the investigated executable is a malware; however, the antivirus attests to benignity in the wrong way.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

Table 1 shows the results of the evaluated 80 antivirus products. Six of these antiviruses scored above 98%. These antiviruses were: Cyren, MAX, Ad-Aware, MicroWorld-eScan, BitDefender, Webroot. Malware detection indicates that these antivirus programs provide a robust service against cyber-intrusions.

A major adversity in combating malicious applications is the fact that antivirus makers do not share their malware blacklists due to commercial disputes. Through Table 1 analyse, the proposed work points to an aggravating factor of this adversity: the same antivirus vendor does not even share its databases between its different antivirus programs. Note, for example, that McAfee and McAfee-GW-Edition antiviruses belong to the same company. Their blacklists, though robust, are not shared with each other. Therefore, the commercial strategies of the same company hinder the confrontation with malware. It complements that antivirus vendors are not necessarily concerned with avoiding cyber-invasions, but with optimizing their business income.

Malware detection ranged from 0% to 98.98%, depending on the antivirus being investigated. On average, the 80 antiviruses were able to detect 70.42% of the evaluated virtual threats, with a standard deviation of 28.23%. The high standard deviation indicates that the detection of malicious executables may suffer abrupt variations depending on the antivirus chosen. It is determined that the protection, against cybernetic invasions, is due to the choice of a robust antivirus with a large and updated blacklist.

As for the false negatives, the Zoner antivirus wrongly stated that malware was benign in more than 90% of cases. On average, antiviruses attested false negatives in 17.80% of the cases, with a standard deviation of 19.87%. Tackling the benignity of malware can lead to irrecoverable damage. A person or institution, for example, would rely on a particular malicious application when, in fact, it is malware.

On average, the antiviruses were missing in 11.78% of the cases, with a standard deviation of 15.82%. The omission of the diagnosis points to the limitation of these antiviruses that have limited blacklists for detection of malware in real time.

It is included as adversity, in the combat to malicious applications, the fact of the commercial antiviruses do not possess a pattern in the classification of the malwares as seen in Table 2. We choose 2 of 1,865 malwares samples in order to exemplify the miscellaneous classifications of commercial antiviruses. In this way, the time when manufacturers react to a new virtual plague is affected dramatically. As there is no a pattern, antiviruses give the names that they want, for example, a company can identify a malware as "Malware.1" and a second company identify it as "Malware12310". Therefore, the lack of a pattern, besides the no-sharing of information among the antivirus manufacturers, hinders the fast and effective detection of a malicious application.


###### Table 1 Results of 80 commercial antiviruses:

Antivirus | Deteccion (%) | False Negative (%) | Omission (%)
--------- | ------------- | ------------------ | -------------
Cyren | 98.98% | 0.91% | 0.11%| 
MAX | 98.28%|  1.55%|  0.16%| 
Ad-Aware | 98.28% | 1.72% | 0%| 
MicroWorld-eScan|  98.18%|  1.72%|  0.11%| 
BitDefender|  98.18%|  1.77%|  0.05%| 
Webroot|  98.02%|  1.82%|  0.16%| 
GData|  97.86%|  1.77%|  0.38%| 
DrWeb|  97.8%|  1.98%|  0.21%| 
Emsisoft|  97.69%|  1.93%|  0.38%| 
ESET-NOD32|  97.64%|  2.36%|  0%| 
Panda|  97.37%|  2.63%|  0%| 
AhnLab-V3|  97.37%|  2.57%|  0.05%| 
McAfee| 97.32%| 2.52%| 0.16%|
Sophos| 97.27%| 2.52%| 0.21%|
Microsoft| 97.21%| 2.36%| 0.43%|
Kaspersky| 97.05%| 2.68%| 0.27%|
K7AntiVirus| 97%| 3%| 0%|
K7GW| 96.94%| 3%| 0.05%|
AVG| 96.57%| 2.2%| 1.23%|
NANO-Antivirus| 96.57%| 3.43%| 0%|
Jiangmin| 96.35%| 3.27%| 0.38%|
Fortinet| 96.25%| 3.7%| 0.05%|
Ikarus| 96.19%| 0.27%| 3.54%|
Avira| 95.92%| 4.02%| 0.05%|
Rising| 95.71%| 4.13%| 0.16%|
VBA32| 95.66%| 4.08%| 0.27%|
Tencent| 95.17%| 3.11%| 1.72%|
Zillya| 95.12%| 4.34%| 0.54%|
Cylance| 94.69%| 2.31%| 3%|
Yandex| 94.64%| 4.5%| 0.86%|
Qihoo-360| 94.42%| 5.42%| 0.16%|
ALYac| 93.89%| 1.66%| 4.45%|
ZoneAlarm| 93.46%| 6.43%| 0.11%|
Antiy-AVL| 92.92%| 4.99%| 2.09%|
Arcabit| 92.6%| 7.4%| 0%|
TrendMicro-HouseCall| 91.96%| 8.04%| 0%|
VIPRE| 90.67%| 4.72%| 4.61%|
Avast| 89.54%| 8.58%| 1.88%|
F-Secure| 88.95%| 10.35%| 0.7%|
Comodo| 88.85%| 0.32%| 10.83%|
FireEye| 87.61%| 0.64%| 11.74%|
Lionic| 87.45%| 12.33%| 0.21%|
TotalDefense| 87.18%| 7.35%| 5.47%|
Alibaba| 86.92%| 12.98%| 0.11%|
Sangfor| 86.43%| 1.39%| 12.17%|
Symantec| 86.33%| 1.29%| 12.39%|
CAT-QuickHeal| 82.84%| 9.44%| 7.72%|
F-Prot| 73.89%| 0.75%| 25.36%|
McAfee-GW-Edition| 73.19%| 1.02%| 25.79%|
ViRobot| 72.49%| 27.45%| 0.05%|
APEX| 71.42%| 17.27%| 11.31%|
SUPERAntiSpyware| 69.97%| 30.03%| 0%|
ClamAV| 69.54%| 29.01%| 1.45%|
Invincea| 69.28%| 5.95%| 24.77%|
TrendMicro| 60.54%| 38.93%| 0.54%|
CrowdStrike| 55.82%| 44.08%| 0.11%|
BitDefenderTheta| 51.53%| 36.89%| 11.58%|
Cynet| 50.35%| 0.16%| 49.49%|
Bkav| 49.65%| 49.01%| 1.34%|
Endgame| 49.6%| 24.99%| 25.42%|
Trapmine| 49.54%| 12.65%| 37.8%|
Cybereason| 46.65%| 1.39%| 51.96%|
Acronis| 43.81%| 45.36%| 10.83%|
MaxSecure| 40.27%| 35.66%| 24.08%|
Baidu| 35.44%| 64.4%| 0.16%|
SentinelOne| 35.23%| 64.77%| 0%|
eGambit| 27.18%| 66.38%| 6.43%|
CMC| 25.52%| 74.42%| 0.05%|
Kingsoft| 18.82%| 81.02%| 0.16%|
Elastic| 15.6%| 9.38%| 75.01%|
TACHYON| 14.8%| 84.99%| 0.21%|
Malwarebytes| 14.16%| 85.31%| 0.54%|
Paloalto| 10.03%| 89.92%| 0.05%|
TheHacker| 8.1%| 3.22%| 88.69%|
Gridinsoft| 1.39%| 23.32%| 75.28%|
AVware| 0.16%| 0%| 99.84%|
Avast-Mobile| 0%| 72.82%| 27.18%|
Zoner| 0%| 99.79%| 0.21%|
Babable| 0%| 11.05%| 88.95%|
Trustlook| 0%| 11.15%| 88.85%|

###### Table 2 Miscellaneous classifications of commercial antiviruses:

Antivírus | VirusShare_00137b2f5b7dce9169fe52d112782d79 | VirusShare_004275d4ed08a31db5ec99d99e7e8cb2 
--------- | ------------------------------------------- | ------------------------------------------- 
Bkav | HW32.Packed. | HW32.Packed.
Lionic | Trojan.Win32.Generic.lpZj | Trojan.Win32.Generic.4!c
MicroWorld-eScan | Gen:Variant.Graftor.20936 | Gen:Variant.Graftor.20936
CMC | Rootkit.Win32.Mediyes!O | Rootkit.Win32.Mediyes!O
CAT-QuickHeal | Trojan.Mediyes.B | Trojan.Mediyes.B
Qihoo-360 | HEUR/Malware.QVM00.Gen | Win32/RootKit.Rootkit.bf8
McAfee | GenericRXDQ-DN!00137B2F5B7D | Mediyes.a
Cylance | Unsafe | Unsafe
Zillya | Trojan.Mediyes.Win32.151 | Trojan.Mediyes.Win32.55
Sangfor | Malware | Malware
K7AntiVirus | Trojan ( 0055ec0f1 ) | Trojan ( 0055ec0f1 )
Alibaba | Trojan:Win32/Mediyes.34c6136a | Trojan:Win32/Mediyes.e9340ed0
K7GW | Trojan ( 0055ec0f1 ) | Trojan ( 0055ec0f1 )
Cybereason | malicious.f5b7dc | Omission
Arcabit | Trojan.Graftor.D51C8 | Trojan.Graftor.D51C8
TrendMicro | False Negative | False Negative
Baidu | False Negative | False Negative
F-Prot | W32/Mediyes.B.gen!Eldorado | W32/Mediyes.B.gen!Eldorado
Symantec | Hacktool.Rootkit | Hacktool.Rootkit
TotalDefense | Win32/ArchSMS.BR!genus | Win32/ArchSMS.BR!genus
APEX | Malicious | Malicious
Paloalto | False Negative | False Negative
ClamAV | False Negative | Win.Trojan.Mediyes-897
Kaspersky | HEUR:Trojan.Win32.Generic | HEUR:Trojan.Win32.Generic
BitDefender | Gen:Variant.Graftor.20936 | Gen:Variant.Graftor.20936
NANO-Antivirus | Trojan.Win32.Mediyes.dzqjez | Trojan.Win32.Mediyes.wtfcy
ViRobot | False Negative | False Negative
Rising | Trojan.Mediyes!8.BCB (CLOUD) | rojan.Mediyes!8.BCB (CLOUD
Ad-Aware | Gen:Variant.Graftor.20936 | Gen:Variant.Graftor.20936
Sophos | Mal/Mediyes-B | Mal/Mediyes-B
Comodo | TrojWare.Win32.Mediyes.D@4mwpdu | TrojWare.Win32.Mediyes.D@4mwpdu
F-Secure | Trojan.TR/Rootkit.Gen | Trojan.TR/Rootkit.Gen
DrWeb | Trojan.Mediyes.1 | Trojan.Mediyes.1
VIPRE | Trojan.WinNT.Mediyes.b (v) | Trojan.WinNT.Mediyes.b (v)
Invincea | heuristic | heuristic
McAfee-GW-Edition | GenericRXDQ-DN!00137B2F5B7D | Mediyes.a
Fortinet | W32/Mediyes.D!tr | W32/Mediyes.D!tr
Trapmine | malicious.high.ml.score | malicious.high.ml.score
FireEye | Generic.mg.00137b2f5b7dce91 | Generic.mg.004275d4ed08a31d
Emsisoft | Gen:Variant.Graftor.20936 (B) | Gen:Variant.Graftor.20936 (B)
Ikarus | Rootkit.Win32.Mediyes | Trojan.WinNT.Mediyes
Cyren | W32/Mediyes.B.gen!Eldorado | W32/Mediyes.B.gen!Eldorado
Jiangmin | Rootkit.Mediyes.w | Trojan/Generic.xstr
Webroot | W32.Trojan.Gen | W32.Trojan.Gen
Avira | TR/Rootkit.Gen | TR/Rootkit.Gen
MAX | malware (ai score=100) | malware (ai score=100)
Antiy-AVL | Trojan/Win32.Unknown | Trojan/Win32.Unknown
Kingsoft | False Negative | False Negative
Endgame | malicious (high confidence) | malicious (high confidence)
Microsoft | Trojan:WinNT/Mediyes.B | Trojan:WinNT/Mediyes.B
SUPERAntiSpyware | False Negative | False Negative
ZoneAlarm | HEUR:Trojan.Win32.Generic | HEUR:Trojan.Win32.Generic
Avast-Mobile | False Negative | False Negative
AhnLab-V3 | Trojan/Win32.Rootkit.R22021 | Trojan/Win32.Rootkit.R22021
Acronis | suspicious | suspicious
BitDefenderTheta | False Negative | False Negative
ALYac | Gen:Variant.Graftor.20936 | Gen:Variant.Graftor.20936
TACHYON | False Negative | False Negative
VBA32 | BScope.Trojan.Mediyes | BScope.Trojan.Mediyes
Malwarebytes | False Negative | False Negative
Panda | Generic Malware | Generic Malware
Zoner | False Negative | False Negative
ESET-NOD32 | a variant of Win32/Mediyes.E | a variant of Win32/Mediyes.E
TrendMicro-HouseCall | TROJ_MEDIYES_0000030.TOMA | TROJ_MEDIYES_000000e.TOMA
Tencent | Win32.Trojan.Generic.Jz | Rootkit.Rootkit.Rootkit.Bnm
Yandex | Rootkit.Mediyes.Gen | Trojan.Mediyes!p1wtGNydTdU
SentinelOne | False Negative | False Negative
eGambit | Generic.Malware- | False Negative
GData | Win32.Rootkit.Mediyes.B | Win32.Rootkit.Mediyes.B
AVG | Win32:FakeAlert-CGQ [Trj] | Win32:FakeAlert-CGQ [Trj]
Avast | Win32:FakeAlert-CGQ [Trj] | Win32:FakeAlert-CGQ [Trj]
CrowdStrike | False Negative | win/malicious_confidence_60% (D)
MaxSecure | False Negative | False Negative

## Materials and Methods

This paper proposes a database aiming at the classification of 32-bit benign and malware executables. There are 1,865 malicious executables, and 1,865 other benign executables. Therefore, our dataset is suitable for learning with artificial intelligence, since both classes of executables have the same amount.

Virtual plagues were extracted from databases provided by enthusiastic study groups as VirusShare. As for benign executables, the acquisition came from benign applications repositories such as sourceforge, github and sysinternals. It should be noted that all benign executables were submitted to VirusTotal and all were its benign attested by the main commercial antivirus worldwide. The diagnostics, provided by VirusTotal, corresponding to the benign and malware executables are available in the virtual address of our database.

The purpose of the creation of the database is to give full possibility of the proposed methodology being replicated by third parties in future works. Therefore, the proposed article, by making its database freely available, enables transparency and impartiality to research, as well as demonstrating the veracity of the results achieved. Therefore, it is hoped that the methodology will serve as a basis for the creation of new scientific works.

## Executable Feature Extraction

The extraction of features of executables employs the process of disassembling. Then, the algorithm, referring to the executable, can be studied and later classified by the neural networks described in the next section. In total, 370 features of each executable are extracted, referring to the groups mentioned above. The pescanner tool are employed in order to extract the features of executables. Next, the groups of features extracted from the executables investigated are detailed.
######	Histogram of instructions, in assembly, referring to the mnemonic.
######	Number of subroutines invoking TLS (Transport Layer Security).
######	Number of subroutines responsible for exporting data (exports).  
######	APIs (Application Programming Interface) used by the executable.
######	Features related to clues that the computer has suffered fragmentation on its hard disk, as well as accumulated invalid boot attempts.  
######	Application execution mode. There are two options:
-	software with a graphical interface (GUI);
-	software running on the console.
######	Features related to the Operating System. Our digital forensics examines if the tested file tries to:
-	identify the current operating system user name;
-	access APIs in order to create and manage current OS user profiles;
-	detect the number of milliseconds since the system was initialized;
-	execute an operation in a specific file;
-	identify the version of the Windows Operating System in use;
-	monitor internal message traffic among system processes;
-	alter the Windows startup settings and contents (STARTUPINFO);  
-	allow applications to access functionality provided by shell of the operating system, as well as alter it; 
-	change the logon messages at Windows OS startup; 
-	change native applications linked to standard dialog boxes in order to open and save files, choosing color and font, among other customizations;
-	configure Windows Server licensing ; 
-	configure Windows Server 2003;
-	change the system's power settings;
-	open a process, service, or native library of the Operating System; 
-	exclude the context of certificates linked to the Operating System; 
-	copy an existing file to a new file; 
-	create, open, delete, or alter a file;
-	create and execute new process(s); 
-	create new directory(s); 
-	search for specific file(s);  
-	create a service object and add it to the control manager database for a certain service; 
-	encrypt data. It is a typical strategy of ransomwares which sequester the victim's data through cryptography. To decrypt the data, the invader asks the user for a monetary amount so that he victim can have all his data back;
-	access file systems, devices, processes, threads and error handling of the system;
-	change the sound and audio device properties of the system;
-	access graphical content information for monitors, printers, and other Windows OS output devices; 
-	use and/or monitor the USB port;
-	control a driver of a particular device; 
-	investigate if a disk drive is a removable, fixed, CD / DVD-ROM, RAM or network drive;
######	Features related to Windows Registry (Regedit). It is worth noting that the victim may not be free from malware infection even after its detection and elimination. The persistence of malefactions, even after malware exclusion, occurs due to the insertion of malicious entries (keys) in Regedit. Then, when the operating system boots, the cyber-attack restarts because of the malicious key invoking the vulnerability exploited by malware (eg: redirect Internet Explorer home page). Then, our antivirus audits if the suspicious application tries to:
-	detect the NetBIOS name of the local computer. This name is established at system startup, when the system reads it in the registry (Regedit);
-	terminate a key of a specific registry; 
-	create a key from in a specific registry. If the key already exists in Regedit, then it will be read; 
-	delete a key and its values in Regedit; 
-	enumerate and   open subkeys of a specific open registry. 
######	Features related to spywares such as keyloggers (capture of keyboard information in order to theft of passwords and logins) and screenloggers (screen shot of the victim). Our antivirus audits if the analyzed file tries to:
-	detect in which part of the victim's screen there was an update;
-	identify the screen update region by copying it to a particular region;
-	capture AVI movies and videos from web cameras and other video hardware; 
-	capture information on electronic voting, specifically from the company Optical Vote-Trakker;
-	copy an array of keyboard key states. Such strategy is typical of keyloggers
-	monitor user's Internet activity and private information;
-	collect online bank passwords and other confidential information and to send the data to invader creator;
-	access a computer from remote locations, stealing passwords, Internet banking and personal data; 
-	create a BHO (Browser Helper Object) which is executed automatically every time when the web browser is started. It fits to emphasize that BHOs are not impeded by personal firewalls because they are identified as part of the browser. In a distorted way, BHOs are often used by adware and spyware in order to record keyboard and mouse entries
-	locate passwords stored on a computer.
######	Features related to Anti-forensic Digital which are techniques of removal, occultation and subversion of evidences with the goal of reducing the consequences of the results of forensic analyzes. Our antivirus investigates if the file tries to:
-	Suspend its own execution until a certain timeout interval has elapsed. A typical malware strategy that maintains itself inactive until the end of commercial antivirus quarantine;
-	Disable the victim's defense mechanisms, including Firewall and Antivirus;
-	disable automatic Windows updates;
-	detect if the own file is being scanned by an debugger of the Operating System;   
-	retrieve information about the first and next process found in an Operating System snapshot. Such strategy is typical of malwares that aim to corrupt backups and restore points of the Operating System;
-	hide one file in another. This strategy is named, technically, steganography which aims to hide malware in a benign program in the Task Manager;
-	disguise its own name in the Task Manager;
-	make use of libraries associated with Hackers Encyclopedia 2002;
-	Create a ZeroAcess cyber-attack type through firmware updates of hardware devices (eg, hard drive controlled).
######	Features related to the creation of GUI (Graphical User Interface) of the suspicious program. Our antivirus audits if the suspect file tries to: 
-	create a GUI at runtime; 
-	use DirectX which allows multimedia applications to draw 2D graphics; 
-	create a module that contains bitmap compression and decompression routines used for Microsoft Video for Windows;
-	create 3D graphics related to utilitarian functions used by OpenGL; 
-	detect shapes through computer vision and digital image processing;
-	access functionalities in order to create and to manage screen windows and more basic controls such as buttons and scrollbars, receive mouse and keyboard input, and other functionalities associated with the Windows GUI. This includes widgets like status bars, progress bars, toolbars, and guides; 
######	Features related to the illicit forensic of the RAM (main memory) of the local system. Our antivirus investigates if the suspicious application tries to:
-	access information in specific regions of main memory;
-	read data from an area of memory occupied by a specific process;
-	write data to a memory area in a specific process;
-	reserve, confirm or alter the status of a page region in the virtual address space of a process.
######	Features related to network traffic. It is checked if the suspect file tries to:
-	query DNS servers;
-	send request to an HTTP server; 
-	monitor information of the headers of computer data packets associated with an HTTP request;
-	send an ICMP IPv4 echo request; 
-	send an SNMP request used to monitor LAN equipment;
-	terminate the Internet connection;
-	create an FTP or HTTP session at runtime; 
-	fragment a URL at runtime; 
-	query a server in order to determine the amount of traffic data available; 
-	identify the connection state of the local system in relation to the Internet; 
-	initialize the use of an application of the WinINet functions (Windows API for creating and using the application using the Internet); 
-	read data from network packets made from previous local system requests (typical behavior of sniffers); 
-	overwrite data in a local system network packet; 
-	manage local and remote network systems; 
-	create a network socket on the local system. In a conventional application, the server sends data to the client (s). In an opposite way, in malware, the victim sends the data (images, digits) to the server. Therefore, malware can create sockets on the local system waiting (listen) for a remote malicious computer to request a connection and, then, receive the victim's private information;
-	receive data of a socket. Typical strategy of backdoors when the victim starts receiving remote commands; 
-	send data to a socket. Typical strategies of spywares which, after capturing innermost information, they send them to a malicious remote computer; 
######	Features related to utility applications programs. Our created antivirus checks if the suspicious file tries to:
-	reproduce videos/audios through Windows Media Player; 
-	change the shortcut icon and Internet default settings exhibited in the Explorer toolbar address bar; 
-	alter the Wordpad configurations;
-	alter the configurations of sockets, specifically, managed by Internet Explorer; 
-	alter Outlook Express configurations and to access the victim’s  e-mail list; 
-	access information linked to the Microsof Office; 
-	alter the configurations of the Adobe System’s suite;
-	change the system's disk cleanup configurations; 
-	alter the settings of native digital electronic games and others linked to companies Tycoon and Electronic Arts;
-	change Google Inc updates settings; 
-	use Visual Basic. Such strategy is typical of macro viruses that are intended to infect applications that support macro language such as web browsers, Microsoft Office, and Adobe Systems.
-	alter the access settings to Wikipedia.
