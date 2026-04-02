# ThreatFeed

Curated Threat Intelligence Feeds for Network Security

# Overview
ThreatFeed is a collection of community‑curated threat intelligence lists, providing indicators of malicious activity including IP addresses, domains, and network ranges. These feeds are intended to be ingested into firewalls, routers, or network security platforms to block or monitor potential threats.

⚠️ Disclaimer: Use these feeds at your own risk. The repository provides raw threat intelligence with no guarantees of accuracy, completeness, or timeliness. Always validate feeds before applying to production environments.

# Contents

The repository contains various feeds, including but not limited to:

CINSscore.list — suspicious IPs and ASNs by CINSscore
IPSumL3.list — Level 3 ISP aggregated threat IPs
blocklistde‑all.list — Blocklist.de compiled malicious IPs
bruteforcelist.list — Known brute-force source IPs
dshield.list — DShield aggregated attack sources
etknownlist.list — EmergingThreats known bad IPs
firehol.list — FireHOL curated blocklist
greensnow.list — high-confidence malicious IPs
spamhaus.list — Spamhaus DROP & EDROP IPs
tor-exit-nodes.list — TOR exit node IPs
threatfox.list — Abuse.ch threat indicators

Each list is plain text, with one indicator per line, ready to be imported into firewall or security appliances.

# Usage
Firewall Integration: Import lists directly into your firewall, router, or UTM device to block known malicious IPs or domains.
Periodic Updates: Regularly update feeds to maintain coverage against new threats.
Monitoring: Use feeds for network monitoring and alerting, in addition to blocking.

# Best Practices
Test in a lab environment first to assess potential impact on network traffic.
Deduplicate feeds if combining multiple lists.
Automate updates cautiously to avoid downtime or accidental blocks.
Validate indicators before applying to critical systems.

# License
No explicit license is provided. Feeds are community-sourced. Ensure compliance with your organization’s policies before use in production.
