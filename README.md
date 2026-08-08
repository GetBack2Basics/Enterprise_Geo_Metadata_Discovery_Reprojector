# Enterprise Geo Metadata Discovery Reprojector

An ESRI ArcPy and SQL-based workflow to discover enterprise spatial metadata, plan the cleanup of duplicate and archived data, and perform reprojection (such as GDA94 to GDA2020).

It also discovers, reports on, and quality-assures ESRI SDE complex data, including:

- Versioning and archiving
- Metadata
- Attachments and relationships
- Subtypes
- Coordinate columns (uses AI to identify columns that may contain hard-coded spatial data)
- Schemas and projections to automate migration to GDA2020 (or GDA2020 + zone), or leave WGS84 unchanged
- Programmatic and HTML-based QA reporting for easy review
- Node-based reprojection checks on a configurable percentage of each feature class
- Input controls to process selected files only, and continue, overwrite, or skip based on logic requirements

## Explainer
- The basics in a video
https://notebook.google.com/notebook/ce3e2136-8fbc-4bd0-8c6a-fe42510021b2/artifact/205be6fb-015e-478a-a165-7d295582f75d?utm_source=nlm_web_share&utm_medium=google_oo&utm_campaign=art_share_1&utm_content=&utm_smc=nlm_web_share_google_oo_art_share_1_
- Infographic of system
https://notebook.google.com/notebook/ce3e2136-8fbc-4bd0-8c6a-fe42510021b2/artifact/2db1529a-374e-4ca2-8e2e-fb1293625267?utm_source=nlm_web_share&utm_medium=google_oo&utm_campaign=art_share_1&utm_content=&utm_smc=nlm_web_share_google_oo_art_share_1_
- A presentation showing the built and planned functionality
https://notebook.google.com/notebook/ce3e2136-8fbc-4bd0-8c6a-fe42510021b2/artifact/5760f13b-146d-47e8-b08e-566e1dc00fa1?utm_source=nlm_web_share&utm_medium=google_oo&utm_campaign=art_share_1&utm_content=&utm_smc=nlm_web_share_google_oo_art_share_1_

## Notes

**Author's role:**  
Created all code using AI tools and professional experience, then improved it through consultation and implementation across staging, development, test, and production environments in collaboration with senior staff and program teams (data owners) and stakeholders.

Code is maintained in an internal repository and may be accessed via official requests through **coreagc@gmail.com**, where corporate approval will be sought.

© NSW DPHI
