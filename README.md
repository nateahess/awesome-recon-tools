
![header-image](https://github.com/nahberry/Recon-Tools/blob/main/Logo/Recon_Logo.PNG)

# Recon Tools
 A compiled list of tools for reconnaissance and footprinting

## Site Information

Domain and Network Information
Netcraft – https://netcraft.com [web]
nslookup – [Windows cmd]
- Set interactive mode: Type nslookup in cmd prompt
- Set type: type set type=a – sets type to query for domain
                 set type=CNAME – sets type to query for CNAME records
Professional Toolset – https://network-tools.com [application]
You Get Signal – https://yougetsignal.com [web]
tracert – [Windows cmd]
- Traceroute can be used to extract information about topology, firewalls, etc.
traceroute – [Linux cmd]
VisualRoute – http://visualroute.com [web]
Traceroute NG – https://solarwinds.com [application]

## Geographical Data/Ips/Whois

 Shodan – https://shodan.io [web]
 Informer – https://website.informer.com/ [web]
 Domaintools – https://whois.domaintools.com [web]
 SmartWhois – https://tamos.com [application]
 Batch IP Converter – https://www.sabsoft.com [application]
 ARIN Whois/RDAP – https://arin.net/about/welcom/region [web]
 dnsrecon – [Linux cmd]
     - Example:  dnsrecon -r [IP Address range]

##  Operating System Info

 Censys – https://censys.io/domain?q= [web]
 Personal Info
 PeekYou – https://peekyou.com [web]
 Followerwonk – https://followerwonk.com [web]
 Hootsuite – https://hootsuite.com [web]

## Email Footprinting

 eMailTrackerPro – https://emailtrackerpro.com  [Windows application]
 Mailtrack – https://mailtrack.io [application/extension]
 Infoga - https://github.com/m4ll0k/infoga [Linux application]

## Windows CL

 ping [site] -f -l 1300 (Enter packet size)
 nslookup

## Linux Tools

 Harvester [tool]
 Sample commands:
 Linkedin: theHarvester -d [organization] -l 200 -b linkedin
 Search: theHarvester -d [organization] -l 200 -b google
 Sherlock (Personal accounts/sites) [tool]
 Sample commands:
 python3 sherlock.py [name]
