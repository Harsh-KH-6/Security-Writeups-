# Exposed Development API & Internal Endpoints – University of San Diego

**Category:** API Security / Information Disclosure

**Organization:** University of San Diego

**Status:** Fixed

**Recognition:** Security Team Acknowledgement & Appreciation Letter

## Overview

During a security assessment of publicly accessible assets, I identified a development API environment that was accessible without authentication and exposed internal application functionality through publicly available API documentation.

The environment revealed backend API structures, application integrations, and diagnostic endpoints that were not intended for unrestricted public access.

## Discovery Process

While performing reconnaissance on publicly accessible systems, I discovered a development API instance exposing interactive API documentation.

The documentation allowed unauthenticated users to enumerate application functionality and gain visibility into backend services and integrations.

Further review identified publicly accessible diagnostic endpoints that disclosed operational status information about connected enterprise systems.

Testing was limited to passive observation and validation of exposed functionality without attempting unauthorized access to data or privileged operations.

## Security Impact

The exposed development environment increased the attack surface by providing detailed visibility into backend application architecture and available API functionality.

Potential risks included:

* API endpoint enumeration
* Exposure of internal application structure
* Disclosure of backend integrations
* Increased reconnaissance opportunities
* Improved attack planning against exposed services

While no unauthorized access was performed, publicly available API documentation and diagnostic endpoints provided valuable information that could assist an attacker during future attack stages.

## Responsible Disclosure

The issue was reported directly to the University of San Diego security team through a responsible disclosure process.

The report included observations regarding publicly accessible API documentation, diagnostic endpoints, and recommendations for reducing exposure of development resources.

## Outcome

The University of San Diego security team reviewed the report, validated the findings, and remediated the identified exposure.

Following remediation, I performed verification testing to confirm that the reported issues had been successfully addressed.

In recognition of the contribution, the University's Information Technology Services team issued an official appreciation letter acknowledging the quality of the report, the remediation validation process, and the responsible disclosure effort.

## Recognition

The appreciation letter highlighted:

* Thorough vulnerability reporting and documentation
* Assistance with validating remediation efforts
* Professional responsible disclosure practices
* Contribution toward improving the security posture of the University

**Appreciation Letter:**
https://drive.google.com/file/d/1nyS55sWqQElFrxllJBdig-Nj7GgCJgo8/view

## Skills Demonstrated

* API Security Testing
* Reconnaissance
* Information Disclosure Analysis
* Attack Surface Mapping
* Responsible Disclosure
* Technical Reporting
* Remediation Validation
