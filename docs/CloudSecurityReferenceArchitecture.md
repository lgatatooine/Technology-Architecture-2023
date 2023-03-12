## Cloud Security Reference Architecture
* Automated Security Testing
* Layered Security Approach

### Security Principles
* Build a layered security approach (defense-in-depth)
* Design for secured decoupled systems (security-built-in)
* Automate deployment and security best practices
* Automate security monitoring & traceability 
* Meet the data residency, sovereignty, and compliance requirements
* Shift security left

### Automated Security Testing
Static and Dynamic security testing of CI/CD system. 
![Automated Security Testing Diagram](/img/AutomatedSecurityTesting.png)

### Layered Security Approach
![Layered Security](/img/LayeredSecurityApproach.png)

### Public Cloud Reference Matrix

|  | AWS | Azure | GCP | Multi-/Hybrid- Cloud |
| :---: | :---: | :---: | :---: | :---: |
| [SIEM](https://en.wikipedia.org/wiki/Security_information_and_event_management) | [AWS Security Hub + OpenSearch](https://aws.amazon.com/blogs/security/how-to-use-aws-security-hub-and-amazon-opensearch-service-for-siem/)   | [Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/overview) | [Chronicle SIEM](https://chronicle.security/suite/siem/)  | [Splunk](https://www.splunk.com/en_us/products/enterprise-security.html), Sumo Logic, Elastic, more |
| [DDoS](https://en.wikipedia.org/wiki/Denial-of-service_attack) Protection | [AWS Shield Advanced (L3~7)](https://aws.amazon.com/shield/) | [Azure DDoS Protection](https://azure.microsoft.com/en-us/products/ddos-protection) | [Google Cloud Armor](https://cloud.google.com/armor/docs/advanced-network-ddos) | Cloudflare, Fortinet, Akamai, F5, + |
| [Network Firewall](https://www.gartner.com/reviews/market/network-firewalls) | [AWS Network Firewall for VPC](https://docs.aws.amazon.com/network-firewall/latest/developerguide/what-is-aws-network-firewall.html) | [Azure Firewall](https://azure.microsoft.com/en-us/products/azure-firewall/) | [GCP VPC Firewall](https://cloud.google.com/vpc/docs/firewalls) | Checkpoint, Fortinet, Barracuda, + |
| [Web Application and API Protection](https://www.gartner.com/reviews/market/cloud-web-application-and-api-protection) | :---: | :---: | :---: | :---: |
