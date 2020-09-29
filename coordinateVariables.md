# Coordinate Variables

This section contains properties that are common to variables that align observations such as time, geographical position and depth.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Coordinate variables
-----------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>TIME <br /><a href='http://vocab.nerc.ac.uk/standard_name/time/'>[standard_name]</a><br /><a href='#TimeUnit'>[units]</a><br /> <a href='CJDY1101/'>[sdn_parameter]</a><br /> <a href='UTAA/'>[sdn_uom]</a></td><td>N</td><td>Numeric time value referenced to a time origin</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>LATITUDE <br /><a href='http://vocab.nerc.ac.uk/standard_name/latitude/'>[standard_name]</a><br /><a href='#LatUnit'>[units]</a><br /> <a href='http://vocab.nerc.ac.uk/P01/current/ALATGP01/'>[sdn_parameter]</a><br /> <a href='http://vocab.nerc.ac.uk/P06/current/DEGN/'>[sdn_uom]</a></td><td>N</td><td>Geographic coordinate that specifies the north-south position of a point on the Earth's surface.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>LONGITUDE <br /><a href='http://vocab.nerc.ac.uk/standard_name/longitude/'>[standard_name]</a><br /><a href='#LonUnit'>[units]</a><br /> <a href='http://vocab.nerc.ac.uk/P01/current/ALONGP01/'>[sdn_parameter]</a><br /> <a href='http://vocab.nerc.ac.uk/P06/current/DEGE/'>[sdn_uom]</a></td><td>N</td><td>Geographic coordinate that specifies the west-east position of a point on the Earth's surface.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>DEPTH <br /><a href='http://vocab.nerc.ac.uk/standard_name/depth/'>[standard_name]</a><br /><a href='#TimeUnit'>[units]</a><br /> <a href='http://vocab.nerc.ac.uk/P01/current/ADEPZZ01/'>[sdn_parameter]</a><br /> <a href='http://vocab.nerc.ac.uk/P06/current/ULAA/'>[sdn_uom]</a></td><td>N</td><td>Distance of a point below sea level (positive="down" values).</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 


UDunits
-------
<table border="2" cellpadding="5">
  <tr><td><strong>Coordinate variable</strong></td><td><strong>Unit</strong></td></tr>
  <tr><td>TIME</td><td id='TimeUnit'>days since -4713-01-01T00:00:00Z</td></tr>
  <tr><td>LATITUDE</td><td>degrees_north</td></tr>
  <tr><td>LONGITUDE</td><td>degrees_east</td></tr>
