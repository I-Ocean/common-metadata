# Grid mapping

This metadata is used to declare the coordinate reference system (CRS) used for the horizontal spatial coordinate values in a file. Currently, grids are mapped to WGS 84, the latitude/longitude coordinate system based on the Earth's center of mass.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Grid mapping variables
----------------------

<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>crs</td><td>N</td><td>Empty variable</td><td>0</td><td>&nbsp;</td></tr> 


</table> 

Grid mapping variable attributes
--------------------------------

<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>grid_mapping_name</td><td>S</td>Grid mapping from <a href='http://cfconventions.org/Data/cf-conventions/cf-conventions-1.8/cf-conventions.html#appendix-grid-mappings'>CF conventions</a>.<td></td><td>'latitude_longitude'</td><td>&nbsp;</td></tr>
<tr><td>epsg_code</td><td>S</td>EPSG Geodetic Parameter Dataset code.<td></td><td>'EPSG:4326'</td><td><a href='http://www.epsg-registry.org/'>Registry</a></td></tr>
<tr><td>semi_major_axis</td><td>S</td><td>Specifies the length, in metres, of the semi-major axis of the ellipsoidal figure associated with the geodetic datum and used to approximate the shape of the Earth.</td><td>6378137.</td><td>&nbsp;</td></tr>
<tr><td>inverse_flattening</td><td>S</td><td>Used to specify the inverse flattening (1/f) of the ellipsoidal figure associated with the geodetic datum and used to approximate the shape of the Earth.</td><td>298.257223563</td><td>&nbsp;</td></tr>
</table> 

