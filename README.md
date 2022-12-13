# KB v1.0 - _The Multi-Tool Web Vulnerability Scanner_
`KB has been ported to Python3`

## Vulnerability Checks
- :heavy_check_mark: DNS/HTTP Load Balancers & Web Application Firewalls.
- :heavy_check_mark: Checks for Joomla, WordPress and Drupal
- :heavy_check_mark: SSL related Vulnerabilities (_HEARTBLEED, FREAK, POODLE, CCS Injection, LOGJAM, OCSP Stapling_).
- :heavy_check_mark: Commonly Opened Ports.
- :heavy_check_mark: DNS Zone Transfers using multiple tools (_Fierce, DNSWalk, DNSRecon, DNSEnum_).
- :heavy_check_mark: Sub-Domains Brute Forcing (_DNSMap, amass, nikto_)
- :heavy_check_mark: Open Directory/File Brute Forcing.
- :heavy_check_mark: Shallow XSS, SQLi and BSQLi Banners.
- :heavy_check_mark: Slow-Loris DoS Attack, LFI (_Local File Inclusion_), RFI (_Remote File Inclusion_) & RCE (_Remote Code Execution_).

## Requirements
- **Python 3**
- Kali OS (_**Preferred**, as it is shipped with almost all the tools_)
- Tested with Parrot & Ubuntu Operating Systems.

## Usage 
 `python3 kb.py example.com`

## Installation
```
git clone https://github.com/yassir-kb/CyberSecurity.git
```

### Docker Support
- Kali linux image in : https://hub.docker.com/repository/docker/yassirkb/cybersecurity