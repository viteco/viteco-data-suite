# Viteco Data Suite
Viteco Data Suite is a data warehouse automation tool developed by Viteco (Denmark) for building data warehouses, data hubs and generic data platforms for digitalization in an efficient way.

This repository is intended for sharing tips and tricks, scripts and more, that may be of help when building a data warehouse or just working with data, primarily for those using Viteco Data Suite.

The user guide of Viteco Data Suite 2.0 can be found here: https://wiki.viteco.dk/display/VWS20

##VITECO_FWS_TALEND: Utilities published by Viteco for Talend. Use import to get them into Talend.
The utilities are to be used in Talend Data Integration. TO use them import them into your Talend project pointing to VITECO_FWS_TALEND as the root directory.

- vdsUtilities/vdsUtilities_delta_loadgroup: Loadgroup to control one group of incremental updates to be loaded for one delta period.
- vdsUtilities/vdsUtilities_delta_init_extract_interval: (Sub)job called to initiate a new delta period.
- vdsUtilities/vdsUtilities_delta_close_extract_interval: (Sub)job called to mark a delta period as processed.