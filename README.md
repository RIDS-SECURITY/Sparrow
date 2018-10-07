# SPARROW
#### Version 2.0.0
#### By net_freak_criss A.K.A RIDS-SECURITY
All in one tool for Information Gathering  and  Vulnerability Scanning

# Scans That You Can Perform Using SPARROW :
- Basic Scan
        * Site Title 
        * IP Address
        * Web Server Detection 
        * CMS Detection
        * Cloudflare Detection
        * robots.txt Scanner
- Whois Lookup 
- Geo-IP Lookup
- Grab Banners 
- DNS Lookup
- Subnet Calculator
- Nmap Port Scan
- Sub-Domain Scanner 
        * Sub Domain
        * IP Address
- Reverse IP Lookup & CMS Detection 
        * Hostname
        * IP Address
        * CMS
- Error Based SQLi Scanner
- Bloggers View 
 * HTTP Response Code
        * Site Title
        * Alexa Ranking
        * Domain Authority
        * Page Authority
        * Social Links Extractor
        * Link Grabber
- WordPress Scan
        * Sensitive Files Crawling
        * Version Detection
        * Version Vulnerability Scanner
- Crawler
- MX Lookup 
- Scan For Everything - _The Old Lame Scanner_

---
# Released Versions:
    - Version 2.0.0 [10-07-2018]

# Changelog:
- Version 2.0.0
    - Initial Launch

# Installation:
1. Run The Tool and Type `fix` This will Install All Required Modules.
2. For The Bloggers View To Work Properly you have to configure SPARROW with moz.com's api keys.

**How To Configure SPARROW with moz.com for Bloggers View Scan**
+ Create an account in moz follow this link : https://moz.com/community/join
+ After successful account creation and completing the verification you need to generate the API Keys
+ You can get your API Keys here: https://moz.com/products/mozscape/access
+ Get your AccessID and SecretKey and replace the `$accessID` and `$secretKey` variable's value in the config.php file
+ All set, now you can enjoy the bloggers view.

# Usage:
- git clone `https://github.com/RIDS-SECURITY/Sparrow`
- cd Sparrow
- php sparrow.php
- Use the "help" command to see the command list or type in the domain name you want to scan (without https/http)
- Select whether The Site Runs On HTTPS or not.
- Select the type of scan you want to perform
- Leave the rest to the scanner

# List of CMS Supported
Sparrow's `CMS Detector` currently is able to detect the following CMSs (Content Management Systems)

- WordPress
- Joomla
- Drupal
- Magento

# Known Issues
**ISSUE:** Scanner Stops Working After Cloudflare Detection!

**SOLUTION:** Use The `fix` Command OR Manually Install *php-curl* & *php-xml*


Can't donate? well that's no problem just drop a **THANK YOU** this will motivate me to create more

# TODOs

- Make a proper update option ( Installs current version automatically )
- Add more CMS to the detector
- Improve The WordPress Scanner ( Add User, Theme & Plugins Enumeration )
- Create a web version of the scanner
- Add XSS & LFI Scanner
- Improve the Links grabber thingy under bloggers view
- Add some other scans under the Bloggers View


