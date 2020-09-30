# Observed measurements

This section contains properties that are common to observed measurements in the file such as temperature and salinity.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Observation variables
---------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td><i>appropriate variable identifier</i>*</td><td>N</td><td>Contains environmental observations.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 
* Use identifiers specified in file format specifications

Observation variable attributes
-------------------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>long_name</td><td>S</td><td>A descriptive name that indicates a variable's content. This name is not standardised.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>standard_name</td><td>S</td><td>CF standard name that references a description of a variable's content in the standard name table.</td><td>P07 preferred label (if available)</td><td><a href='http://vocab.nerc.ac.uk/collection/P07/current/'>P07</a></td></tr> 
<tr><td>units</td><td>S</td><td>Units of a variable's content.</td><td>P06 alternative label</td><td><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06</a></td></tr> 
<tr><td>valid_min</td><td>N</td><td>Smallest valid value of a variable.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>valid_max</td><td>N</td><td>Largest valid value of a variable.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>ancillary_variables</td><td>S</td><td>Identifies a variable that contains closely associated data, e.g., the quality identifier of a data value.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>sdn_parameter_name</td><td>S</td><td>Preferred label from a NVS controlled vocabulary P01 term that defines variable.</td><td>P01 preferred label</td><td><a href='http://vocab.nerc.ac.uk/collection/P01/current/'>P01</a></td></tr> 
<tr><td>sdn_parameter_urn</td><td>S</td><td>URN for the from a NVS controlled vocabulary P01 term that defines the variable.</td><td>P01 URN</td><td><a href='http://vocab.nerc.ac.uk/collection/P01/current/'>P01</a></td></tr> 
<tr><td>sdn_uom_name</td><td>S</td><td>Preferred label from a NVS controlled vocabulary P06 term that defines the variable's units.</td><td>P06 preferred label</td><td><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06</a></td></tr> 
<tr><td>sdn_uom_urn</td><td>S</td><td>URN for the from a NVS controlled vocabulary P06 term that defines the variable's units.</td><td>P06 URN</td><td><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06</a></td></tr> 
<tr><td>coordinates</td><td>S</td><td>Identifies coordinate variables such as TIME. Coordinate variables are expressed as a blank-separated list if there is more than one coordinate variable for the metadata variable.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>atlantosEVid</td><td>S</td><td>Preferred label from a NVS controlled vocabulary A05 term that defines variable.</td><td>A05 preferred label</td><td><a href='http://vocab.nerc.ac.uk/collection/A05/current/'>A05</a></td></tr> 
<tr><td>atlantosEVname</td><td>S</td><td>URN for the from a NVS controlled vocabulary A05 term that defines the variable.</td><td>A05 URN</td><td><a href='http://vocab.nerc.ac.uk/collection/A05/current/'>A05</a></td></tr> 
<tr><td>instrument</td><td>S</td><td>A list of identifiers used in the file that identify the instruments that created the data. Use a blank, comma or newline separated lists if more than two instruments are assigned.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>calibration</td><td>S</td><td>A list of identifiers used in the file that identify the calibrations that created the data. Use a blank, comma or newline separated lists if more than two instruments are assigned.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>deployment</td><td>S</td><td>A list of identifiers used in the file that identify the deployments that were used to collect the data. Use a blank, comma or newline separated lists if more than two instruments are assigned.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 

