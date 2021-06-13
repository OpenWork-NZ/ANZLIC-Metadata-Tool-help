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
1. Help for specific elements is available by clicking on the element name or field (Tooltips must be enabled)
1. Deleting individual items - if a red X appears to the right of a line, this element may be deleted by clicking the red X
    1. Also applies to sections when allowed
1. Page navigation aids. Useful for longer more complex metadata and small screens where visibility of all elements is difficult.
    1. Collapsing and expanding sections is accomplished by clicking the caret at the left of the section name. 
    1. Located in the upper left is a double caret in a blue circle. Clicking this collapses and expands all sections on a page.
    1. The single caret in the blue circle on the lower left brings you to the top of the page.
    1. Also on the lower left is a hamburger menu button in a blue circle. This exposes or hides the sidebar navigator. This consists of a list of all expandable sections in a page. Clicking a section in this sidebar takes one to that section.

## General Tab
The General tab holds most of the most common metadata for a resource. It consist of the following sections:
* General Information
* Maintenance Information 
* Key Dates
* Resource Identification

### General Information
* **Title** - The name by which the cited resource is known.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceTitle
    * Text field **Must** be populated with a single entry.
        * Overwrite any placeholder text from the template
* **Abstract** - Brief narrative summary of the content of the resource.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Abstract.html
    * Text box **Must** be populated with a single entry.
        * Overwrite any placeholder text from the template
* **Purpose** - _Optional_ - Summary of the intentions with which the resource was developed.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Purpose
    * Text box _May_ be populated with a single entry.
        * Overwrite any placeholder text from the template
* **Supplemental Information** - Any other descriptive information about the dataset.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/DataIdentification.html
    * Text box _May_ be populated with a single entry.
        * Overwrite any placeholder text from the template
* **Topic category** - Main theme(s) of the dataset, selected from an official ISO list.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/TopicCategory
    * Tagged entry field must be populated with at least one entry. 
        * Add entries by clicking in the field and selecting values from the dropdown list. 
        * Remove any unneeded entries by selecting the "x" next to its name.
* **Status** - The lifecycle state of a resource. Selected from a progress code codelist.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Status
    * Select the most appropriate value from the provided dropdown selection, if any.

### Maintenance Information
* **Maintenance and update frequency** - Frequency with which changes and additions are made to the resource after the initial resource is completed
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Maintenance
    * One value **Must** be selected from the provided dropdown list.
* **Date** - The date at which the last update to the resource was made.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Maintenance
    * Use the provided date selector tools to populate. **Must** be populated if maintenance information is provided.
* **Maintenance note** - Textual information about the last update committed to a resource.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Maintenance
    * This update note should include the name of the resource editor, when the update occurred and what changes were made.

### Key Dates
* **Date** - Important dates related to the resource.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Maintenance
    * As a minimum, dates for _Creation_ and _Publication_ **Must** be provided. 
        * Use the dropdown to select the appropriate Date type.
        * Use the provided date selector tools to populate date and, if needed, time. 
        * Use the _Date_ "+" button to add more dates if needed.

### Resource Identification
* **Identifier** - A unique identifier for the resource describe by this metadata record. 
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceIdentifier
    * At least one resource identifier should be provided. 
        * If useful, provide multiple entries.
        * For service resources, the service http endpoint URL may serve as a useful identifier.
* **Description** - A textual description of the nature and purpose of the provided resource identifier.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceIdentifier
    * Recommended for all resource identifier entries
        * If a service endpoint, description may say "Service Endpoint URL"
## Service Tab (Only visible when editing Service Metadata records)
The Service tab holds most important additional metadata elements needed for a service resource. It consist of two sections:
* Service
* Contains Operation 

When creating metadata for services, it is recommended that one metadata record be created for each service type provided by the resource. If a service offers a viewer and an API for data delivery, separate metadata records should be provided for each.

### Service
* **Service Type** - A name identifying the type of service provided by the described resource. Should be sourced from a controlled vocabulary.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ServiceType
    * One Service type entry **Must** be populated in a service metadata record.
        * The value of this field should be populated with a selection from the provided "Recommended values" dropdown.
        * If necessary, other values can be entered as free text.
* **Service Type Version** - Provides search based on the value of the service type.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ServiceTypeVersion
    * One or more service type versions _May_ be provided if useful to allow discovery and use of resources based on the version of the service provided.
* **Coupling Type** - Documents the relation of the service to associated data. May be "Tight", "Loose" or "Mixed".
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/CouplingType
    * One selection **Must** be made from the three options provided in the dropdown.
        * For tight couplings, a coupled resource **Must** be provided using the "Link to a dataset" button in the "Thumbnails & Distributions" sidebar section.

### Contains Operation 
* Each _Contains Operation_ instance describes one and only one method provided by the service.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ContainsOperations.html
    * **Operation Name** - A unique identifier for this interface.
        * A name for the operation **Must ** be provided in the provided text field.
    * **Distributed computing platform (DCP)** - DCP on which the operation has been implemented
        * One value _Should_ be selected from provided dropdown.
    * **Operation Description** - Free text description of the intent and results of the operation.
        * Provided text entry field _Should_ be populated with a short description of the purpose of the service.
    * **Connect point** - Address for connecting to the described service interface.
    * **URL** - The address of the service endpoint **Must** be entered here.
    * **Protocol** - The protocol of the service _Should_be populated using the dropdown to the right of this field.
        * Free text entry maybe used if the appropriate protocol is not in the list.
    * **Function** - A value _Should_ be selected from the dropdown that aligns with the service purpose.
    * If additional connect points are needed for a service, the _Connect point_ "+" button will allow additional entries.
    * **Not Recommended** - Addition operations provided by a service can be documented by clicking on the _Contains Operation_ "+" button.
        * EMA guidance states that there should be one metadata entry for each service type.

## Contacts
This tab is used to capture:
* Resource Contacts - Information about parties that have some responsibility to the resource described in the metadata.
* Metadata Contacts - Information about parties that have some responsibility to the metadata record describing the resource.

### **Search for contact** tool guidance
This tool allows contacts to be selected from a list maintained by your administrator. This improves consistency, searchability, correctness and eases population of responsible party information.

This tool can be used in two ways -
1. Simple search
    * In the "Search for contact" field, type the first few letters of the desired party.
    * To the right of the desired entry select the appropriate role for the party by clicking either the "Chain link" ![Link icon](/image/chainlink.png) or "+" ![Add icon](/image/addIcon.png) icon. 
    * A new entry will appear in the table.
1. Advanced search
    * To the left of the "Search for contact" field, click the spyglass icon ![spygalss](/image/spyglass.png) to display the advanced search interface. ![Advanced contact search](/image/contactSearch)
    * **Narrowing your search -** Searches can be narrowed in two ways
        * Using the "Search for contact" field, at the top of the popup as you would in Simple search
        * Using the _Facets_ in the left sidebar, select the category appropriate to the party 
    * Select the desired contact from the results
    * Two ways to populate the metadata record with the chosen contact
        1. Select the appropriate role for your chosen contact by clicking on the "Choose role" button in the lower left of the window and click the "+" ![Add icon](/image/addIcon.png) icon.
        1. Click the spyglass icon ![spygalss](/image/spyglass.png), also in the lower left, and select a role from the dropdown menu
    * A new entry will appear in the table.
    > NOTE: Do not use the "+" icon. A bug in GeoNetwork requires its presence while not allowing it to function properly. If a row to the table is added with this method, only the _Role_ element will present. As usual, this row can be removed by clicking the red "X" to the right of the row.

**When the party is not found**
If a party is not available via search, do the following:
* Following the _Simple search_ guidance above, type a "!" in the "Search for contact" box
* Select "!Custom entry". 
* Overwrite the provided fields with appropriate contact information. 
   * Remember to select the appropriate role from the dropdown
* If the contact is likely to be used again for other metadata, contact your administrator to add entry for this party to the *Contacts* managed directory.

> NOTE: Your administrator will provide guidance about whether to use the either the "Chain link" ![Link icon](/image/chainlink.png) or "+" ![Add icon](/image/addIcon.png)icon when adding contacts.

### Resource Contacts
* **Point of Contact** - Contact information for those who provide a first point of contact related to the resource. 
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourcePointOfContact
    * **Custodian** and a **Owner** contact information **Must** be provided. Other points of contact may be added
        * Use the **Search for contact** tool guidance provided above
* **Responsible party** - Name and position information for an individual or organisation that is responsible for the resource
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceResponsibleParty
    * Additional contacts ay be provided for parties that hold particular roles related to the resource. Any number may be added.
        * Responsible party contacts may be the same as parties cited in _Point of contact_ or _Metadata Contacts_
        ** Use the **Search for contact** tool guidance provided above

### Metadata Contacts
* **Contact** Contact information for those parties that hold responsibilities related to the metadata record and its maintenance (Not the resource).
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/MetadataContact
    * Using the **Search for contact** tool guidance provided above, populate this table as many times as needed (one entry is common).
    >NOTE: A bug in the GeoNetwork interface makes it necessary for their to be a blank record in the template. This appears in the table as a  "Point of contact" entry with "!Please remove" in as _Name_. After adding a valid contact to this table, remove this entry by clicking the red "X" that now will appear to the right on mouse over on this entry.      

## Lineage Tab
Lineage is where information about resource provenance - the sources and methods used to create the resource - is captured.
This page has one section _Resource Lineage_.
### Resource Lineage 
* **Statement** - General explanation about the producer's knowledge about the lineage of the resource.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceLineage
    * Overwrite the message in the text box with details that provides useful background information about the resource.
        * Or remove provided placeholder text if no lineage information is available and state why
* **Source Description** - General explanation about the producer's knowledge about source information used to create the resource.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceLineage
    * Overwrite the message in the text box with details that provides useful source information about the resource.

## Keyword Tab
Keywords are the important ideas and topics that summarise and define what your resource is about. In most search engines, these are indexed and typically normalised to resemble the base word in order to capture variations. Keywords are useful in discovering and organising resources.

To be most useful to these purposes it is important that keywords used in metadata be consistent in spelling and definition. This is best done through the use of well managed controlled vocabularies. GeoNetwork supports the use of controlled vocabularies stored in internal **Thesauri**. The ANZLIC Metadata tool makes heavy use of these vocabularies and is designed to encourage their use whenever possible. These keyword vocabularies are managed by your metadata administrator and sourced from external authoritative sources in alignment with other experts across the domain.

The Keyword page contains one Section - **Keywords**. 

To speed population of metadata with keywords, several thesauri have been preselected in the template. 

### **Keyword Thesaurus** tool guidance
This tool allows keywords to be selected from a thesauri maintained by your administrator. This improves consistency, searchability, correctness and eases population of keyword information.

* The Thesaurus name appears above the _Search Keywords ..._ entry field
* Click on the _Search Keywords ..._ entry field to produce a list of available keywords
* Select a Keyword
* If multiple keywords are needed from a thesaurus click on the _Search Keywords ..._ entry field again and select another keyword. It will appear in the same box
* To remove a selected keyword, click on the "x" to the right of it.
* **Hierarchical Thesauri**
    * **Thesaurus** will label a select box if the controlled vocabulary has hierarchy and will contain the thesaurus name to expose options ![Thesaurus](/image/thesaurusTaxon.png)
    * **Navigating a Thesaurus**
        * Clicking the circled "+" ![Add Keyword](/image/keywordAdd.png) adds the keyword to the metadata
        * Clicking on the concept text expands the concept
            * _Except for "Current concept" which will add this keyword to the metadata_
        * Clicking the _Parent concept_ text (if present) brings you to the that concept
        * In the upper right, the "Display top concepts" button ![Top concept](/image/topConcept.png) returns the select to the top concept of the hierarchy
        * In the upper right, the "Previous" button ![Previous concepts](/image/previousConcepts.png) displays a selectable list of previously viewed concepts

### Keywords
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Keywords.html
* Each template metadata record provides a selection of thesauri from which keywords should be selected.
    * For **Dataset** metadata these include:
        * **Hazard type** - a list of common emergency management hazard types
        * **Continents, countries, sea regions of the world.** - an international list of locations 
            * Is a hierarchal thesaurus
            * _May not be adequate to the local context. Consult your administrator_
        * **Dataset Method** - four options _Modelled, Observed, Modelled and Observed, and other_
        * **CAP-AU Compliance** - the nature of CAP compliance of the resource
* **Descriptive keywords** options ![Descriptive keywords](/image/descriptiveKeywords.png)
    * **Choose keywords from thesaurus** - provides a list of available thesauri. Selected thesaurus will be added to the page for further selection.
    * **Add new keyword** - allows the addition of free-text keywords. _Use Sparingly!_ 
        * Require selection of a keyword **Type** selected from a dropdown list

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
        * The date should hold, in decimal year format, the date of which the coordinates used were captured.
        * _Reference system type_ and _Description_ should remain as prepopulated.
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
    * Legal and Security constraints may be selected using the searchable dropdown available by clicking the _Search by constraint statement ..._ field
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
    * This table should be populated using the **Constraints selection** tool guidance above
    * The correct _Constraint application scope_ **Must** be selected the dropdown in the Legal constraints table

* **Security Constraints** - A table of security constraints that apply to the cited resource
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceSecurityConstraints
    * This table should be populated using the **Constraints selection** tool guidance above

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



    
