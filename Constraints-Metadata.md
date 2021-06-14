# Constraints Tab
This page holds information about constraints that may apply to the resource or the metadata record itself.
These constraints may be of a legal, security of other nature.

## Using the _Constraints selection_ tool
The **Constraints Selection** tool allows constraints to be selected from a a managed directory maintained by your administrator. This improves consistency, searchability, correctness and eases population of constraint information. This is useful for both legal and security constraints which commonly have precise meanings. ![Basic constraints selection tool](/image/constraintsToolBasic.png)

This tool is applied to both Resource and Metadata constraints.
Both Security and Legal constraints can be sourced using this tool.
* **Basic Usage:**
    * Clicking the "+" icon to the left side of the tool presents a dropdown which allows the selection of _Constraints, Legal constraints_ or _Security constraints_.
        * Selecting _Constraints_ creates an entry for addition disclaimers and limitations to be entered.
        >NOTE: Do not create Legal or Security constraints using the "+" icon
    * Legal and Security constraints can be selected using the searchable dropdown available by clicking the _Search by constraint statement ..._ field
* Advanced usage
    * Click on the spyglass icon ![spyglass](/image/spyglass.png) 
    * Results may be restricted to either Legal or Security constraints by selecting the appropriate _Subtemplatetype_
    * Select the desired constraint and click the "+" icon in the lower left.


## Resource constraints
### Use limitation - _Holds general constraint information such as "Not to be used for navigation"_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ResourceOtherConstraints.html
* Populate this field as needed with general restriction and disclaimer information
* Additional Use limitations may be added by selecting the _Constraints_ option under "+" icon

### Legal Constraints - _A table of legal constraints that apply to the cited resource_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ResourceLegalConstraints
* This table _Should_ be populated using the [**Constraints selection**](https://github.com/OpenWork-NZ/mdwg/wiki/Constraints-Metadata#using-the-constraints-selection-tool) tool guidance above
    * The correct _Constraint application scope_ **Must** be selected the dropdown in the Legal constraints table

### Security Constraints - _A table of security constraints that apply to the cited resource_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ResourceSecurityConstraints
* This table _Should_ be populated using the [**Constraints selection**](https://github.com/OpenWork-NZ/mdwg/wiki/Constraints-Metadata#using-the-constraints-selection-tool) tool guidance above

### Metadata constraints
Metadata constraints are not as common as resource constraints and are often prepopulated in the template and do not need to be altered.
Consult with your administrator for further guidance.

* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/MetadataLegalConstraints and https://icsm-au.github.io/metadata-working-group/defs/MetadataSecurityConstraints
