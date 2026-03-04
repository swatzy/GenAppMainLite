SQLite Library

Copyright 2012-14, James David Powell
All rights reserved.

Author:	 James David Powell
LAVA Name: drjdpowell
Contact Info:	Contact via PM on lavag.org 

LabVIEW Versions:
2011-2013

Dependencies:
none

Description:
SQLite3 is a very light-weight, server-less, database-in-a-file library. See www.SQLite.org. This package is a wrapper of the SQLite3 C library and follows it closely.

There are basically two use modes: (1) calling “Execute SQL” on a Connection to run SQL scripts (and optionally return 2D arrays of strings or variants from an SQL statement that returns results); and (2) “Preparing" a single SQL statement and executing it step-by-step explicitly. The advantage of the later is the ability to “Bind” parameters to the statement, and get the column data back in the desired datatype. The “Bind” and “Get Column” VIs are set as properties of the “SQL Statement” object, for convenience in working with large numbers of them.

Installation and instructions:
Use VI Package Manager

Examples:
<LabVIEW>\examples\drjdpowell\SQLite LabVIEW

Known Issues:


Acknowledgements:


Version History:
See Code Repository page on LAVAg.org

License:
Distributed under the Simplified BSD License

Support:
If you have any problems with this code or want to suggest features:
please go to lavag.org and Navigate to LAVA > Resources > Code Repository (Certified) and
search for the SQLite LabVIEW support page.
