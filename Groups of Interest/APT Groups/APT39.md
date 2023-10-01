[Source](https://www.mandiant.com/resources/insights/apt-groups)

Suspected attribution: Iran

Target sectors: While APT39's targeting scope is global, its activities are concentrated in the Middle East. APT39 has prioritized the telecommunications sector, with additional targeting of the travel industry and IT firms that support it and the high-tech industry.

Overview: The group's focus on the telecommunications and travel industries suggests intent to perform monitoring, tracking, or surveillance operations against specific individuals, collect proprietary or customer data for commercial or operational purposes that serve strategic requirements related to national priorities, or create additional accesses and vectors to facilitate future campaigns. Government entities targeting suggests a potential secondary intent to collect geopolitical data that may benefit nation-state decision making.

Associated malware: The group primarily leverages the SEAWEED and CACHEMONEY backdoors along with a specific variant of the POWBAT backdoor.

Attack vectors: For initial compromise Mandiant Intelligence has observed APT39 leverage spearphishing with malicious attachments and/or hyperlinks typically resulting in a POWBAT infection. In some cases previously compromised email accounts have also been leveraged, likely to abuse inherent trusts and increase the chances of a successful attack. APT39 frequently registers and leverages domains that masquerade as legitimate web services and organizations that are relevant to the intended target. Furthermore, this group has routinely identified and exploited vulnerable web servers of targeted organizations to install web shells, such as ANTAK and ASPXSPY, and used stolen legitimate credentials to compromise externally facing Outlook Web Access (OWA) resources. We have not observed APT39 exploit vulnerabilities.

[additional information](https://www.mandiant.com/resources/blog/apt39-iranian-cyber-espionage-group-focused-on-personal-information)