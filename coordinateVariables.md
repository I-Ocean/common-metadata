# Coordinate Variables

This section contains properties that are common to variables that align observations such as time, geographical position and depth.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Coordinate variables
--------------------
<table border="2" cellpadding="5"> 
<tr><td id='CoordVar'><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>TIME <br /><a href='http://vocab.nerc.ac.uk/standard_name/time/'>[standard_name]</a><br /><a href='#TimeUnit'>[units]</a><br /> <a href='CJDY1101/'>[sdn_parameter]</a><br /> <a href='UTAA/'>[sdn_uom]</a></td><td>N</td><td>Numeric time value referenced to a time origin</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>LATITUDE <br /><a href='http://vocab.nerc.ac.uk/standard_name/latitude/'>[standard_name]</a><br /><a href='#LatUnit'>[units]</a><br /> <a href='http://vocab.nerc.ac.uk/P01/current/ALATGP01/'>[sdn_parameter]</a><br /> <a href='http://vocab.nerc.ac.uk/P06/current/DEGN/'>[sdn_uom]</a></td><td>N</td><td>Geographic coordinate that specifies the north-south position of a point on the Earth's surface.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>LONGITUDE <br /><a href='http://vocab.nerc.ac.uk/standard_name/longitude/'>[standard_name]</a><br /><a href='#LonUnit'>[units]</a><br /> <a href='http://vocab.nerc.ac.uk/P01/current/ALONGP01/'>[sdn_parameter]</a><br /> <a href='http://vocab.nerc.ac.uk/P06/current/DEGE/'>[sdn_uom]</a></td><td>N</td><td>Geographic coordinate that specifies the west-east position of a point on the Earth's surface.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>DEPTH <br /><a href='http://vocab.nerc.ac.uk/standard_name/depth/'>[standard_name]</a><br /><a href='#DepUnit'>[units]</a><br /> <a href='http://vocab.nerc.ac.uk/P01/current/ADEPZZ01/'>[sdn_parameter]</a><br /> <a href='http://vocab.nerc.ac.uk/P06/current/ULAA/'>[sdn_uom]</a></td><td>N</td><td>Distance of a point below sea level (positive="down" values).</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 


Coordinate variable attributes
------------------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>long_name</td><td>S</td><td>A descriptive name that indicates a variable's content. This name is not standardised.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>standard_name</td><td>S</td><td>CF standard name that references a description of a variable's content in the standard name table.</td><td>P07 preferred label</td><td>See <a href='#CoordVar'>'coordinate variables</a></td></tr> 
<tr><td>units</td><td>S</td><td>Units of a variable's content.</td><td><a href='https://www.unidata.ucar.edu/software/udunits/'>Udunits</a></td><td>See <a href='#CoordVar'>'coordinate variables</a></td></tr> 
<tr><td>calendar</td><td>S</td><td>Calendar used for encoding time axes.</td><td>'gregorian' or 'julian'</td><td>&nbsp;</td></tr> 
<tr><td>valid_min</td><td>N</td><td>Smallest valid value of a variable.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>valid_max</td><td>N</td><td>Largest valid value of a variable.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>axis</td><td>S</td><td>Identifies latitude, longitude, vertical or time axes.</td><td>'T', 'X', 'Y', 'Z' (for time, longitude, latitude, depth)</td><td>&nbsp;</td></tr> 
<tr><td>positive</td><td>S</td><td>Direction of increasing vertical coordinate value.</td><td>'down'</td><td>&nbsp;</td></tr> 
<tr><td>ancillary_variables</td><td>S</td><td>Identifies a variable that contains closely associated data e.g., the quality identifier of a data value.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>sdn_parameter_name</td><td>S</td><td>Preferred label from a NVS controlled vocabulary P01 term that defines variable.</td><td>P01 preferred label</td><td>See <a href='#CoordVar'>'coordinate variables</a></td></tr> 
<tr><td>sdn_parameter_urn</td><td>S</td><td>URN for the from a NVS controlled vocabulary P01 term that defines the variable.</td><td>P01 URN</td><td>See <a href='#CoordVar'>'coordinate variables</a></td></tr> 
<tr><td>sdn_uom_name</td><td>S</td><td>Preferred label from a NVS controlled vocabulary P06 term that defines the variable's units.</td><td>P06 preferred label</td><td>See <a href='#CoordVar'>'coordinate variables</a></td></tr> 
<tr><td>sdn_uom_urn</td><td>S</td><td>URN for the from a NVS controlled vocabulary P06 term that defines the variable's units.</td><td>P06 URN</td><td>See <a href='#CoordVar'>'coordinate variables</a></td></tr> 
<tr><td>grid_mapping</td><td>S</td><td>Identifies a variable that defines a grid mapping.</td><td>'crs'</td><td>&nbsp;</td></tr> 
<tr><td>instrument</td><td>S</td><td>A list of identifiers used in the file that identify the instruments that created the data. Use a blank, comma or newline separated lists if more than two instruments are assigned.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>calibration</td><td>S</td><td>A list of identifiers used in the file that identify the calibrations that created the data. Use a blank, comma or newline separated lists if more than two instruments are assigned.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>deployment</td><td>S</td><td>A list of identifiers used in the file that identify the deployments that were used to collect the data. Use a blank, comma or newline separated lists if more than two instruments are assigned.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 


UDunits
-------
<table border="2" cellpadding="5">
  <tr><td><strong>Coordinate variable</strong></td><td><strong>Unit</strong></td></tr>
  <tr><td>TIME</td><td id='TimeUnit'>days since -4713-01-01T00:00:00Z</td></tr>
  <tr><td>LATITUDE</td><td id='LatUnit'>degrees_north</td></tr>
  <tr><td>LONGITUDE</td><td id='LonUnit'>degrees_east</td></tr>
  <tr><td>DEPTH</td><td id='DepUnit'>m</td></tr>
  </table>
  
