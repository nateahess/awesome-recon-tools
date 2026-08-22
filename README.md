<h1 align="center">
  <a href="https://github.com/servicelogon/awesome-recon-tools">
    <img src="Logo/Recon-Tools.PNG" alt="Awesome Recon Tools" width="400">
  </a>
  <br>
  Awesome Recon Tools
</h1>

<p align="center">
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
  </a>
</p>

Reconnaissance and footprinting techniques for discovering hosts, domains, infrastructure, identities, and other publicly available information.

## Contents

- [Domain and Network Recon](#domain-and-network-recon) - Tools for gathering network-related information.
- [Personal Information and Email Footprinting](#personal-information-and-email-footprinting) - Tools for finding personal information, social networks, and email-related information.
- [See Also](#see-also) - Additional curated OSINT resources.
- [Hacking with Google](#hacking-with-google) - Search operators for reconnaissance and information discovery.

## Domain and Network Recon

Robust tools for gathering domain and network information.

### Programs and Web Applications

- [Amass](https://github.com/owasp-amass/amass) - In-depth attack-surface mapping and asset discovery tool combining passive OSINT, active DNS, certificate transparency, and brute force.
- [ARIN Whois/RDAP](https://www.arin.net/resources/registry/whois/) - Retrieves information about IP number resources, organizations, and points of contact registered with ARIN.
- [BuiltWith](https://builtwith.com) - Identifies technologies used by websites, including hosting, analytics, frameworks, and ecommerce platforms.
- [Censys](https://censys.io) - Searches internet-wide datasets to discover hosts, services, certificates, and exposed infrastructure.
- [crt.sh](https://crt.sh) - Searches certificate transparency logs to discover domains and subdomains from certificate history.
- [DataSploit](https://github.com/DataSploit/datasploit) - Performs automated OSINT on domains, email addresses, usernames, and phone numbers using multiple data sources.
- [DNSDumpster](https://dnsdumpster.com) - Discovers hosts related to a domain and helps map an organization's external attack surface.
- [DomScan](https://domscan.net/tools/security) - Performs domain and network reconnaissance across DNS, WHOIS/RDAP, TLS, subdomains, reputation, and typosquatting.
- [DomainTools](https://whois.domaintools.com) - Provides WHOIS information, registrar details, name servers, and related domain intelligence.
- [FireCompass](https://firecompass.com) - Discovers an organization's external digital attack surface.
- [GreyNoise](https://greynoise.io) - Provides context on internet background noise and scanners to help distinguish broad scanning from targeted activity.
- [httpx](https://github.com/projectdiscovery/httpx) - Fast, multi-purpose HTTP probing toolkit for identifying live web services from discovered hosts.
- [Informer](https://website.informer.com/) - Provides an aggregated view of publicly available information about a website.
- [Maltego](https://maltego.com) - Open-source intelligence and graphical link-analysis platform for gathering and connecting investigative information.
- [Netcraft](https://netcraft.com) - Provides site reports, DNS searches, hosting intelligence, and other internet reconnaissance tools.
- [Nmap](https://nmap.org) - Network discovery and security auditing tool for host discovery, port scanning, and service detection.
- [Nuclei](https://github.com/projectdiscovery/nuclei) - Template-based scanner for validating vulnerabilities and exposures discovered during reconnaissance.
- [Professional Toolset](https://network-tools.com) - Provides ping, traceroute, HTTP header inspection, and other network utilities.
- [SecurityTrails](https://securitytrails.com) - Provides historical DNS, WHOIS, and passive DNS data for investigating infrastructure history.
- [Shodan](https://shodan.io) - Internet intelligence search engine for discovering internet-connected systems, services, and exposed devices.
- [SpiderFoot](https://github.com/smicallef/spiderfoot) - Automated OSINT collection and attack-surface reconnaissance framework.
- [Subfinder](https://github.com/projectdiscovery/subfinder) - Fast passive subdomain discovery tool from ProjectDiscovery.
- [Traceroute NG](https://solarwinds.com/free-tools/traceroute-ng) - Continuously probes network paths, detects route changes, supports IPv4 and IPv6, and creates text log files.
- [URL Fuzzer](https://pentest-tools.com/website-vulnerability-scanning/discover-hidden-directories-and-files#) - Scans websites for hidden files and directories.
- [VisualRoute](http://www.visualroute.com) - Provides continuous tracerouting, reverse tracing, port probing, and route analysis.
- [Wappalyzer](https://www.wappalyzer.com) - Identifies technologies and software stacks used by websites.
- [Whois.net](https://whois.net) - Provides WHOIS lookup, domain registration information, and domain availability searches.
- [Wireshark](https://wireshark.org) - Network protocol analyzer for inspecting and troubleshooting network traffic.
- [You Get Signal](https://yougetsignal.com) - Provides port testing, network location, visual traceroute, reverse IP lookup, and related network utilities.

### Windows CLI

- [nslookup](https://learn.microsoft.com/windows-server/administration/windows-commands/nslookup) - Queries the Domain Name System for host, address, and DNS record information.
- [tracert](https://learn.microsoft.com/windows-server/administration/windows-commands/tracert) - Displays a network route and measures transit delays across an Internet Protocol network.

### Linux CLI / Kali

- [dig](https://linuxhandbook.com/dig-command/) - Queries DNS servers for domain name and DNS record information.
- [dnsrecon](https://www.kali.org/tools/dnsrecon/) - Enumerates DNS records, checks for zone transfers, and performs related DNS reconnaissance.
- [dnstracer](https://www.kali.org/tools/dnstracer/) - Traces DNS queries to determine where a DNS server obtains information for a hostname.
- [Fierce](https://github.com/mschwager/fierce) - DNS reconnaissance tool for locating non-contiguous IP space and discovering targets.
- [Ghost Eye](https://github.com/BullsEye0/ghost_eye) - Information-gathering toolkit for WHOIS, DNS, EtherApe, Nmap, and related reconnaissance tasks.
- [recon-ng](https://github.com/lanmaster53/recon-ng) - Modular framework for conducting web-based open-source intelligence reconnaissance.
- [ronin-recon](https://github.com/ronin-rb/ronin-recon#readme) - Recursive reconnaissance framework for subdomains, DNS records, ports, TLS certificates, websites, and email addresses.
- [traceroute](https://www.commandlinux.com/man-page/man1/traceroute.db.1.html) - Displays the route packets take to a network host.
- [unicornscan](https://www.kali.org/tools/unicornscan/) - Asynchronous network reconnaissance and stimulus-response measurement tool.
- [whois](https://www.commandlinux.com/man-page/man1/whois.1.html) - Command-line client for querying WHOIS directory services.

## Personal Information and Email Footprinting

Tools for gathering personal information, social-network information, and email-related intelligence.

### Programs and Web Applications

- [BeenVerified](https://beenverified.com) - Provides public-record and background-information searches.
- [Epieos](https://epieos.com) - Browser-based account and identity lookup tool using email addresses and related public information.
- [Followerwonk](https://followerwonk.com) - Social media audience research and analytics tool operated as part of Fedica's suite.
- [GHunt](https://github.com/mxrch/GHunt) - Google-account OSINT framework for gathering publicly available information associated with an email address or Gaia ID.
- [Have I Been Pwned](https://haveibeenpwned.com) - Checks email addresses and domains for exposure in known data breaches.
- [Hunter.io](https://hunter.io) - Finds and verifies email addresses associated with a domain.
- [Maigret](https://github.com/soxoj/maigret) - Username OSINT tool that checks thousands of sites for matching accounts and profiles.
- [PeekYou](https://peekyou.com) - Searches publicly available information associated with people and online identities.
- [Xquik](https://github.com/Xquik-dev/x-twitter-scraper) - Independent X data API for search, follower export, and monitoring.

### Linux CLI / Kali

- [sherlock](https://github.com/sherlock-project/sherlock) - Searches many social networks for accounts associated with a username.
- [theHarvester](https://www.kali.org/tools/theharvester/) - Collects email addresses, names, subdomains, IPs, and URLs from public sources.

## See Also

- [OSINT Framework](https://osintframework.com) - Visual directory of OSINT tools and data sources organized by investigation category.

## Hacking with Google

Search operators for finding publicly indexed information with Google.

| Operator       | Purpose                                                                  |
| -------------- | ------------------------------------------------------------------------ |
| `"phrase"`     | Searches for an exact word or phrase.                                    |
| `allintext:`   | Searches for pages containing all specified terms in the page text.      |
| `allintitle:`  | Searches for pages containing all specified terms in the page title.     |
| `allinurl:`    | Searches for pages containing all specified terms in the URL.            |
| `after:`       | Finds documents updated after a specified date.                          |
| `before:`      | Finds documents updated before a specified date.                         |
| `filetype:`    | Restricts results to a specified file type.                              |
| `inurl:`       | Searches for pages containing a specified term in the URL.               |
| `intitle:`     | Searches for pages containing a specified term in the title.             |
| `inanchor:`    | Searches for pages containing specified anchor text.                     |
| `intext:`      | Searches for pages containing a specified term in the page text.         |
| `site:`        | Restricts results to a specified domain or site.                         |
| `*`            | Acts as a wildcard for one or more unspecified words.                    |
| `\|`           | Acts as a logical OR operator between search terms.                      |
| `-`            | Excludes results containing a specified term.                            |
