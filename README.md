# Mediyes
Retrieval for Mediyes Malware Analysis

## Commercial Antivirus Limitation

Technically, the modus operandi for the identification of malicious files and servers refers to consult in named blacklist databases. The VirusTotal platform issues the diagnoses regarding malignant characteristics related to files and web servers.

When it comes to suspicious files, VirusTotal issues the diagnostics provided by the world's leading commercial antivirus products. Regarding suspicious web servers, VirusTotal uses the database responsible for sensing virtual addresses with malicious practices.

VirusTotal has Application Programming Interface (APIs) that allow programmers to query the platform in an automated way and without the use of the graphical web interface. The proposed paper employs two of the APIs made available by VirusTotal. The first one is responsible for sending the investigated files to the platform server. The second API, in turn, makes commercial antivirus diagnostics available for files submitted to the platform by the first API.

Initially, the executable malwares are sent to the server belonging to the VirusTotal platform. After that, the executables are analyzed by the 80 commercial antiviruses linked to VirusTotal. Therefore, the antivirus provides its diagnostics for the executables submitted to the platform. VirusTotal allows the possibility of issuing three different types of diagnostics: malware, benign and omission.

Then, through the VirusTotal platform, the proposed paper investigates 80 commercial antiviruses with their respective results presented in Table 1. We used 1865 malicious executables for 32-bit architecture. The goal of the work is to check the number of virtual pests cataloged by antivirus. The motivation is that the acquisition of new virtual plagues plays an important role in combating malicious applications. Therefore, the larger the database of malwares blacklisted, the better it tends to be the defense provided by the antivirus.

As for the first possibility of VirusTotal, the antivirus detects the malignity of the suspicious file. In the proposed experimental environment, all submitted executables are public domain malwares. Therefore, in the proposed study, the antivirus hits when it detects the malignity of the investigated executable. Malware detection indicates that the antivirus provides a robust service against cyber-intrusions. As larger the blacklist database, better tends to be the defense provided by the antivirus.

In the second possibility, the antivirus attests to the benignity of the investigated file. Therefore, in the proposed study, when the antivirus attests the benignity of the file, it is a case of a false negative – since all the samples are malicious. That is, the investigated executable is a malware; however, the antivirus attests to benignity in the wrong way.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

Table 1 shows the results of the evaluated 80 antivirus products. Six of these antiviruses scored above 98%. These antiviruses were: Cyren, MAX, Ad-Aware, MicroWorld-eScan, BitDefender, Webroot. Malware detection indicates that these antivirus programs provide a robust service against cyber-intrusions.

A major adversity in combating malicious applications is the fact that antivirus makers do not share their malware blacklists due to commercial disputes. Through Table 1 analyse, the proposed work points to an aggravating factor of this adversity: the same antivirus vendor does not even share its databases between its different antivirus programs. Note, for example, that K7AntiVirus and K7GW antiviruses belong to the same company. Their blacklists, though robust, are not shared with each other. Therefore, the commercial strategies of the same company hinder the confrontation with malware. It complements that antivirus vendors are not necessarily concerned with avoiding cyber-invasions, but with optimizing their business income.

Malware detection ranged from 0% to 99.11%, depending on the antivirus being investigated. On average, the 86 antiviruses were able to detect 54.84% of the evaluated virtual pests, with a standard deviation of 39,67. The high standard deviation indicates that the detection of malicious executables may suffer abrupt variations depending on the antivirus chosen. It is determined that the protection, against cybernetic invasions, is due to the choice of a robust antivirus with a large and updated blacklist.

As for the false negatives, the Zoner, Malwarebytes and SUPERAntiSpyware antiviruses, wrongly stated that malware was benign in more than 90% of cases. On average, antiviruses attested false negatives in 14.34% of the cases, with a standard deviation of 21.67. Tackling the benignity of malware can lead to irrecoverable damage. A person or institution, for example, would rely on a particular malicious application when, in fact, it is malware.

VirusBuster, NOD32, eSafe, eTrust-Vet, Authentium, Prevx, Sunbelt, PCTools, a-squared, WhiteArmor, Command, SAVMail, FileAdvisor,Ewido and Webwasher-Gateway antivirus companies have not omitted opinion on any of the 3136 samples malicious. Therefore, about 17% of antivirus softwares were not able to diagnose any of the malicious samples. On average, the antiviruses were missing in 30.82% of the cases, with a standard deviation of 40.97. The omission of the diagnosis points to the limitation of these antiviruses that have limited blacklists for detection of malware in real time.

It is included as adversity, in the combat to malicious applications, the fact of the commercial antiviruses do not possess a pattern in the classification of the malwares as seen in Table 3. We choose 3 of 3136 REWEMA malwares samples in order to exemplify the miscellaneous classifications of commercial antiviruses. The chosen malware are Backdoor.IRC.Darkirc.exe, Backdoor.Win32.Zomby.exe e Constructor.VBS.Alamar.20.exe. In this way, the time when manufacturers react to a new virtual plague is affected dramatically. As there is no a pattern, antiviruses give the names that they want, for example, a company can identify a malware as "Malware.1" and a second company identify it as "Malware12310". Therefore, the lack of a pattern, besides the no-sharing of information among the antivirus manufacturers, hinders the fast and effective detection of a malicious application.


###### Table 2 Results of 80 commercial antiviruses:

Antivirus | Deteccion (%) | False Negative (%) | Omission (%)
--------- | ------------- | ------------------ | -------------
Cyren | 98.98 | 0.91 | 0.11| 
MAX | 98.28|  1.55|  0.16| 
Ad-Aware | 98.28 | 1.72 | 0| 
MicroWorld-eScan|  98.18|  1.72|  0.11| 
BitDefender|  98.18|  1.77|  0.05| 
Webroot|  98.02|  1.82|  0.16| 
GData|  97.86|  1.77|  0.38| 
DrWeb|  97.8|  1.98|  0.21| 
Emsisoft|  97.69|  1.93|  0.38| 
ESET-NOD32|  97.64|  2.36|  0| 
Panda|  97.37|  2.63|  0| 
AhnLab-V3|  97.37|  2.57|  0.05| 
McAfee| 97.32| 2.52| 0.16|
Sophos| 97.27| 2.52| 0.21|
Microsoft| 97.21| 2.36| 0.43|
Kaspersky| 97.05| 2.68| 0.27|
K7AntiVirus| 97| 3| 0|
K7GW| 96.94| 3| 0.05|
AVG| 96.57| 2.2| 1.23|
NANO-Antivirus| 96.57| 3.43| 0|
Jiangmin| 96.35| 3.27| 0.38|
Fortinet| 96.25| 3.7| 0.05|
Ikarus| 96.19| 0.27| 3.54|
Avira| 95.92| 4.02| 0.05|
Rising| 95.71| 4.13| 0.16|
VBA32| 95.66| 4.08| 0.27|
Tencent| 95.17| 3.11| 1.72|
Zillya| 95.12| 4.34| 0.54|
Cylance| 94.69| 2.31| 3|
Yandex| 94.64| 4.5| 0.86|
Qihoo-360| 94.42| 5.42| 0.16|
ALYac| 93.89| 1.66| 4.45|
ZoneAlarm| 93.46| 6.43| 0.11|
Antiy-AVL| 92.92| 4.99| 2.09|
Arcabit| 92.6| 7.4| 0|
TrendMicro-HouseCall| 91.96| 8.04| 0|
VIPRE| 90.67| 4.72| 4.61|
Avast| 89.54| 8.58| 1.88|
F-Secure| 88.95| 10.35| 0.7|
Comodo| 88.85| 0.32| 10.83|
FireEye| 87.61| 0.64| 11.74|
Lionic| 87.45| 12.33| 0.21|
TotalDefense| 87.18| 7.35| 5.47|
Alibaba| 86.92| 12.98| 0.11|
Sangfor| 86.43| 1.39| 12.17|
Symantec| 86.33| 1.29| 12.39|
CAT-QuickHeal| 82.84| 9.44| 7.72|
F-Prot| 73.89| 0.75| 25.36|
McAfee-GW-Edition| 73.19| 1.02| 25.79|
ViRobot| 72.49| 27.45| 0.05|
APEX| 71.42| 17.27| 11.31|
SUPERAntiSpyware| 69.97| 30.03| 0|
ClamAV| 69.54| 29.01| 1.45|
Invincea| 69.28| 5.95| 24.77|
TrendMicro| 60.54| 38.93| 0.54|
CrowdStrike| 55.82| 44.08| 0.11|
BitDefenderTheta| 51.53| 36.89| 11.58|
Cynet| 50.35| 0.16| 49.49|
Bkav| 49.65| 49.01| 1.34|
Endgame| 49.6| 24.99| 25.42|
Trapmine| 49.54| 12.65| 37.8|
Cybereason| 46.65| 1.39| 51.96|
Acronis| 43.81| 45.36| 10.83|
MaxSecure| 40.27| 35.66| 24.08|
Baidu| 35.44| 64.4| 0.16|
SentinelOne| 35.23| 64.77| 0|
eGambit| 27.18| 66.38| 6.43|
CMC| 25.52| 74.42| 0.05|
Kingsoft| 18.82| 81.02| 0.16|
Elastic| 15.6| 9.38| 75.01|
TACHYON| 14.8| 84.99| 0.21|
Malwarebytes| 14.16| 85.31| 0.54|
Paloalto| 10.03| 89.92| 0.05|
TheHacker| 8.1| 3.22| 88.69|
Gridinsoft| 1.39| 23.32| 75.28|
AVware| 0.16| 0| 99.84|
Avast-Mobile| 0| 72.82| 27.18|
Zoner| 0| 99.79| 0.21|
Babable| 0 11.05| 88.95|
Trustlook| 0| 11.15| 88.85|

###### Table 3 Miscellaneous classifications of commercial antiviruses:

Antivírus | VirusShare_001627d61a1bde3478ca4965e738dc1e | VirusShare_075efef8c9ca2f675be296d5f56406fa | VirusShare_0dab86f850fd3dafc98d0f2b401377d5
--------- | ------------------------------------------- | ------------------------------------------- | --------------------------------------------


## Materials and Methods

This paper proposes a database aiming at the classification of 32-bit benign and malware executables. The database is referred to as REWEMA (Retrieval of 32-bit Windows Architecture Executables Applied to Malware Analysis). There are 3136 malicious executables, and 3136 other benign executables. Therefore, the REWEMA base is suitable for learning with artificial intelligence, since both classes of executables have the same amount.

As for malicious executables, REWEMA is the junction of several malware databases. Virtual plagues were extracted from databases provided by enthusiastic study groups such as Vxheaven and TheZoo. As for benign executables, the acquisition came from benign applications repositories such as sourceforge, github and sysinternals. It should be noted that all benign executables were submitted to VirusTotal and all were its benign attested by the main commercial antivirus worldwide. The diagnostics, provided by VirusTotal, corresponding to the benign and malware executables are available in the virtual address of the REWEMA database.

The purpose of the creation of the REWEMA database is to give full possibility of the proposed methodology being replicated by third parties in future works. Therefore, the proposed article, by making its database freely available, enables transparency and impartiality to research, as well as demonstrating the veracity of the results achieved. Therefore, it is hoped that the methodology, to be reported in chapter 6, will serve as a basis for the creation of new scientific works.
