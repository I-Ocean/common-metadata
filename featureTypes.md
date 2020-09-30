# Feature types

A discrete geometry (featureType) of a file can be associated with a variable that identifies instances of the feature and provide other metadata as needed to describe it. 

To request additions or changes please raise a new [GitHub issue](https://github.com/I-Ocean/common-metadata/issues/new)

The "Data type" values are S for string, N for numeric, Date for a date string and D for the type of the data variable.

Feature type variables
----------------------

<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>trajectory</td><td>S</td><td>Trajectory identifier that identifies each instance of the feature in a series of trajectories.</td><td> This cannot be the same the as the deployment identifier.</td><td>&nbsp;</td></tr> 
</table> 


Feature type variable attributes
--------------------------------

<table border="2" cellpadding="5"> 
<tr><td><strong>Name</strong></td><td><strong>Data type</strong></td><td><strong>Description</strong></td><td><strong>Allowed values</strong></td><td><strong>Link</strong></td></tr> 
<tr><td>long_name</td><td>S</td><td>A descriptive name that indicates a variable's content. This name is not standardised.</td><td>'trajectory'</td><td>&nbsp;</td></tr> 
<tr><td>cf_role</td><td>S</td><td>Identifies the roles of variables that identify features in discrete sampling geometries.</td><td>'trajectory_id'</td><td>&nbsp;</td></tr> 
</table>
