# Spatial Tab
The Spatial page consist of three separate sections.
* **Extents** - Used for discovery purposes. Holds common term description of the the area of earth to which the resource pertains. 
* **Resolution** - Provides a guide to the spatial scale at which the resource is meant to be used.
* **Reference System** - Holds information about the standardised parameters used to store location information.

## Extents
### Description - _Written explanation of the spatial and temporal extents of the resource_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ExtentGeographicDescription
* Optional field to be used when verbal descriptions help explain the extents of a resource.
    * When no text is present, clicking the boxed "+" under _Description_ exposes a text box to populate.
### Geographic bounding box - _Four values which define a box containing the resource area of relevance_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/ExtentBoundingBox
* Geographic extents may be populated via two mechanisms
    * **Choose a region** - provides a search box against a selected source and displays this on the map. ![Choose a region](/image/chooseRegion.png)
    >NOTE: the geonames option is slow but comprehensive. The other reference internal files and are much quicker.
    * The map may be directly edited by 
        * Entering and adjusting coordinate values
        >NOTE: The CRS for this map is stated in the upper right dropdown. This should be left as "WGS 84 (EPSG:4326)".
        * Manually drawing extents by selecting the _Draw extents_ button in the upper right and then navigating to you desired location and clicking and dragging a box over the desired location
    >NOTE: If multiple, polygonal or other extents are needed, expert users can do so in the **Advanced** metadata editing interface.

## Resolution
### Equivalent scale - _Level of detail expressed as the scale of a comparable hardcopy map or chart_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/SpatialResolution
* Each metadata record for a spatial resource **Must** include an _Equivalent scale_.
    * The _Recommended values_ dropdown to the right provides a useful list of common values to select.
    * Values can be adjusted or entered free form in the _Denominator_ box.

## Reference system
### Reference System Information - _Displays a table of reference systems applicable to the resource_
* **ICSM Guidance** - https://icsm-au.github.io/metadata-working-group/defs/SpatialReferenceSystem.html
* A partially completed **Coordinate epoch** entry provides a way to capture information needed to account for coordinate drift due to earth plate techtonics.
    * The date _Should_ hold, in decimal year format, the date of which the coordinates used were captured.
    * _Reference system type_ and _Description_ prepopulated values _Should_ remain.
* Appropriate additional references systems **Must** be added
    * Use the _Search for a reference system_ dialogue to select from a prepopulated list of applicable CRS
        * Search using the dropdown or
        * The extended search available by clicking the spyglass icon ![spygalss](/image/spyglass.png)
    * Additional CRS values may be added using the **Advanced** interface.
    * Add as many or few CRS as needed to describe the resource.