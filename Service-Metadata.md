# Service Tab 
>Note: Only visible when editing Service Metadata records

The Service tab holds most important additional metadata elements needed for a service resource. It consist of two sections:
* **Service**
* **Contains Operation**

When creating metadata for services, it is recommended that one metadata record be created for each service type provided by the resource. If a service offers a viewer and an API for data delivery, separate metadata records _Should_ be provided for each.

## Service
### Service Type - _A name identifying the type of service provided by the described resource_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ServiceType
* One Service type entry **Must** be populated in a service metadata record.
    * The value of this field _Should_ be populated with a selection from the provided "Recommended values" dropdown.
    * If necessary, other values can be entered as free text.
### Service Type Version** - _Provides search based on the value of the service type_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ServiceTypeVersion
* One or more service type versions _Should_ be provided if useful to allow discovery and use of resources based on the version of the service provided.
### Coupling Type - _Documents the relation of the service to associated data_ 
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/CouplingType
* One selection **Must** be made from the three options provided in the dropdown - "Tight", "Loose" or "Mixed".
    * For tight couplings, a coupled resource **Must** be provided using the "Link to a dataset" button in the "Thumbnails & Distributions" sidebar section.

## Contains Operation 
>NOTE: Each _Contains Operation_ instance describes one and only one method provided by the service. By EMA guidance, there _Should_ be one metadata entry for each service type.


### Operation Name - _A unique identifier for this interface_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ContainsOperations.html
* A name for the operation **Must** be provided in the provided text field.

### Distributed computing platform (DCP) - _DCP on which the operation has been implemented_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ContainsOperations.html
* One value _Should_ be selected from provided dropdown.

### Operation Description - _Free text description of the intent and results of the operation_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ContainsOperations.html
* Provided text entry field _Should_ be populated with a short description of the purpose of the service.

### Connect point - _Address for connecting to the described service interface_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ContainsOperations.html
* Consist of the following fields:
    * **URL** - The address of the service endpoint **Must** be entered here.
    * **Protocol** - The protocol of the service _Should_be populated using the dropdown to the right of this field.
        * Free text entry maybe used if the appropriate protocol is not in the list.
    * **Function** - A value _Should_ be selected from the dropdown that aligns with the service purpose.
* If additional connect points are needed for a service, the _Connect point_ "+" button will allow additional entries.
>Note: **Not Recommended** - Addition operations provided by a service can be documented by clicking on the _Contains Operation_ "+" button.

