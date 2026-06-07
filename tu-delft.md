# Public Repository Enumeration – TU Delft

**Category:** Information Disclosure / Reconnaissance

**Organization:** Delft University of Technology (TU Delft)

**Status:** Fixed

**Recognition:** Hall of Fame

## Overview

During a security review of publicly accessible TU Delft assets, I identified an information disclosure issue within a repository management interface. The application exposed internal repository names and project identifiers without requiring authentication.

While no repository content was accessed, the exposed information provided insight into internal development projects and infrastructure components.

## Discovery Process

The finding was identified through reconnaissance and asset enumeration of publicly accessible university systems.

During testing, I observed that a repository management interface was accessible without authentication and displayed multiple internal repository names associated with research and development projects.

The issue did not allow direct access to repository contents; however, it disclosed valuable internal information that could be leveraged during further reconnaissance activities.

## Security Impact

Exposure of internal repository names can provide attackers with valuable intelligence about an organization's technology stack, development environment, and ongoing projects.

Potential risks included:

* Identification of internal research initiatives
* Mapping of development infrastructure
* Correlation with other exposed services
* More targeted phishing or social engineering campaigns
* Improved reconnaissance for future attack paths

## Responsible Disclosure

The issue was reported directly to the TU Delft ICT Security Team through their Responsible Disclosure Program.

To remain within the scope of responsible testing, no attempt was made to access repository contents or perform any intrusive actions beyond observing publicly exposed information.

## Outcome

The TU Delft Security Team acknowledged the report, investigated the issue, and remediated the exposure.

As recognition for the responsible disclosure, I was included in the TU Delft Security Researcher Hall of Fame.

Hall of Fame : https://www.tudelft.nl/en/hall-of-fame

## Skills Demonstrated

* Reconnaissance
* Asset Discovery
* Information Disclosure Testing
* Security Assessment
* Responsible Disclosure
* Technical Reporting
