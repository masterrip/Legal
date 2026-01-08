NOVATOR Legal Hub
Universal License System for All Projects
Quick Overview
Single source for all legal documents across NOVATOR projects. Modular license system with one core license and adaptable components.

Repository Structure
```
Legal/
├── LICENSE-UNIVERSAL.md       # Core license (applies to everything)
├── SCHEDULES/                 # Project type specifics
├── TERMS/                     # User type terms
├── PROJECTS/                  # Project-specific adaptations
├── versions/                  # Archived versions (immutable)
└── README.md                  # This file
```

How to Use This System
For Developers (Adding to Projects)
```
# SPDX-License-Identifier: LicenseRef-NOVATOR-UNSL-1.0.0-A-CORPORATE
# Copyright (c) 2025-2026 NOVATOR. All rights reserved.
#
# Universal NOVATOR Software License v1.0.0
# Schedule A (SDK) + Corporate Terms
# Full text: https://github.com/masterrip/Legal
```
For Project Managers (Choosing a License)
Choose a Schedule (project type):

A: SDK/Library
B: API/Service
C: SaaS
D: On-premise

Choose Terms (user type):
Individual: Single user, freelancer
Corporate: Business, organization
Enterprise: Large company, custom needs
Combine for SPDX Identifier:

LicenseRef-NOVATOR-UNSL-{version}-{schedule}-{terms}
Example: LicenseRef-NOVATOR-UNSL-1.0.0-B-ENTERPRISE

Contact
Licensing & Sales: inovator49@gmail.com

Legal Questions: inovator49@gmail.com

Technical Support: inovator49@gmail.com

This repository is the single source of truth for all NOVATOR legal documents.

