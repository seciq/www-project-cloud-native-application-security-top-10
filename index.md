---
layout: col-sidebar
title: OWASP Cloud-Native Application Security Top 10
site_side: true
tags: cloud-native-application-security
level: 4
type: documentation
auto-migrated: 0
pitch: The primary goal of the OWASP Cloud-Native Application Security Top 10 document is to provide assistance and education for organizations looking to adopt Cloud-Native Applications securely. The guide provides information about what are the most prominent security risks for Cloud-Native applications, the challenges involved, and how to overcome them.
---
[![Follow on Twitter](https://img.shields.io/twitter/follow/owaspcloudnati1?label=Follow%20%40owaspcloudnati1&style=social)](https://twitter.com/owaspcloudnati1)
## Overview
Cloud native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach. Cloud-Native applications are a fundamentally new and exciting approach to designing and building software. However, it also raises a completely new set of security challenges. For example, when you move to a microservice model, end-to-end visibility, monitoring and detection become more complex and difficult to execute.
<br>
<br>
The primary goal of the OWASP Cloud-Native Application Security Top 10 document is to provide assistance and education for organizations looking to adopt Cloud-Native applications securely. The guide provides information about what are the most prominent security risks for cloud-native applications, the challenges involved, and how to overcome them.

## Interim List of Risks - Currently Under Review!

The OWASP Cloud-Native Top 10 list is currently under development (July 2021). As part of our effort to collect feedback, we are presenting an interim list below. Please feel free to contact the project leaders if you have any feedback. 

#### CNAS-1: Insecure cloud, container or orchestration configuration
Examples:
 * Publicly open s3 bucket
 * Container runs as root
 * Container shares resources with the host (network interface, etc.)
 * Unauthenticated Kubernetes console access 
 * Insecure Infrastructure-as-Code (IaC) configuration

#### CNAS-2: Injection flaws (app layer, cloud events, cloud services)
Examples:
 * SQL injection
 * XXE
 * NoSQL injection
 * OS command injection
 * Serverless event data injection
 * ...

#### CNAS-3: Improper authentication & authorization
Examples:
 * Unauthenticated API access on a microservice
 * Over-permissive cloud IAM role
 * ... 

#### CNAS-4: CI/CD pipeline & software supply chain flaws
Examples:
 * Insufficient authentication on CI/CD pipeline systems
 * ...

#### CNAS-5: Insecure secrets storage
Examples:
 * Kubernetes secrets stored unencrypted
 * API keys or passwords stored unencrypted inside containers
 * Hardcoded application secrets
 * ...

#### CNAS-6: Over-permissive or insecure network policies
Examples:
 * Over-permissive pod to pod communication allowed
 * Internal microservices exposed to the public Internet
 * No network segmentation defined
 * ...

#### CNAS-7: Using components with known vulnerabilities
Examples:
 * Vulnerable 3rd party open source packages
 * Vulnerable versions of application components
 * Use of known vulnerable container images
 * ...

#### CNAS-8: Improper assets management
Examples:
 * Undocumented microservices & APIs
 * Obsolete & unmanaged cloud resources
 * ...

#### CNAS-9: Inadequate 'compute' resource quota limits
Examples:
 * Resource-unbound containers
 * Over-permissive request quota set on APIs
 * ...

#### CNAS-10: Ineffective logging & monitoring (e.g. runtime activity)
Examples:
 * No container or host process activity monitoring
 * No network communications monitoring among microservices
 * ...

## Getting Involved
You do not have to be a security expert or a programmer to contribute. Contact the project leader(s) to get involved, we welcome any type of suggestion and comments. Possible ways to contribute:
 * We are actively looking for organizations and individuals that will provide vulnerability prevalence data
 * Translation efforts (later stages)
 * Individuals and organizations that will contribute to the project will be listed on the acknowledgments page.

## Project Sponsors
The OWASP Cloud-Native Application Security Top 10 project is supported by [Oxeye](https://oxeye.io)
<br>
[![Oxeye](assets/images/oxeye_logo.png)](https://oxeye.io/)
