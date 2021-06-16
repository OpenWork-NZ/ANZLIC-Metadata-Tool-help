# User Guide - Creating Metadata
## Help contents
- [Getting Started](./README.md#getting-started---sign-in-and-select-a-template)
- [Navigating the Editor](README.md#navigating-the-editing-window)
  - [Tabs](./README.md#tabs)
  - [Sidebar](./README.md#sidebar)
  - [Tools and Notation](./README.md#tools-and-notation)
- [General tab](./General-Metadata.md)
  - [General information](./General-Metadata.md#general-information)
    - [Title](./General-Metadata.md#title---the-name-by-which-the-cited-resource-is-known)
    - [Abstract](./General-Metadata.md#abstract---brief-narrative-summary-of-the-content-of-the-resource)
    - [Purpose](./General-Metadata.md#purpose----summary-of-the-intentions-with-which-the-resource-was-developed)
    - [Supplemental Information](./General-Metadata.md#supplemental-information---any-other-descriptive-information-about-the-dataset)
    - [Topic category](./General-Metadata.md#topic-category---main-themes-of-the-dataset-selected-from-an-official-iso-list)
    - [Status](./General-Metadata.md#topic-category---main-themes-of-the-dataset-selected-from-an-official-iso-list)
  - [Maintenance Information](./General-Metadata.md#maintenance-information)
    - [Maintenance and update frequency](./General-Metadata.md#maintenance-and-update-frequency_---how-often-changes-and-additions-are-made-to-the-resource)
    - [Maintenance Date](./General-Metadata.md#maintenance-and-update-frequency_---how-often-changes-and-additions-are-made-to-the-resource)
    - [Maintenance note](./General-Metadata.md#maintenance-note---textual-information-about-the-last-update-committed-to-a-resource)
  - [Key Dates](./General-Metadata.md#key-dates)
  - [Resource Identification](./General-Metadata.md#resource-identification)
    - [Identifier](./General-Metadata.md#identifier---a-unique-identifier-for-the-resource-describe-by-this-metadata-record)
    - [Description](./General-Metadata.md#description---a-textual-description-of-the-nature-and-purpose-of-the-provided-resource-identifier)
- [Service Tab](./Service-Metadata.md)
  - [Service](./Service-Metadata.md#service)
    - [Service Type](./Service-Metadata.md#service-type---a-name-identifying-the-type-of-service-provided-by-the-described-resource)
    - [Service Type Version](./Service-Metadata.md#service-type-version---provides-search-based-on-the-value-of-the-service-type)
    - [Coupling Type](./Service-Metadata.md#coupling-type---documents-the-relation-of-the-service-to-associated-data)
  - [Contains Operation](./Service-Metadata.md#contains-operation)
    - [Operation Name](./Service-Metadata.md#operation-name---a-unique-identifier-for-this-interface)
    - [Distributed computing platform (DCP)](./ervice-Metadata.md#distributed-computing-platform-dcp---dcp-on-which-the-operation-has-been-implemented)
    - [Operation Description](./Service-Metadata.md#operation-description---free-text-description-of-the-intent-and-results-of-the-operation)
    - [Connect point](./Service-Metadata.md#connect-point---address-for-connecting-to-the-described-service-interface)
- [Contacts Tab](./Contacts-Metadata.md)
  - [Using the Search for contact tool](./Contacts-Metadata.md#using-the-search-for-contact-tool)
  - [Resource Contacts](./Contacts-Metadata.md#resource-contacts)
    - [Point of Contact](./point-of-contact---contact-information-for-those-who-provide-a-first-point-of-contact-related-to-the-resource)
    - [Responsible party](./Contacts-Metadata.md#responsible-party---name-and-position-information-for-an-individual-or-organisation-that-is-responsible-for-the-resource)
  - [Metadata Contacts](./Contacts-Metadata.md#metadata-contacts)
- [Lineage Tab](./Linage-Metadata.md)
  - [Resource Lineage](./Linage-Metadata.md#resource-lineage)
- [Keyword Tab](./Keyword-Metadata.md)
  - [Using the Keyword Thesaurus tool](./Contacts-Metadata.md#using-the-search-for-contact-tool)
  - [Keywords](./Keyword-Metadata.md#keywords)
- [Spatial Tab](./Spatial-Metadata.md)
  - [Extents](./Spatial-Metadata.md#extents)
    - [Description](./Spatial-Metadata.md#description---written-explanation-of-the-spatial-and-temporal-extents-of-the-resource)
    - [Geographic bounding box](./Spatial-Metadata.md#geographic-bounding-box---four-values-which-define-a-box-containing-the-resource-area-of-relevance)
  - [Resolution](./Spatial-Metadata.md#resolution)
  - [Reference system](./Spatial-Metadata.md#reference-system)
- [Constraints Tab](./Constraints-Metadata.md)
  - [Using the Constraints selection tool](./Constraints-Metadata.md#using-the-constraints-selection-tool)
  - [Resource constraints](./Constraints-Metadata.md#resource-constraints)
    - [Use limitation](./Constraints-Metadata.md#use-limitation---holds-general-constraint-information-such-as-not-to-be-used-for-navigation)
    - [Legal Constraints](./Constraints-Metadata.md#legal-constraints---a-table-of-legal-constraints-that-apply-to-the-cited-resource)
    - [Security Constraints](./Constraints-Metadata.md#security-constraints---a-table-of-security-constraints-that-apply-to-the-cited-resource)
  - [Metadata constraints](./Constraints-Metadata.md#metadata-constraints)
- [Thumbnails & Distributions panel](./Thumbnails-and-Distributions-Metadata.md)
  - [Link to an online resource](./Thumbnails-and-Distributions-Metadata.md#link-to-an-online-resource)
    - [Add a distribution](./Thumbnails-and-Distributions-Metadata.md#add-a-distribution)
    - [Add a Thumbnail](./Thumbnails-and-Distributions-Metadata.md#add-a-thumbnail)
  - [Link to a service / dataset](./Thumbnails-and-Distributions-Metadata.md#link-to-a-service--dataset)
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
    1. View selector 
        1. (insert screenshot)
        1. Advanced
        1. XML
        1. More details (leave unchecked)
        1. Tooltips (make sure is checked to access inline help)
### Tabs 
(insert image)
1. General - General information about the resource
1. Service - Special metadata related to services
1. Contacts - Information about relevant parties to the resource or metadata
1. Linage - Background and provenance information about the resource
1. Keywords - Specific search terms by which the resource may be discovered
1. Spatial - Includes metadata describing the resource location, reference systems used, and intended scale or resolution
1. Constraints - The legal, security and other restrictions that may apply to the resource

### Sidebar

* **Thumbnails & Distributions**

1. Link to an online resource
    1. Add a distribution
    1. Add a thumbnail
1. Link to a service or Link to a dataset if service metadata record

* **Validate**

* **Need Help?*
Opens this document in a new window

### Tools and Notation
1. Mandatory elements are marked by a red asterisk
1. Help for specific elements is available by clicking on the element name or field (Tooltips **Must* be enabled)
1. Deleting individual items - if a red X appears to the right of a line, this element may be deleted by clicking the red X
    1. Also applies to sections when allowed
1. Page navigation aids. Useful for longer more complex metadata and small screens where visibility of all elements is difficult.
    1. Collapsing and expanding sections is accomplished by clicking the caret at the left of the section name. 
    1. Located in the upper left is a double caret in a blue circle. Clicking this collapses and expands all sections on a page.
    1. The single caret in the blue circle on the lower left brings you to the top of the page.
    1. Also on the lower left is a hamburger menu button in a blue circle. This exposes or hides the sidebar navigator. This consists of a list of all expandable sections in a page. Clicking a section in this sidebar takes one to that section.







