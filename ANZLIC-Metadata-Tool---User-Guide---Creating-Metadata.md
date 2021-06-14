# User Guide - Creating Metadata
## Getting Started - Sign in and Select a template
1. To edit metadata using the ANZLIC Metadata Tool, you will first need a user account with sufficient permission. If you do not have one, ask your administrator for help
1. Sign in by clicking "Sign in" in the toolbar and entering your credentials. (image)
1. Under the "Contribute" option in the toolbar and select "Add new record."
1. (insert screenshot)
1. Describe process - how to find your template
1. Assign Group (and possibly ID)
1. Start editing - Opens in ICSM view
## Navigating the Editing Window
1. (insert screenshot)
1. Describe header buttons (to be used after metadata is complete). Look to GN general help
    1. Categories
    1. Group
    1. Validate
    1. Cancel
    1. Save & close
    1. Save metadata
    1. View options 
        1. (insert screenshot)
        1. Advanced
        1. XML
        1. More details (leave unchecked)
        1. Tooltips (make sure is checked to access inline help)
## Tabs (insert image)
1. General - General information about the resource
1. Service - Special metadata related to services
1. Contacts - Information about relevant parties to the resource or metadata
1. Linage - Background and provenance information about the resource
1. Keywords - Specific search terms by which the resource may be discovered
1. Spatial - Includes metadata describing the resource location, reference systems used, and intended scale or resolution
1. Constraints - The legal, security and other restrictions that may apply to the resource

## Sidebar

### Thumbnails & Distributions

1. Link to an online resource
    1. Add a distribution
    1. Add a thumbnail
1. Link to a service or Link to a dataset if service metadata record

### Validate

### Need Help - Opens this document in a new window

## Editing interface - Tools and Notation
1. Mandatory elements are marked by a red asterisk
1. Help for specific elements is available by clicking on the element name or field (Tooltips **Must* be enabled)
1. Deleting individual items - if a red X appears to the right of a line, this element may be deleted by clicking the red X
    1. Also applies to sections when allowed
1. Page navigation aids. Useful for longer more complex metadata and small screens where visibility of all elements is difficult.
    1. Collapsing and expanding sections is accomplished by clicking the caret at the left of the section name. 
    1. Located in the upper left is a double caret in a blue circle. Clicking this collapses and expands all sections on a page.
    1. The single caret in the blue circle on the lower left brings you to the top of the page.
    1. Also on the lower left is a hamburger menu button in a blue circle. This exposes or hides the sidebar navigator. This consists of a list of all expandable sections in a page. Clicking a section in this sidebar takes one to that section.







## Constraints Tab
This page holds information about constraints that may apply to the resource or the metadata record itself.
These constraints may be of a legal, security of other nature.

###  **Constraints selection** tool guidance
This tool allows constraints to be selected from a a managed directory maintained by your administrator. This improves consistency, searchability, correctness and eases population of constraint information. This is useful for both legal and security constraints which commonly have precise meanings. ![Basic constraints selection tool](/image/constraintsToolBasic.png)

* This tool is applied to both Resource and Metadata constraints.
* Both Security and Legal constraints can be sourced using this tool.
* Basic Usage
    * Clicking the "+" icon to the left presents a dropdown which allows the selection of _Constraints, Legal constraints_ or _Security constraints_.
        * Selecting _Constraints_ creates an entry for addition disclaimers and limitations to be entered.
        >NOTE: Do not create Legal or Security constraints using the "+" icon
    * Legal and Security constraints _Should_ be selected using the searchable dropdown available by clicking the _Search by constraint statement ..._ field
* Advanced usage
    * Click on the spyglass icon ![spyglass](/image/spyglass.png) 
    * Results may be restricted to either Legal or Security constraints by selecting the appropriate _Subtemplatetype_
    * Select the desired constraint and click the "+" icon in the lower left.
    >NOTE: Do not use the _Chain link_ icon


### Resource constraints
* **Use limitation** - holds general constraint information such as "Not to be used for navigation"
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceOtherConstraints.html
    * Populate this field as needed with general restriction and disclaimer information
    * Additional Use limitations may be added by selecting the _Constraints_ option under "+" icon

* **Legal Constraints** - A table of legal constraints that apply to the cited resource
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceLegalConstraints
    * This table _Should_ be populated using the **Constraints selection** tool guidance above
    * The correct _Constraint application scope_ **Must** be selected the dropdown in the Legal constraints table

* **Security Constraints** - A table of security constraints that apply to the cited resource
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceSecurityConstraints
    * This table _Should_ be populated using the **Constraints selection** tool guidance above

### Metadata constraints
Metadata constraints are not as common as resource constraints and are often prepopulated in the template and do not need to be altered.
Consult with your administrator for further guidance.

* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/MetadataLegalConstraints and https://icsm-au.github.io/metadata-working-group/defs/MetadataSecurityConstraints

## Thumbnails & Distributions instructions
After completing the tabs, the next step is to link the metadata to representational images (Thumbnails) and access points (Distributions). 

### Link to an online resource
* Add a distribution instructions
* Add a thumbnail instructions

### Link to a service (if dataset metadata) or Link to a dataset (if service metadata)



    
