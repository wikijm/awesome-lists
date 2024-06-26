# Security lists for SOC detections 

## Threat Hunting:
- [ThreatHunting keywords Site](https://mthcht.github.io/ThreatHunting-Keywords/)
- [ThreatHunting keywords Lists](https://github.com/mthcht/ThreatHunting-Keywords)
- [ThreatHunting Yara rules](https://github.com/mthcht/ThreatHunting-Keywords-yara-rules)

[ThreatHunting searches](https://github.com/mthcht/Purpleteam/tree/main/Detection/Threat%20Hunting/generic)
<details>
  
  - [Windows Services Searches](https://detect.fyi/threat-hunting-suspicious-windows-service-names-2f0dceea204c)
  - [User-Agents Searches](https://mthcht.medium.com/threat-hunting-suspicious-user-agents-3dd764470bd0)
  - [DNS Over HTTPS Searches](https://mthcht.medium.com/detecting-dns-over-https-30fddb55ac78)
  - [Suspicious TLDs Searches](https://mthcht.medium.com/threat-hunting-suspicious-tlds-a742c2adbf58)
  - [HijackLibs Searches](https://mthcht.medium.com/detect-dll-hijacking-techniques-from-hijacklibs-with-splunk-c760d2e0656f)
  - [Phishing & DNSTWIST Searches](https://detect.fyi/detecting-phishing-attempts-with-dnstwist-37c426b3bbb8)
  - [Browsers extensions Searches](https://mthcht.medium.com/detecting-browser-extensions-installations-e0ac2b45c46b)
  - [C2 hiding in plain sigh](https://mthcht.medium.com/c2-hiding-in-plain-sight-7a83963b9344)
  - [HTML Smuggling artifacts](https://mthcht.medium.com/detecting-html-smuggling-phishing-attempts-15af824e60e4)
  - [PSEXEC & similar tools Searches](https://mthcht.medium.com/detecting-psexec-and-similar-tools-c812bf3dca6c)
  - [Time Slipping detection](https://mthcht.medium.com/event-log-manipulations-1-time-slipping-55bf95631c40)
</details>

## Detection Lists 
- 📋 Lists: https://github.com/mthcht/awesome-lists/tree/main/Lists
- 🕵️‍♂️ ThreatHunting Guides: https://mthcht.medium.com/list/threat-hunting-708624e9266f
- 📚 Hijacklibs: https://github.com/mthcht/awesome-lists/tree/main/Hijacklibs
- 🚰 Suspicious Named pipes: https://github.com/mthcht/awesome-lists/blob/main/Lists/suspicious_named_pipe_list.csv
- 🔧 Suspicious Windows Services: https://github.com/mthcht/awesome-lists/blob/main/Lists/suspicious_windows_services_names_list.csv
- ⏲️ Suspicious Windows Tasks: https://github.com/mthcht/awesome-lists/blob/main/Lists/suspicious_windows_tasks_list.csv
- 🚪 Suspicious destination port: https://github.com/mthcht/awesome-lists/blob/main/Lists/suspicious_ports_list.csv
- 🛡️ Suspicious Firewall rules: https://github.com/mthcht/awesome-lists/blob/main/Lists/suspicious_windows_firewall_rules_list.csv
- 🆔 Suspicious User-agent: https://github.com/mthcht/awesome-lists/blob/main/Lists/suspicious_http_user_agents_list.csv
- 📇 Suspicious USB Ids: https://github.com/mthcht/awesome-lists/blob/main/Lists/suspicious_usb_ids_list.csv
- 🔢 Suspicious MAC address: https://github.com/mthcht/awesome-lists/blob/main/Lists/suspicious_mac_address_list.csv
- 📛 Suspicious Hostname: https://github.com/mthcht/awesome-lists/blob/main/Lists/suspicious_hostnames_list.csv
- 🧮 Metadata Executables: https://github.com/mthcht/awesome-lists/blob/main/Lists/executables_metadata_informations_list.csv
- 🕸️ DNS over HTTPS server list: https://github.com/mthcht/awesome-lists/blob/main/Lists/dns_over_https_servers_list.csv
- 🌐 TOR Nodes List: https://github.com/mthcht/awesome-lists/tree/main/Lists/TOR
- 🛠️ LOLDriver List: https://github.com/mthcht/awesome-lists/blob/main/Lists/loldrivers_list.csv

## SIEM/SOC related:
- [EDR Telemetry](https://github.com/tsale/EDR-Telemetry)
- [PurpleTeam Scripts](https://github.com/mthcht/Purpleteam)

##  Investigation

### TI

<details>
  
  - [Virustotal](https://www.virustotal.com/#/home/search)
  - [SpamHaus](https://check.spamhaus.org/)
  - [AbuseIPDB](https://www.abuseipdb.com/)
  - [Malwarebazaar](https://bazaar.abuse.ch/)
  - [emailrep](https://emailrep.io/)
  - [shodan](https://www.shodan.io/)
  - [Onyphe](https://www.onyphe.io/)
  - [Censys](https://search.censys.io/)
  - [threatminer](https://www.threatminer.org/)
  - [urlscan](https://urlscan.io/)
  - [Apptotal (apps and extensions analysis)](https://apptotal.io/)
  - [urlquery](http://urlquery.net/)
  - [urlvoid](https://www.urlvoid.com)
  - [ipvoid](https://www.ipvoid.com/)
  - [mxtoolbox](https://mxtoolbox.com/NetworkTools.aspx)
  - [Microsoft TI](https://ti.defender.microsoft.com/)
  - [pulsedive](https://pulsedive.com/)
  - [threatbook](https://threatbook.io/)
  - [McAfee Threat Intelligence Exchange](https://www.mcafee.com/enterprise/en-us/products/threat-intelligence-exchange.html)
  - [Kaspersky Security Network](https://www.kaspersky.com/security-network)
  - [Microsoft Security Intelligence Report](https://www.microsoft.com/en-us/wdsi/intelligence-report)
  - [IBM X-Force Exchange](https://exchange.xforce.ibmcloud.com/) 
  - [AlienVault OTX](https://otx.alienvault.com/)
  - [greynoise](https://viz.greynoise.io/)

</details>

### More TI

<details>
  
  - [echotrail](https://www.echotrail.io/)
  - [redhuntlabs](https://redhuntlabs.com/online-ide-search)
  - [whois domaintools](https://whois.domaintools.com/)
  - [ASN check bgp.he](/bgp.he.net/)
  - [viewdns](http://viewdns.info/)
  - [OUI mac address lookup](https://www.wireshark.org/tools/oui-lookup.html)
  - [xcyclopedia](https://strontic.github.io/xcyclopedia/)
  - [abuse.ch](https://abuse.ch/#platforms)
  - [malware-traffic-analysis](https://www.malware-traffic-analysis.net/index.html)
  - [waybackmachine](http://web.archive.org/)
  - [dnshistory](https://dnshistory.org/)
  - [asnlookup](https://asnlookup.com/)
  - [fofa.info](https://fofa.info/)

</details>


### Sandbox

<details>
  
- [Sandbox HA](https://www.hybrid-analysis.com/)
- [Sandbox Anyrun](https://any.run/)
- [triage](https://tria.ge/reports/public)
- [capesandbox](https://www.capesandbox.com/)
- [joesandbox](https://www.joesandbox.com/analysispaged/0)
- 
</details>


## Data manipulation

<details>
  
- [jsoncrack](https://jsoncrack.com/editor)
- [cyberchef](https://cyberchef.org/)
- [Hash calculator](https://md5calc.com/hash)
- [regex101](https://regex101.com/)
- [CyberChef](https://gchq.github.io/CyberChef/)
- [Javascript Deobfuscator](https://deobfuscate.relative.im/)
- [JSONViewer](https://jsonviewer.stack.hu/)
- [TextMechanic](https://textmechanic.com/)
- [UrlEncode.org](https://www.urlencoder.org/)
- [TextFixer](https://www.textfixer.com/)
- [RegExr](https://regexr.com/)
- [TextUtils](https://textutils.com/)
- [TextCompactor](https://textcompactor.com/)
- [Pretty Diff](https://prettydiff.com/)
- [XML Tree](http://www.xmltree.com/)
- [Online XML Formatter and Beautifier](https://www.freeformatter.com/xml-formatter.html)
- [XML Escape Tool](https://www.freeformatter.com/xml-escape.html)
- [DiffChecker](https://www.diffchecker.com/)
- [CSVJSON](https://www.csvjson.com/)
- [HTML Formatter](https://htmlformatter.com/)
- [Text Tool](https://texttools.netlify.app/)
- [String Manipulation Tool](https://string-functions.com/)
- [unshorten it](https://www.unshorten.it)
- [urlunscrambler](https://www.urlunscrambler.com/)
- [longurl](https://www.longurl.org/)
- [Message Header](https://mha.azurewebsites.net/pages/mha.html)
- [MXToolbox EmailHeaders](https://mxtoolbox.com/EmailHeaders.aspx)
- [Email Header Analyzer](https://emailheaders.verification-check.com/)
- [Email Header Analysis](https://www.email-format.com/header-analysis/)
- [Gitlab dashboard from Excel](https://thisdavej.com/copy-table-in-excel-and-paste-as-a-markdown-table/)
- [OPENAI](https://openai.com/playground)
- [uncoder](https://uncoder.io/)

</details>


## Detection Resources

<details>
  
- [MITRE techniques](https://attack.mitre.org/techniques/enterprise/)
- [MITRE Updates](https://attack.mitre.org/resources/updates/)
- [MITRE D3fend](https://d3fend.mitre.org/)
- [MITRE Navigator](https://mitre-attack.github.io/attack-navigator/)
- [MITRE Datasources](https://attack.mitre.org/datasources/)
- [GTFOBIN](https://github.com/mthcht/GTFOBins.github.io)
- [LOLBAS](https://github.com/mthcht/LOLBAS)
- [LOTS](https://lots-project.com/)
- [loldrivers](https://www.loldrivers.io/)
- [WTFBIN](https://wtfbins.wtf/)
- [Sigma](https://github.com/mthcht/sigma/tree/master/rules)
- [Splunk Rules](https://research.splunk.com/detections/)
- [Elastic Rules](https://github.com/elastic/detection-rules)
- [DFIR-Report Sigma-Rules](https://github.com/The-DFIR-Report/Sigma-Rules)
- [JoeSecurity Sigma-Rules](https://github.com/joesecurity/sigma-rules/tree/master/rules)
- [mdecrevoisier Sigma-Rules](https://github.com/mdecrevoisier/SIGMA-detection-rules)
- [P4T12ICK Sigma-Rules](https://github.com/P4T12ICK/Sigma-Rule-Repository)
- [tsale Sigma-Rules](https://github.com/tsale/Sigma_rules)
- [list of detections resources](https://github.com/jatrost/awesome-detection-rules)
  
</details>


## DFIR

<details>

  - [EricZimmerman Tools](https://ericzimmerman.github.io/#!index.md)
  - [dfir-orc](https://github.com/dfir-orc)
  - [dfir-orc-config](https://github.com/DFIR-ORC/dfir-orc-config)
  - [Splunk4DFIR](https://github.com/mf1d3l/Splunk4DFIR)
  - [dfiq](https://github.com/google/dfiq)
  - [PSBits](https://github.com/gtworek/PSBits)
  - [Yara TH](https://github.com/mthcht/ThreatHunting-Keywords-yara-rules) + [TH](https://github.com/mthcht/ThreatHunting-Keywords)
  - [Hayabusa](https://github.com/Yamato-Security/hayabusa)
  - [chainsaw](https://github.com/WithSecureLabs/chainsaw)
  - [regripper](https://github.com/warewolf/regripper)
  - [RdpCacheStitcher](https://github.com/BSI-Bund/RdpCacheStitcher)
  - [ripgrep](https://github.com/BurntSushi/ripgrep)
  - [Kape](https://www.kroll.com/en/insights/publications/cyber/kroll-artifact-parser-extractor-kape)
  - [Kape Files](https://github.com/EricZimmerman/KapeFiles)
  - [More Kape ressources](https://github.com/AndrewRathbun/Awesome-KAPE)
  - [VolatileDataCollector](https://github.com/gtworek/VolatileDataCollector)
  - [Velociraptor](https://github.com/Velocidex/velociraptor)
  - [MemDump](https://nircmd.nirsoft.net/memdump.html)
  - [MemProcFS](https://github.com/ufrisk/MemProcFS)
  - [avml](https://github.com/microsoft/avml)
  - [Lime](https://github.com/504ensicsLabs/LiME)
  - [WinPmem](https://github.com/Velocidex/WinPmem)
  - [Volatility](https://github.com/volatilityfoundation/volatility3/)
  - [Windows artifacts](https://github.com/Psmths/windows-forensic-artifacts)

</details>

## Security News

<details>
  
- [Twitter](https://twitter.com/home)
- [CERT-FR](https://www.cert.ssi.gouv.fr/)
- [CERT FR Alerts](https://www.cert.ssi.gouv.fr/alerte/)
- [CERT FR Avis](https://www.cert.ssi.gouv.fr/avis/)
- [NIST CVEs](https://nvd.nist.gov/vuln/search/results?isCpeNameSearch=false&results_type=overview&form_type=Basic&search_type=all&startIndex=0)
- [JPCERT](https://www.jpcert.or.jp/english/)
- [CISA news](https://www.cisa.gov/news-events/news)
- [thedfirreport Feed](https://thedfirreport.com/feed/)
- [Splunk Research Blog](https://www.splunk.com/en_us/blog/author/secmrkt-research.html)
- [Unit42 Feed](http://feeds.feedburner.com/Unit42)
- [DFIR weekly sumary - thisweekin4n6](https://thisweekin4n6.wordpress.com/feed/)
- [akamai Feed](http://blogs.akamai.com/atom.xml)
- [Elastic Blog](https://www.elastic.co/security-labs)
- [Checkpoint research Feed](https://research.checkpoint.com/feed)
- [Cisco Talos Feed](http://vrt-sourcefire.blogspot.com/feeds/posts/default)
- [Crowdstrike Feed](http://blog.crowdstrike.com/feed)
- [Hexacorn Blog](http://www.hexacorn.com/blog/feed/)
- [simone kraus Blog](https://medium.com/@simone.kraus)
- [Michael Haag Blog](https://haggis-m.medium.com/)
- [EricaZelic Blog](https://ericazelic.medium.com/)
- [Adam Chester Blog Feed](https://blog.xpnsec.com/rss.xml)
- [Mauricio Velazco Blog](https://medium.com/@mvelazco)
- [Clément Notin Feed](https://clement.notin.org/feed.xml)
- [tenable Blog](https://medium.com/tenable-techblog)
- [horizon3 Feed](https://www.horizon3.ai/feed/)
- [Incidents reports Feed](https://fetchrss.com/rss/65b0eb775582bd1c19083c4365b0fdb664898a0daa63bef4.xml)
- [NCC Group Research Feed](https://research.nccgroup.com/feed/)
- [SpecterOps Feed](https://posts.specterops.io/feed)
- [Redcanary Feed](https://www.redcanary.co/feed/)
- [Sophos Research Feed](https://news.sophos.com/en-us/category/threat-research/feed/)
- [virusbulletin](https://www.virusbulletin.com/virusbulletin/)
- [Offensive Research - DSAS by INJECT](https://blog.injectexp.dev/)
- [HackerNews Feed](https://feeds.feedburner.com/TheHackersNews)
- [Bleepingcomputer Feed](https://www.bleepingcomputer.com/feed/)
- [detect.fyi](https://detect.fyi/)
</details>

## Formations

<details>

### DFIR
  - @inversecos - APT Emulation Labs: [xintra](https://www.xintra.org/labs)
  - 13cubed - Investigating Windows Endpoints: [13cubed.com](https://training.13cubed.com/investigating-windows-endpoints)
  - @0gtweet - Forensic course: [Mastering Windows Forensics](https://grzegorz-tworek-s-school.teachable.com/)
  - SANS: [SANS508](https://www.sans.org/cyber-security-courses/advanced-incident-response-threat-hunting-training/)

</details>
 
## Others

<details>
  
- [Crontab check](https://crontab.guru/every-2-minutes)
- [Subnet Calculator](https://mxtoolbox.com/subnetcalculator.aspx)
- [chmod calculator](https://chmod-calculator.com/)
- [Epoch time converter](https://www.epochconverter.com/)
- [cyberchef](https://cyberchef.org/)

</details>

