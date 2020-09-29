# Quality indicator properties

This metadata is used to describe quality indicators associated to observation variables. 

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Quality indicator variables
---------------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td><i>appropriate QC identifier</i>*</td><td>N</td><td>Contains quality control identifiers for environmental observations.</td><td>L20 identifier suffix</td><td><a href='http://vocab.nerc.ac.uk/collection/L20/current/'>L20</a></td></tr> 
</table> 
* Use identifiers specified in file format specifications

Quality indicator variable attributes
-------------------------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>long_name</td><td>S</td><td>A descriptive name that indicates a variable's content. This name is not standardised.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>Conventions</td><td>S</td><td>Name of the conventions followed by the quality indicators.</td><td>'SeaDataNet quality flag'</td><td>&nbsp;</td></tr> 
<tr><td>coordinates</td><td>S</td><td>Identifies coordinate variables such as TIME. Coordinate variables are expressed as a blank-separated list if there is more than one coordinate variable for the metadata variable.</td><td>'SeaDataNet measurand qualifier flags'</td><td>&nbsp;</td></tr> 
<tr><td>sdn_conventions_urn</td><td>S</td><td>URN prefix of convention followed by quality indicators.</td><td>'SDN:L20::'</td><td>&nbsp;</td></tr> 
<tr><td>flag_values</td><td>D</td><td>Provides a list of the flag values. Use in conjunction with flag_meanings.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>flag_meanings</td><td>S</td><td>Use in conjunction with flag_values to provide descriptive words or phrases for each flag value. If multi-word phrases are used to describe the flag values, then the words within a phrase should be connected with underscores.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 
