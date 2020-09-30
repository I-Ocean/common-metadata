# Calibrations

Properties of calibrations that are relevant to instrument instances or observed properties. The metadata are designed to identify an instance of a calibration. In other words, one input unit and one output unit. Thus, manufacturer calibrations for temperature and salinity derived from a thermosalinograph would require separate calibration instances.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Attributes
----------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>date_valid_from</td><td>Date</td><td>Date calibration valid from.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>date_valid_to</td><td>Date</td><td>Date calibration valid to.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>comment</td><td>S</td><td>Miscellaneous information about the calibration.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 

Metadata variables
------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>calibration_function</td><td>S</td><td>Plain language label for the calibration.</td><td></td><td></td></tr> 
<tr><td>input_units</td><td>S</td><td>Units of the source variable.</td><td>P06 preferred label</td><td><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06</a></td></tr> 
<tr><td>input_units_id</td><td>S</td><td>URI from a NVS controlled vocabulary P06 term that defines the source variable's units.</td><td>P06 URI</td><td><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06</a></td></tr> 
<tr><td>output_units</td><td>S</td><td>Units of the result variable.</td><td>P06 preferred label</td><td><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06</a></td></tr> 
<tr><td>output_units_id</td><td>S</td><td>URI from a NVS controlled vocabulary P06 term that defines the result variable's units.</td><td>P06 URI</td><td><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06</a></td></tr> 
<tr><td>calibration_coefficients</td><td>S</td><td>JSON representation of the calibration coefficients</td><td></td><td></td></tr> 
</table> 

Metadata variable attributes
----------------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>long_name</td><td>S</td><td>A descriptive name that indicates a variable's content. This name is not standardised.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>sdn_variable_name</td><td>S</td><td>Preferred label from a NVS controlled vocabulary term that defines the metadata variable.</td><td>NERC Vocabulary Server (NVS2.0) preferred label</td><td> <a href='http://vocab.nerc.ac.uk/'>NVS</a></td></tr> 
<tr><td>sdn_variable_url</td><td>S</td><td>URI from a NVS controlled vocabulary term that defines the metadata variable.</td><td>NERC Vocabulary Server (NVS2.0) URI</td><td> <a href='http://vocab.nerc.ac.uk/'>NVS</a></td></tr> 
</table> 
