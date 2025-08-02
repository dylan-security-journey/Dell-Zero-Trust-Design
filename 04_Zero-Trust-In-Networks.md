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






























































