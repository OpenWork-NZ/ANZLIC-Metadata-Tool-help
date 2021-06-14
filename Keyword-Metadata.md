# Keyword Tab
Keywords are the important ideas and topics that summarise and define what your resource is about. In most search engines, these are indexed and typically normalised to resemble the base word in order to capture variations. Keywords are useful in discovering and organising resources.

To be most useful to these purposes it is important that keywords used in metadata be consistent in spelling and definition. This is best done through the use of well managed controlled vocabularies. GeoNetwork supports the use of controlled vocabularies stored in internal **Thesauri**. The ANZLIC Metadata tool makes heavy use of these vocabularies and is designed to encourage their use whenever possible. These keyword vocabularies are managed by your metadata administrator and sourced from external authoritative sources in alignment with other experts across the domain.

The Keyword page contains one Section - **Keywords**. 

To speed population of metadata with keywords, several thesauri have been preselected in the template. 

## Using the _Keyword Thesaurus_ tool
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

## Keywords
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/Keywords.html
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
* **Descriptive keywords** (and Keyword Help) ![Descriptive keywords](/image/descriptiveKeywords.png) 
    >NOTE: Keyword help (this page) can be accessed through the Tooltip available [here](https://github.com/OpenWork-NZ/mdwg/wiki/Keyword-Metadata#using-the-keyword-thesaurus-tool).
    * Options:
        * **Choose keywords from thesaurus** - provides a list of available thesauri. Selected thesaurus will be added to the page for further selection.
        * **Add new keyword** - allows the addition of free-text keywords. _Use Sparingly!_ 
            * Require selection of a keyword **Type** selected from a dropdown list
   
