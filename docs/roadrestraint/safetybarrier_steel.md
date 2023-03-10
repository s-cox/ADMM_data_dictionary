---
layout: default
title: Safety Barrier (Steel)
parent: Vehicle Restraint
grand_parent: Road Restraint
nav_order: 6
---

# Safety Barrier (Steel)
This model was last updated on **12/01/2023**, this is version **1.0**

Experimental
{: .label .label-yellow }

## Model created
12/01/2023

## Description
Safety Barriers appear on the road network in several forms: creating an upstanding barrier running parallel to the carriageway (adjacent to or within the central reservation). The main purpose of Safety Barriers is to contain and redirect errant road vehicles to reduce the risk of them crossing central reservations or leaving the carriageway.

## Asset Image

![activity](/ADMM_data_dictionary/docs/roadrestraint/diagrams/safety_barrier_steel.png)

## Asset Code
``RRVS``

## UniClass
``Ss_25_16_94_50``

## Geometry
Linear

## Asset Rules

``RRVC_1``

Where a Safety Barrier has been installed to prevent impact with an over bridge, then Hazard = Foundations/Bases/Supports.

``RRVS_2``

Safety Barrier which occur in the central reserve of dual carriageways and motorways and which are common to both sections (i.e. e. double sided, with a shared post) are recorded in the nominated section ONLY.

``RRVS_3``

Safety Barrier which are located in the central reserve or central island and are single sided or on separate posts are to recorded in the section to which they pertain and not the nominated section.

``RRVS_4``

Safety Barrier installed to prevent crossover accidents in the central reserve will be recorded as Hazard = None and Crossover = Yes.

``RRVS_6``

If the beam profile is identified as open box, the type is recorded as untensioned.

``RRVS_7``

If Ground Surface Type = Solid; then the Foundation = Concrete Post.

``RRVS_8``

If Ground Surface Type = Solid; then the Foundation = Driven Post.

``RRVS_9``

Ground Surface Type = Granular, unless the asset has been installed on a man made/constructed surface; in which case Ground Surface Type = Solid.

``RRVS_10``

Any section where part of the Safety Barrier has been designed to be removed to allow traffic to cross on to the opposite carriageway in the event of an accident or incident is to be recorded as Demountable =Yes.

## Data Catalogue

| Asset Data Category | Attribute Name                     | Attribute Description                                                                                                                                                            |
|---------------------|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Construct           | Compliant to Current DMRB Standard | Indicates whether the asset is compliant to the current DMRB standard.                                                                                                           |
| Construct           | [Date of Installation](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/dateofinstallation.html)               | The date the asset was installed on site; applicable to prefabricated items manufactured off-site. This should take the form DD-MON-YYYY.                                        |
| Construct           | [Departure - DAS ID](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/departure.html)                 | The unique identifier within the WebDAS system corresponding to an approved Departure from Standard.                                                                             |
| Construct           | Design/Drawing Number              |                                                                                                                                                                                  |
| Construct           | [Expected Service Life](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/expectedservicelife.html)              | The time period during which the asset is expected to remain suitable for its intended use.                                                                                      |
| Construct           | If Not Compliant                   |                                                                                                                                                                                  |
| Construct           | If RRRAP not applicable            |                                                                                                                                                                                  |
| Construct           | Was RRRAP used                     | Indicates whether a Road Restraint Risk Assessment Process was used.                                                                                                             |
| Inventory           | [Additional Information](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/additonalinformation.html)             | A text note to provide specific information about an asset, in cases where an attribute value is set to "Other".                                                                 |
| Inventory           | [CE Certificate Reference Number](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/cecertno.html)    |                                                                                                                                                                                  |
| Inventory           | Connected Parapet                  |                                                                                                                                                                                  |
| Inventory           | End Chainage                       | The along carriageway position corresponding to the termination of a linear or polygon asset, as measured within the section.                                                    |
| Inventory           | End Date                           | The date from which the asset ceases to be recognised under maintenance.  Note: a record of retirement will be populated. Should take the form DD-MON-YYYY.                      |
| Inventory           | Foundation                         |                                                                                                                                                                                  |
| Inventory           | Ground Surface Type                | See Rule RRVR_9.                                                                                                                                                                 |
| Inventory           | [Hazard (reason for asset)](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/hazardreason.html)          | Defines the reason for the installation of a safety barrier (i.e. e. any potential hazards to road users).                                                                       |
| Inventory           | Impact Severity Level (ISL)        |                                                                                                                                                                                  |
| Inventory           | Length                             |                                                                                                                                                                                  |
| Inventory           | Length of Need                     |                                                                                                                                                                                  |
| Inventory           | [Location Text](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/locationtext.html)                      | A text note to describe the local position of the asset, in generic terms.                                                                                                       |
| Inventory           | [Manufacturer](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/manufacturer.html)                       | The manufacturer of the asset.                                                                                                                                                   |
| Inventory           | Maximum Height Limit               |                                                                                                                                                                                  |
| Inventory           | Number of Beams                    |                                                                                                                                                                                  |
| Inventory           | Number of Impact Sides             | Number of sides from impact the asset affords protection to.                                                                                                                     |
| Inventory           | Owner                              |                                                                                                                                                                                  |
| Inventory           | Post Frequency                     |                                                                                                                                                                                  |
| Inventory           | Post Type                          |                                                                                                                                                                                  |
| Inventory           | [Product Name/ID](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/productname_id.html)                    |                                                                                                                                                                                  |
| Inventory           | Profile                            | Cross-sectional profile of the asset.                                                                                                                                            |
| Inventory           | Required Mounting Height           | Manufacturer's required mounting height of the beam to the post above pavement (within 1.5m setback) and/or ground level (above 1.5m).                                           |
| Inventory           | Required Mounting Height Tolerance | Manufacturer's tolerance for the Required Mounting Height.                                                                                                                       |
| Inventory           | [Section](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/section.html)                            | Section referencing is used to divide the network into sections. Further information can be found in section 4 of the Part 2 - Requirements and Additional Information document. |
| Inventory           | [Start Chainage](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/startchainage.html)                     | The along carriageway position corresponding to the beginning of a linear or polygon asset, as measured within the section.                                                      |
| Inventory           | [Start Date](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/startdate.html)                         | The date from which the asset is recognised in under maintenance. Should take the form DD-MON-YYYY.                                                                              |
| Inventory           | Suicide Prevention Objective       | Is this item serving a suicide prevention objective? (i.e. e. a normal, unaltered asset supporting a suicide prevention strategy).                                               |
| Inventory           | Theoretical Working Width          |                                                                                                                                                                                  |
| Inventory           | Working Width Class                |                                                                                                                                                                                  |
| Inventory           | [X End (Easting)](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/xend_easting.html)                    | OS Easting coordinate, at the end of the asset.                                                                                                                                  |
| Inventory           | [X Start (Easting)](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/xstart_easting.html)                  | OS Easting coordinate, at the beginning of the asset.                                                                                                                            |
| Inventory           | [XSP](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/xsp.html)                                | Defines the location of the asset across the carriageway.                                                                                                                        |
| Inventory           | [Y End (Northing)](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/yend_northing.html)                   | OS Northing coordinate, at the end of the asset.                                                                                                                                 |
| Inventory           | [Y Start (Northing)](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/ystart_northing.html)                 | OS Northing coordinate, at the beginning of the asset.                                                                                                                           |
| Maintenance         | [Maintenance Contractor](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/maintenancecontractor.html)             | Contractor responsible for maintenance of the asset. Should only be recorded if HE is responsible for the assets maintenance.                                                    |
| Maintenance         | [Maintenance Responsibility](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/maintenanceresponsibility.html)         | The organisation responsible for the maintenance of the asset.                                                                                                                   |
| Operate             | [Area/Region](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/area_region.html)                        |                                                                                                                                                                                  |
| Operate             | Containment Levels - SL <50MPH     |                                                                                                                                                                                  |
| Operate             | Containment Levels - SL 50MPH+     |                                                                                                                                                                                  |
| Operate             | [Defect Liability Period](https://s-cox.github.io/ADMM_data_dictionary/docs/attribute/defectliabilityperiod.html)            | The end date of the supplier assurance period. Should take the form DD-MON-YYYY.                                                                                                 |
| Operate             | Installation Height Requirement    |                                                                                                                                                                                  |
| Operate             | Mounted Asset                      |                                                                                                                                                                                  |
| Operate             | Proprietary                        |                                                                                                                                                                                  |
| Operate             | Redundant                          |                                                                                                                                                                                  |
| Operate             | Setback                            |                                                                                                                                                                                  |
| Operate             | Tensioned Barrier                  | Does the steel safety barrier have a tensioning requirement?.                                                                                                                    |
| Operate             | Vehicle Intrusion Class            |                                                                                                                                                                                  |
| Operate             | Vehicle Intrusion Value            |                                                                                                                                                                                  |
| System              | Source ID                          | Supplier's external reference ID (scheme, major project, survey etc.).                                                                                                           |
| System              | System ID                          | The unique identity code for this item in its current prime system.                                                                                                              |