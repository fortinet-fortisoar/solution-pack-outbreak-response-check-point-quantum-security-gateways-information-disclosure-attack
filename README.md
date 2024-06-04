# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

A zero-day vulnerability affecting Check Point Security Gateways is being exploited by attackers to gain remote access. The vulnerability can allow an attacker to read sensitive information on Check Point Security Gateways enabled with remote Access VPN or Mobile Access Software Blades.  

 The **Outbreak Response - Check Point Quantum Security Gateways Information Disclosure Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/1.1.0/README.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/check-point-information-disclosure) contains information about the outbreak alert **Outbreak Response - Check Point Quantum Security Gateways Information Disclosure Attack**. 

## Background: 

The vulnerability CVE-2024-24919 allows an unauthenticated remote attacker to read the contents of an arbitrary file located on the affected appliance, including disclosing the password hashes for local accounts. Weak passwords can be compromised, leading to further misuse and potential lateral movement within the network. Check Point mentioned in their advisory that the exploitation attempts were seen as early as April 7, 2024.
 

## Announced: 

FortiGuard recommends users to apply the emergency hotfix provided and follow instructions as mentioned on the vendor’s advisory. All the known IoCs involved in the campaign are blocked by Web Filtering and IOC service. FortiGuard Labs is continuously monitoring the situation and as new information becomes available this report will be updated accordingly. 

## Latest Developments: 

May 30, 2024: CISA added CVE-2024-24919 to its Known Exploited Catalog (KEV) list
https://www.cisa.gov/known-exploited-vulnerabilities-catalog

May 30, 2024: FortiGuard Labs released IPS protection for CVE-2024-24919
https://www.fortiguard.com/encyclopedia/ips/55956

May 30, 2024: FortiGuard Labs released a Threat Signal
https://www.fortiguard.com/threat-signal-report/5464/

May 30, 2024: Check Point has released a hotfix for CVE-2024-24919 and extra measures that should be taken to mitigate the risks.
https://support.checkpoint.com/results/sk/sk182336

May 28, 2024: Check Point issued an advisory, warning that threat actors are actively targeting their Remote Access VPN devices in an ongoing campaign to infiltrate enterprise networks.
https://support.checkpoint.com/results/sk/sk182337 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|