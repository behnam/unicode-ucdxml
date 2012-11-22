XML Representation of Unicode 5.1.0 UCD

This directory contains the representation in XML of version 5.1.0 of
the UCD, using the schema defined by UAX 42, "Unicode Character
Database in XML".

While every effort has been made to ensure consistency of the 
XML representation with the UCD files, there may be some errors;
the UCD files are authoritative.


There are six files, available in zip/jar format; the size is that of
the archive:

                    flat         grouped

no Unihan data       481 KB          327 KB
Unihan data only   4,967 KB        4,971 KB
complete UCD       6,084 KB        5,298 KB

The flat versions do not use the group mechanism. The grouped versions
use the group mechanism, with groups corresponding approximately to
the blocks (a few blocks have been subdivided).

The no Unihan data files do not contain the properties expressed only
in the Unihan.txt UCD data file. The Unihan data files contain only
the properties and code points expressed in Unihan.txt. The complete
UCD files reflect the complete UCD data.

