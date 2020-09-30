# Instrument installations

This metadata is used to describe an instrument instance's position, orientation and sampling depth referenced to a datum. The metadata are designed to identify an instrument's physical location over a valid time range (installation instance). A new installation record is created should an instrument's position, orientation or sampling depth change.

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Attributes
----------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>date_valid_from</td><td>Date</td><td>Date from which the installation record is valid.</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>date_valid_to</td><td>Date</td><td>End date of the installation record</td><td>ISO 8601</td><td>&nbsp;</td></tr> 
<tr><td>comment</td><td>S</td><td>Miscellaneous information about the installation.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 


Metadata variables
------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>position_datum</td><td>S</td><td>Plain language label that describes the coordinate reference point of an instrument's position expressed in a 3-dimensional coordinate system (e.g. the central reference point  a research vessel).</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>orientation_datum</td><td>S</td><td>Plain language label that describes the reference point of an instrument's orientation (e.g. the bow of the ship).</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>sample_depth_datum</td><td>S</td><td>Plain language label that describes the reference point of an instrument's sampling depth (e.g. sea level).</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>x <br /><a href='http://vocab.nerc.ac.uk/collection/W02/current/002/'>[sdn_variable]</a></td><td>D</td><td>The distance along the instrument mount centre line from the external coordinate reference point.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>y <br /><a href='http://vocab.nerc.ac.uk/collection/W02/current/003/'>[sdn_variable]</a></td><td>D</td><td>The vertical distance from the instrument mount centre line from the external coordinate reference point.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>z <br /><a href='http://vocab.nerc.ac.uk/collection/W02/current/004/'>[sdn_variable]</a></td><td>D</td><td>The distance across (perpendicular to) the instrument mount centre line from the external coordinate reference point.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>orientation</td><td>D</td><td>The rotational relationship of an instrument relative to an external coordinate reference point.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>sample_depth</td><td>D</td><td>The depth of the sampling point (positive = down)</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 

Metadata variable attributes
----------------------------
<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>long_name</td><td>S</td><td>A descriptive name that indicates a variable's content. This name is not standardised.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>units</td><td>S</td><td>Units of a variable's content.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>data_variable</td><td>S</td><td>The observed property to which the metadata applies (e.g. the detection limit of observed property temperature).</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
<tr><td>sdn_variable_name</td><td>S</td><td>Preferred label from a NVS controlled vocabulary term that defines the metadata variable.</td><td>NERC Vocabulary Server (NVS2.0) preferred label</td><td> <a href='http://vocab.nerc.ac.uk/'>NVS</a></td></tr> 
<tr><td>sdn_variable_url</td><td>S</td><td>URI for the from a NVS controlled vocabulary term that defines the metadata variable.</td><td>NERC Vocabulary Server (NVS2.0) URI</td><td> <a href='http://vocab.nerc.ac.uk/'>NVS</a></td></tr> 
<tr><td>sdn_uom_name</td><td>S</td><td>Preferred label from a NVS controlled vocabulary P06 term that defines the metadata's units.</td><td>P06 preferred label</td><td><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06</a></td></tr> 
<tr><td>sdn_uom_url</td><td>S</td><td>URI for the from a NVS controlled vocabulary P06 term that defines the metadata's units.</td><td>P06 URI</td><td><a href='http://vocab.nerc.ac.uk/collection/P06/current/'>P06</a></td></tr> 
<tr><td>coordinates</td><td>S</td><td>Identifies coordinate variables such as sample_depth_datum orientation_datum and/or position_datum. Coordinate variables are expressed as a blank-separated list if there is more than one coordinate variable for the metadata variable.</td><td>&nbsp;</td><td>&nbsp;</td></tr> 
</table> 
