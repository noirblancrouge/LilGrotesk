## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[5] LilGrotesk-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	* section (U+00A7) contains a short segment B<<468.5,705.5>-<481.0,693.0>-<482.0,692.0>>

	* germandbls (U+00DF) contains a short segment L<<354.0,416.0>--<376.0,416.0>>

	* Eng (U+014A) contains a short segment B<<514.0,-140.0>-<526.0,-140.0>-<535.0,-130.5>>

	* uni019D (U+019D) contains a short segment B<<50.0,-140.0>-<62.0,-140.0>-<71.0,-130.5>>

	* uni2325 (U+2325) contains a short segment B<<212.0,492.0>-<217.0,492.0>-<219.0,487.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* aacute (U+00E1): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* abreve (U+0103): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* acircumflex (U+00E2): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* adieresis (U+00E4): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* ae (U+00E6): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* aeacute (U+01FD): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* agrave (U+00E0): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* amacron (U+0101): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* aogonek (U+0105): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* aring (U+00E5): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* aringacute (U+01FB): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* atilde (U+00E3): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* uni01CE (U+01CE): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674

	* uni1EA1 (U+1EA1): L<<364.0,0.0>--<364.0,106.0>>/B<<364.0,106.0>-<354.0,62.0>-<314.5,28.0>> = 12.80426606528674 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[5] LilGrotesk-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	* comma (U+002C) contains a short segment B<<214.0,76.0>-<214.0,75.0>-<214.0,74.0>>

	* semicolon (U+003B) contains a short segment B<<214.0,76.0>-<214.0,75.0>-<214.0,74.0>>

	* at (U+0040) contains a short segment B<<613.0,302.0>-<636.0,299.0>-<652.0,294.0>>

	* at (U+0040) contains a short segment B<<714.5,57.0>-<707.0,79.0>-<707.0,96.0>>

	* section (U+00A7) contains a short segment B<<479.5,690.5>-<493.0,677.0>-<493.0,677.0>>

	* section (U+00A7) contains a short segment B<<383.0,593.0>-<381.0,595.0>-<370.0,605.0>>

	* cedilla (U+00B8) contains a short segment L<<294.0,-49.0>--<301.0,-49.0>>

	* Ccedilla (U+00C7) contains a short segment L<<370.0,-51.0>--<377.0,-51.0>>

	* germandbls (U+00DF) contains a short segment L<<413.0,439.0>--<437.0,439.0>>

	* ccedilla (U+00E7) contains a short segment L<<273.0,-49.0>--<280.0,-49.0>>

	* eth (U+00F0) contains a short segment B<<294.0,498.0>-<303.0,498.0>-<307.0,496.0>>

	* Eng (U+014A) contains a short segment B<<497.0,-76.0>-<509.0,-76.0>-<516.5,-68.0>>

	* OE (U+0152) contains a short segment L<<515.0,0.0>--<515.0,24.0>>

	* Scedilla (U+015E) contains a short segment L<<272.0,-49.0>--<279.0,-49.0>>

	* scedilla (U+015F) contains a short segment L<<229.0,-49.0>--<236.0,-49.0>>

	* uni0162 (U+0162) contains a short segment L<<324.0,-49.0>--<331.0,-49.0>>

	* uni0163 (U+0163) contains a short segment L<<214.0,-49.0>--<221.0,-49.0>>

	* uni019D (U+019D) contains a short segment B<<53.0,-76.0>-<65.0,-76.0>-<72.5,-68.0>>

	* uni0327 (U+0327) contains a short segment L<<294.0,-49.0>--<301.0,-49.0>>

	* uni1E08 (U+1E08) contains a short segment L<<370.0,-51.0>--<377.0,-51.0>>

	* uni1E09 (U+1E09) contains a short segment L<<273.0,-49.0>--<280.0,-49.0>>

	* uni1E1C (U+1E1C) contains a short segment L<<333.0,-49.0>--<340.0,-49.0>>

	* uni1E1D (U+1E1D) contains a short segment L<<292.0,-49.0>--<299.0,-49.0>>

	* Euro (U+20AC) contains a short segment B<<143.0,316.0>-<142.0,324.0>-<141.5,332.5>>

	* Euro (U+20AC) contains a short segment B<<141.5,332.5>-<141.0,341.0>-<141.0,349.0>>

	* Euro (U+20AC) contains a short segment B<<141.0,349.0>-<141.0,357.0>-<141.5,365.0>>

	* Euro (U+20AC) contains a short segment B<<141.5,365.0>-<142.0,373.0>-<143.0,380.0>>

	* Euro (U+20AC) contains a short segment B<<286.0,380.0>-<285.0,373.0>-<284.5,365.0>>

	* Euro (U+20AC) contains a short segment B<<284.5,365.0>-<284.0,357.0>-<284.0,349.0>>

	* Euro (U+20AC) contains a short segment B<<284.0,349.0>-<284.0,341.0>-<284.5,332.5>>

	* Euro (U+20AC) contains a short segment B<<284.5,332.5>-<285.0,324.0>-<286.0,316.0>>

	* uni2325 (U+2325) contains a short segment B<<212.0,492.0>-<217.0,492.0>-<219.0,487.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* trademark (U+2122): L<<567.0,393.0>--<537.0,515.0>>/L<<537.0,515.0>--<537.0,341.0>> = 13.81502534126161

	* trademark (U+2122): L<<689.0,341.0>--<689.0,515.0>>/L<<689.0,515.0>--<662.0,393.0>> = 12.479071801927638 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[5] LilGrotesk-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	* dollar (U+0024) contains a short segment B<<388.0,535.0>-<387.0,537.0>-<375.5,549.0>>

	* at (U+0040) contains a short segment B<<608.0,305.5>-<630.0,302.0>-<645.0,298.0>>

	* at (U+0040) contains a short segment B<<645.0,303.0>-<645.0,325.0>-<627.0,340.0>>

	* at (U+0040) contains a short segment B<<809.0,117.0>-<824.0,100.0>-<844.0,100.0>>

	* at (U+0040) contains a short segment B<<713.0,54.0>-<705.0,75.0>-<705.0,91.0>>

	* asciitilde (U+007E) contains a short segment B<<455.0,363.0>-<457.0,363.0>-<464.0,365.0>>

	* sterling (U+00A3) contains a short segment B<<130.0,185.0>-<131.0,190.0>-<131.0,194.5>>

	* sterling (U+00A3) contains a short segment B<<131.0,194.5>-<131.0,199.0>-<131.0,203.0>>

	* section (U+00A7) contains a short segment B<<481.5,688.0>-<495.0,675.0>-<495.0,675.0>>

	* section (U+00A7) contains a short segment B<<376.0,583.0>-<374.0,585.0>-<364.0,594.5>>

	* cedilla (U+00B8) contains a short segment L<<296.0,-48.0>--<299.0,-48.0>>

	* Ccedilla (U+00C7) contains a short segment L<<372.0,-50.0>--<375.0,-50.0>>

	* germandbls (U+00DF) contains a short segment L<<423.0,443.0>--<447.0,443.0>>

	* ccedilla (U+00E7) contains a short segment L<<278.0,-48.0>--<281.0,-48.0>>

	* eth (U+00F0) contains a short segment B<<294.0,503.0>-<294.0,503.0>-<294.5,504.0>>

	* eth (U+00F0) contains a short segment B<<294.5,504.0>-<295.0,505.0>-<293.0,506.0>>

	* Eng (U+014A) contains a short segment B<<494.0,-65.0>-<506.0,-65.0>-<513.5,-57.5>>

	* OE (U+0152) contains a short segment L<<504.0,0.0>--<504.0,18.0>>

	* Scedilla (U+015E) contains a short segment L<<278.0,-48.0>--<281.0,-48.0>>

	* scedilla (U+015F) contains a short segment L<<238.0,-48.0>--<241.0,-48.0>>

	* uni0162 (U+0162) contains a short segment L<<328.0,-48.0>--<331.0,-48.0>>

	* uni0163 (U+0163) contains a short segment L<<218.0,-48.0>--<221.0,-48.0>>

	* uni019D (U+019D) contains a short segment B<<54.0,-65.0>-<66.0,-65.0>-<73.0,-57.5>>

	* uni0327 (U+0327) contains a short segment L<<296.0,-48.0>--<299.0,-48.0>>

	* uni1E08 (U+1E08) contains a short segment L<<372.0,-50.0>--<375.0,-50.0>>

	* uni1E09 (U+1E09) contains a short segment L<<278.0,-48.0>--<281.0,-48.0>>

	* uni1E1C (U+1E1C) contains a short segment L<<340.0,-48.0>--<343.0,-48.0>>

	* uni1E1D (U+1E1D) contains a short segment L<<296.0,-48.0>--<299.0,-48.0>>

	* Euro (U+20AC) contains a short segment B<<146.0,324.0>-<145.0,330.0>-<145.0,336.5>>

	* Euro (U+20AC) contains a short segment B<<145.0,336.5>-<145.0,343.0>-<145.0,349.0>>

	* Euro (U+20AC) contains a short segment B<<145.0,349.0>-<145.0,357.0>-<145.5,365.5>>

	* Euro (U+20AC) contains a short segment B<<145.5,365.5>-<146.0,374.0>-<147.0,381.0>>

	* Euro (U+20AC) contains a short segment B<<302.0,381.0>-<301.0,374.0>-<300.5,365.5>>

	* Euro (U+20AC) contains a short segment B<<300.5,365.5>-<300.0,357.0>-<300.0,349.0>>

	* Euro (U+20AC) contains a short segment B<<300.0,349.0>-<300.0,343.0>-<300.0,336.5>>

	* Euro (U+20AC) contains a short segment B<<300.0,336.5>-<300.0,330.0>-<301.0,324.0>>

	* partialdiff (U+2202) contains a short segment B<<283.0,571.0>-<290.0,571.0>-<296.5,571.0>>

	* partialdiff (U+2202) contains a short segment B<<296.5,571.0>-<303.0,571.0>-<310.0,571.0>>

	* integral (U+222B) contains a short segment B<<141.0,12.0>-<147.0,10.0>-<154.0,10.0>>

	* integral (U+222B) contains a short segment B<<154.0,10.0>-<162.0,10.0>-<165.5,17.5>>

	* uni2325 (U+2325) contains a short segment B<<212.0,492.0>-<217.0,492.0>-<219.0,487.0>>

	* fi (U+FB01) contains a short segment B<<270.0,581.0>-<262.0,581.0>-<252.5,572.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* trademark (U+2122): L<<577.0,393.0>--<556.0,499.0>>/L<<556.0,499.0>--<556.0,338.0>> = 11.205947507402552

	* trademark (U+2122): L<<696.0,338.0>--<696.0,499.0>>/L<<696.0,499.0>--<678.0,393.0>> = 9.637538112930923 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[5] LilGrotesk-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	* comma (U+002C) contains a short segment B<<164.0,55.0>-<165.0,55.0>-<164.0,55.0>>

	* semicolon (U+003B) contains a short segment B<<164.0,55.0>-<165.0,55.0>-<164.0,55.0>>

	* sterling (U+00A3) contains a short segment B<<149.0,136.0>-<152.0,145.0>-<154.0,157.0>>

	* section (U+00A7) contains a short segment B<<471.0,701.5>-<484.0,689.0>-<485.0,688.0>>

	* germandbls (U+00DF) contains a short segment L<<369.0,422.0>--<391.0,422.0>>

	* Eng (U+014A) contains a short segment B<<510.0,-124.0>-<522.0,-124.0>-<530.5,-115.0>>

	* uni019D (U+019D) contains a short segment B<<51.0,-124.0>-<63.0,-124.0>-<71.5,-115.0>>

	* Euro (U+20AC) contains a short segment B<<125.0,349.0>-<125.0,356.0>-<125.5,363.0>>

	* Euro (U+20AC) contains a short segment B<<125.5,363.0>-<126.0,370.0>-<126.0,377.0>>

	* Euro (U+20AC) contains a short segment B<<214.0,377.0>-<214.0,370.0>-<214.0,363.0>>

	* Euro (U+20AC) contains a short segment B<<214.0,363.0>-<214.0,356.0>-<214.0,349.0>>

	* uni2325 (U+2325) contains a short segment B<<212.0,492.0>-<217.0,492.0>-<219.0,487.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* aacute (U+00E1): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* abreve (U+0103): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* acircumflex (U+00E2): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* adieresis (U+00E4): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* ae (U+00E6): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* aeacute (U+01FD): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* agrave (U+00E0): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* amacron (U+0101): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* aogonek (U+0105): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* aring (U+00E5): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* aringacute (U+01FB): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* atilde (U+00E3): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* uni01CE (U+01CE): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484

	* uni1EA1 (U+1EA1): L<<354.0,0.0>--<354.0,93.0>>/B<<354.0,93.0>-<344.0,53.0>-<307.0,23.5>> = 14.036243467926484 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[4] LilGrotesk-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	* a (U+0061): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* aacute (U+00E1): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* abreve (U+0103): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* acircumflex (U+00E2): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* adieresis (U+00E4): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* ae (U+00E6): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* aeacute (U+01FD): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* agrave (U+00E0): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* amacron (U+0101): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* aogonek (U+0105): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* aring (U+00E5): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* aringacute (U+01FB): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* atilde (U+00E3): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* r (U+0072): L<<117.0,500.0>--<117.0,382.0>>/B<<117.0,382.0>-<132.0,451.0>-<169.0,478.5>> = 12.2647737278924

	* racute (U+0155): L<<117.0,500.0>--<117.0,382.0>>/B<<117.0,382.0>-<132.0,451.0>-<169.0,478.5>> = 12.2647737278924

	* rcaron (U+0159): L<<117.0,500.0>--<117.0,382.0>>/B<<117.0,382.0>-<132.0,451.0>-<169.0,478.5>> = 12.2647737278924

	* rmacronbelow (U+1E5F): L<<117.0,500.0>--<117.0,382.0>>/B<<117.0,382.0>-<132.0,451.0>-<169.0,478.5>> = 12.2647737278924

	* uni0157 (U+0157): L<<117.0,500.0>--<117.0,382.0>>/B<<117.0,382.0>-<132.0,451.0>-<169.0,478.5>> = 12.2647737278924

	* uni01CE (U+01CE): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358

	* uni1E5B (U+1E5B): L<<117.0,500.0>--<117.0,382.0>>/B<<117.0,382.0>-<132.0,451.0>-<169.0,478.5>> = 12.2647737278924

	* uni1EA1 (U+1EA1): L<<390.0,0.0>--<390.0,144.0>>/B<<390.0,144.0>-<384.0,106.0>-<361.0,71.5>> = 8.972626614896358 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[5] LilGrotesk-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	* dollar (U+0024) contains a short segment B<<471.0,645.5>-<482.0,634.0>-<482.0,634.0>>

	* dollar (U+0024) contains a short segment B<<439.0,603.0>-<438.0,605.0>-<427.0,617.0>>

	* ampersand (U+0026) contains a short segment B<<230.0,377.0>-<229.0,378.0>-<228.0,379.0>>

	* comma (U+002C) contains a short segment B<<133.0,42.0>-<133.0,41.0>-<133.0,41.0>>

	* semicolon (U+003B) contains a short segment B<<133.0,42.0>-<133.0,41.0>-<133.0,41.0>>

	* sterling (U+00A3) contains a short segment B<<600.0,57.0>-<599.0,52.0>-<592.0,38.5>>

	* section (U+00A7) contains a short segment B<<466.0,708.5>-<479.0,696.0>-<480.0,695.0>>

	* germandbls (U+00DF) contains a short segment L<<341.0,411.0>--<362.0,411.0>>

	* Eng (U+014A) contains a short segment B<<518.0,-154.0>-<530.0,-154.0>-<539.0,-144.5>>

	* uni019D (U+019D) contains a short segment B<<49.0,-154.0>-<61.0,-154.0>-<70.5,-144.5>>

	* Euro (U+20AC) contains a short segment B<<115.0,349.0>-<115.0,356.0>-<115.0,362.0>>

	* Euro (U+20AC) contains a short segment B<<115.0,362.0>-<115.0,368.0>-<115.0,375.0>>

	* Euro (U+20AC) contains a short segment B<<169.0,375.0>-<169.0,368.0>-<169.0,362.0>>

	* Euro (U+20AC) contains a short segment B<<169.0,362.0>-<169.0,356.0>-<169.0,349.0>>

	* summation (U+2211) contains a short segment L<<422.0,359.0>--<422.0,337.0>>

	* radical (U+221A) contains a short segment L<<379.0,-6.0>--<363.0,-6.0>>

	* uni2325 (U+2325) contains a short segment B<<212.0,492.0>-<217.0,492.0>-<219.0,487.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* aacute (U+00E1): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* abreve (U+0103): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* acircumflex (U+00E2): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* adieresis (U+00E4): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* ae (U+00E6): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* aeacute (U+01FD): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* agrave (U+00E0): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* amacron (U+0101): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* aogonek (U+0105): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* aring (U+00E5): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* aringacute (U+01FB): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* atilde (U+00E3): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* uni01CE (U+01CE): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333

	* uni1EA1 (U+1EA1): L<<373.0,0.0>--<373.0,119.0>>/B<<373.0,119.0>-<366.0,86.0>-<345.5,57.5>> = 11.976132444203333 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 6 | 23 | 716 | 43 | 627 | 0 |
| 0% | 0% | 2% | 51% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
