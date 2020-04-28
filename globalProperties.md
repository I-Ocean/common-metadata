
# Global properties


This section contians metadata common to the whole file.

<table>
<tr><td><strong>Property</strong></td><td><strong>Obligation</strong></td><td><strong>Occurence</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Reference</strong></td></tr>
<tr><td>campaign name</td><td>M</td><td>1</td><td>Cruise ID or programme name</td><td>&nbsp;</td><td>&nbsp;</td></tr>
<tr><td>deployment id</td><td>M</td><td>1</td><td>Deployment identifier such as the cruise name</td><td>&nbsp;</td><td>&nbsp;</td></tr>
<tr><td>institution</td><td>M</td><td>1</td><td>Full name of the lead institution responsible for the campaign</td><td>&nbsp;</td><td>&nbsp;</td></tr>
<tr><td>institution id</td><td>M</td><td>1</td><td>Code identifying the lead institution of the cruise</td><td>Controlled code from vocabulary collection B75 </td><td>https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/B75/</td></tr>
<tr><td>platform</td><td>M</td><td>1</td><td>Free text name of platform</td><td>Free text</td><td>&nbsp;</td></tr>
<tr><td>platform type id</td><td>M</td><td>1</td><td>SeaDataNet code identifying the class of platform</td><td>Controlled code from vocabulary collection L06</td><td>https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/L06/</td></tr>
<tr><td>platform model id</td><td>M</td><td>1</td><td>SeaDataNet code identifying the model of platform</td><td>Controlled code from vocabulary collection B76</td><td>https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/B76/</td></tr>
<tr><td>platform type name</td><td>M</td><td>1</td><td>Full name of platform type</td><td>Controlled preflabel from vocabulary collection L06</td><td>https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/L06/</td></tr>
<tr><td>platform model name</td><td>M</td><td>1</td><td>Full name of platform model (i.e. preferred label of B76)</td><td>Controlled preflabel from vocabulary collection B76</td><td>&nbsp;</td></tr>
<tr><td>platform ices id</td><td>R</td><td>0-1</td><td>ICES platform code</td><td>Controlled code from vocabulary collection C17</td><td>https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/C17/</td></tr>
<tr><td>platform wmo id</td><td>R</td><td>0-1</td><td>WMO platform code</td><td>Controlled WMO code</td><td>&nbsp;</td></tr>
<tr><td>platform imo id</td><td>R</td><td>0-1</td><td>IMO platform code</td><td>Controlled IMO code</td><td>&nbsp;</td></tr>
<tr><td>platform wigos id</td><td>O</td><td>0-1</td><td>WIGOS platform code</td><td>Controlled WIGOS code</td><td>&nbsp;</td></tr>
<tr><td>title </td><td>M</td><td>1</td><td>Short description of file contents</td><td>&nbsp;</td><td>&nbsp;</td></tr>
<tr><td>conventions</td><td>M</td><td>1</td><td>Name of the conventions followed by the dataset</td><td>&nbsp;</td><td>&nbsp;</td></tr>
<tr><td>source</td><td>M</td><td>1</td><td>The method of production of the original data</td><td>&nbsp;</td><td>&nbsp;</td></tr>
<tr><td>history</td><td>M</td><td>1-n</td><td>"List of modifications to the data where each modification identified with a ISO 8601 date format (""YYYY-MM-DDThh:mm:ssZ"")"</td><td>&nbsp;</td><td>&nbsp;</td></tr>
<tr><td>references</td><td>O</td><td>0-n</td><td>Published or web-based references that describe the data or methods used to produce it</td><td>&nbsp;</td><td>&nbsp;</td></tr>
<tr><td>vocabulary conventions</td><td>M</td><td>1-n</td><td>A list of the URLs to controlled vocabulary collections used in the file</td><td>&nbsp;</td><td>&nbsp;</td></tr>
</table>




