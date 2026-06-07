# Exposed Debug & Health Endpoints – SweetHawk

**Category:** Information Disclosure

**Organization:** SweetHawk

**Status:** Fixed

**Recognition:** Security Researcher Hall of Fame

## Overview

During a security assessment conducted under SweetHawk's Responsible Disclosure Program, I identified publicly accessible debugging and health monitoring endpoints that exposed internal application and infrastructure information without authentication.

The exposed endpoints revealed operational details that could assist attackers during reconnaissance and target profiling activities.

## Discovery Process

While reviewing publicly accessible assets, I identified diagnostic and monitoring functionality that was accessible without authentication.

The exposed endpoints returned information related to:

* Application configuration
* Environment details
* Deployment information
* Internal service configuration
* Application feature metadata

The issue was verified through passive observation without attempting to modify data, bypass controls, or access unauthorized resources.

## Security Impact

Although the exposed information did not directly provide system access, it revealed internal operational details that could be leveraged during subsequent attack phases.

Potential risks included:

* Infrastructure reconnaissance
* Technology stack identification
* Internal environment mapping
* Improved attack planning
* Increased effectiveness of targeted attacks

Information disclosure findings are often considered low severity individually but can become valuable when combined with other weaknesses.

## Responsible Disclosure

The issue was responsibly reported to the SweetHawk Security Team together with supporting evidence and remediation recommendations.

Testing was limited to observation of publicly exposed information, and no intrusive actions were performed.

## Outcome

The SweetHawk Security Team reviewed the report and acknowledged the finding.

The issue was remediated, and I was recognized on the SweetHawk Security Researcher Hall of Fame for contributing to the security of the platform.

## Skills Demonstrated

* Reconnaissance
* Information Disclosure Testing
* Security Assessment
* Risk Analysis
* Responsible Disclosure
* Technical Reporting
