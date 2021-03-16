
# Global properties


This section contians metadata variables and attributes common to the whole file.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Global attributes
----------

<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>deployment_id</td><td>S</td><td>An identifier for the deployment such as a cruise ID. This could be an identifier for a deployment instance in the file or a plain language string if deployment instances are not used in the file. Use the deployment_id in the global attributes if it is the same for the whole file.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>title</td><td>S</td><td>Short description of the file contents.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>Conventions</td><td>S</td><td>Name of the conventions followed by the dataset.</td><td>'CF-1.8 SeaDataNet-1.0 ACDD-1.3 IOcean-1.0'</td><td>&nbsp;</td></tr> 
<tr><td>source</td><td>S</td><td>The method of production of the original data</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>history</td><td>S</td><td>List of modifications to the data where each modification identified with a date and time.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>references</td><td>S</td><td>Published or web-based references that describe the data or methods used to produce it.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>date_created</td><td>Date</td><td>The date on which this version of the data was created. Metadata changes are not considered when assigning the date created.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>date_updated</td><td>Date</td><td>The date on which the data was last modified. Note that this applies just to the data not the metadata.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>processing_level</td><td>S</td><td>A textual description of the processing level of the data.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>standard_name_vocabulary</td><td>S</td><td>Identifies the name of the controlled vocabulary or server from which variable standard_names are taken (e.g. 'http://vocab.nerc.ac.uk/collection/P07/current/' or 'CF Standard Name Table v73')</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>sdn_vocabulary</td><td>S</td><td>Identifies the name of the controlled vocabulary or server from which variable standard_names are taken (e.g. 'http://vocab.nerc.ac.uk/')</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>featureType</td><td>S</td><td>Geometry from the <a href='http://cfconventions.org/Data/cf-conventions/cf-conventions-1.7/cf-conventions.html#discrete-sampling-geometries'>CF Discrete Sampling Geometries (DSG) standard</a></td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>data_interval</td><td>S</td><td>Time interval of the data.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>comment</td><td>S</td><td>Miscellaneous information about the data or methods used to produce it.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 
