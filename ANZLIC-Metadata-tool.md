ANZLIC Metadata tool - Editor  
# Introduction
## Overview
### Background 
1. Purpose - ICSM and EMCINA
    1. Commissioned by GA and EMCINA to support the creation and editing of ISO19115-3 metadata following the guidance developed by MDWG
        1. To support ISO 19115-3 
            1. ANZLIC / ICSM retired the ANLIC profile in (year) in preference of ISO19115-1:2014 
            1. 3 year (?) gap with no guidance 
            1. 5 year (?) gap with no tool - Guidance came first. Tool aligns with guidance
        1. Guidance developed by the MDWG
            1. Alignment with through Layout, Thesaurus, Managed directories (Explain & List)
            1. Help Links to guidance
        1. About previous ANZMet Lite
            1. Designed as a tool to create ANZLIC metadata
            1. Desktop tool
            1. Windows only 
            1. Not opensource
            1. Not flexible
        1. Summary - Differences to ANZMet Lite
            1. Web based tool 
            1. built on GeoNetwork 3.10.6
            1. flexible 
            1. template based
            1. In house modifications allowed
    1. Technical underpinnings
        1. Built on GN 3.10.6
            1. Bug fixes and other changes pushed to core and will be available in future versions
            1. Can work with current GN ISO19115-3 Databases 
        1. GN Editor changes only
            1. No changes to the viewer or other metadata standards (save hiding the map interface)
        1. Supports ICSM guidance ISO 19115-3 
            1. As a Replacement Schema for the default ISO 19115-3
            1. Not yet fully compatible with schema plug-in process
        1. Managed directories
            1. Better ISO19115-3 support for responsible party (Includes identifier support)
	    1. Adds support for Legal Constraints, Security Constraint (based on Aus Security regime)
            1. CRS
        1. Thesauri
            1. List added thesauri
    1. Project management and hosting
        1. GA commitment
            1. Contact info
        1. Version and future work
            1. Version alignment with changes to Standard & ICSM guidance
            1. Versions for other audiences
1. Workflow – standard GeoNetwork framework
    1. Editor Role - 
        1. Creates metadata
        1. Preferably the editor is near the data creation process
        1. Detailed steps included in this document
    1. Reviewer – publishes metadata records
        1. Strongly recommend that Editors do not self publish
        1. Encourages consistency and completeness
        1. Not detailed in this document – follow GN guidance (link)
    1. Admin – 
        1. May be the same as the reviewer or tasks may be divided
        1. manages Users, Templates, Managed directories
1. Installation – Separate document
