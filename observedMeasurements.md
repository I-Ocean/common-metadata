# Observed measurements

This section contains properties that are common to observed environmental measurements in the file such as temperature and salinity.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

<table border="2" cellpadding="5"> 
<tr><td><strong>Property</strong></td><td><strong>Obligation</strong></td><td><strong>Occurrence</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Reference</strong></td></tr> 
<tr><td>variable name</td><td>M</td><td>1</td><td>A short local name (with no spaces) that is used to reference a variable in a file</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>long name</td><td>M</td><td>1</td><td>A free text descriptive name that indicates a variable's content.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>standard name</td><td>O</td><td>1</td><td>A Climate Forecast standard name that references a description of a variable's content.</td><td>Controlled preflabel from vocabulary collection P07</td><td><a href='https://www.bodc.ac.uk
/resources/vocabularies/vocabulary_search/P07/'>P07 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/P07/current/'>P07 linked data (SKOS)</a></td></tr> 
<tr><td>units</td><td>M</td><td>1</td><td>Units of a variable's content.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>ancillary variables</td><td>M</td><td>1</td><td>QC variables that contains closely associated data</td><td>Controlled codes from SeaDataNet collection C15</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_
search/C15/'>C15 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/C15/current/'>C15 linked data (SKOS)</a></td></tr> 
<tr><td>sdn parameter code</td><td>M</td><td>1</td><td>SeaDataNet URN or URL code that identifies the variable's content. Applicable to specified formats.</td><td>Controlled code from SeaDataNet collection P01</td><td><a href='https://ww
w.bodc.ac.uk/resources/vocabularies/vocabulary_search/P01/'>P01 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/P01/current/'>P01 linked data (SKOS)</a></td></tr> 
<tr><td>sdn uom code</td><td>M</td><td>1</td><td>SeaDataNet URN or URL code that identifies the variable's unit. Applicable to specified formats.</td><td>Controlled code from SeaDataNet collection P06</td><td><a href='https://www.bodc.ac
.uk/resources/vocabularies/vocabulary_search/P06/'>P06 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06 linked data (SKOS)</a></td></tr> 
<tr><td>sdn parameter name</td><td>M</td><td>1</td><td>Full name of SeaDataNet parameter</td><td>Controlled preflabel from SeaDataNet collection P01</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/P01/'>P
01 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/P01/current/'>P01 linked data (SKOS)</a></td></tr> 
<tr><td>sdn uom name</td><td>M</td><td>1</td><td>Full name of SeaDataNet unit</td><td>Controlled preflabel from SeaDataNet collection P06</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/P06/'>P06 search</
a><br /><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06 linked data (SKOS)</a></td></tr> 
<tr><td>FillValue</td><td>M</td><td>1</td><td>A value used to represent missing or undefined data.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>comment</td><td>R</td><td>0-n</td><td>"List of miscellaneous information about the data where each comment is identified with a ISO 8601 date format (""YYYY-MM-DDThh:mm:ssZ"")"</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>instrument</td><td>R</td><td>0-n</td><td>A list of instrument identifiers used to measure the variable</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>atlantos ev id</td><td>O</td><td>0-1</td><td>AtlantOS identifier for an Essential Variable</td><td>Controlled code from vocabuary collection A05</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/A05
/'>A05 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/A05/current/'>A05 linked data (SKOS)</a></td></tr> 
<tr><td>atlantos ev name</td><td>O</td><td>0-1</td><td>Full name of AtlantOS Essential Variable</td><td>Controlled preflabel from vocabulary collection A05</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/
A05/'>A05 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/A05/current/'>A05 linked data (SKOS)</a></td></tr> 
<tr><td>method</td><td>R</td><td>0-1</td><td>A description of the method used to obtain the variable</td><td>Controlled preflabel from vocabulary collection A05</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_se
arch/S05/'>S05 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/S05/current/'>S05 linked data (SKOS)</a></td></tr> 
<tr><td>method id</td><td>R</td><td>0-1</td><td>An identifier to reference the method used to obtain the variable</td><td>Controlled preflabel from vocabulary collection A05</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/
vocabulary_search/S05/'>S05 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/S05/current/'>S05 linked data (SKOS)</a></td></tr> 
<tr><td>uncertainty</td><td>O</td><td>0-1</td><td>A quantity associated to the uncertainty associated to a variable</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>application</td><td>O</td><td>0-1</td><td>A description of the applications that the data are suited to</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>application id</td><td>O</td><td>0-1</td><td>An identifier that defines the applications</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 
