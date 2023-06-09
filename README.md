# Detecting human operated ransomware attacks and Hunt Them Down
This is the note for reminding myself about advanced in security networked attacks, _Human-operated ransomware_, which is coordinated and a planned attack by network enemy, not network academy. They employ multiple attack methods such as [1].

#### Initial access:

•	RDP brute force

•	Vulnerable internet-facing system

•	Weak application settings

•	Phishing email

#### Credential theft:
•	Mimikatz

•	LSA secrets

•	Credential vault

•	Credentials in plaintext

•	Abuse of service accounts

#### Lateral movement:

•	Cobalt Strike

•	WMI

•	Abuse of management tools

•	PsExec

#### Persistence:

•	New accounts

•	GPO changes

•	Shadow IT tools

•	Schedule tasks

•	Service registration

#### Defense evasion:

•	Disabling security features

•	Clearing log files

•	Deleting attack artifact files

•	Resetting timestamps on altered files

#### Exfiltration:

•	Exfiltration of sensitive data Impact (financial leverage):

•	Encryption of data in place and in backups

•	Deletion of data in place and backups, which might be combined with a preceding exfiltration

•	Threat of public leakage of exfiltrated, sensitive data

If we don’t have __Proactive detection__ as mention in early stage , it will destroy your organization  assets, data and operations.
https://learn.microsoft.com/en-us/microsoft-365/media/defender/playbook-detecting-ransomware-m365-defender-qualitative-diagram.png?view=o365-worldwide

## What have we must learn and looking for?

Like nature as human, every attack has __Signal source__ which categorized as 

1.	Initial attacks to gain entry

2.	Spike in otherwise typical behavior

3.	New entities are added

4.	Suspicious behavior 

## Migration security tools?

1.	Incident and Alert system for 	

 a.	Filtering ransomware-identified incident
 
 b.	Filtering ransomware-identified threat analytics reports
 
2.	Query-based threat hunting tool lets us explore and inspect events in your network to locate threat indicators and entities

3.	AI can use query-based hunting  to create customize rules and actions.

## Team work
 Thirty winters of network enemy is almost the same, if we lacked behind them one step, we were the looser. Network system is system of networks that needs skilled networking, system administration, application and network policy team to acting like Silicon Velley Bank solved by three pillars of finacial officers in US on Sunday afternoon since Wednesday bank announcement. They need collective monitor, active and aggressive executor team who are like them in the opposite goals. Lastly, last resource, several copies of offline backups in secured place.
 
## Now what?
If your team can access to some _proactive scanning_ and _alert system_ for ransomware collaborative hunting global team such as Microsoft 365 defender portal and Future US LLC [2]. 
Hopping that we will see Incident alert sources, advanced hunting tools _enabled_ for network community. Finally, *Hunting Them Down* is our challenge. So let "proactively searching through logs, endpoints, __NetFlow traffic__, DNS data, and any other security source for __malicious activity on the network that may not be detected by existing security tools__. Threat hunting is the first step in a process. It has to be integrated into the regular security workflow"[2].

References:
1.	Microsoft , ‘Detecting human-operated ransomware attacks with Microsoft 365 Defender ‘, March 14, 2023, https://learn.microsoft.com/en-us/microsoft-365/security/defender/playbook-detecting-ransomware-m365-defender?view=o365-worldwide, accessed time March 18, 2023.
2. Future US LLC, 'Threat Hunting For Ransomware', https://ransomware.org/how-to-prevent-ransomware/threat-hunting/threat-hunting-for-ransomware/,  accessed time March 18, 2023.
