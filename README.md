# awesome-blocklists
A list of IP Blocklists and known malicious ip lists.
WIP, if you want to add any more just make a PR, not sure how much I'll maintain this at the moment

## Table of contents
- Crowdsec
- Blocklists
- Misc Lists (Internet Scanner Ranges, etc)

## Crowdsec
[Crowdsec](https://crowdsec.net) offers 4 (including default community list) free blocklists if you enroll a machine as a security engine and give it a bouncer.
I made a script to import some of the blocklists from below into crowdsec, you can check it out [here](https://codeberg.org/Itsyourdriver/crowdsec-blocklist-import-manual)

## Lists (In no particular order)
- [firehol](https://iplists.firehol.org/) - [Homepage](https://firehol.org/) - `I heavily recommend picking the list that you feel works best. Different lists have different confidence levels.`
- [abuseipdb](https://www.abuseipdb.com/) - Requires account + API token.
- [ipthreat](https://ipthreat.net/lists) - Requires account
- [CINSscore](https://cinsscore.com/list/ci-badguys.txt) - [Homepage](https://cinsscore.com/#list)
- [Greensnow](https://blocklist.greensnow.co/greensnow.txt) - [Homepage](https://www.greensnow.co/)
- [blocklist.de](https://lists.blocklist.de/lists/all.txt) - [Homepage](https://www.blocklist.de/en/index.html) - [List of lists](https://www.blocklist.de/en/export.html)
- [rtbh.com.tr](https://list.rtbh.com.tr/output.txt) - [Homepage](https://list.rtbh.com.tr/)

## Misc Lists
- [internet-measurement](https://internet-measurement.com/#ips) - Shows their IPRanges in a list for you to block, some lists above may come with some of these IPs loaded.
- [2023 Aggregated list of Shodan IPs](https://www.ipfire.org/docs/configuration/firewall/blockshodan) - A list from 2023 (double check with something like abuseipdb) of shodan.io's ips (Shodan is an internet "search engine" which scans ports & hosts)
- [Uptimerobot](https://uptimerobot.com/help/locations/) - Uptimerobot is an uptime monitoring service. If you use them to check for downtime, do NOT block their IP ranges!
- [ipranges](https://github.com/lord-alfred/ipranges) - Lists IPRanges for large cloud providers or other services such as Google, ChatGPT/OpenAI, Facebook (Meta), Amazon AWS, and more.
