# Multi-Finding Security Assessment – GEA

**Category:** API Security / Access Control / Information Disclosure

**Organization:** GEA

**Status:** Fixed

**Recognition:** Hall of Fame

## Overview

During security research conducted against publicly accessible GEA development assets, I identified multiple security issues affecting API services and development infrastructure.

The findings included broken access control weaknesses, exposed configuration data, and publicly accessible API documentation that disclosed internal system architecture.

All issues were responsibly reported to the GEA Product Security Team and subsequently addressed.

## Discovery Process

The assessment focused on externally accessible development environments and API services.

Through asset discovery, endpoint enumeration, and manual security testing, multiple weaknesses were identified that exposed internal application structure and operational information.

The identified issues affected different services but shared a common theme: sensitive functionality and infrastructure details were accessible without appropriate access controls.

## Key Findings

### 1. Broken Access Control (IDOR)

An API endpoint exposed internal organizational data through direct object references without enforcing authentication or authorization controls.

The issue allowed access to structured records associated with internal entities and system resources.

**Category:** Broken Access Control (IDOR)

---

### 2. Internal Configuration Exposure

A publicly accessible configuration endpoint disclosed detailed application settings and infrastructure information.

Exposed information included:

* Service configuration details
* Administrative functionality mappings
* Authentication configuration
* Access control metadata
* Internal service references

**Category:** Information Disclosure

---

### 3. Public IoT API Documentation Exposure

An IoT-related API service exposed interactive API documentation and schema definitions without authentication.

The documentation revealed operational endpoints associated with device management, deployment workflows, and configuration management.

**Category:** Sensitive API Exposure

## Security Impact

The findings collectively increased the attack surface of the affected environment by exposing internal architecture, application workflows, and operational services.

Potential risks included:

* Infrastructure reconnaissance
* Attack surface mapping
* Access control analysis
* Identification of sensitive functionality
* Facilitation of future attack paths

While the findings affected development services, they demonstrated the importance of restricting access to internal APIs, configuration endpoints, and operational documentation.

## Responsible Disclosure

All findings were reported directly to the GEA Product Security Team through their responsible disclosure process.

Testing was performed in a safe and non-intrusive manner.

No data was modified, no privileged actions were performed, and no attempt was made to exceed the scope necessary for vulnerability validation.

## Outcome

The GEA Product Security Team reviewed and remediated the reported issues.

In recognition of the contribution, I was added to the GEA Security Hall of Fame.

## Skills Demonstrated

* API Security Testing
* Access Control Review
* Information Disclosure Analysis
* Attack Surface Mapping
* IoT Security Assessment
* Reconnaissance
* Responsible Disclosure
* Technical Reporting
