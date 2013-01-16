Randomly generated Aalto University logos.
==========================================

A collection of Aalto University Logo files that where the character after the A is randomly generated on each rendering of the image. The original paths and colors for the images were generated from [http://media.digtator.fi/digtator/clients/aalto/logo.php](http://media.digtator.fi/digtator/clients/aalto/logo.php).


SVG
---

The randomisation is performed with simple JavaScript that is embedded into the document and executed on page load. The JavaScript code chooses a random path and color from predefined values using `Math.random()`.

PostScript
----------

The randomisation is performed within the PostScript language. Character forms and colors are defined as variables in the file, and a random is chosen using the `rand` keyword.

PDF
---

PDF support is not yet implemented. The PDF specification does not directly support a source of randomness. There are some possibilities for this:
 * Embedding JavaScript in an page load action. Unsure if this can actually affect the content of the PDF. Additionally, this is, for security reasons, not supported by many viewers.
 * Using a custom font that produces random character. This would work using PostScript Type 3 fonts in the same way the PostScript randomisation works. Unfortunately very few readers support the Type 3 specificaiton.
