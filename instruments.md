# Instruments

Properties that accurately identify the instruments that are used to measure environmental observations and help to interpret their variables, putting data into context.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

(M = Mandatory, R = Recommended, O = Optional)
<table> 
<tr><td><strong>Property</strong></td><td><strong>Obligation</strong></td><td><strong>Occur.</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Reference</strong></td></tr> 
<tr><td>identifier</td><td>M</td><td>1</td><td>An identifier such as a UUID, used to reference an instrument and associate metadata. It should contain no spaces.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>instrumentName</td><td>M</td><td>1</td><td>The full name of an instrument used in the file</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>serialNumber</td><td>M</td><td>1</td><td>The serial number of the instrument</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>modelID</td><td>M</td><td>1</td><td>A code that identifies the instrument model</td><td>Controlled code from vocabulary collection L22</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/L22/'>L22 se
arch</a><br /><a href='http://vocab.nerc.ac.uk/collection/L22/current/'>L22 linked data (SKOS)</a></td></tr> 
<tr><td>modelName</td><td>M</td><td>1</td><td>The full name of the instrument model</td><td>Controlled preflabel from vocabulary collection L22</td><td><a href='https://www.bodc.ac.uk/resources/vocabularies/vocabulary_search/L22/'>L22 s
earch</a><br /><a href='http://vocab.nerc.ac.uk/collection/L22/current/'>L22 linked data (SKOS)</a></td></tr> 
<tr><td>instrumentPID</td><td>R</td><td>0-1</td><td>A persistent identifier for the instrument (not data) such as a DOI or Handle (e.g. a Research Data Alliance PIDINST identifier)</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>calibrationDate</td><td>R</td><td>0-n</td><td>The date of a manufacturer or laboratory calibration to convert raw output to engineering units</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>calibrationDateUnits</td><td>R</td><td>0-n</td><td>The date units</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>calibrationFunction</td><td>O</td><td>0-n</td><td>The function used to calibrate observations</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>calibrationCoefficients</td><td>R</td><td>0-n</td><td>The coefficients used in the calibration</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>calibrationPreUnits</td><td>O</td><td>0-n</td><td>The units of the input variable to the calibration</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>calibrationPostUnits</td><td>O</td><td>0-n</td><td>The units of the output variable to the calibration</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>xyzPositionDate</td><td>O</td><td>0-n</td><td>The date of the current instrument position on an instrument mount</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>xyzPostionDateUnits</td><td>O</td><td>0-n</td><td>The date units</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>xPosition</td><td>O</td><td>0-n</td><td>The distance along the instrument mount centre line from the external coordinate reference point.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>xPositionUnits</td><td>O</td><td>0-n</td><td>The units of the position</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>yPosition</td><td>O</td><td>0-n</td><td>The vertical distance from the instrument mount centre line from the external coordinate reference point.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>yPositionUnits</td><td>O</td><td>0-n</td><td>The units of the position</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>zPosition</td><td>O</td><td>0-n</td><td>The distance across (perpendicular to) the instrument mount centre line from the external coordinate reference point.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>zPositionUnits</td><td>O</td><td>0-n</td><td>The units of the position</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>xyzDatum</td><td>O</td><td>0-n</td><td>The external reference point such as the central reference point of a research vessel</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>orientationDate</td><td>O</td><td>0-n</td><td>The date of the current instrument orientation</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>orientationDateUnits</td><td>O</td><td>0-n</td><td>The orientation date units</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>orientation</td><td>O</td><td>0-n</td><td>The rotational relationship of an instrument relative to an external coordinate reference point.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>orientationDatum</td><td>O</td><td>0-n</td><td>The external reference point of the instrument orientation</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>comment</td><td>R</td><td>0-n</td><td>"List of miscellaneous information about the instrument where each comment is identified with a ISO 8601 date format (""YYYY-MM-DDThh:mm:ssZ"")"</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 
