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






### Keywords
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Keywords.html
* Each template metadata record provides a selection of thesauri from which keywords _Should_ be selected.
    * For **Dataset** and *Service** metadata these include:
        * **Hazard type** - a list of common emergency management hazard types
        * **Continents, countries, sea regions of the world.** - an international list of locations 
            * Is a hierarchal thesaurus
            * This thesaurus may not be suited to the local context. Consult your administrator_
        * **Dataset Method** - _Dataset only_ - Four options _Modelled, Observed, Modelled and Observed, and other_
        * **CAP-AU Compliance** - the nature of CAP compliance of the resource
    * For **Service** metadata additional keywords include:
        * **ISO19119 Service Type** - **Must** be populated with at least one value from the provided thesaurus.
        * **Service Keyword** - Suggested keywords for the platform or standard describing the service.
* **Descriptive keywords** options ![Descriptive keywords](/image/descriptiveKeywords.png) (and Keyword Help)
    * **Choose keywords from thesaurus** - provides a list of available thesauri. Selected thesaurus will be added to the page for further selection.
    * **Add new keyword** - allows the addition of free-text keywords. _Use Sparingly!_ 
        * Require selection of a keyword **Type** selected from a dropdown list
    * Keyword help can be accessed through the Tooltip available here.

## Spatial Tab
The Spatial page consist of three separate sections.
* **Extents** - Used for discovery purposes. Holds common term description of the the area of earth to which the resource pertains. 
* **Resolution** - Provides a guide to the spatial scale at which the resource is meant to be used.
* **Reference System** - Holds information about the standardised parameters used to store location information.

### Extents
* **Description** - Written explanation of the spatial and temporal extents of the resource.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ExtentGeographicDescription
    * Optional field to be used when verbal descriptions help explain the extents of a resource.
        * When no text is present, clicking the boxed "+" under _Description_ exposes a text box to populate.
* **Geographic bounding box** - provides a list of four values share in a common coordinate system which define a box containing the resource area of relevance.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ExtentBoundingBox
    * Geographic extents may be populated via two mechanisms
        * **Choose a region** - provides a search box against a selected source and displays this on the map. ![Choose a region](/image/chooseRegion.png)
        >NOTE: the geonames option is slow but comprehensive. The other reference internal files and are much quicker.
        * The map may be directly edited by 
            * Entering and adjusting coordinate values
            >NOTE: The CRS for this map is stated in the upper right dropdown. This should be left as "WGS 84 (EPSG:4326)".
            * Manually drawing extents by selecting the _Draw extents_ button in the upper right and then navigating to you desired location and clicking and dragging a box over the desired location
        >NOTE: If multiple, polygonal or other extents are needed, expert users can do so in the **Advanced** metadata editing interface.

### Resolution
* **Equivalent scale** - Level of detail expressed as the scale of a comparable hardcopy map or chart
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/SpatialResolution
    * Each metadata record for a spatial resource **Must** include an _Equivalent scale_.
        * The _Recommended values_ dropdown to the right provides a useful list of common values to select.
        * Values can be adjusted or entered free form in the _Denominator_ box.

### Reference system
* **Reference System Information** - Displays a table of reference systems applicable to the resource.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/SpatialReferenceSystem.html
    * A partially completed **Coordinate epoch** entry provides a way to capture information needed to account for coordinate drift due to earth plate techtonics.
        * The date _Should_ hold, in decimal year format, the date of which the coordinates used were captured.
        * _Reference system type_ and _Description_ _should_ remain with the prepopulated values.
    * Appropriate additional references systems **Must** be added
        * Use the _Search for a reference system_ dialogue to select from a prepopulated list of applicable CRS
            * Search using the dropdown or
            * The extended search available by clicking the spyglass icon ![spygalss](/image/spyglass.png)
        * Additional CRS values may be added using the **Advanced** interface.
        * Add as many or few CRS as needed to describe the resource.

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



    
