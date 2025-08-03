## Zero Trust in a Cloud Environment

Based on comprehensive unified strategy, micro segmentation, allow users to have consistent experience, using multiple cloud providers

Challenges of security policies spanning on-premise and public clouds, security risk migrating to public cloud providers (require re-design), multiple cloud proivders add more complexity

What tyoe of data? How is it classified? What is source of data? Who is expected to access data?

## Using Cloud Based Options for Zero Trust

Infrastructure: Organizations just have to worry about OPEX values rather than in-house infrastructure, less work to do and provider authenticates every user, additional services like VLANs and VPNs with related compliance

Utilizing Software as a Service: Application data is considered company confidential, difficult to control access to ensure not vulnerable to attacks, SaaS Security Posture Management (SSPM)

## Common Implementation Strategies

Deploy SASE: Secure Access Service Edge (SASE) moves networking to cloud instead of data centers, secure remote access, centralized management, single cloud-based solution

Employ Microsegmentation: Creating zones in data centers or cloud environments to isolate workloads, custom policies for each, provide visibilityinto all network traffic, 

Incorporate MFA: MFA is effective when combined with RBAC or ABAC, can protect endpoint is cloud based or software or BYOD

Consider Software Defined Perimeter: (SDP) assigns user access to internal applications based on user's identity (identify-centered)

Use Kubernetes: Kubernetes cluster has an API service which exposes an HTTP API, API can modify namespaces and services, Kubernetes orchestrator is an additional attack surface that needs to be protected (Data Plane and Control Plane) (horizontal and vertical traffic)

Combine Kubernetes and Service Mesh: Large-scale containerized workloads, Authentication/Authorization/Auditing/Logging, control communication between different components

## Best Practices 

Security Tools: provider offers tools for environment and shared responsibility between cloud provider and organization

Monitoring: inspect all traffic, identify unexpected behavior, adjust security policies

Protect Surface: Need to be defined for microsegmentation, policies, RBAC or ABAC, in-house functionality should be used

## Use Case - Migration

Migration Applications: who will be accessing applications? What protections needed? What devices will access them? How is data being used?

## Use Case - Kubernetes

Kubernetes: How to maintain consistency? Cluster misconfiguration can cause security vulnerabilities and each new container adds potential attack target




















