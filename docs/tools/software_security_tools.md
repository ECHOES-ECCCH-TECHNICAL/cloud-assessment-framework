# Software Security Tools

Security-related tools.

## Summary

- **OWASP Application Security Verification Standard (ASVS)** — A standard that defines security requirements and verification levels for designing, building, and testing secure web applications and APIs.
- **OWASP Web Security Testing Guide (WSTG)** — A comprehensive guide that provides methodologies and test cases for performing web application security testing and penetration testing.
- **OWASP Zed Attack Proxy (ZAP)** — An open-source dynamic application security testing tool for finding vulnerabilities in running web applications through automated and manual testing.
- **Bandit (Python security linter)** — A static analysis tool that identifies common security issues and insecure coding practices in Python source code.
- **OWASP Software Assurance Maturity Model (SAMM)** — A framework for measuring and improving the maturity of secure software development practices across governance, design, implementation, and operations.
- **CIS Critical Security Controls** — A prioritized set of best-practice security controls to improve an organisation’s overall cybersecurity posture and resilience.
- **CIS Benchmarks** — Configuration best practices and hardening guidelines for operating systems, cloud services, containers, and applications.
- **Cloud Security Alliance Cloud Controls Matrix (CCM) and CAIQ** — A cloud security control framework and questionnaire that helps assess and communicate cloud security capabilities and assurance.
- **ENISA Cloud Computing Security Risk Assessment and Information Assurance Framework** — Guidance and frameworks from ENISA for assessing, managing, and assuring cloud computing security risks.
- **OWASP Dependency-Check** — A tool that identifies known vulnerabilities in third-party dependencies by scanning project dependency manifests.
- **OSV-Scanner** — A command-line tool that scans source code, dependencies, and SBOMs for known vulnerabilities using the OSV database.
- **Trivy** — A security scanner for containers, cloud-native workloads, dependencies, and infrastructure-as-code configurations.
- **SLSA (Supply-chain Levels for Software Artifacts)** — A framework that defines maturity levels and best practices for securing software supply chains and build processes.
- **CHAOSS Libyears and related risk metrics** — A set of metrics that quantify how outdated software dependencies are and help assess open-source dependency risk.
- **OpenSSF Scorecard** — An automated tool that assesses open-source projects against a set of security best practices and produces a security score.
- **OWASP DefectDojo** — An open-source vulnerability management platform that aggregates, tracks, and prioritises security findings from multiple tools.
- **Bearer CLI** — Bearer CLI is a static application security testing (SAST) tool that scans your source code and analyzes your data flows to discover, filter and prioritize security and privacy risks.

## OWASP Application Security Verification Standard (ASVS)

- **ID:** `SOFTWARE_SECURITY_TOOLS_OWASP_APPLICATION_SECURITY`
- **Dimensions covered:** Security.
- **Description:** A standard that defines security requirements and verification levels for designing, building, and testing secure web applications and APIs.
- **Link:** https://owasp.org/www-project-application-security-verification-standard/

### Additional properties

- **Security dimensions:** Application and API security controls; secure coding requirements.
- **Type of tool:** Standard + requirements checklist (verification standard).

## OWASP Web Security Testing Guide (WSTG)

- **ID:** `SOFTWARE_SECURITY_TOOLS_OWASP_WEB_SECURITY`
- **Dimensions covered:** Security.
- **Description:** A comprehensive guide that provides methodologies and test cases for performing web application security testing and penetration testing.
- **Link:** https://owasp.org/www-project-web-security-testing-guide/

### Additional properties

- **Security dimensions:** Application and API security controls; penetration testing coverage.
- **Type of tool:** Methodology + test catalogue.

## OWASP Zed Attack Proxy (ZAP)

- **ID:** `SOFTWARE_SECURITY_TOOLS_OWASP_ZED_ATTACK`
- **Dimensions covered:** Security.
- **Description:** An open-source dynamic application security testing tool for finding vulnerabilities in running web applications through automated and manual testing.
- **Link:** https://www.zaproxy.org/
https://www.zaproxy.org/intro-video/

### Additional properties

- **Security dimensions:** Application and API runtime security; web vulnerability exposure.
- **Type of tool:** Application (DAST scanner).

## Bandit (Python security linter)

- **ID:** `SOFTWARE_SECURITY_TOOLS_BANDIT_PYTHON_SECURITY`
- **Dimensions covered:** Security.
- **Description:** A static analysis tool that identifies common security issues and insecure coding practices in Python source code.
- **Link:** https://bandit.readthedocs.io/

### Additional properties

- **Security dimensions:** Secure coding practices for Python-based components.
- **Type of tool:** Application (SAST security linter).

## OWASP Software Assurance Maturity Model (SAMM)

- **ID:** `SOFTWARE_SECURITY_TOOLS_OWASP_SOFTWARE_ASSURANCE`
- **Dimensions covered:** Security.
- **Description:** A framework for measuring and improving the maturity of secure software development practices across governance, design, implementation, and operations.
- **Link:** https://owaspsamm.org/

### Additional properties

- **Security dimensions:** Secure development lifecycle maturity; security governance and process quality.
- **Type of tool:** Maturity model + self-assessment toolkit.

## CIS Critical Security Controls

- **ID:** `SOFTWARE_SECURITY_TOOLS_CIS_CRITICAL_SECURITY`
- **Dimensions covered:** Security.
- **Description:** A prioritized set of best-practice security controls to improve an organisation’s overall cybersecurity posture and resilience.
- **Link:** https://www.cisecurity.org/controls

### Additional properties

- **Security dimensions:** Cloud and infrastructure security; organisational security posture; incident response readiness.
- **Type of tool:** Control framework + checklist.

## CIS Benchmarks

- **ID:** `SOFTWARE_SECURITY_TOOLS_CIS_BENCHMARKS`
- **Dimensions covered:** Security.
- **Description:** Configuration best practices and hardening guidelines for operating systems, cloud services, containers, and applications.
- **Link:** https://www.cisecurity.org/cis-benchmarks

### Additional properties

- **Security dimensions:** Cloud and infrastructure configuration hardening; secure configuration management.
- **Type of tool:** Benchmark baselines + configuration checklists.

## Cloud Security Alliance Cloud Controls Matrix (CCM) and CAIQ

- **ID:** `SOFTWARE_SECURITY_TOOLS_CLOUD_SECURITY_ALLIANCE`
- **Dimensions covered:** Security.
- **Description:** A cloud security control framework and questionnaire that helps assess and communicate cloud security capabilities and assurance.
- **Link:** https://cloudsecurityalliance.org/research/cloud-controls-matrix

### Additional properties

- **Security dimensions:** Cloud security controls; transparency and assurance for cloud consumers.
- **Type of tool:** Control matrix + assessment questionnaire.

## ENISA Cloud Computing Security Risk Assessment and Information Assurance Framework

- **ID:** `SOFTWARE_SECURITY_TOOLS_ENISA_CLOUD_COMPUTING`
- **Dimensions covered:** Security.
- **Description:** Guidance and frameworks from ENISA for assessing, managing, and assuring cloud computing security risks.
- **Link:** https://www.enisa.europa.eu/publications/cloud-computing-risk-assessment 
https://www.enisa.europa.eu/publications/cloud-computing-information-assurance-framework

### Additional properties

- **Security dimensions:** Cloud and infrastructure security risk; alignment with EU cloud-assurance expectations.
- **Type of tool:** Risk assessment methodology + assurance criteria framework.

## OWASP Dependency-Check

- **ID:** `SOFTWARE_SECURITY_TOOLS_OWASP_DEPENDENCY_CHECK`
- **Dimensions covered:** Security.
- **Description:** A tool that identifies known vulnerabilities in third-party dependencies by scanning project dependency manifests.
- **Link:** https://owasp.org/www-project-dependency-check/

### Additional properties

- **Security dimensions:** Supply chain and third-party dependency security; vulnerable component exposure.
- **Type of tool:** Application (Software Composition Analysis tool).

## OSV-Scanner

- **ID:** `SOFTWARE_SECURITY_TOOLS_OSV_SCANNER`
- **Dimensions covered:** Security.
- **Description:** A command-line tool that scans source code, dependencies, and SBOMs for known vulnerabilities using the OSV database.
- **Link:** https://github.com/google/osv-scanner

### Additional properties

- **Security dimensions:** Supply chain security; vulnerability exposure in open-source dependencies and SBOMs.
- **Type of tool:** Application (CLI vulnerability scanner).

## Trivy

- **ID:** `SOFTWARE_SECURITY_TOOLS_TRIVY`
- **Dimensions covered:** Security.
- **Description:** A security scanner for containers, cloud-native workloads, dependencies, and infrastructure-as-code configurations.
- **Link:** https://aquasecurity.github.io/trivy/

### Additional properties

- **Security dimensions:** Container and cloud-native workload security; dependency vulnerabilities; infrastructure-as-code misconfigurations.
- **Type of tool:** Application (multi-target security scanner).

## SLSA (Supply-chain Levels for Software Artifacts)

- **ID:** `SOFTWARE_SECURITY_TOOLS_SLSA_SUPPLY_CHAIN`
- **Dimensions covered:** Security.
- **Description:** A framework that defines maturity levels and best practices for securing software supply chains and build processes.
- **Link:** https://slsa.dev/

### Additional properties

- **Security dimensions:** Software supply-chain integrity; build and release process maturity.
- **Type of tool:** Maturity model / framework.

## CHAOSS Libyears and related risk metrics

- **ID:** `SOFTWARE_SECURITY_TOOLS_CHAOSS_LIBYEARS_AND`
- **Dimensions covered:** Security.
- **Description:** A set of metrics that quantify how outdated software dependencies are and help assess open-source dependency risk.
- **Link:** https://chaoss.community/ 
https://chaoss.community/kb/metric-libyears/

### Additional properties

- **Security dimensions:** Dependency freshness; open-source project risk and sustainability.
- **Type of tool:** Metric model + tooling.

## OpenSSF Scorecard

- **ID:** `SOFTWARE_SECURITY_TOOLS_OPENSSF_SCORECARD`
- **Dimensions covered:** Security.
- **Description:** An automated tool that assesses open-source projects against a set of security best practices and produces a security score.
- **Link:** https://scorecard.dev/

### Additional properties

- **Security dimensions:** Open-source project security practices; governance and automation quality.
- **Type of tool:** Automated assessment tool + score model.

## OWASP DefectDojo

- **ID:** `SOFTWARE_SECURITY_TOOLS_OWASP_DEFECTDOJO`
- **Dimensions covered:** Security.
- **Description:** An open-source vulnerability management platform that aggregates, tracks, and prioritises security findings from multiple tools.
- **Link:** https://www.defectdojo.org/

### Additional properties

- **Security dimensions:** Vulnerability management; remediation workflow; overall application security posture.
- **Type of tool:** Application (vulnerability management platform).

## Bearer CLI

- **ID:** `SOFTWARE_SECURITY_TOOLS_BEARER_CLI`
- **Dimensions covered:** Security.
- **Description:** Bearer CLI is a static application security testing (SAST) tool that scans your source code and analyzes your data flows to discover, filter and prioritize security and privacy risks.
- **Link:** https://github.com/bearer/bearer

### Additional properties

- **Security dimensions:** Confidentiality, integrity.
- **Type of tool:** Application (CLI).
