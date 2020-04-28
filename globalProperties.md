
# Global properties


This section contians metadata common to the whole file.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

(M = Mandatory, R = Recommended, O = Optional)
<table> 
<tr><td><strong>Property</strong></td><td><strong>Obligation</strong></td><td><strong>Occur.</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Reference</strong></td></tr> 
<tr><td>campaignName</td><td>M</td><td>1</td><td>Cruise ID or programme name</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>deploymentID</td><td>M</td><td>1</td><td>Deployment identifier such as the cruise name</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>institution</td><td>M</td><td>1</td><td>Full name of the lead institution responsible for the campaign</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>institutionID</td><td>M</td><td>1</td><td>Code identifying the lead institution of the cruise</td><td>Controlled code from vocabulary collection B75 </td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_sear
ch/B75/'>B75 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/B75/current/'>B75 linked data (SKOS)</a></td></tr> 
<tr><td>platform</td><td>M</td><td>1</td><td>Free text name of platform</td><td>Free text</td><td>&nbsp;</td></tr> 
<tr><td>platformTypeID</td><td>M</td><td>1</td><td>SeaDataNet code identifying the class of platform</td><td>Controlled code from vocabulary collection L06</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_searc
h/L06/'>L06 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/L06/current/'>L06 linked data (SKOS)</a></td></tr> 
<tr><td>platformModelID</td><td>M</td><td>1</td><td>SeaDataNet code identifying the model of platform</td><td>Controlled code from vocabulary collection B76</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_sear
ch/B76/'>B76 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/B76/current/'>B76 linked data (SKOS)</a></td></tr> 
<tr><td>platformTypeName</td><td>M</td><td>1</td><td>Full name of platform type</td><td>Controlled preflabel from vocabulary collection L06</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/L06/'>L06 sear
ch</a><br /><a href='http://vocab.nerc.ac.uk/collection/L06/current/'>L06 linked data (SKOS)</a></td></tr> 
<tr><td>platformModelName</td><td>M</td><td>1</td><td>Full name of platform model (i.e. preferred label of B76)</td><td>Controlled preflabel from vocabulary collection B76</td><td>&nbsp;</td></tr> 
<tr><td>platformICESid</td><td>R</td><td>0-1</td><td>ICES platform code</td><td>Controlled code from vocabulary collection C17</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/C17/'>C17 search</a><br /><a href='http://vocab.nerc.ac.uk/collection/C17/current/'>C17 linked data (SKOS)</a></td></tr> 
<tr><td>platformWMOid</td><td>R</td><td>0-1</td><td>WMO platform code</td><td>Controlled WMO code</td><td>&nbsp;</td></tr> 
<tr><td>platformIMOid</td><td>R</td><td>0-1</td><td>IMO platform code</td><td>Controlled IMO code</td><td>&nbsp;</td></tr> 
<tr><td>platformWIGOSid</td><td>O</td><td>0-1</td><td>WIGOS platform code</td><td>Controlled WIGOS code</td><td>&nbsp;</td></tr> 
<tr><td>title</td><td>M</td><td>1</td><td>Short description of file contents</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>conventions</td><td>M</td><td>1</td><td>Name of the conventions followed by the dataset</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>source</td><td>M</td><td>1</td><td>The method of production of the original data</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>history</td><td>M</td><td>1-n</td><td>"List of modifications to the data where each modification identified with a ISO 8601 date format (""YYYY-MM-DDThh:mm:ssZ"")"</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>references</td><td>O</td><td>0-n</td><td>Published or web-based references that describe the data or methods used to produce it</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>vocabularyConventions</td><td>M</td><td>1-n</td><td>A list of the URLs to controlled vocabulary collections used in the file</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>dateCreated</td><td>M</td><td>1</td><td>The date on which this version of the data was created. Metadata changes are not considered when assigning the date created.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>dateModified</td><td>M</td><td>1-n</td><td>The date on which the data was last modified. Note that this applies just to the data not the metadata.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>processingLevel</td><td>M</td><td>1</td><td>A textual description of the processing (or quality control) level of the data</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>dataInterval</td><td>M</td><td>1</td><td>Time interval of data</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 





