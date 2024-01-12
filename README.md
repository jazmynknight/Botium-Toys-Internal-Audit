# Botium-Toys-Internal-Audit
NIST CSF audit to provide an overview of the risks Botium Toys may experience due to the company's current security posture
## Scope
Current user permissions set in the following systems: accounting, end point detection, firewalls, intrusion detection system, security information and event management (SIEM) tool.
Current implemented controls in the following systems: accounting, end point detection, firewalls, intrusion detection system, Security Information and Event Management (SIEM) tool.
Current procedures and protocols set for the following systems: accounting, end point detection, firewall, intrusion detection system, Security Information and Event Management (SIEM) tool.
Ensure current user permissions, controls, procedures, and protocols in place align with necessary compliance requirements.
Ensure current technology is accounted for. Both hardware and system access.
## Goals
To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)
Establish a better process for their systems to ensure they are compliant
Fortify system controls
Implement the concept of least permissions when it comes to user credential management
Establish their policies and procedures, which includes their playbooks
Ensure they are meeting compliance requirements
## Risk Assessment
### Current Assets
On-premises equipment for in-office business needs
Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
Internet access
Internal network
Vendor access management
Data center hosting services
Data retention and storage
Badge readers
Legacy system maintenance: end-of-life systems that require human monitoring
#### Does not Have
Least Privilege
Disaster Recovery Plans
Password Policies
Separarion of Duties
Intrusion Detection System
Backups
Manual Monitoring, Maintenance, and Interveiotn for legacy systems
Encryption
Password managmeent system
#### Does Have
Firewall
Antivirus Software
Locks (physical)
CCTV survelliance
Fire detection/prevention
### Risk Description
Inadequare management of assets and no proper controls in place and may not be compliant with US and International regulations and standards.
### Control Best Practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to managing assets. Additionally, they will need to determine the impact of the loss of existing assets, including systems, on business continuity.
### Risk Score
8/10 (high) 
### Compliance Chekclist
PCI DSS - currently all employees have acces to the company's data; Credit card information is not encrypted; the compnay doesn't use encryption to better ensure the confidentiality of customer financial information; no password management in place
GDPR - No encryption to ensure confidientality; current assessts not classified
SOC type 1, SOC type 2 - Controls of Least Privilege and seperation fo duties not in place; no encryption to ensure confidentiality; authorzation needs to be limited to only those who need to access it
