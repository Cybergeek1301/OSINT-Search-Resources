Email & Domain OSINT Resources

A curated collection of tools and reference resources for researching email addresses, domain names, DNS records, website infrastructure, and publicly available technical information.

These resources are intended for OSINT research, cybersecurity education, phishing investigations, and defensive security analysis.

Table of Contents

* Email Security & Validation
* Domain Registration & Ownership
* DNS & Website Infrastructure
* Certificate Transparency
* Domain Reputation & Threat Intelligence
* Search Techniques
* Verification & Limitations

Email Security & Validation

Google Admin Toolbox

* URL: https://toolbox.googleapps.com/
* Purpose: Provides diagnostic tools for DNS, email configuration, and domain troubleshooting.
* Best for: Investigating email delivery and technical configuration issues.

MXToolbox

* URL: https://mxtoolbox.com/
* Purpose: Checks MX records, DNS configuration, mail server reputation, and email authentication records.
* Best for: Investigating mail delivery problems and suspicious email infrastructure.

Have I Been Pwned

* URL: https://haveibeenpwned.com/
* Purpose: Checks whether an email address appears in known data breaches.
* Best for: Personal account security checks and authorized security investigations.
* Note: A breach listing does not establish that an account is currently compromised.

Domain Registration & Ownership

ICANN Lookup

* URL: https://lookup.icann.org/
* Purpose: Looks up registration information for supported domain names.
* Best for: Reviewing registration dates, registrar information, and available registration data.
* Limitations: Privacy protection and data access restrictions may hide registrant details.

RDAP

* URL: https://www.icann.org/rdap
* Purpose: Learn about the Registration Data Access Protocol used to retrieve domain registration information.
* Best for: Understanding structured domain registration lookups.

DNS & Website Infrastructure

DNSDumpster

* URL: https://dnsdumpster.com/
* Purpose: Provides DNS and host information for domains.
* Best for: Reviewing publicly visible domain infrastructure.

DNSChecker

* URL: https://dnschecker.org/
* Purpose: Checks DNS records and their propagation across different locations.
* Best for: Comparing DNS responses and troubleshooting domain configuration.

Google Admin Toolbox Dig

* URL: https://toolbox.googleapps.com/apps/dig/
* Purpose: Queries DNS records for a domain.
* Best for: Examining records such as A, AAAA, MX, NS, TXT, and CNAME.

Certificate Transparency

crt.sh

* URL: https://crt.sh/
* Purpose: Searches publicly logged TLS certificates associated with domain names.
* Best for: Discovering certificate records and potentially identifying publicly documented subdomains.
* Note: A certificate entry does not prove that a hostname is currently active or vulnerable.

Domain Reputation & Threat Intelligence

VirusTotal

* URL: https://www.virustotal.com/
* Purpose: Reviews security vendor detections and available intelligence for domains, URLs, IP addresses, and file hashes.
* Best for: Investigating suspicious links and potentially malicious infrastructure.
* Important: A detection is an indicator for further investigation, not definitive proof of malicious activity.

URLhaus

* URL: https://urlhaus.abuse.ch/
* Purpose: Provides information about URLs associated with malware distribution.
* Best for: Defensive research into suspicious URLs and malware infrastructure.

urlscan.io

* URL: https://urlscan.io/
* Purpose: Analyzes submitted URLs and records information about webpage behavior and resources.
* Best for: Investigating suspicious websites.
* Privacy warning: Submissions may be publicly visible depending on submission settings. Do not submit private URLs, authentication links, or sensitive information.

Search Techniques

Search for a Domain

"example.com"

Search for publicly indexed references to a domain.

Search for Public Email References

"user@example.com"

Search for exact references to an email address that may appear in public webpages.

Search for a Domain’s Subdomains

site:example.com

Find pages indexed under a domain. This does not reliably enumerate every subdomain.

Search for Email Authentication Information

Review a domain’s SPF, DKIM, and DMARC configuration using appropriate DNS and email diagnostic tools.

These records help evaluate email authentication configuration but do not independently prove that a message is legitimate.

Replace example addresses and domains with the relevant research targets.

Verification & Limitations

* Email addresses can be spoofed in message headers or impersonated through lookalike domains.
* Domain registration records may be redacted, outdated, or incomplete.
* DNS records describe technical configuration and do not necessarily identify the person operating a website.
* Security scanners can produce false positives and false negatives.
* A domain’s reputation can change over time.
* Avoid uploading confidential emails, private URLs, or sensitive data to public analysis services.
* Use these resources for lawful research and authorized security investigations.

Maintenance

Review links periodically and update entries when tools, features, or access requirements change.

When suggesting a resource, include its name, official URL, purpose, access requirements, and relevant limitations.
