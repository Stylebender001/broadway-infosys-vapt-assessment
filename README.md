# Vulnerability Assessment and Penetration Testing (VAPT)

## Project Overview
A practical Vulnerability Assessment and Penetration Testing exercise conducted as part of cybersecurity training. The assessment covered web application security, network services, and Active Directory environments using intentionally vulnerable lab systems.

## Assessment Scope

- **Web Application Security:** DVWA, OWASP WebGoat, and other vulnerable lab applications.
- **Network Security:** OWASP Broken Web Applications (OWASP BWA) and exposed network services.
- **Active Directory Security:** TryHackMe VulnNet Active lab environment.

## Key Findings

| Finding | Severity |
|---|---|
| SQL Injection | Critical |
| Command Injection | Critical |
| SMBv1 Enabled | High |
| XPath Injection | High |
| Exposed `.bash_history` | Medium |
| Exposed phpMyAdmin | Medium |
| Directory Listing Enabled | Medium |
| Outdated Joomla Components | Medium |
| Tomcat Manager Interface Exposed | Medium |

## Tools and Technologies

- Nmap
- SQLmap
- SMBClient
- NetExec
- BloodHound
- Web application security testing tools

## Methodology

1. Identify and enumerate target services and applications.
2. Assess potential vulnerabilities and security misconfigurations.
3. Validate findings within the authorized lab environments.
4. Document observations, risks, and remediation recommendations.

## Recommendations

- Disable legacy protocols such as SMBv1.
- Apply security updates to outdated software.
- Restrict access to administrative interfaces.
- Prevent command and SQL injection through secure input handling.
- Disable unnecessary directory listings and sensitive file exposure.
- Improve network segmentation, logging, and monitoring.

## Disclaimer

This project documents a historical cybersecurity training assessment conducted in intentionally vulnerable lab environments. It is provided for educational and portfolio purposes only. It does not represent an assessment of Broadway Infosys' production infrastructure or any real-world client environment.

## Author

Shardul Sapkota  
Cybersecurity | Vulnerability Assessment | Penetration Testing
