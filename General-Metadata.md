# General Tab
The General tab holds most of the most common metadata for a resource. It consist of the following sections:
* **General Information**
* **Maintenance Information** 
* **Key Dates**
* **Resource Identification**

## General Information
### **Title** - The name by which the cited resource is known.
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceTitle
* Text field **Must** be populated with a single entry.
    * Overwrite any placeholder text from the template
### **Abstract** - Brief narrative summary of the content of the resource.
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Abstract.html
* Text box **Must** be populated with a single entry.
    * Overwrite any placeholder text from the template
### **Purpose** - _Optional_ - Summary of the intentions with which the resource was developed.
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Purpose
* Text box _Should_ be populated with a single entry.
    * Overwrite any placeholder text from the template
### **Supplemental Information** - Any other descriptive information about the dataset.
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/DataIdentification.html
* Text box _Should_ be populated with a single entry.
    * Overwrite any placeholder text from the template
### **Topic category** - Main theme(s) of the dataset, selected from an official ISO list.
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/TopicCategory
* Tagged entry field **Must** be populated with at least one entry. 
    * Add entries by clicking in the field and selecting values from the dropdown list. 
    * Remove any unneeded entries by selecting the "x" next to its name.
### **Status** - The lifecycle state of a resource. Selected from a progress code codelist.
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Status
* Select the most appropriate value from the provided dropdown selection, if any.

## Maintenance Information
### **Maintenance and update frequency** - Frequency with which changes and additions are made to the resource after the initial resource is completed
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Maintenance
* One value **Must** be selected from the provided dropdown list.
### **Date** - The date at which the last update to the resource was made.
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Maintenance
* Use the provided date selector tools to populate. **Must** be populated if maintenance information is provided.
### **Maintenance note** - Textual information about the last update committed to a resource.
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Maintenance
* This update note _Should_ include the name of the resource editor, when the update occurred and what changes were made.

## Key Dates
### **Date** - Important dates related to the resource.
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/Maintenance
* As a minimum, dates for _Creation_ and _Publication_ **Must** be provided. 
    * Use the dropdown to select the appropriate Date type.
    * Use the provided date selector tools to populate date and, if needed, time. 
    * Use the _Date_ "+" button to add more dates if needed.

## Resource Identification
### **Identifier** - A unique identifier for the resource describe by this metadata record. 
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceIdentifier
* At least one resource identifier _Should_ be provided. 
    * If useful, provide multiple entries.
    * For service resources, the service http endpoint URL _Should_ serve as a useful identifier.
### **Description** - A textual description of the nature and purpose of the provided resource identifier.
* ICSM Guidance - https://icsm-au.github.io/metadata-working-group/defs/ResourceIdentifier
* Recommended for all resource identifier entries
    * If a service endpoint, description _Should_ say "Service Endpoint URL"