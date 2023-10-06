# Vulnerabilities Assessment Report
Description: This Assessment is a mock assessment for a Vulnerabilities Assessment Report. The assessment is based on the scope and the system description and I was tasked with finding three possible threat actors, assessing the risk for each and then providing possible solutions for those threat actors.
 
**Project: System Vulnerability Assessment**

**System Description:**
Our server hardware comprises a powerful CPU processor and 128GB of memory, running on the latest version of the Linux operating system. It hosts a MySQL database management system and has a stable network connection using IPv4 addresses. The server interacts with other servers on the network and has SSL/TLS encrypted connections for security purposes.

**Scope:**
The scope of this vulnerability assessment focuses on the current access controls of the system. The assessment period covers three months, from June 20XX to August 20XX, and we are using NIST SP 800-30 Rev. 1 to guide the risk analysis of the information system.

**Purpose:**
Our database server is critical to our marketing operations as it stores large amounts of data, including customer PII, campaigns, and analytical data. Therefore, it is essential to ensure the system is secure to prevent unauthorized access to sensitive information, primarily as the server interacts with other servers on the network.

**Risk Assessment:**

| **Threat Source** | **Threat Event**                        | **Likelihood** | **Severity** | **Risk** |
| ------------------ | ---------------------------------------- | -------------- | ------------ | -------- |
| Hacker             | Obtain sensitive Information via Exfiltration | 3              | 3            | 9        |
| Employee           | Disrupt mission-critical operations        | 2              | 3            | 6        |
| Customer           | Alter/Delete critical information        | 1              | 3            | 3        |


**Approach:**
We have assessed the data storage and management methods of the business and weighed the likelihood of a threat occurrence against the impact of potential events on day-to-day operational needs. To address the open access permissions on the system, we recommend implementing authentication, authorization, and auditing measures. Strong passwords, role-based access controls, and multi-factor authentication will restrict user privileges and prevent unauthorized access to the server. Additionally, we suggest updating the encryption of data in motion to use just TLS instead of SSL and implementing IP allow-listing to corporate offices to prevent random users on the internet from connecting to the database.

**Remediation Strategy:**
Our remediation strategy focuses on implementing the measures mentioned above to prevent unauthorized access to our server and ensure the security and privacy of our sensitive information. We will also conduct regular vulnerability assessments of our system to promptly identify and address potential threats.
