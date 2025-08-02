## What is Zero Trust on Data

Aims to protect data and prevent leakage, acess remain in compliance with security policy

Identifying, Understanding, Controlling, Protecting, Auditing

Protect business critical data, defend against data loss, and assess data, on-premise and off-premise

## Traditional Data Security vs. Data Centric Zero Trust

Traditional Data Security: network perimeter controls data access and not data sensitivity, apply senstive labels on data manually, does not continuously monitor or threat protect

Data Centric Zero Trust: defenses protect data even after leaving controlled environment, strong authentication to request, automation techniques to classify data, continuously monitors and prevent data breach

## Need for Data Centric Zero Trust

Massive Data growth: data volume increasing and ZT limits access to sensitive data and monitors attempts

Increase in lateral movement: public cloud, data centers and remote servers require the need for segmenting resources into isolated zones

Inadequate network and application security: application have intrinsic security vulnerabilities

Need for granular control over what and when users can access resources: fine-grained access controls for greater flexibility

Lesser visibility: identify who/what/how data is access beyond network

Data complexity: information spread across data landscape, centralized management implemented across entire organization

## Considerations

Which type of data used in organization? Structured or unstructured data?

What is state of data, need for protected at rest/use/in-transit?

What is source of data? log, files, servers?

How is data used?

Who is data represented? stored in native format or predefined data model?

## Considerations: Types of Data and State of Data

Unstructured Data: must know what is kept in data, how sensitive it is, who has access to it, limiting access, (business docs, emails, audio/video files)

Structured Data: identify data and locate, controlling access based on standardized format, protective measures in database in place, user prompting, (network logs, online forms)

Data at rest: volume of data is higher and need to be protected the most, encryption, proactive measures of risk data,  protocols apploed, (email messages with attachments, files in one drive)

Data in transit (more vulnerable): Implement firewalls/segmentation when data travels, eavesdropping attacks, network access controls, creation of policies, encryption, (conversations in online meeting)

Data in Use (most vulnerable): only authorized users, mfa, identity management

## Benefits of Data Centric Zero Trust

Accelerated Recovery: important assets identified, data recovered only to allowed users

Risk Management: reduce risk within perimeters, examine security gaps, detect anaomalies

Data Integrity: protect data against threats using (IAM) Identity and Access Management, micro-segmentation and isolating workloads

Compliance: (SLA) Service Level Agreement, least privilege, GDPR, HIPPA

Confidentiality: Define measures to be implemented, ensuring authentication, endpoint security, hardening infrastructure

## Data Centric Zero Trust Techniques

Data catalog and risk management: organize inventory, collection of activites, know what data they have, ensure processes are put in place,  landscape asssess for association to data loss

Data classification and tagging: identify nature of data and categorize type, who should have access, policies put in place, adding labels to data, relies on metadata (PII)

## Data Centric Zero Trust Techniques (Continued)

Encryption, data loss prevention, tokenization

Encryption alters data to look like random data, does not prevent contreception

Symmetric encryption more common with one key to encrypt and access (best for large sets of data)

Asymmetric encryption uses two keys, sender encrypts with private key, and sender uses public key to decrypt data (email communication/e-commerce)

Data loss prevention prevents exfiltration and breach, monitor acrross cloud and on-premise, categorize content, automated protection policies, end point protection

Tokenization replaces sensitive data with non-sensitive equivalent called tokens, primarily used to protect transactional, help to maintain, no correlation to original data, substitue with random numbers

Data access control determined by roles, groups, functions, and availability, discretionary access control guarantee data is accessible while not jeopardizing data sensitivity

Context-centric methods use environmental factors, location context

Role based access control is determine by privileges on role

Attribute-based access control defines permissions based on attributes, customize granular data access privileges, easy implementation

Trusted Data Format file format, file locking, and access relocation


















