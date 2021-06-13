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
* **Abstract** - Brief narrative summary of the content of the resource.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Abstract.html
    * Text box **Must** be populated with a single entry.
* **Purpose** - _Optional_ - Summary of the intentions with which the resource was developed.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Purpose
    * Text box _May_ be populated with a single entry.
* **Supplemental Information** - Any other descriptive information about the dataset.
    * ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/DataIdentification.html
    * Text box _May_ be populated with a single entry.
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
Each _Contains Operation_ instance describes one and only one method provided by the service.
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
    * To the right of the desired entry select the appropriate role for the party by clicking either the "Chain link" ![Link icon](/image/chainlink.png) or "+" ![Add icon](/image/addIcon.png)icon. 
    * A new entry will appear in the table.
1. Advanced search
    * To the left of the "Search for contact" field, click the spyglass icon ![spygalss](/image/spyglass.png) to display the advanced search interface. ![Advanced contact search](/image/contactSearch)
    * **Narrowing your search -** Searches can be narrowed in two ways
        * Using the "Search for contact" field, at the top of the popup as you would in Simple search
        * Using the _Facets_ in the left sidebar, select the category appropriate to the party 
    * Select the desired contact from the results
    * Two ways to populate the metadata record with the chosen contact
        1. Select the appropriate role for your chosen contact by clicking on the "Choose role" button in the lower left of the window and click the "+" ![Add icon](/image/addIcon.png)icon.
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
        






    
