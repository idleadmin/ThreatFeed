# ThreatFeed

**Curated Threat Intelligence Feeds for Firewall Enforcement**

## Overview

**ThreatFeed** provides consolidated, ready-to-use blocklists designed for **firewalls, routers, and network security platforms**. These feeds contain known malicious or suspicious IP addresses sourced from reputable threat intelligence providers.

---

## Feeds

| Feed | Direction | Description |
|------|----------|------------|
| **FireHOL Level 1** | IN | General-purpose blocklist of aggressive IPs involved in attacks, scans, and suspicious behavior |
| **GreenSnow IP Blocklist** | IN | Blacklist of IPs involved in brute-force, scanning, and infrastructure attacks |
| **IPSum Level 3** | IN | Strict blocklist of high-risk IPs for aggressive filtering |
| **Spamhaus** | IN / OUT | Reputation-based blocklist of spam, malware, and botnet-related IPs |
| **Blocklist.de** | IN | IPs flagged for SSH, FTP, and web-based attacks from honeypots |
| **CINSscore** | IN | Reputation-based list of IPs involved in scanning and exploitation |
| **DShield** | IN / OUT | Community-driven feed of scanning and exploit attempt sources |
| **Emerging Threats** | IN / OUT | Compromised hosts and botnet infrastructure |
| **ThreatFox** | IN / OUT | IPs linked to malware campaigns and ransomware activity |
| **Tor Exit Nodes** | IN | Public Tor exit nodes used for anonymized traffic |
| **Unified Blocklist** | IN | Consolidated list combining multiple feeds above |

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
