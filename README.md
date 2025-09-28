# cybersecurity-internship-task3


## 1. Executive Summary

The purpose of this vulnerability assessment was to identify common security weaknesses on the local machine using Nessus Essentials, a network vulnerability scanner. The scan focused on detecting outdated patches, insecure protocols, and vulnerable applications that could be exploited by attackers.

The assessment revealed several high and medium severity vulnerabilities including outdated operating system patches and insecure SMB and TLS configurations. Recommendations for remediation are included to improve system security and minimize risk.

## 2. Scan Details

- **Tool:** Nessus Essentials
- **Target:** Localhost (127.0.0.1)
- **Scan Date:** September 25, 2025
- **Scan Duration:** Approximately 20 minutes
- **Scan Type:** Basic Network Scan (Unauthenticated)
- **Severity Framework:** CVSS v3.0

## 3. Findings

Multiple vulnerabilities were identified and classified into severity levels:

- **High Severity:** Outdated Windows patches, SMBv1 enabled
- **Medium Severity:** Weak TLS protocols, outdated third-party software
- **Low/Info:** Various informational findings for system configuration and network exposure

## 4. Risk Assessment

High severity issues pose immediate risks such as remote code execution and ransomware exploitation due to outdated patches and legacy protocols. Medium severity items increase the system exposure and could be exploited under certain conditions.

## 5. Recommendations

- Apply all available system and software updates immediately.
- Disable SMBv1 and enable SMBv2 or SMBv3.
- Configure the system to use strong encryption protocols (TLS 1.2 or higher).
- Review and update any outdated applications flagged in the scan.

## 6. Conclusion

Regular vulnerability assessments help maintain a secure computing environment by identifying and remediating security risks. This assessment provides actionable insights to strengthen the local machine's security posture.


