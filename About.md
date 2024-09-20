# About ANZMetLite v2
## Purpose
ANZMetLite v2 provides a tool to simplify the creation of metadata according to the [ICSM ISO 19115-1 Metadata Best Practice Guide](https://icsm-au.github.io/metadata-working-group/) provided by the [ICSM Metadata Working Group](https://icsm.gov.au/what-we-do/metadata-working-group).
The metadata standard it supports is ISO 19115-3:2018 and the GNSS Profile of ISO 19115-3:2018.
This tool may be considered as a replacemnt for the desktop ANZMetLite tool which provided a metadata editor for the now retired ANZLIC Profile of ISO19115:2004.

ANZMetLite v2 is not designed support the ANZLIC Profile of ISO19115:2004 or ISO 19139 encoded metadata in general.
However, it also does not prohibit the use of this standard.
And tools are provided that allow the conversion of metadata in this older format to be converted to ISO19115=3.

While the ANZMetLite v2 provides all the capabilities of a GeoNetwork metadata catalogue, its purpose is limited to the creation of ISO 19115-3:2018 compliant metadata.
Editors cannot use AMZMetLite v2 for the purpose of publishing metadata.
It is only intended for metadata creation.
As such, users are advised to download any metadata the wish to save or publish and do so in their choice of alternate management and publishing services.

This ANZMetLite v2 deployment may remove old metadata from time to time, as required to improve the experience of metadata creation.

Please download any metadata you wish to save and publish.
Instructions are provided to guide you through this process.

## Background
The ANZMetLite v2 was funding by the ICSM Metadata Working Group in 2021 to replace the previous ANZMetLite desktop application. 
This was necessary for multiple reasons. 
First, the old tool was difficult to maintain and customise. 
Also, the standard the older tool was designed to support, ANZLIC Profile of ISO 19115 (encoded in ISO 19139 xml), had been retired in favour of the new ISO 19115-1:2014 for which ICSM guidance was developed to ensure constant use across Australia and New Zealand. 
This new tool is designed to simplify adherence to this guidance. 
A web based editing tool was also desired.
As many metadata creators in the ICSM Metadata Working Group were already using GeoNetwork opensource, the editor was built within the framework of this application to ease addoption.

## License and Access to Code
This ANZMetLite v2 deployment is a fork of GeoNetwork opensource 4.2.5. As such, it is published under the same opensource [GPL license.](https://docs.geonetwork-opensource.org/4.2/overview/license/GPL/)
This code is free to use and may be accessed [here](https://github.com/OpenWork-NZ/core-geonetwork/tree/gn425-icsm).

ANZMetLite v2 was created by [OpenWork Ltd ](https://www.openwork.nz) on behalf of and with guidance and contributions from the ICSM Metadata Working Group. 

OpenWork is responible for support and maintenance of this tool. OpenWork my be contacted at
support_anzmetlite@openwork.nz.