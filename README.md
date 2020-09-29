# Common metadata
**Harmonising ship data through the use of common metadata** 

This repository aims to identify the common metadata and standards required to harmonise data formats across the UK large research vessels. Our aim is to ensure all files are self-describing, no matter the format used while making them easily interpretable by users of all abilities. Common metadata have been extracted from several conventions including [CF Metadata Conventions](https://cfconventions.org/latest.html), [ACDD](https://wiki.esipfed.org/Attribute_Convention_for_Data_Discovery_1-3#Context) and [SeaDataNet Transportation Formats](https://www.doi.org/10.13155/56547). Not all metadata are applicable to all I/Ocean file types. 

Below, common metadata have been grouped according to:


|Group | Description
--- | --- 
| [Global properties](globalProperties.md) | Properties common to the whole file |
| [Coordinate variables](coordinateVariables.md) | Properties that are common to variables that align observations such as time, geographical position and depth. |
| [Feature types](featureTypes.md) | Describes instances and metadata of discrete sampling geometries | 
| [Observed measurements](observedMeasurements.md) | Properties that are common to observed measurements in the file such as temperature and salinity. |
| [Quality indicators](qualityIndicators.md) | Describes quality indicators associated to observation variables |
| [Instruments](instrumentProperties.md) | Describes the instruments or sensors used to collect the data |
| [Platforms](platformProperties.md) | Describes the platforms used to collect the data |
| [Deployments](deploymentProperties.md) | Describes the deployment of platforms and instruments used to collect the data |
| [Calibrations](calibrationProperties.md) | Describes calibrations associated to instruments or directly applied to observations |
| [Instrument installations](instrumentInstallationProperties.md) | Describes an instrument's position, orientation and sampling depth on a platform |


To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)



