# Coordinate Variables

Properties that align variables such as time and geographical position.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

<table border="2" cellpadding="5"> 
<tr><td><strong>Property</strong></td><td><strong>Obligation</strong></td><td><strong>Occurence</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Reference</strong></td></tr> 
<tr><td>variable name</td><td>M</td><td>1</td><td>A short local name (with no spaces) that is used to reference a variable in a file</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>long name</td><td>M</td><td>1</td><td>A free text descriptive name that indicates a variable's content.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>standard name</td><td>R</td><td>0-1</td><td>A Climate Forecast standard name that references a description of a variable's content.</td><td>Controlled preflabel from vocabulary collection P07</td><td><a href='https://www.bodc.ac.
uk/resources/vocabularies/vocabulary_search/P07/'>P07 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/P07/current/'>P07 linked data (SKOS)</a></td></tr> 
<tr><td>units</td><td>M</td><td>1</td><td>Units of a variable's content.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>calendar</td><td>R</td><td>0-1</td><td>Recommended for time coordinates. Calendar used for encoding time axes.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>axis</td><td>R</td><td>0-1</td><td>Identifies latitude (Y), longitude (X), depth (Z) and time (T) axes</td><td>X, Y, Z or T</td><td>&nbsp;</td></tr> 
<tr><td>ancillary variables</td><td>M</td><td>1</td><td>QC variables that contains closely associated data</td><td>Controlled codes from SeaDataNet collection C15</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_
search/C15/'>C15 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/C15/current/'>C15 linked data (SKOS)</a></td></tr> 
<tr><td>positive</td><td>O</td><td>0-1</td><td>Recommended for depth coordinates. Direction of increasing vertical coordinate value.</td><td> 'up' or 'down'</td><td>&nbsp;</td></tr> 
<tr><td>sdn parameter code</td><td>M</td><td>1</td><td>SeaDataNet URN or URL code that identifies the variable's content. URN/URL will be applicable to specified formats.</td><td>Controlled code from SeaDataNet collection P01</td><td><a 
href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/P01/'>P01 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/P01/current/'>P01 linked data (SKOS)</a></td></tr> 
<tr><td>sdn uom code</td><td>M</td><td>1</td><td>SeaDataNet code that identifies the variable's unit. Applicable to specified formats.</td><td>Controlled code from SeaDataNet collection P06</td><td><a href='https://www.bodc.ac.uk/resourc
es/vocabularies/vocabulary_search/P06/'>P06 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06 linked data (SKOS)</a></td></tr> 
<tr><td>sdn parameter name</td><td>M</td><td>1</td><td>Full name of SeaDataNet parameter</td><td>Controlled preflabel from SeaDataNet collection P01</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/P01/'>P
01 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/P01/current/'>P01 linked data (SKOS)</a></td></tr> 
<tr><td>sdn uom name</td><td>M</td><td>1</td><td>Full name of SeaDataNet unit</td><td>Controlled preflabel from SeaDataNet collection P06</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/P06/'>P06 search</
a><br /><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06 linked data (SKOS)</a></td></tr> 
<tr><td>grid mapping</td><td>O</td><td>0-1</td><td>Defines a grid mapping for positional coordinates (lat and lon)</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>FillValue</td><td>M</td><td>1</td><td>A value used to represent missing or undefined data. Allowed for spatial variables (e.g. latitude, longitude and depth) but not allowed for time where there should be no gaps</t
d><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>comment</td><td>R</td><td>0-n</td><td>List of miscellaneous information about the data where each comment is identified with a ISO 8601 date format (""YYYY-MM-DDThh:mm:ssZ"")</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>instrument</td><td>R</td><td>0-n</td><td>A list of instrument identifiers used to measure the variable</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 


