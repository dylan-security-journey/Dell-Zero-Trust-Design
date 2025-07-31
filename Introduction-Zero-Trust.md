## What is Zero Trust?

Zero trust is a dynamic methodology, moves defense from static (network-based perimters) to focus on users/assets/resources, assumes no implicit trust is granted to users/assets

Never trust, always verify, have zero trust in a digital system, explicit control of their IT environment

## Importance  of Zero Trust

Evolution of the Perimeter: Security has expanded beyond enterprise network, lots of data/application moving outside network causing dynamic situation where attacks can come from inside & outside the network

Perimeter-based defenses that are traditional like VPNs, DMZs, Firewalls, ACL's are no longer sufficient in modern environments (Data centers are susceptible to lateral movements like VLAN hopping even if internal traffic is segmented)

Fragmented Security Policies and Tools: complex vendor landscapes and supply chain require more streamlined approach to security, traditional security models use siloed approach to threat prevention, security tools misconfigured

Policies not well defined, increase cost in hardware and overhead, limitied visibility, critical to define and enforce security policies across organization

Evolving Threat Landscape: Moving target, increase in attack frequency & sophistication, AI adoption leads to more concerns with data poisoning/privacy leakage, target all data/valuables, complex layers of IT like IaaS, SaaS, Paas and number of devices

Shift Towards Remote and Hybrid Workforce: Mobile workforce from anywhere, unsecured wifi networks, no longer verified/controlled, BYOD (Bring your own Device), employees forget basic hygiene skills and using their devices to access work networks

## Traditional Security vs. Zero Trust

Traditional Security: VPNs, Trust but verify (bad guys outside firewall and good guys inside firewall)

Zero Trust: Focus on users, assets, and resources (whether internal or external, continuously verified)

## How Does Zero Trust Work?

Ensures that (DAAS) data, application, asset, and services is protected with security capabilities that move along protect surface, provides zones for visibility (secure, manage, monitor)

Verify Explicitly: Always verify users and network requests regardless of location or access history (does not matter if you had access before) (trusted until proven otherwise)

Use least priviledged access: Limit user access to resources they absolutely need for current role, access is granular and per session

Assume Breach: Segmnet user access, encryption, continuously monitor and strengthen defenses 

## Benefits of Zero Trust

Prevent unauthorized access: adaptive identity-based access control, continuously verify aand authenticate regardless of location or time (role based and attribute based)

Reduce the impact radius: Mitigates most attack vectors and surface due to 'trust none' policy, can't pivot freely within network

Enhance response effectiveness: Automate and orchestrate security response quickly, not to overlook anything

Curb freedom of movement: focused on priviledged access management to control how it's used and revoked

Avoid too many on-ranmps: 'comply to connect' limits employees to log into sensitive systems on a unsecure network

Minimize operational risk: systems not being patched, automation of updates

## Application Areas of Zero Trust

Multicloud: reliance on enterprise perimeter becomes liability, ZT does not differentiate between boundaries

Containerized Software & Micro-services: containers isolated but share resources, assigns identity to every service instance                                                                                             

Internet-of-Things: new devices accessing the network, varying levels of trust

5G/6G: Data transfer rate increase

Varied Access needs: temporary user access, given access to only resources needed

Cross-enterprise collaboration: Enroll in federated ID management system

Remote work/mobile management: most organizations support remote workforce

## Keys for a Successful Zero Trust Implementation

Embrace Change: Applying change management practices and identifying culture

Having end-to-end visibility: visibility to know what you have and how it's used 

Business collaboration: Communication across siloed teams in and outside IT organization, Close collaboration helps understand purpose and alignment

Designing for adaptability and scalability: flexible approach

Taking the first step: Establishing proper governance and knowing where to start

## Introduction to Zero Trust Architecture

(ZTA) framework of the tools and technologies used to deploy and build Zero Trust environment

Rules/policies added to original, operation concepts, capability planning, identify what work best for an organization Kipling method (who, what, when, where, why, how)

## NIST Zero Trust Architecture

Provides a roadmap, different ways to implement based on NIST guidelines, (Enhanced identity governance, logical microsegmentation, network-based segmentation), operated onsite or through cloud-based

## Components of NIST Zero Trust Architecture

CDM System: Continuous Diagnostics and Mitigation gathers all information related to access request and feed it to PD, applies configuration and provides PE with information

Industry Compliance: Check for regulatory and requirements a company must follow

Threat Intelligence: gather data on existing and potential threats to policy engine 

Activity Logs: keep track of relevant information to every single access request (for granted and denied access)

Data Access Policy: governing regulations applied when accessing a resource and helps PDP

PKI: Public Key Infrastructure distribution of digital certificates and encryption

ID Management: manages user identity records and authorize who has access to resources

SIEM System: Security Information and Event Management, carrying out analysis followed by corrective/preventive measures

Policy Enforcement Point: Brawn behind any access decision, enabling and terminating 

Policy Decision Point:  Drives access decisions, policy engine makes ultimate decision, policy administrator configures PEP according to PE decisions

## US DoD Trust Reference Architecture

U.S. Department of Defense (DoD) focuses on data-centric design, maintaining services independent from each other, 

Seven Pillars: Users, Devices, Applications & Workloads, Daa, Network & Environment, Automation & Orchestration, Visibility & Analytics

Reference architecture identifies 45 capabilities and further divided into 152 activities

Two levels of maturity: Target level: minimum of 91 activities, Advanced Level includes complete set of 152 activties that enable adaptaive responses 

## CISA Zero Trust Maturity Model

Cybersecurity and Infrastructure Security Agency provide situational awarenesss

Five pillar of Zero Trust: Identity, Devices, Networks, Applications & Workloads, Data

Maturity levels across the pillars: Traditional, Initial, Advanced, Optimal

## Which Architecture to Use?

What are the security goals? 

How well does architecture identify threats and assess risk levels?

What are recommended control approaches?

What is total cost of implementing architecture?

## Differences between Zero Trust Reference Architecture

NIST | Advantage: segmentation of data, stronger user identification | Disadvantages: More users to manage, require reccuring maintenance

U.S. DoD | Advantage: less vulnerability, improved compliance | Disadvantages: Increase application complexity, disrupt productivity

CISA | Advantage: strong data security, security orchestration | Disadvantages: More applications to be protected, time and effort into creating ZTA

## Other Zero Trust Standards & Regulations

National Cybersecurity Council (NCSC):

General Data Protection and Regulation (GDPR): 

