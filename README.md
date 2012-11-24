Edgedesign.cz mPDF 5.4-fork
============================

Fork info
----------

This is mPDF is forked from finwe/mpdf with aim to enable Open Sans
support in mPDF. Helvetica is mapped to became Open Sans.

History
----------
- **5.4.1**
    - Liberalized un/ordered list styles within Tables
    - ULs in tables are using "–" (EN DASH) Unicode: U+2013, UTF-8: E2 80 93
    - OLs in tables are using Arabic numerals (there are no hidden terrorists ;)
    - BTW There can be set custom Unicode character to UL outside Tables in mPDF since 5.2.
        - Custom list-style-type is recognised e.g.: U+263Argb(255,0,0);
        - where U+263A is the Unicode HEX value of the character you want for the bullet
        - the character MUST be included in the font used for that list item
        - rgb() bit is optional
- **5.4.0**
    - Forked and fixed composer.json to be Symfony2 ready
    - Added Open Sans font face subset optimized for central Europe languages with aim to be fast and small:
        - Supported languages/countries: Czech, Slovak, Poland, Hungary, German, English
        - Subset does not include some math symbols not used in common web documents.
        - Subset was created using excellent http://www.fontsquirrel.com/fontface/generator so please do not hesitate to donate this tool


