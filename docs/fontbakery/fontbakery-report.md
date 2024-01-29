## FontBakery report

fontbakery version: 0.10.2

<details><summary><b>[7] LilGrotesk-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.2, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tai-le, malayalam, syriac, math, canadian-aboriginal, coptic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, syriac, caucasian-albanian, tifinagh, gothic
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2105 CARE OF: not included in any glyphset definition
 * U+2106 CADA UNA: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+21E7 UPWARDS WHITE ARROW: try adding symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+2219 BULLET OPERATOR: try adding one of: symbols, yi, tai-tham, math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+2318 PLACE OF INTEREST SIGN: try adding symbols
 * U+2325 OPTION KEY: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CC DOTTED CIRCLE: try adding one of: sogdian, tagalog, sinhala, chakma, manichaean, cham, miao, batak, coptic, wancho, kharoshthi, rejang, mongolian, kayah-li, javanese, malayalam, gujarati, hanifi-rohingya, hebrew, grantha, pahawh-hmong, kaithi, music, tai-le, yi, math, tirhuta, meetei-mayek, lao, thaana, lepcha, syriac, psalter-pahlavi, bhaiksuki, siddham, buhid, thai, symbols, old-permic, masaram-gondi, khmer, oriya, bengali, bassa-vah, zanabazar-square, balinese, caucasian-albanian, khojki, gurmukhi, osage, adlam, mandaic, tamil, sundanese, hanunoo, brahmi, mende-kikakui, dogra, takri, kannada, elbasan, ahom, marchen, tai-viet, sharada, new-tai-lue, syloti-nagri, limbu, myanmar, telugu, newa, gunjala-gondi, soyombo, devanagari, nko, modi, tibetan, khudawadi, buginese, tagbanwa, tifinagh, phags-pa, duployan, mahajani
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<578.0,284.5>-<599.0,281.0>-<615.0,277.0>>

	* section (U+00A7) contains a short segment B<<452.5,651.5>-<465.0,639.0>-<465.0,638.0>>

	* section (U+00A7) contains a short segment B<<361.0,559.0>-<359.0,561.0>-<349.0,570.5>>

	* germandbls (U+00DF) contains a short segment L<<389.0,414.0>--<412.0,414.0>>

	* eth (U+00F0) contains a short segment B<<277.0,470.0>-<286.0,470.0>-<290.0,468.0>>

	* Eng (U+014A) contains a short segment B<<469.0,-72.0>-<480.0,-72.0>-<487.0,-64.5>>

	* OE (U+0152) contains a short segment L<<486.0,0.0>--<486.0,23.0>>

	* uni019D (U+019D) contains a short segment B<<50.0,-72.0>-<61.0,-72.0>-<68.0,-64.5>>

	* Euro (U+20AC) contains a short segment B<<135.0,298.0>-<134.0,306.0>-<133.5,313.5>>

	* Euro (U+20AC) contains a short segment B<<133.5,313.5>-<133.0,321.0>-<133.0,329.0>>

	* Euro (U+20AC) contains a short segment B<<133.0,329.0>-<133.0,336.0>-<133.5,343.5>>

	* Euro (U+20AC) contains a short segment B<<133.5,343.5>-<134.0,351.0>-<135.0,358.0>>

	* Euro (U+20AC) contains a short segment B<<270.0,358.0>-<269.0,351.0>-<268.5,344.0>>

	* Euro (U+20AC) contains a short segment B<<268.5,344.0>-<268.0,337.0>-<268.0,329.0>>

	* Euro (U+20AC) contains a short segment B<<268.0,329.0>-<268.0,321.0>-<268.5,313.5>>

	* Euro (U+20AC) contains a short segment B<<268.5,313.5>-<269.0,306.0>-<270.0,298.0>>

	* uni2325 (U+2325) contains a short segment B<<340.0,-11.0>-<334.0,-11.0>-<332.0,-7.0>>

	* uni2325 (U+2325) contains a short segment B<<200.0,464.0>-<205.0,464.0>-<207.0,459.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* trademark (U+2122): L<<535.0,371.0>--<506.0,486.0>>/L<<506.0,486.0>--<506.0,322.0>> = 14.15341258785141

	* trademark (U+2122): L<<650.0,322.0>--<650.0,486.0>>/L<<650.0,486.0>--<624.0,371.0>> = 12.739646792482095 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[6] LilGrotesk-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.2, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tai-le, malayalam, syriac, math, canadian-aboriginal, coptic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, syriac, caucasian-albanian, tifinagh, gothic
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2105 CARE OF: not included in any glyphset definition
 * U+2106 CADA UNA: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+21E7 UPWARDS WHITE ARROW: try adding symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+2219 BULLET OPERATOR: try adding one of: symbols, yi, tai-tham, math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+2318 PLACE OF INTEREST SIGN: try adding symbols
 * U+2325 OPTION KEY: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CC DOTTED CIRCLE: try adding one of: sogdian, tagalog, sinhala, chakma, manichaean, cham, miao, batak, coptic, wancho, kharoshthi, rejang, mongolian, kayah-li, javanese, malayalam, gujarati, hanifi-rohingya, hebrew, grantha, pahawh-hmong, kaithi, music, tai-le, yi, math, tirhuta, meetei-mayek, lao, thaana, lepcha, syriac, psalter-pahlavi, bhaiksuki, siddham, buhid, thai, symbols, old-permic, masaram-gondi, khmer, oriya, bengali, bassa-vah, zanabazar-square, balinese, caucasian-albanian, khojki, gurmukhi, osage, adlam, mandaic, tamil, sundanese, hanunoo, brahmi, mende-kikakui, dogra, takri, kannada, elbasan, ahom, marchen, tai-viet, sharada, new-tai-lue, syloti-nagri, limbu, myanmar, telugu, newa, gunjala-gondi, soyombo, devanagari, nko, modi, tibetan, khudawadi, buginese, tagbanwa, tifinagh, phags-pa, duployan, mahajani
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* comma (U+002C) contains a short segment B<<155.0,52.0>-<155.0,51.0>-<155.0,52.0>>

	* semicolon (U+003B) contains a short segment B<<155.0,52.0>-<155.0,51.0>-<155.0,52.0>>

	* section (U+00A7) contains a short segment B<<444.5,662.0>-<457.0,650.0>-<457.0,649.0>>

	* germandbls (U+00DF) contains a short segment L<<348.0,398.0>--<369.0,398.0>>

	* Eng (U+014A) contains a short segment B<<481.0,-117.0>-<492.0,-117.0>-<500.0,-108.5>>

	* uni019D (U+019D) contains a short segment B<<48.0,-117.0>-<59.0,-117.0>-<67.0,-108.5>>

	* Euro (U+20AC) contains a short segment B<<118.0,329.0>-<118.0,336.0>-<118.0,342.5>>

	* Euro (U+20AC) contains a short segment B<<118.0,342.5>-<118.0,349.0>-<119.0,356.0>>

	* Euro (U+20AC) contains a short segment B<<202.0,356.0>-<202.0,349.0>-<201.5,342.5>>

	* Euro (U+20AC) contains a short segment B<<201.5,342.5>-<201.0,336.0>-<201.0,329.0>>

	* uni2325 (U+2325) contains a short segment B<<340.0,-11.0>-<334.0,-11.0>-<332.0,-7.0>>

	* uni2325 (U+2325) contains a short segment B<<200.0,464.0>-<205.0,464.0>-<207.0,459.0>> [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[6] LilGrotesk-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.2, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tai-le, malayalam, syriac, math, canadian-aboriginal, coptic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, syriac, caucasian-albanian, tifinagh, gothic
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2105 CARE OF: not included in any glyphset definition
 * U+2106 CADA UNA: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+21E7 UPWARDS WHITE ARROW: try adding symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+2219 BULLET OPERATOR: try adding one of: symbols, yi, tai-tham, math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+2318 PLACE OF INTEREST SIGN: try adding symbols
 * U+2325 OPTION KEY: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CC DOTTED CIRCLE: try adding one of: sogdian, tagalog, sinhala, chakma, manichaean, cham, miao, batak, coptic, wancho, kharoshthi, rejang, mongolian, kayah-li, javanese, malayalam, gujarati, hanifi-rohingya, hebrew, grantha, pahawh-hmong, kaithi, music, tai-le, yi, math, tirhuta, meetei-mayek, lao, thaana, lepcha, syriac, psalter-pahlavi, bhaiksuki, siddham, buhid, thai, symbols, old-permic, masaram-gondi, khmer, oriya, bengali, bassa-vah, zanabazar-square, balinese, caucasian-albanian, khojki, gurmukhi, osage, adlam, mandaic, tamil, sundanese, hanunoo, brahmi, mende-kikakui, dogra, takri, kannada, elbasan, ahom, marchen, tai-viet, sharada, new-tai-lue, syloti-nagri, limbu, myanmar, telugu, newa, gunjala-gondi, soyombo, devanagari, nko, modi, tibetan, khudawadi, buginese, tagbanwa, tifinagh, phags-pa, duployan, mahajani
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* aacute (U+00E1): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* abreve (U+0103): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* acircumflex (U+00E2): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* adieresis (U+00E4): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* ae (U+00E6): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* aeacute (U+01FD): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* agrave (U+00E0): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* amacron (U+0101): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* aogonek (U+0105): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* aring (U+00E5): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* aringacute (U+01FB): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* atilde (U+00E3): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* r (U+0072): L<<110.0,472.0>--<110.0,360.0>>/B<<110.0,360.0>-<125.0,425.0>-<159.5,451.0>> = 12.994616791916512

	* racute (U+0155): L<<110.0,472.0>--<110.0,360.0>>/B<<110.0,360.0>-<125.0,425.0>-<159.5,451.0>> = 12.994616791916512

	* rcaron (U+0159): L<<110.0,472.0>--<110.0,360.0>>/B<<110.0,360.0>-<125.0,425.0>-<159.5,451.0>> = 12.994616791916512

	* rmacronbelow (U+1E5F): L<<110.0,472.0>--<110.0,360.0>>/B<<110.0,360.0>-<125.0,425.0>-<159.5,451.0>> = 12.994616791916512

	* uni0157 (U+0157): L<<110.0,472.0>--<110.0,360.0>>/B<<110.0,360.0>-<125.0,425.0>-<159.5,451.0>> = 12.994616791916512

	* uni01CE (U+01CE): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613

	* uni1E5B (U+1E5B): L<<110.0,472.0>--<110.0,360.0>>/B<<110.0,360.0>-<125.0,425.0>-<159.5,451.0>> = 12.994616791916512

	* uni1EA1 (U+1EA1): L<<368.0,0.0>--<368.0,136.0>>/B<<368.0,136.0>-<362.0,100.0>-<340.5,67.0>> = 9.462322208025613 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[7] LilGrotesk-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.2, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tai-le, malayalam, syriac, math, canadian-aboriginal, coptic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, syriac, caucasian-albanian, tifinagh, gothic
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2105 CARE OF: not included in any glyphset definition
 * U+2106 CADA UNA: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+21E7 UPWARDS WHITE ARROW: try adding symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+2219 BULLET OPERATOR: try adding one of: symbols, yi, tai-tham, math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+2318 PLACE OF INTEREST SIGN: try adding symbols
 * U+2325 OPTION KEY: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CC DOTTED CIRCLE: try adding one of: sogdian, tagalog, sinhala, chakma, manichaean, cham, miao, batak, coptic, wancho, kharoshthi, rejang, mongolian, kayah-li, javanese, malayalam, gujarati, hanifi-rohingya, hebrew, grantha, pahawh-hmong, kaithi, music, tai-le, yi, math, tirhuta, meetei-mayek, lao, thaana, lepcha, syriac, psalter-pahlavi, bhaiksuki, siddham, buhid, thai, symbols, old-permic, masaram-gondi, khmer, oriya, bengali, bassa-vah, zanabazar-square, balinese, caucasian-albanian, khojki, gurmukhi, osage, adlam, mandaic, tamil, sundanese, hanunoo, brahmi, mende-kikakui, dogra, takri, kannada, elbasan, ahom, marchen, tai-viet, sharada, new-tai-lue, syloti-nagri, limbu, myanmar, telugu, newa, gunjala-gondi, soyombo, devanagari, nko, modi, tibetan, khudawadi, buginese, tagbanwa, tifinagh, phags-pa, duployan, mahajani
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* section (U+00A7) contains a short segment B<<442.0,665.0>-<454.0,653.0>-<455.0,653.0>>

	* germandbls (U+00DF) contains a short segment L<<334.0,392.0>--<355.0,392.0>>

	* Eng (U+014A) contains a short segment B<<485.0,-132.0>-<496.0,-132.0>-<504.5,-123.5>>

	* uni019D (U+019D) contains a short segment B<<47.0,-132.0>-<58.0,-132.0>-<66.5,-123.5>>

	* summation (U+2211) contains a short segment L<<424.0,339.0>--<424.0,316.0>>

	* uni2325 (U+2325) contains a short segment B<<340.0,-11.0>-<334.0,-11.0>-<332.0,-7.0>>

	* uni2325 (U+2325) contains a short segment B<<200.0,464.0>-<205.0,464.0>-<207.0,459.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* aacute (U+00E1): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* abreve (U+0103): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* acircumflex (U+00E2): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* adieresis (U+00E4): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* ae (U+00E6): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* aeacute (U+01FD): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* agrave (U+00E0): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* amacron (U+0101): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* aogonek (U+0105): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* aring (U+00E5): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* aringacute (U+01FB): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* atilde (U+00E3): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* uni01CE (U+01CE): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089

	* uni1EA1 (U+1EA1): L<<343.0,0.0>--<343.0,100.0>>/B<<343.0,100.0>-<334.0,58.0>-<296.5,26.0>> = 12.094757077012089 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[7] LilGrotesk-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.2, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tai-le, malayalam, syriac, math, canadian-aboriginal, coptic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, syriac, caucasian-albanian, tifinagh, gothic
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2105 CARE OF: not included in any glyphset definition
 * U+2106 CADA UNA: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+21E7 UPWARDS WHITE ARROW: try adding symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+2219 BULLET OPERATOR: try adding one of: symbols, yi, tai-tham, math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+2318 PLACE OF INTEREST SIGN: try adding symbols
 * U+2325 OPTION KEY: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CC DOTTED CIRCLE: try adding one of: sogdian, tagalog, sinhala, chakma, manichaean, cham, miao, batak, coptic, wancho, kharoshthi, rejang, mongolian, kayah-li, javanese, malayalam, gujarati, hanifi-rohingya, hebrew, grantha, pahawh-hmong, kaithi, music, tai-le, yi, math, tirhuta, meetei-mayek, lao, thaana, lepcha, syriac, psalter-pahlavi, bhaiksuki, siddham, buhid, thai, symbols, old-permic, masaram-gondi, khmer, oriya, bengali, bassa-vah, zanabazar-square, balinese, caucasian-albanian, khojki, gurmukhi, osage, adlam, mandaic, tamil, sundanese, hanunoo, brahmi, mende-kikakui, dogra, takri, kannada, elbasan, ahom, marchen, tai-viet, sharada, new-tai-lue, syloti-nagri, limbu, myanmar, telugu, newa, gunjala-gondi, soyombo, devanagari, nko, modi, tibetan, khudawadi, buginese, tagbanwa, tifinagh, phags-pa, duployan, mahajani
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* ampersand (U+0026) contains a short segment B<<217.0,356.0>-<216.0,357.0>-<215.0,357.0>>

	* sterling (U+00A3) contains a short segment B<<566.0,54.0>-<565.0,49.0>-<558.5,36.5>>

	* section (U+00A7) contains a short segment B<<440.0,668.5>-<452.0,657.0>-<452.0,656.0>>

	* germandbls (U+00DF) contains a short segment L<<322.0,388.0>--<342.0,388.0>>

	* Eng (U+014A) contains a short segment B<<488.0,-146.0>-<499.0,-146.0>-<508.0,-136.5>>

	* uni019D (U+019D) contains a short segment B<<47.0,-146.0>-<58.0,-146.0>-<66.5,-136.5>>

	* Euro (U+20AC) contains a short segment B<<109.0,329.0>-<109.0,335.0>-<108.5,341.0>>

	* Euro (U+20AC) contains a short segment B<<108.5,341.0>-<108.0,347.0>-<108.0,354.0>>

	* Euro (U+20AC) contains a short segment B<<159.0,354.0>-<159.0,347.0>-<159.0,341.0>>

	* Euro (U+20AC) contains a short segment B<<159.0,341.0>-<159.0,335.0>-<159.0,329.0>>

	* summation (U+2211) contains a short segment L<<398.0,338.0>--<398.0,317.0>>

	* radical (U+221A) contains a short segment L<<358.0,-6.0>--<343.0,-6.0>>

	* uni2325 (U+2325) contains a short segment B<<340.0,-11.0>-<334.0,-11.0>-<332.0,-7.0>>

	* uni2325 (U+2325) contains a short segment B<<200.0,464.0>-<205.0,464.0>-<207.0,459.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* aacute (U+00E1): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* abreve (U+0103): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* acircumflex (U+00E2): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* adieresis (U+00E4): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* ae (U+00E6): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* aeacute (U+01FD): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* agrave (U+00E0): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* amacron (U+0101): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* aogonek (U+0105): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* aring (U+00E5): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* aringacute (U+01FB): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* atilde (U+00E3): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* uni01CE (U+01CE): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365

	* uni1EA1 (U+1EA1): L<<351.0,0.0>--<351.0,112.0>>/B<<351.0,112.0>-<343.0,66.0>-<303.0,30.0>> = 9.865806943084365 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[7] LilGrotesk-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ConnectionError'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.2, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tai-le, malayalam, syriac, math, canadian-aboriginal, coptic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, syriac, caucasian-albanian, tifinagh, gothic
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2105 CARE OF: not included in any glyphset definition
 * U+2106 CADA UNA: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+21E7 UPWARDS WHITE ARROW: try adding symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+2219 BULLET OPERATOR: try adding one of: symbols, yi, tai-tham, math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+2318 PLACE OF INTEREST SIGN: try adding symbols
 * U+2325 OPTION KEY: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CC DOTTED CIRCLE: try adding one of: sogdian, tagalog, sinhala, chakma, manichaean, cham, miao, batak, coptic, wancho, kharoshthi, rejang, mongolian, kayah-li, javanese, malayalam, gujarati, hanifi-rohingya, hebrew, grantha, pahawh-hmong, kaithi, music, tai-le, yi, math, tirhuta, meetei-mayek, lao, thaana, lepcha, syriac, psalter-pahlavi, bhaiksuki, siddham, buhid, thai, symbols, old-permic, masaram-gondi, khmer, oriya, bengali, bassa-vah, zanabazar-square, balinese, caucasian-albanian, khojki, gurmukhi, osage, adlam, mandaic, tamil, sundanese, hanunoo, brahmi, mende-kikakui, dogra, takri, kannada, elbasan, ahom, marchen, tai-viet, sharada, new-tai-lue, syloti-nagri, limbu, myanmar, telugu, newa, gunjala-gondi, soyombo, devanagari, nko, modi, tibetan, khudawadi, buginese, tagbanwa, tifinagh, phags-pa, duployan, mahajani
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: Ldot	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 5	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: quotedblbase	Contours detected: 1	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<366.0,505.0>-<365.0,506.0>-<354.0,517.5>>

	* at (U+0040) contains a short segment B<<573.5,288.0>-<594.0,285.0>-<608.0,281.0>>

	* at (U+0040) contains a short segment B<<608.0,286.0>-<608.0,306.0>-<591.0,320.5>>

	* at (U+0040) contains a short segment B<<763.0,110.5>-<777.0,94.0>-<796.0,94.0>>

	* asciitilde (U+007E) contains a short segment B<<429.0,342.0>-<431.0,342.0>-<437.5,344.0>>

	* sterling (U+00A3) contains a short segment B<<123.0,174.0>-<123.0,179.0>-<123.5,183.0>>

	* sterling (U+00A3) contains a short segment B<<123.5,183.0>-<124.0,187.0>-<124.0,191.0>>

	* section (U+00A7) contains a short segment B<<454.0,649.0>-<466.0,637.0>-<467.0,637.0>>

	* section (U+00A7) contains a short segment B<<355.0,550.0>-<353.0,552.0>-<343.5,560.5>>

	* cedilla (U+00B8) contains a short segment L<<279.0,-45.0>--<282.0,-45.0>>

	* Ccedilla (U+00C7) contains a short segment L<<351.0,-47.0>--<354.0,-47.0>>

	* germandbls (U+00DF) contains a short segment L<<399.0,418.0>--<422.0,418.0>>

	* ccedilla (U+00E7) contains a short segment L<<262.0,-45.0>--<265.0,-45.0>>

	* eth (U+00F0) contains a short segment B<<277.0,474.0>-<277.0,474.0>-<277.5,475.0>>

	* eth (U+00F0) contains a short segment B<<277.5,475.0>-<278.0,476.0>-<276.0,477.0>>

	* Eng (U+014A) contains a short segment B<<466.0,-61.0>-<477.0,-61.0>-<484.0,-54.5>>

	* OE (U+0152) contains a short segment L<<475.0,0.0>--<475.0,17.0>>

	* Scedilla (U+015E) contains a short segment L<<262.0,-45.0>--<265.0,-45.0>>

	* scedilla (U+015F) contains a short segment L<<224.0,-45.0>--<227.0,-45.0>>

	* uni0162 (U+0162) contains a short segment L<<309.0,-45.0>--<312.0,-45.0>>

	* uni0163 (U+0163) contains a short segment L<<205.0,-45.0>--<208.0,-45.0>>

	* uni019D (U+019D) contains a short segment B<<51.0,-61.0>-<62.0,-61.0>-<68.5,-54.5>>

	* uni0327 (U+0327) contains a short segment L<<279.0,-45.0>--<282.0,-45.0>>

	* uni1E08 (U+1E08) contains a short segment L<<351.0,-47.0>--<354.0,-47.0>>

	* uni1E09 (U+1E09) contains a short segment L<<262.0,-45.0>--<265.0,-45.0>>

	* uni1E1C (U+1E1C) contains a short segment L<<320.0,-45.0>--<323.0,-45.0>>

	* uni1E1D (U+1E1D) contains a short segment L<<279.0,-45.0>--<282.0,-45.0>>

	* Euro (U+20AC) contains a short segment B<<138.0,306.0>-<137.0,311.0>-<137.0,317.0>>

	* Euro (U+20AC) contains a short segment B<<137.0,317.0>-<137.0,323.0>-<137.0,329.0>>

	* Euro (U+20AC) contains a short segment B<<137.0,329.0>-<137.0,336.0>-<137.5,344.0>>

	* Euro (U+20AC) contains a short segment B<<137.5,344.0>-<138.0,352.0>-<139.0,359.0>>

	* Euro (U+20AC) contains a short segment B<<285.0,359.0>-<284.0,352.0>-<283.5,344.5>>

	* Euro (U+20AC) contains a short segment B<<283.5,344.5>-<283.0,337.0>-<283.0,329.0>>

	* Euro (U+20AC) contains a short segment B<<283.0,329.0>-<283.0,323.0>-<283.0,317.0>>

	* Euro (U+20AC) contains a short segment B<<283.0,317.0>-<283.0,311.0>-<284.0,306.0>>

	* partialdiff (U+2202) contains a short segment B<<267.0,538.0>-<273.0,538.0>-<279.5,538.0>>

	* partialdiff (U+2202) contains a short segment B<<279.5,538.0>-<286.0,538.0>-<292.0,538.0>>

	* uni2325 (U+2325) contains a short segment B<<340.0,-11.0>-<334.0,-11.0>-<332.0,-7.0>>

	* uni2325 (U+2325) contains a short segment B<<200.0,464.0>-<205.0,464.0>-<207.0,459.0>>

	* fi (U+FB01) contains a short segment B<<255.0,548.0>-<247.0,548.0>-<238.0,539.5>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* trademark (U+2122): L<<544.0,371.0>--<524.0,471.0>>/L<<524.0,471.0>--<524.0,319.0>> = 11.309932474020227

	* trademark (U+2122): L<<656.0,319.0>--<656.0,471.0>>/L<<656.0,471.0>--<639.0,371.0>> = 9.648045316098152 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 6 | 6 | 28 | 716 | 43 | 635 | 0 |
| 0% | 0% | 2% | 50% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
