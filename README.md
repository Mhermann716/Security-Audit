# Botium Toys Controls and Compliance Checklist

## Controls Assessment Checklist
| Control | Yes | No | Explanation |
| ------- | --- | -- | ----------- |
| **Least Privilege** | | X| Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach. |
| **Disaster Recovery Plans** | |X | There are no disaster recovery plans in place. These need to be implemented to ensure business continuity. |
| **Password Policies** | |X | Employee password requirements are minimal, which could allow a threat actor to more easily access secure data/other assets via employee work equipment/the internal network. |
| **Separation of Duties** | |X | Needs to be implemented to reduce the possibility of fraud/access to critical data, since the company CEO currently runs day-to-day operations and manages the payroll. |
| **Firewall** |X | | The existing firewall blocks traffic based on an appropriately defined set of security rules. |
| **Intrusion Detection System (IDS)** | |X | The IT department needs an IDS in place to help identify possible intrusions by threat actors. |
| **Backups** | |X | The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity. |
| **Antivirus Software** |X | | Antivirus software is installed and monitored regularly by the IT department. |
| **Manual Monitoring, Maintenance, and Intervention for Legacy Systems** | |X | The list of assets notes the use of legacy systems. The risk assessment indicates that these systems are monitored and maintained, but there is not a regular schedule in place for this task and procedures/policies related to intervention are unclear, which could place these systems at risk of a breach. |
| **Encryption** | |X | Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information. |
| **Password Management System** | |X | There is no password management system currently in place; implementing this control would improve IT department/other employee productivity in the case of password issues. |
| **Locks (Offices, Storefront, Warehouse)** |X | | The store’s physical location, which includes the company’s main offices, store front, and warehouse of products, has sufficient locks. |
| **Closed-Circuit Television (CCTV) Surveillance** |X | | CCTV is installed/functioning at the store’s physical location. |
| **Fire Detection/Prevention (Fire Alarm, Sprinkler System, etc.)** |X | | Botium Toys’ physical location has a functioning fire detection and prevention system. |

## Compliance Checklist

### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice | Yes | No | Explanation |
| ------------- | --- | -- | ----------- |
| **Only authorized users have access to customers’ credit card information.** | |X | Currently, all employees have access to the company’s internal data. |
| **Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment.** | |X | Credit card information is not encrypted and all employees currently have access to internal data, including customers’ credit card information. |
| **Implement data encryption procedures to better secure credit card transaction touchpoints and data.** | |X | The company does not currently use encryption to better ensure the confidentiality of customers’ financial information. |
| **Adopt secure password management policies.** | |X | Password policies are nominal and no password management system is currently in place. |

### General Data Protection Regulation (GDPR)

| Best Practice | Yes | No | Explanation |
| ------------- | --- | -- | ----------- |
| **E.U. customers’ data is kept private/secured.** | |X | The company does not currently use encryption to better ensure the confidentiality of customers’ financial information. |
| **There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach.** |X | | There is a plan to notify E.U. customers within 72 hours of a data breach. |
| **Ensure data is properly classified and inventoried.** | |X | Current assets have been inventoried/listed, but not classified. |
| **Enforce privacy policies, procedures, and processes to properly document and maintain data.** |X | | Privacy policies, procedures, and processes have been developed and enforced among IT team members and other employees, as needed. |

### System and Organizations Controls (SOC Type 1, SOC Type 2)

| Best Practice | Yes | No | Explanation |
| ------------- | --- | -- | ----------- |
| **User access policies are established.** | |X | Controls of Least Privilege and separation of duties are not currently in place; all employees have access to internally stored data. |
| **Sensitive data (PII/SPII) is confidential/private.** | |X | Encryption is not currently used to better ensure the confidentiality of PII/SPII. |
| **Data integrity ensures the data is consistent, complete, accurate, and has been validated.** |X | | Data integrity is in place. |
| **Data is available to individuals authorized to access it.** | |X | While data is available to all employees, authorization needs to be limited to only the individuals who need access to it to do their jobs. |

## Recommendations

Multiple controls need to be implemented to improve Botium Toys’ security posture and better ensure the confidentiality of sensitive information, including: Least Privilege, disaster recovery plans, password policies, separation of duties, an IDS, ongoing legacy system management, encryption, and a password management system.
