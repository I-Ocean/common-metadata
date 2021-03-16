# Deployment properties


This section contians metadata variables and attributes common to platform deployments.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Attributes
----------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>date_valid_from</td><td>Date</td><td>Start date of deployment.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>date_valid_to</td><td>Date</td><td>End date of deployment.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>platform</td><td>S</td><td>A list of identifiers used in the file that identify the instances of platforms used in the deployment. Use a blank, comma or newline separated lists if more than two platforms are assigned.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>instrument</td><td>S</td><td>A list of identifiers used in the file that identify the instances of instruments used in the deployment. Use a blank, comma or newline separated lists if more than two instruments are assigned.</td><td>&nbsp;</td><td>&nbsp;</td></tr>
<tr><td>comment</td><td>S</td><td>Miscellaneous information about the deployment.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 

Metadata variables
------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>Deployment_id</td><td>S</td><td>An identifier for the deployment such as a cruise ID.</td><td>&nbsp;</td><td>&nbsp;</td></tr>  
<tr><td>owner_id</td><td>S</td><td>Institution or body identifier.</td><td>B75 URI</td><td><a href='http://vocab.nerc.ac.uk/collection/B75/current/'>B75</a></td></tr> 
<tr><td>campaign_name</td><td>S</td><td>The name of the activity to which the deployment belongs. </td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 

Metadata variable attributes
----------------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>long_name</td><td>S</td><td>A descriptive name that indicates a variable's content. This name is not standardised.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>sdn_variable_name</td><td>S</td><td>Preferred label from a NVS controlled vocabulary term that defines the metadata variable.</td><td>NVS preferred label</td><td> <a href='http://vocab.nerc.ac.uk/'>NVS</a></td></tr> 
<tr><td>sdn_variable_urn</td><td>S</td><td>URN identifier containing a NVS controlled vocabulary term identifier that defines the metadata variable.</td><td>SDN:<i>collection ID</i>::<i>term ID</i><br />e.g. SDN:W07::IDEN0002</td><td> <a href='http://vocab.nerc.ac.uk/'>NVS</a></td></tr>  
</table> 
