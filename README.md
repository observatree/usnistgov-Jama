The JAMA Project by The MathWorks and NIST
==========================================

This project is derived from Jama-1.0.3.zip downloaded on 2018-12-08 from the
[JAMA Project](https://math.nist.gov/javanumerics/jama/) home page.

The aim of the present project is to (a) get the sources into GitHub, and
(b) minimally reorganize those sources to conform to Maven conventions.

In the present project, the test code is executed using Maven:

```mvn exec:java -Dexec.mainClass="Jama.test.TestMatrix" -Dexec.classpathScope="test"```

Since one goal of this project is minimal alteration of the Java sources, and 
indeed, none of the source files have been altered in any way, the version
number remains at the version number designated by the authors, 1.0.3.

Authorship
----------

The following authorship information is reproduced verbatim from the
[JAMA Project](https://math.nist.gov/javanumerics/jama/) home page:

JAMA's initial design, as well as this reference implementation, was developed by

Joe Hicklin
Cleve Moler
Peter Webb	... from The MathWorks

Ronald F. Boisvert
Bruce Miller
Roldan Pozo
Karin Remington	... from NIST

Copyright Notice
----------------

The following copyright notice is reproduced verbatim from the
[JAMA Project](https://math.nist.gov/javanumerics/jama/) home page:

This software is a cooperative product of The MathWorks and the National Institute of Standards and Technology (NIST) which has been released to the public domain. Neither The MathWorks nor NIST assumes any responsibility whatsoever for its use by other parties, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic.
