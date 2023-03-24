# Annotator for Clinical Data Cartridges

The IBM Clinical Insights v1.0 cartridge is now deprecated, and a newer version is available as ACD Clinical Insights v1.0.  You can install the latest cartridge using the ACD Configuration Editor tool by selecting the "New->Import Cartridge" option.  After importing the latest cartridge, you will see both the deprecated IBM Clinical Insights v1.0 and the new ACD Clinical Insights v1.0 cartridge in the cartridge catalog.

For any cartridges that have extended the IBM Clinical Insights v1.0 cartridge, we recommend that they are updated to use the new ACD Clinical Insights v1.0 cartridge.  When you open the extension cartridge, you will see a warning message that indicates that the newer ACD Clinical Insights v1.0 cartridge is available.  The warning message provides an Update link that can be used to update the cartridge automatically. When you click Update, the cartridge dependencies will be updated to the new cartridge and any artifacts that depend on or extend artifacts in the previous cartridge will be updated to equivalent artifacts in the new cartridge.  It is recommended that you backup your cartridge before updating. To backup the cartridge, select the Export button and select the Source version.

The ACD Clinical Insights v1.0 cartridge has been validated using UMLS 2022AA.  It is recommended that the cartridges that have extended ACD Clinical Insights v1.0 also use UMLS 2022AA.  After the update, if there are conflicting UMLS versions,  a warning message will appear at the top of your cartridge. To update to UMLS 2022AA:

1. Click “Add from catalog”. Find UMLS 2022AA and select Add from the three dot menu.
2. Remove any previous UMLS versions from your cartridge.
