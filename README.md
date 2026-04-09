# ThreatFeed

**Curated Threat Intelligence Feeds for Firewall Enforcement**

## Overview

**ThreatFeed** provides consolidated, ready-to-use blocklists designed for **firewalls, routers, and network security platforms**. These feeds contain known malicious or suspicious IP addresses sourced from reputable threat intelligence providers.

---

## Feeds

| Feed | Direction | Description | Read More |
|------|----------|------------|-----------|
| [**FireHOL Level 1**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/fireholl1.list) | IN | General-purpose blocklist of aggressive IPs involved in attacks, scans, and suspicious behavior | [Link](https://iplists.firehol.org/?ipset=firehol_level1) |
| [**GreenSnow IP Blocklist**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/greensnow.list) | IN | Blacklist of IPs involved in brute-force, scanning, and infrastructure attacks | [Link](https://greensnow.co/) |
| [**IPSum Level 3**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/ipsuml3.list) | IN | Strict blocklist of high-risk IPs for aggressive filtering | [Link](https://github.com/stamparm/ipsum) |
| [**Spamhaus**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/spamhaus.list) | IN / OUT | Reputation-based blocklist of spam, malware, and botnet-related IPs | [Link](https://www.spamhaus.org/) |
| [**Blocklist.de**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/blocklistde-all.list) | IN | IPs flagged for SSH, FTP, and web-based attacks from honeypots | [Link](https://www.blocklist.de/en/index.html) |
| [**Binary Defense**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/binarydefense.list) | IN | Honeypot-derived list of malicious IPs observed in real-world attacks | [Link](https://binarydefense.com/) |
| [**CINSscore**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/cinsscore.list) | IN | Reputation-based list of IPs involved in scanning and exploitation | [Link](https://cinsscore.com/) |
| [**DShield**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/dshield.list) | IN / OUT | Community-driven feed of scanning and exploit attempt sources | [Link](https://www.dshield.org/) |
| [**Emerging Threats**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/etknownlist.list) | IN / OUT | Compromised hosts and botnet infrastructure | [Link](https://community.emergingthreats.net/) |
| [**ThreatFox**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/threatfox.list) | IN / OUT | IPs linked to malware campaigns and ransomware activity | [Link](https://threatfox.abuse.ch/) |
| [**BruteForceBlocker**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/bruteforcelist.list) | IN | IPs reported for repeated failed authentication attempts (SSH brute-force activity) | [Link](https://danger.rulez.sk) |
| [**Tor Exit Nodes**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/tor-exit-nodes.list) | IN | Public Tor exit nodes used for anonymized traffic | N/A |
| [**Unified Blocklist**](https://raw.githubusercontent.com/idleadmin/ThreatFeed/refs/heads/main/unifiedblocklist.list) | IN | Consolidated list combining multiple feeds above | N/A |

---

## Usage

- Import lists directly into **firewall address groups / external threat feeds**
- Apply to **deny policies** for inbound (and outbound where applicable)
- Configure **scheduled updates** via firewall or automation

---

## Best Practices

- Start with **monitoring/logging before blocking**
- Be cautious with **OUT rules** to avoid business disruption
- Use **Unified Blocklist carefully**
- Whitelist **critical IPs/services**
- Always test in **lab/staging** before production

---

## Disclaimer

⚠️ **Use at your own risk**

- These feeds are **community-sourced and aggregated**
- No guarantee of **accuracy, completeness, or timeliness**
- May include **false positives**
- Improper use may cause **service disruption**

You are fully responsible for validating and applying these feeds in your environment.

---

## License

No explicit license provided. Verify usage rights from original sources if required.

---

⭐ **If you find this useful, consider giving the repo a star!**

---
