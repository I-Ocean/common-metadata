# Deployment properties


This section contians metadata variables and attributes common to platform deployments.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

Attributes
----------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>date_valid_from</td><td>Date</td><td>Start date of deployment.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>date_valid_to</td><td>Date</td><td>End date of deployment.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>comment</td><td>S</td><td>Miscellaneous information about the deployment.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 

Metadata variables
------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>Deployment_id</td><td>S</td><td>An identifier for the deployment such as a cruise ID.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>owner</td><td>S</td><td>The name of the institution or body responsible for the deployment.</td><td>B75 preferred label</td><td><a href='http://vocab.nerc.ac.uk/collection/B75/current/'>B75</a></td></tr> 
<tr><td>owner_id</td><td>S</td><td>Institution or body identifier.</td><td>B75 URI</td><td><a href='http://vocab.nerc.ac.uk/collection/B75/current/'>B75</a></td></tr> 
<tr><td>campaign_name</td><td>S</td><td>The name of the activity to which the deployment belongs. </td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>platforms</td><td>S</td><td>Identifier used in the file that identifies the deployment platform.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>instruments</td><td>S</td><td>A list of identifiers used in the file that identify the instruments used in the deployment.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 
