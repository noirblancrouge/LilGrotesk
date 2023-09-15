## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[6] LilGrotesk-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1360, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 368, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni01CE.ss01
 [code: unreachable-glyphs]
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

	* a (U+0061): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* aacute (U+00E1): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* abreve (U+0103): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* acircumflex (U+00E2): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* adieresis (U+00E4): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* ae (U+00E6): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* aeacute (U+01FD): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* agrave (U+00E0): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* amacron (U+0101): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* aogonek (U+0105): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* aring (U+00E5): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* aringacute (U+01FB): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* atilde (U+00E3): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* braceleft (U+007B): B<<152.5,338.0>-<125.0,321.0>-<80.0,318.0>>/B<<80.0,318.0>-<125.0,315.0>-<152.5,298.0>> = 7.628149668580618

	* braceright (U+007D): B<<240.5,298.0>-<268.0,315.0>-<313.0,318.0>>/B<<313.0,318.0>-<268.0,321.0>-<240.5,338.0>> = 7.628149668580618

	* nine (U+0039): L<<314.0,327.0>--<333.0,348.0>>/B<<333.0,348.0>-<306.0,327.0>-<267.0,317.5>> = 9.987421575013531

	* r (U+0072): L<<117.0,500.0>--<117.0,369.0>>/B<<117.0,369.0>-<131.0,444.0>-<167.5,475.0>> = 10.573523418560926

	* racute (U+0155): L<<117.0,500.0>--<117.0,369.0>>/B<<117.0,369.0>-<131.0,444.0>-<167.5,475.0>> = 10.573523418560926

	* rcaron (U+0159): L<<117.0,500.0>--<117.0,369.0>>/B<<117.0,369.0>-<131.0,444.0>-<167.5,475.0>> = 10.573523418560926

	* rmacronbelow (U+1E5F): L<<117.0,500.0>--<117.0,369.0>>/B<<117.0,369.0>-<131.0,444.0>-<167.5,475.0>> = 10.573523418560926

	* six (U+0036): L<<124.0,369.0>--<105.0,348.0>>/B<<105.0,348.0>-<133.0,369.0>-<171.5,378.5>> = 10.992507580267716

	* sterling (U+00A3): L<<583.0,41.0>--<609.0,25.0>>/B<<609.0,25.0>-<607.0,26.0>-<603.0,18.0>> = 5.042451069170812

	* uni0157 (U+0157): L<<117.0,500.0>--<117.0,369.0>>/B<<117.0,369.0>-<131.0,444.0>-<167.5,475.0>> = 10.573523418560926

	* uni1E5B (U+1E5B): L<<117.0,500.0>--<117.0,369.0>>/B<<117.0,369.0>-<131.0,444.0>-<167.5,475.0>> = 10.573523418560926

	* uni1EA1 (U+1EA1): L<<391.0,0.0>--<391.0,144.0>>/B<<391.0,144.0>-<385.0,106.0>-<362.0,71.0>> = 8.972626614896358

	* uni2076 (U+2076): L<<75.0,619.0>--<64.0,606.0>>/B<<64.0,606.0>-<80.0,619.0>-<103.5,624.5>> = 10.669782804496695

	* uni2079 (U+2079): L<<190.0,593.0>--<202.0,606.0>>/B<<202.0,606.0>-<185.0,593.0>-<161.5,587.5>> = 9.885253411230009

	* uni2086 (U+2086): L<<75.0,224.0>--<64.0,211.0>>/B<<64.0,211.0>-<80.0,224.0>-<103.5,229.5>> = 10.669782804496695

	* uni2089 (U+2089): L<<190.0,198.0>--<202.0,211.0>>/B<<202.0,211.0>-<185.0,198.0>-<161.5,192.5>> = 9.885253411230009 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[7] LilGrotesk-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1360, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 368, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni01CE.ss01
 [code: unreachable-glyphs]
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

	* three (U+0033) contains a short segment L<<185.0,416.0>--<197.0,416.0>>

	* sterling (U+00A3) contains a short segment B<<85.0,3.0>-<81.0,-7.0>-<81.0,-7.0>>

	* sterling (U+00A3) contains a short segment B<<13.0,11.0>-<13.0,11.0>-<19.0,26.0>>

	* sterling (U+00A3) contains a short segment B<<520.5,69.5>-<526.0,82.0>-<528.0,90.0>>

	* sterling (U+00A3) contains a short segment B<<596.0,73.0>-<595.0,69.0>-<589.5,53.0>>

	* section (U+00A7) contains a short segment B<<468.5,705.5>-<481.0,693.0>-<482.0,692.0>>

	* uni00B3 (U+00B3) contains a short segment L<<112.0,647.0>--<119.0,647.0>>

	* threequarters (U+00BE) contains a short segment L<<112.0,647.0>--<119.0,647.0>>

	* germandbls (U+00DF) contains a short segment L<<364.0,416.0>--<376.0,416.0>>

	* Eng (U+014A) contains a short segment L<<609.0,0.0>--<604.0,0.0>>

	* Eng (U+014A) contains a short segment B<<509.0,-140.0>-<521.0,-140.0>-<530.0,-130.5>>

	* Eng (U+014A) contains a short segment L<<539.0,0.0>--<544.0,0.0>>

	* uni019D (U+019D) contains a short segment L<<150.0,0.0>--<145.0,0.0>>

	* uni019D (U+019D) contains a short segment B<<45.0,-140.0>-<57.0,-140.0>-<66.0,-130.5>>

	* uni019D (U+019D) contains a short segment L<<75.0,0.0>--<80.0,0.0>>

	* uni2083 (U+2083) contains a short segment L<<112.0,252.0>--<119.0,252.0>>

	* summation (U+2211) contains a short segment L<<450.0,359.0>--<450.0,336.0>>

	* radical (U+221A) contains a short segment L<<372.0,-6.0>--<367.0,-6.0>>

	* uni2325 (U+2325) contains a short segment B<<359.0,-12.0>-<354.0,-12.0>-<352.0,-7.0>>

	* uni2325 (U+2325) contains a short segment B<<212.0,492.0>-<217.0,492.0>-<219.0,487.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* aacute (U+00E1): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* abreve (U+0103): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* acircumflex (U+00E2): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* adieresis (U+00E4): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* ae (U+00E6): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* aeacute (U+01FD): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* agrave (U+00E0): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* amacron (U+0101): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* aogonek (U+0105): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* aring (U+00E5): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* aringacute (U+01FB): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* atilde (U+00E3): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195

	* r (U+0072): L<<145.0,500.0>--<145.0,398.0>>/B<<145.0,398.0>-<158.0,454.0>-<191.5,480.0>> = 13.069317896282163

	* racute (U+0155): L<<145.0,500.0>--<145.0,398.0>>/B<<145.0,398.0>-<158.0,454.0>-<191.5,480.0>> = 13.069317896282163

	* rcaron (U+0159): L<<145.0,500.0>--<145.0,398.0>>/B<<145.0,398.0>-<158.0,454.0>-<191.5,480.0>> = 13.069317896282163

	* rmacronbelow (U+1E5F): L<<145.0,500.0>--<145.0,398.0>>/B<<145.0,398.0>-<158.0,454.0>-<191.5,480.0>> = 13.069317896282163

	* uni0157 (U+0157): L<<145.0,500.0>--<145.0,398.0>>/B<<145.0,398.0>-<158.0,454.0>-<191.5,480.0>> = 13.069317896282163

	* uni1E5B (U+1E5B): L<<145.0,500.0>--<145.0,398.0>>/B<<145.0,398.0>-<158.0,454.0>-<191.5,480.0>> = 13.069317896282163

	* uni1EA1 (U+1EA1): L<<364.0,0.0>--<364.0,108.0>>/B<<364.0,108.0>-<355.0,63.0>-<315.5,28.5>> = 11.309932474020195 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] LilGrotesk-Ultra.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Ultra'. Expected OS/2 usWeightClass is 400, got 200. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Lil Grotesk Ultra | Lil Grotesk Ultra |
| Subfamily Name | Regular | Regular |
| Full Name | Lil Grotesk Ultra | Lil Grotesk Ultra Regular |
| Poscript Name | LilGrotesk-Ultra | LilGroteskUltra-Regular |
| Typographic Family Name | Lil Grotesk | N/A |
| Typographic Subfamily Name | Ultra | N/A | [code: bad-names]
* ⚠ **WARN** Regular missing from full name [code: lacks-regular]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1360, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 368, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni01CE.ss01
 [code: unreachable-glyphs]
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

	* dollar (U+0024) contains a short segment B<<466.0,647.5>-<477.0,635.0>-<477.0,635.0>>

	* dollar (U+0024) contains a short segment B<<448.0,614.0>-<447.0,616.0>-<435.0,628.5>>

	* ampersand (U+0026) contains a short segment B<<231.0,385.0>-<229.0,387.0>-<227.0,389.0>>

	* three (U+0033) contains a short segment L<<178.0,406.0>--<190.0,406.0>>

	* sterling (U+00A3) contains a short segment B<<74.0,2.0>-<68.0,-8.0>-<68.0,-8.0>>

	* sterling (U+00A3) contains a short segment B<<31.0,1.0>-<31.0,1.0>-<37.0,14.0>>

	* sterling (U+00A3) contains a short segment B<<553.5,39.5>-<560.0,51.0>-<565.0,57.0>>

	* sterling (U+00A3) contains a short segment B<<605.0,41.0>-<603.0,40.0>-<598.5,29.5>>

	* section (U+00A7) contains a short segment B<<463.5,712.0>-<476.0,700.0>-<477.0,699.0>>

	* uni00B3 (U+00B3) contains a short segment L<<108.0,641.0>--<115.0,641.0>>

	* threequarters (U+00BE) contains a short segment L<<108.0,641.0>--<115.0,641.0>>

	* germandbls (U+00DF) contains a short segment L<<338.0,406.0>--<349.0,406.0>>

	* Eng (U+014A) contains a short segment L<<589.0,0.0>--<584.0,0.0>>

	* Eng (U+014A) contains a short segment B<<516.0,-169.0>-<528.0,-169.0>-<538.0,-159.0>>

	* Eng (U+014A) contains a short segment L<<548.0,0.0>--<553.0,0.0>>

	* uni019D (U+019D) contains a short segment L<<117.0,0.0>--<112.0,0.0>>

	* uni019D (U+019D) contains a short segment B<<44.0,-169.0>-<56.0,-169.0>-<65.5,-159.0>>

	* uni019D (U+019D) contains a short segment L<<75.0,0.0>--<80.0,0.0>>

	* uni03A9 (U+03A9) contains a short segment L<<558.0,1.0>--<561.0,24.0>>

	* uni1E9E (U+1E9E) contains a short segment L<<300.0,373.0>--<300.0,401.0>>

	* uni2083 (U+2083) contains a short segment L<<108.0,246.0>--<115.0,246.0>>

	* Euro (U+20AC) contains a short segment B<<111.0,349.0>-<111.0,355.0>-<110.5,361.5>>

	* Euro (U+20AC) contains a short segment B<<110.5,361.5>-<110.0,368.0>-<110.0,374.0>>

	* Euro (U+20AC) contains a short segment B<<147.0,374.0>-<148.0,368.0>-<148.0,361.5>>

	* Euro (U+20AC) contains a short segment B<<148.0,361.5>-<148.0,355.0>-<148.0,349.0>>

	* uni2126 (U+2126) contains a short segment L<<558.0,1.0>--<561.0,24.0>>

	* summation (U+2211) contains a short segment L<<395.0,354.0>--<395.0,341.0>>

	* radical (U+221A) contains a short segment L<<376.0,-6.0>--<370.0,-6.0>>

	* uni2325 (U+2325) contains a short segment B<<359.0,-12.0>-<354.0,-12.0>-<352.0,-7.0>>

	* uni2325 (U+2325) contains a short segment B<<212.0,492.0>-<217.0,492.0>-<219.0,487.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* aacute (U+00E1): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* abreve (U+0103): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* acircumflex (U+00E2): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* adieresis (U+00E4): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* ae (U+00E6): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* aeacute (U+01FD): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* agrave (U+00E0): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* amacron (U+0101): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* aogonek (U+0105): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* aring (U+00E5): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* aringacute (U+01FB): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* atilde (U+00E3): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613

	* r (U+0072): L<<126.0,500.0>--<126.0,379.0>>/B<<126.0,379.0>-<140.0,447.0>-<175.5,476.5>> = 11.633633998940427

	* racute (U+0155): L<<126.0,500.0>--<126.0,379.0>>/B<<126.0,379.0>-<140.0,447.0>-<175.5,476.5>> = 11.633633998940427

	* rcaron (U+0159): L<<126.0,500.0>--<126.0,379.0>>/B<<126.0,379.0>-<140.0,447.0>-<175.5,476.5>> = 11.633633998940427

	* rmacronbelow (U+1E5F): L<<126.0,500.0>--<126.0,379.0>>/B<<126.0,379.0>-<140.0,447.0>-<175.5,476.5>> = 11.633633998940427

	* uni0157 (U+0157): L<<126.0,500.0>--<126.0,379.0>>/B<<126.0,379.0>-<140.0,447.0>-<175.5,476.5>> = 11.633633998940427

	* uni1E5B (U+1E5B): L<<126.0,500.0>--<126.0,379.0>>/B<<126.0,379.0>-<140.0,447.0>-<175.5,476.5>> = 11.633633998940427

	* uni1EA1 (U+1EA1): L<<382.0,0.0>--<382.0,132.0>>/B<<382.0,132.0>-<376.0,96.0>-<354.0,64.5>> = 9.462322208025613 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[8] LilGrotesk-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Black'. Expected OS/2 usWeightClass is 900, got 800. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1360, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 368, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni01CE.ss01
 [code: unreachable-glyphs]
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

	* three (U+0033) contains a short segment L<<203.0,443.0>--<217.0,443.0>>

	* question (U+003F) contains a short segment B<<142.5,542.0>-<137.0,534.0>-<137.0,534.0>>

	* at (U+0040) contains a short segment B<<608.0,305.5>-<630.0,302.0>-<645.0,298.0>>

	* at (U+0040) contains a short segment B<<645.0,303.0>-<645.0,325.0>-<627.0,340.0>>

	* at (U+0040) contains a short segment B<<809.0,117.0>-<824.0,100.0>-<844.0,100.0>>

	* at (U+0040) contains a short segment B<<713.0,54.0>-<705.0,75.0>-<705.0,91.0>>

	* asciitilde (U+007E) contains a short segment B<<455.0,363.0>-<457.0,363.0>-<464.0,365.0>>

	* sterling (U+00A3) contains a short segment B<<118.0,27.0>-<115.0,15.0>-<114.5,6.0>>

	* sterling (U+00A3) contains a short segment B<<114.5,6.0>-<114.0,-3.0>-<114.0,-3.0>>

	* sterling (U+00A3) contains a short segment B<<-35.0,38.0>-<-35.0,38.0>-<-28.0,58.0>>

	* section (U+00A7) contains a short segment B<<481.5,688.0>-<495.0,675.0>-<495.0,675.0>>

	* section (U+00A7) contains a short segment B<<376.0,583.0>-<374.0,585.0>-<364.0,594.5>>

	* uni00B3 (U+00B3) contains a short segment L<<123.0,664.0>--<132.0,664.0>>

	* cedilla (U+00B8) contains a short segment L<<296.0,-48.0>--<299.0,-48.0>>

	* threequarters (U+00BE) contains a short segment L<<123.0,664.0>--<132.0,664.0>>

	* questiondown (U+00BF) contains a short segment B<<295.5,-41.5>-<301.0,-33.0>-<301.0,-34.0>>

	* Ccedilla (U+00C7) contains a short segment L<<372.0,-50.0>--<375.0,-50.0>>

	* germandbls (U+00DF) contains a short segment L<<433.0,443.0>--<447.0,443.0>>

	* ccedilla (U+00E7) contains a short segment L<<278.0,-48.0>--<281.0,-48.0>>

	* eth (U+00F0) contains a short segment B<<294.0,503.0>-<294.0,503.0>-<294.5,504.0>>

	* eth (U+00F0) contains a short segment B<<294.5,504.0>-<295.0,505.0>-<293.0,506.0>>

	* Eng (U+014A) contains a short segment L<<662.0,0.0>--<657.0,0.0>>

	* Eng (U+014A) contains a short segment B<<489.0,-65.0>-<501.0,-65.0>-<508.5,-57.5>>

	* Eng (U+014A) contains a short segment L<<516.0,0.0>--<521.0,0.0>>

	* OE (U+0152) contains a short segment L<<504.0,0.0>--<504.0,18.0>>

	* Scedilla (U+015E) contains a short segment L<<278.0,-48.0>--<281.0,-48.0>>

	* scedilla (U+015F) contains a short segment L<<238.0,-48.0>--<241.0,-48.0>>

	* uni0162 (U+0162) contains a short segment L<<328.0,-48.0>--<331.0,-48.0>>

	* uni0163 (U+0163) contains a short segment L<<218.0,-48.0>--<221.0,-48.0>>

	* uni019D (U+019D) contains a short segment L<<235.0,0.0>--<230.0,0.0>>

	* uni019D (U+019D) contains a short segment B<<49.0,-65.0>-<61.0,-65.0>-<68.0,-57.5>>

	* uni019D (U+019D) contains a short segment L<<75.0,0.0>--<80.0,0.0>>

	* uni0327 (U+0327) contains a short segment L<<296.0,-48.0>--<299.0,-48.0>>

	* uni1E08 (U+1E08) contains a short segment L<<372.0,-50.0>--<375.0,-50.0>>

	* uni1E09 (U+1E09) contains a short segment L<<278.0,-48.0>--<281.0,-48.0>>

	* uni1E1C (U+1E1C) contains a short segment L<<340.0,-48.0>--<343.0,-48.0>>

	* uni1E1D (U+1E1D) contains a short segment L<<296.0,-48.0>--<299.0,-48.0>>

	* uni2083 (U+2083) contains a short segment L<<123.0,269.0>--<132.0,269.0>>

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

	* radical (U+221A) contains a short segment L<<362.0,-6.0>--<359.0,-6.0>>

	* integral (U+222B) contains a short segment B<<141.0,12.0>-<147.0,10.0>-<154.0,10.0>>

	* integral (U+222B) contains a short segment B<<154.0,10.0>-<162.0,10.0>-<165.5,17.5>>

	* uni2325 (U+2325) contains a short segment B<<359.0,-12.0>-<354.0,-12.0>-<352.0,-7.0>>

	* uni2325 (U+2325) contains a short segment B<<212.0,492.0>-<217.0,492.0>-<219.0,487.0>>

	* fi (U+FB01) contains a short segment B<<270.0,581.0>-<262.0,581.0>-<252.5,572.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* trademark (U+2122): L<<577.0,393.0>--<556.0,499.0>>/L<<556.0,499.0>--<556.0,338.0>> = 11.205947507402552

	* trademark (U+2122): L<<696.0,338.0>--<696.0,499.0>>/L<<696.0,499.0>--<678.0,393.0>> = 9.637538112930923 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[7] LilGrotesk-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1360, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 368, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni01CE.ss01
 [code: unreachable-glyphs]
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

	* three (U+0033) contains a short segment L<<182.0,411.0>--<193.0,411.0>>

	* semicolon (U+003B) contains a short segment B<<133.0,42.0>-<133.0,41.0>-<133.0,41.0>>

	* sterling (U+00A3) contains a short segment B<<80.0,2.5>-<75.0,-8.0>-<75.0,-8.0>>

	* sterling (U+00A3) contains a short segment B<<22.0,6.0>-<22.0,6.0>-<28.0,20.0>>

	* sterling (U+00A3) contains a short segment B<<537.0,54.0>-<543.0,66.0>-<546.0,74.0>>

	* sterling (U+00A3) contains a short segment B<<600.0,57.0>-<599.0,54.0>-<594.0,41.0>>

	* section (U+00A7) contains a short segment B<<466.0,708.5>-<479.0,696.0>-<480.0,695.0>>

	* uni00B3 (U+00B3) contains a short segment L<<110.0,644.0>--<117.0,644.0>>

	* threequarters (U+00BE) contains a short segment L<<110.0,644.0>--<117.0,644.0>>

	* germandbls (U+00DF) contains a short segment L<<351.0,411.0>--<362.0,411.0>>

	* Eng (U+014A) contains a short segment L<<599.0,0.0>--<594.0,0.0>>

	* Eng (U+014A) contains a short segment B<<513.0,-154.0>-<525.0,-154.0>-<534.0,-144.5>>

	* Eng (U+014A) contains a short segment L<<543.0,0.0>--<548.0,0.0>>

	* uni019D (U+019D) contains a short segment L<<134.0,0.0>--<129.0,0.0>>

	* uni019D (U+019D) contains a short segment B<<44.0,-154.0>-<56.0,-154.0>-<65.5,-144.5>>

	* uni019D (U+019D) contains a short segment L<<75.0,0.0>--<80.0,0.0>>

	* uni2083 (U+2083) contains a short segment L<<110.0,249.0>--<117.0,249.0>>

	* Euro (U+20AC) contains a short segment B<<115.0,349.0>-<115.0,356.0>-<115.0,362.0>>

	* Euro (U+20AC) contains a short segment B<<115.0,362.0>-<115.0,368.0>-<115.0,375.0>>

	* Euro (U+20AC) contains a short segment B<<169.0,375.0>-<169.0,368.0>-<169.0,362.0>>

	* Euro (U+20AC) contains a short segment B<<169.0,362.0>-<169.0,356.0>-<169.0,349.0>>

	* summation (U+2211) contains a short segment L<<422.0,356.0>--<422.0,339.0>>

	* radical (U+221A) contains a short segment L<<374.0,-6.0>--<369.0,-6.0>>

	* uni2325 (U+2325) contains a short segment B<<359.0,-12.0>-<354.0,-12.0>-<352.0,-7.0>>

	* uni2325 (U+2325) contains a short segment B<<212.0,492.0>-<217.0,492.0>-<219.0,487.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* aacute (U+00E1): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* abreve (U+0103): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* acircumflex (U+00E2): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* adieresis (U+00E4): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* ae (U+00E6): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* aeacute (U+01FD): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* agrave (U+00E0): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* amacron (U+0101): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* aogonek (U+0105): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* aring (U+00E5): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* aringacute (U+01FB): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* atilde (U+00E3): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009

	* r (U+0072): L<<136.0,500.0>--<136.0,388.0>>/B<<136.0,388.0>-<149.0,450.0>-<183.5,478.0>> = 11.842076115327746

	* racute (U+0155): L<<136.0,500.0>--<136.0,388.0>>/B<<136.0,388.0>-<149.0,450.0>-<183.5,478.0>> = 11.842076115327746

	* rcaron (U+0159): L<<136.0,500.0>--<136.0,388.0>>/B<<136.0,388.0>-<149.0,450.0>-<183.5,478.0>> = 11.842076115327746

	* rmacronbelow (U+1E5F): L<<136.0,500.0>--<136.0,388.0>>/B<<136.0,388.0>-<149.0,450.0>-<183.5,478.0>> = 11.842076115327746

	* uni0157 (U+0157): L<<136.0,500.0>--<136.0,388.0>>/B<<136.0,388.0>-<149.0,450.0>-<183.5,478.0>> = 11.842076115327746

	* uni1E5B (U+1E5B): L<<136.0,500.0>--<136.0,388.0>>/B<<136.0,388.0>-<149.0,450.0>-<183.5,478.0>> = 11.842076115327746

	* uni1EA1 (U+1EA1): L<<373.0,0.0>--<373.0,120.0>>/B<<373.0,120.0>-<367.0,87.0>-<346.0,58.0>> = 10.304846468766009 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[7] LilGrotesk-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1360, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 368, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + l

	- l + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni01CE.ss01
 [code: unreachable-glyphs]
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

	* three (U+0033) contains a short segment L<<200.0,439.0>--<214.0,439.0>>

	* semicolon (U+003B) contains a short segment B<<214.0,76.0>-<214.0,75.0>-<214.0,74.0>>

	* at (U+0040) contains a short segment B<<613.0,302.0>-<636.0,299.0>-<652.0,294.0>>

	* at (U+0040) contains a short segment B<<714.5,57.0>-<707.0,79.0>-<707.0,96.0>>

	* sterling (U+00A3) contains a short segment B<<110.0,5.0>-<109.0,-4.0>-<109.0,-4.0>>

	* sterling (U+00A3) contains a short segment B<<-28.0,34.0>-<-28.0,34.0>-<-21.0,53.5>>

	* section (U+00A7) contains a short segment B<<479.5,690.5>-<493.0,677.0>-<493.0,677.0>>

	* section (U+00A7) contains a short segment B<<383.0,593.0>-<381.0,595.0>-<370.0,605.0>>

	* uni00B3 (U+00B3) contains a short segment L<<121.0,661.0>--<130.0,661.0>>

	* cedilla (U+00B8) contains a short segment L<<294.0,-49.0>--<301.0,-49.0>>

	* threequarters (U+00BE) contains a short segment L<<121.0,661.0>--<130.0,661.0>>

	* Ccedilla (U+00C7) contains a short segment L<<370.0,-51.0>--<377.0,-51.0>>

	* germandbls (U+00DF) contains a short segment L<<423.0,439.0>--<437.0,439.0>>

	* ccedilla (U+00E7) contains a short segment L<<273.0,-49.0>--<280.0,-49.0>>

	* eth (U+00F0) contains a short segment B<<294.0,498.0>-<303.0,498.0>-<307.0,496.0>>

	* Eng (U+014A) contains a short segment L<<654.0,0.0>--<649.0,0.0>>

	* Eng (U+014A) contains a short segment B<<492.0,-76.0>-<504.0,-76.0>-<511.5,-68.0>>

	* Eng (U+014A) contains a short segment L<<519.0,0.0>--<524.0,0.0>>

	* OE (U+0152) contains a short segment L<<515.0,0.0>--<515.0,24.0>>

	* Scedilla (U+015E) contains a short segment L<<272.0,-49.0>--<279.0,-49.0>>

	* scedilla (U+015F) contains a short segment L<<229.0,-49.0>--<236.0,-49.0>>

	* uni0162 (U+0162) contains a short segment L<<324.0,-49.0>--<331.0,-49.0>>

	* uni0163 (U+0163) contains a short segment L<<214.0,-49.0>--<221.0,-49.0>>

	* uni019D (U+019D) contains a short segment L<<223.0,0.0>--<218.0,0.0>>

	* uni019D (U+019D) contains a short segment B<<48.0,-76.0>-<60.0,-76.0>-<67.5,-68.0>>

	* uni019D (U+019D) contains a short segment L<<75.0,0.0>--<80.0,0.0>>

	* uni0327 (U+0327) contains a short segment L<<294.0,-49.0>--<301.0,-49.0>>

	* uni1E08 (U+1E08) contains a short segment L<<370.0,-51.0>--<377.0,-51.0>>

	* uni1E09 (U+1E09) contains a short segment L<<273.0,-49.0>--<280.0,-49.0>>

	* uni1E1C (U+1E1C) contains a short segment L<<333.0,-49.0>--<340.0,-49.0>>

	* uni1E1D (U+1E1D) contains a short segment L<<292.0,-49.0>--<299.0,-49.0>>

	* uni2083 (U+2083) contains a short segment L<<121.0,266.0>--<130.0,266.0>>

	* Euro (U+20AC) contains a short segment B<<143.0,316.0>-<142.0,324.0>-<141.5,332.5>>

	* Euro (U+20AC) contains a short segment B<<141.5,332.5>-<141.0,341.0>-<141.0,349.0>>

	* Euro (U+20AC) contains a short segment B<<141.0,349.0>-<141.0,357.0>-<141.5,365.0>>

	* Euro (U+20AC) contains a short segment B<<141.5,365.0>-<142.0,373.0>-<143.0,380.0>>

	* Euro (U+20AC) contains a short segment B<<286.0,380.0>-<285.0,373.0>-<284.5,365.0>>

	* Euro (U+20AC) contains a short segment B<<284.5,365.0>-<284.0,357.0>-<284.0,349.0>>

	* Euro (U+20AC) contains a short segment B<<284.0,349.0>-<284.0,341.0>-<284.5,332.5>>

	* Euro (U+20AC) contains a short segment B<<284.5,332.5>-<285.0,324.0>-<286.0,316.0>>

	* radical (U+221A) contains a short segment L<<363.0,-6.0>--<360.0,-6.0>>

	* uni2325 (U+2325) contains a short segment B<<359.0,-12.0>-<354.0,-12.0>-<352.0,-7.0>>

	* uni2325 (U+2325) contains a short segment B<<212.0,492.0>-<217.0,492.0>-<219.0,487.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* trademark (U+2122): L<<567.0,393.0>--<537.0,515.0>>/L<<537.0,515.0>--<537.0,341.0>> = 13.81502534126161

	* trademark (U+2122): L<<689.0,341.0>--<689.0,515.0>>/L<<689.0,515.0>--<662.0,393.0>> = 12.479071801927638 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 9 | 35 | 721 | 43 | 607 | 0 |
| 0% | 1% | 2% | 51% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
