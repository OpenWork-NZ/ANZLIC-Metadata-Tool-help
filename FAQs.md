1. ***What metadata standards does the ANZMet Lite v2 support?***
   
   ANZMet Lite v2 is primarilly designed to support ISO 19115-3:2018 according to [ICSM ISO 19115-1 Metadata Best Practice Guide](https://icsm-au.github.io/metadata-working-group/).
   Priliminary support for the draft GNSS Profile of ISO 19115-3:2018 is also included. Several templates are provided, all adhering to the ICSM guidance, for services and datasets and to suit ACS and EMSINA requirements.
   
1. ***Does ANZMetLite support the ANZLIC profile of ISO 19115?***
   
   ANZMetLite v2 does not support the ANZLIC Profile of ISO19115:2004 or, more generally, any ISO 19139 encoded metadata.
   The ISO19115:2004 was superceded by ISO 19115-1:2014 and the ICSM Metadata Working group voted to move to this new standard and cease support for the ANZLIC profile.
   Therefor, support of ISO 19139 encoded metadata was not included in the remit of this tool.
   
1. ***Can I install ANZMetLite v2 on my own device?***

    Yes! The ANZMetLite is a fork of GeoNetwork opensource and the code can be accessed via GitHub repository [here](https://github.com/OpenWork-NZ/core-geonetwork/tree/gn425-icsm).

1. ***Can I i used ANZMetLite v2 to validate metadata created elsewhere?***
   
   Yes! The ANZMetLite v2 may also be used to validate metadata created elswhere.
   Or it may also be used to programatlically convert metadata in the ANZLIC Profile (or other metadata encoded in ISO 19139) to ISO 19115-3:2018.
   Once uploaded, ANZMetLite v2 can be used to validate and edit these metadata.
   Help for uploading metadata is available [here](https://openwork-nz.github.io/ANZLIC-Metadata-Tool-help/GettingStarted.html#upload-metadata).
1. ***Can we use ANZMetLite v2 to store and share our metadata?***
   
   No. ANZMetLite v2 administrators may remove old metadata from time to time, as required to improve the experience of metadata creation.
   While the ANZMetLite v2 provides all the capabilities of a GeoNetwork metadata catalogue, its purpose is limited to the creation of ISO 19115-3:2018 compliant metadata. Editors cannot use AMZMetLite v2 for the purpose of publishing metadata. It is only intended for metadata creation. As such, users are advised to download any metadata the wish to save or publish and do so in their choice of alternate management and publishing services.
1. ***How do I export my metadata from ANZMetLite v2?***

1. ***Can i install the ANZMetLite editor in my own GeoNetwork instance?***

1. ***Is ANZMetLite v2 open source? How can I access the code?***
