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

|  | AWS | Azure | GCP | On-Prem |
| :---:   | :---: | :---: | :---: | :---: |
| [SIEM](https://en.wikipedia.org/wiki/Security_information_and_event_management) | [Security Hub + OpenSearch](https://aws.amazon.com/blogs/security/how-to-use-aws-security-hub-and-amazon-opensearch-service-for-siem/)   | [Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/overview) | [Chronicle SIEM](https://chronicle.security/suite/siem/)  | Splunk, Sumo Logic, Elastic, more |
