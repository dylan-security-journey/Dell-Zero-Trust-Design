## Identity Based Zero Trust

Business resource risk exposure, human and non-human users risk

Identity based zero trust protects diverse users and myriad access points, secures IT resources by establishing following criteria

Identity-centric approach as anchor of security policy creations, user 

authenticity validated: (MFA), biometrics, token, certificates

Least Privilege and Default Access Deny, access control

Positive Verification: ensured only authorized and authenticated

Contextual awareness: user roles, time of day, location, device health

User accountability: linking their activities to their identities

## Identity Based Zero Trust Deployment

Include all users and partners,user experience impact minimal, retain current user settings/permissions, balance resource protection

Identity based zero trust policy types: require mfa, allow apporved moble apps, block clients that do not support modern application,  require users to change password, apply protection policies to device and application

Starting Point: Resource access policies, device compliance policies, application protection policies,  allow approved mobile apps only

Mid-Journey Point: allow approved mobile apps only, block clients that do not support modern application, require compliant pcs and mobile devices, apply protection policies  for app data protection

Approaching Journey: require high-risk users to change their passowrds, require all users, device compliant

## Identity Based Zero Trust Techniques

Single-Sign-On (SSO): trusted relationship between IdP (Identity provider) and SP (Service Provider), verified token exchange

Multifactor authentication (MFA): uses more than one factor of authentication, (know,have,are) 

Privileged Access Management (PAM): help access for elevated users, managers, administrators, machine user accounts, least privilege access, Human user accounts: admin, domain, emergency, business, socket shell | Machine user accounts: application, service, secret

Role-based Access Management (RBAC): restrict access based on roles, separation of duties, ABAC users who they are and not what they do and also location

Open Device Authentication (OAuth 2.0): open standard, browserless and text limited devices, SSO 

Mobile Device Management (MDM): restricts access to only authorized mobile devices

Extended Detection and Response (XDR): collects and correlates endpoints (SIEM) does not replace SIEM or SOAR, invoked machine learning and automated incident response

Federated Identity Management: trust domains across business units, allow users to work together across domains, multidomain access (third-party vendor same sign on as enterprise)

SAML is open standard exchanging authentication data between parties (XML assertion)

OpenID: open standard that uses third-party authentication services

## Other Techniques

Unified Endpoint Management (UEM): securely manage from single console, through agent and agentless management, supports and manages BYOD

Integrated ICAM: Identity, Credential, and Access Management set of principles/policies/tools, support PKI (public key infrastructure) systems

Conditional User Access: considers signals from different sources, signals regarding user location/IP address

Continuous Authentication: validate users throughout an entire session, NPEs (nonperson entities) ongoin, behavior data

## Introduction

improve risk visibility by analyzing each access request on every entry point, elevates decision-making process to entity, better detection of security threats and anomalies

## Stages of Identity Based Zero Trust

Fragmented Identity: several (IAM) making it difficult to maintain centralized view and control over access rights

Unified IAM: providing SSO and centralizing procedures (consolidation)

Contextual Access: After centralized processes of (IAM) established, tracking of identity/device health, location, time, behavior contibute to real-time decision making to ensure proper levels of access are granted

Adaptive: Use of machine learning to monitor and adapt to behavioral analytics and unusual user patterns

## Strategies

Continuous monitoring/auditing

Risk Assessment

Enforcement of real-time access policies

## Continuous Monitoring and Auditing

Monitoring: detect potential threats in real time, user activity, device health (security pateches), network behavior (unusual traffic flow)

Auditing: capturing activities of users and devices to generate audit logs, track compliant and non-compliant users

## Risk Assessment

contextual information plays an important role in providing access rights (proactive and adaptive approach)

Identify potential vulnerabilities, prioritize security measures, optimize access control policies (least privilege)

## Enforcement of Real-Time Access Policy

make access decisions based on current context and user attributes

Enforce policies, reduce attack surface 

## Implementation Steps

Discover: Discovering all digital resources and information, continuous activity to support change

Classify and Protect: Classif to group sensitive information together, protect is implemeting MFA and protecting the classified resources with encryption (firewalls)

Monitor: visibility to gain knowledge through (SIEM) security information and event management, (UEBA) user and entity behavior analytics

Respond: Incident response and remediation activites, isolating, apply patches

Recover: Restoring data from backups, perform post-incident analysis

Adapt: refining and adjusting, modifying entry protocols, and recommended methodologies

















