# Platform properties

This section contians metadata variables and attributes common to the platforms used to house sensors.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Attributes
----------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>date_valid_from</td><td>Date</td><td>Commission date.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>date_valid_to</td><td>Date</td><td>De-commission date.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>comment</td><td>S</td><td>Miscellaneous information about the platform.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 

Metadata variables
------------------

<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>platform_name <br /><a href='http://vocab.nerc.ac.uk/collection/W07/current/IDEN0002/'>[sdn_variable]</a></td><td>S</td><td>Plain language label for the platform.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>platform_model_id<br /><a href='http://vocab.nerc.ac.uk/collection/W07/current/IDEN0003/'>[sdn_variable]</td><td>S</td><td>URI identifier of the platform design.</td><td>B76 URI</td><td><a href='http://vocab.nerc.ac.uk/collection/B76/current/'>B76</a></td></tr> 
<tr><td>platform_ices_id <br /> <a href='http://vocab.nerc.ac.uk/collection/W07/current/IDEN0001/'>[sdn_variable]</a></td><td>S</td><td>ICES platform code.</td><td>C17 URI</td><td><a href='http://vocab.nerc.ac.uk/collection/C17/current/'>C17</a></td></tr> 
<tr><td>platform_imo_id </td><td>S</td><td>IMO platform number.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>platform_call_sign <br /><a href='http://vocab.nerc.ac.uk/collection/W07/current/IDEN0010/'>[sdn_variable]</a></td><td>S</td><td>Platform call sign.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 

Metadata variable attributes
----------------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>long_name</td><td>S</td><td>A descriptive name that indicates a variable's content. This name is not standardised.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>sdn_variable_name</td><td>S</td><td>Preferred label from a NVS controlled vocabulary term that defines the metadata variable.</td><td>NERC Vocabulary Server (NVS2.0) preferred label</td><td> <a href='http://vocab.nerc.ac.uk/'>NVS</a></td></tr> 
<tr><td>sdn_variable_url</td><td>S</td><td>URI from a NVS controlled vocabulary term that defines the metadata variable.</td><td>NERC Vocabulary Server (NVS2.0) URI</td><td> <a href='http://vocab.nerc.ac.uk/'>NVS</a></td></tr> 
</table> 
