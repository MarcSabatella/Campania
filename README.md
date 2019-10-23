# Campania
Font for Roman numeral analysis (music theory)

This font is inspired by the work of [Florian Kretlow](https://github.com/fkretlow)
and the impressive [Figurato](https://github.com/fkretlow/figurato) font he developed for figured bass,
as well as the work of Ronald Caltabiano and his pioneering Sicilian Numerals font.
This current version of Campania is not directly based on either of these, however.
Instead, it uses the glyphs from [Doulos](https://software.sil.org/doulos/)
and adds some relatively straightforward contextual substitutions and positioning rules
to allow you to enter the most common symbols just by typing naturally.

To install Campania, download either the [TTF](Campania.ttf?raw=true) or [OTF](Campania.otf?raw=true) files
and follow the standard procedures for installing and selecting fonts on your system.

To use Campania, simply type as you normally would, and the formatting happens automatically.
Numeric indications for inversions and seventh/extended chords (e.g., 6, 7, 64, 643, 43, 9, 13)
are automatically superscripted and stacked vertically.
When used in a context where this makes sense,
"b" and "#" turn into flat and sharp,
"bb" and "##" turn into double flat and double sharp,
"h" turns into natural,
"o" and "0" turn into diminished and half-diminished symbols,
and "^" turns into a triangle.
"-" and "=" can be used and repeated to create dashes of arbitrary length
to connect superscripted and subscripted numbers.
Backslash before a character can be used to prevent the usual substitution
(e.g., "\b" to prevent a "b" from turning into a flat).

![Campania](Campania.png?raw=true)

This font should work in any program that handles fonts reasonably.
It is tested to work in [MuseScore](https://musescore.org) and in [LibreOffice](https://www.libreoffice.org/),
and will probably work in the commercial alternatives as well.
