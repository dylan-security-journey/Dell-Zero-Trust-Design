## Introduction to Zero Trust in Networks

Zero Trust Network (ZTN) implement context-aware policies to athorize access, network presumed hostile, vulnerable to both interal and external, network locality insufficient to trust, authenticated and authorized, policies should be adaptive

## Zero Trust Network Techniques

key techniques include microsegmentation, access control, encryption, and data flow mapping

Microsegmenation: divides network up to prvent spread of lateral contamination through organization, granular and role-based access for unified policy enforcement, L4/L7 firewalls, intrusion detection and prevention, sandboxing


Access Control: Determines who has access to data/applications dependenant on location/role/attributes

Encryption: Encodes data and makes it unreadable to hackers, secure data in use and at rest or transit, data in-flight encryption provided by SSL (Secure Socket Layer)

Data Flow Mapping: Flow of data routes and it's location 

## What is Zero Trust Network Access?

(ZTNA) creates identity-based and context-based around applications, masks network location (IP address) 

## Features of ZTNA

context-aware by time or geographic location

continual verification, handle real-time dynamic policies based on user behavior, protect all business application, centralized management, identify applications depending on APP-IDs, extended detection and response

## Why ZTNA?

Exposed IP Address: VPN/firewalls exposes entire network

Layered Security Approach: seamless and well integrated 

Distributed Access Controls: pn-premises and off-premises (cloud scenarios)

Authentication & Privilege Access Management: verify identity and provid access capabilities beyond standard user (MFA), minimum neccessary to perform activities

## Benefits of Zero trust Network Access

Creates Virtual Overlay Network: IP addresses never exposed on internet (encrypted)

Elevates End-User Experience: access cloud and private applications, fast direct access

Improved Data Protection: enforced policies (DLP) Data Loss Prevention, regardless of where data is in

Improved Security Network Visibility: monitor from centralized dashboard, who is using what

Protect the Remote Workforce: Firewalls/porxies/DMZs not enough, security principles additional layer of protection

Avoid Lateral Movements: software-defined perimeters, Endpoint Detection and Response (EDR) to Extended Detection and Response (XDR)

## Challenges of ZTNA

Mapping access rights: who or what need access (ongoing effort)

Existing product and services: establish a deployment procedure into current architecture

Resistance from end users: opposition for need to deploy

Cost: can be expensive, when something is already working like VPN solution

Policy beyond laptops/desktops/devices: consent of non-managed devices 

## Differences between VPNs and ZTNA

Virtual Private Network (VPN) vs Zero Trust Network Access

Virtual Private Network (VPN): allows complete private network access, operate at layer 3, verify login keys, no visbility to user action, lack of application level control, does not consider risk factors, not designed to increasingly workforce environment, usage of on-premise VPN servers

ZTNA: operate at application layer, limit individual access, prevent lateral movement, monitoring of user behavior, secure data, evaluates device security posture, adaptive access depending on device trust, direct-to-app connections, mostly offered through cloud 

## SASE vs ZTNA

SASE (Secure Access Service Edge): based on ZT, combines point solutions like ZTNA/FWaaS/SD-WAN into single integrated service (complete approach)

ZTNA: technique for handling authenticated user access, no such thing as trustworthy user, trust algorithms

SASE: complete network and security services, identity-driven

## Types of ZTNA

Endpoint Initiated (agent based): software agaent on each device, works well with SDP (CSA > SDP), sends request (time/location) to ZTNA controller, ZTNA controller sends a list of approved applications, gateway secures so not accessed on internet

Service Initiated Architecture: resides in cloud and doesn't need agent to be installed, authenticated by cloud service provider and redirected to identity management, useful in organizations with BYOD (HTTP & HTTPS), application connects to ZTNA connector, ZTNA connector to broker proxy, user authenticate with provider/broker, proxy prevents direct access


## Implementation of ZTNA

Endpoint initiated and service initiated can be implemented in various ways

Gateway Integration: part of network gateway, endpoint initiated is mainly used with gateway based on access control policies

Secure SD-WAN: centralized access management, service initiated geneally use Secure SD-WAN, difficult to adapt dependent on development of different vendors

## Implementation Steps for ZTNA

trust broker validates identity and forbids lateral movement

Identify: Identify devices that need access, Identity and Access management (SSO) (Okta)

Define Policy: set-up access controls, (NGFW-Micro segmentation)

Enforce: test policies and implement it

Monitor: continuously track policy violation and insights on encrypted communication, OpenManager Network Manager

Maintain: continue to apply ZT policies and perform audits, AIOps platforms

## Considerations for ZTNA

Vendor Specialization:  search for vendor that meets needs of business goals or specialize in one area of needs

Level of Implementation: some have parts of ZT like IdP while others need entire ZTNA from scratch

Support for legacy applications: few ZTNA vendors operate with specific IdP while others are IdP-agnostic meaning they can integrate with any IdP (endpoint protection providers)

## Best Practices

Consistent security policy: same degree of authentication regardless of location or application

Visibility: decrypt traffic to analyze malicious behavior and data exfiltration

Validate: continuously validate users/applications

Zero trust mindset: never trust, always verify























































