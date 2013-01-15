Randomly generated Aalto University logos.
==========================================

A collection of Aalto University Logo files that where the character after the A is randomly generated on each rendering of the image. The original paths and colors for the images were generated from [http://media.digtator.fi/digtator/clients/aalto/logo.php](http://media.digtator.fi/digtator/clients/aalto/logo.php).


SVG
---

The randomisation is performed with simple JavaScript that is embedded into the document and executed on rendering. The JavaScript code chooses a random path and color from predefined values using `Math.random()`.

PostScript
----------

The randomisation is performed within the PostScript language. Character forms and colors are defined as variables in the file, and a random is chosen using the `rand` keyword.

PDF
---

PDF support is not yet implemented, but possible using PDF Actions or JavaScript in the file. Sadly, these Actions are not supported by all PDF viewers.
