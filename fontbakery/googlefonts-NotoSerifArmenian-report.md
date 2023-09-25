## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[13] NotoSerifArmenian-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, tifinagh, coptic, math, canadian-aboriginal, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, lisu, coptic, kaithi, sundanese, kharoshthi, yi, sora-sompeng, cham, kayah-li
 * U+25CC DOTTED CIRCLE: try adding one of: tibetan, rejang, lepcha, duployan, kayah-li, pahawh-hmong, sinhala, coptic, mongolian, oriya, bengali, syriac, miao, tamil, limbu, sogdian, hanunoo, math, gujarati, symbols, batak, chakma, thaana, javanese, meetei-mayek, modi, elbasan, bassa-vah, khojki, siddham, sundanese, new-tai-lue, tirhuta, old-permic, khudawadi, manichaean, tagbanwa, kharoshthi, buginese, takri, yi, bhaiksuki, thai, gunjala-gondi, dogra, cham, buhid, ahom, masaram-gondi, hebrew, devanagari, soyombo, kannada, marchen, tifinagh, khmer, gurmukhi, psalter-pahlavi, balinese, phags-pa, grantha, adlam, telugu, tai-viet, brahmi, music, tai-le, malayalam, newa, sharada, lao, kaithi, mahajani, nko, wancho, mandaic, mende-kikakui, caucasian-albanian, zanabazar-square, hanifi-rohingya, myanmar, syloti-nagri, osage, tagalog

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0536
	* uni0537
	* uni053E
	* uni0540
	* uni0541
	* uni0543
	* uni0554
	* uni0556
	* uni0568
	* uni0569
	* uni0571
	* uni0572
	* uni0573
	* uni0579
	* uni057B
	* uni0584
	* uni0586
	* uni0588
	* uni058F
	* uniFB13
	* uniFB14
	* uniFB15
	* uniFB16 and uniFB17
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0548 + uni0552

	- uni0574 + uni0565

	- uni0565 + uni056B

	- uni056B + uni056D

	- uni056D + uni0576

	- uni0578 + uni0582

	- uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Armenian Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 569 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=765.0,Y=-2.0 (should be at baseline 0?)

	* J (U+004A): X=117.0,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=317.0,Y=2.0 (should be at baseline 0?)

	* Q (U+0051): X=317.0,Y=-1.0 (should be at baseline 0?)

	* c (U+0063): X=431.0,Y=535.0 (should be at x-height 536?)

	* f (U+0066): X=155.0,Y=713.5 (should be at cap-height 714?)

	* p (U+0070): X=337.5,Y=1.5 (should be at baseline 0?)

	* q (U+0071): X=386.0,Y=1.0 (should be at baseline 0?)

	* s (U+0073): X=376.5,Y=535.5 (should be at x-height 536?)

	* t (U+0074): X=93.0,Y=535.5 (should be at x-height 536?)

	* t (U+0074): X=367.0,Y=1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=329.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=469.0,Y=2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=281.0,Y=-1.0 (should be at baseline 0?)

	* dcaron (U+010F): X=666.5,Y=712.5 (should be at cap-height 714?)

	* lcaron (U+013E): X=376.5,Y=712.5 (should be at cap-height 714?)

	* tcaron (U+0165): X=371.0,Y=1.5 (should be at baseline 0?)

	* tcaron (U+0165): X=378.5,Y=712.5 (should be at cap-height 714?)

	* uni021B (U+021B): X=367.0,Y=1.5 (should be at baseline 0?)

	* uni0312 (U+0312): X=98.0,Y=713.0 (should be at cap-height 714?)

	* uni0545 (U+0545): X=208.0,Y=1.0 (should be at baseline 0?)

	* uni0545 (U+0545): X=461.5,Y=0.5 (should be at baseline 0?)

	* uni055A (U+055A): X=184.5,Y=714.5 (should be at cap-height 714?)

	* uni055C (U+055C): X=284.5,Y=712.0 (should be at cap-height 714?)

	* uni0561 (U+0561): X=433.0,Y=2.0 (should be at baseline 0?)

	* uni056D (U+056D): X=611.0,Y=-0.5 (should be at baseline 0?)

	* uni0573 (U+0573): X=302.0,Y=-0.5 (should be at baseline 0?)

	* uni0574 (U+0574): X=301.0,Y=-0.5 (should be at baseline 0?)

	* uni0575 (U+0575): X=272.0,Y=-2.0 (should be at baseline 0?)

	* uni0576 (U+0576): X=299.5,Y=2.0 (should be at baseline 0?)

	* uni057A (U+057A): X=448.0,Y=2.0 (should be at baseline 0?)

	* uni057E (U+057E): X=300.0,Y=-0.5 (should be at baseline 0?)

	* uni057F (U+057F): X=300.0,Y=-0.5 (should be at baseline 0?)

	* uni0583 (U+0583): X=300.0,Y=-0.5 (should be at baseline 0?)

	* uni0587 (U+0587): X=300.0,Y=-0.5 (should be at baseline 0?)

	* quoteleft (U+2018): X=246.0,Y=713.0 (should be at cap-height 714?)

	* uni2019 (U+2019): X=184.5,Y=714.5 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=462.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=246.0,Y=713.0 (should be at cap-height 714?)

	* uniFB13 (U+FB13): X=301.0,Y=-0.5 (should be at baseline 0?)

	* uniFB13 (U+FB13): X=927.5,Y=2.0 (should be at baseline 0?)

	* uniFB15 (U+FB15): X=301.0,Y=-0.5 (should be at baseline 0?)

	* uniFB16 (U+FB16): X=921.5,Y=2.0 (should be at baseline 0?)

	* uniFB17 (U+FB17): X=1239.0,Y=-0.5 (should be at baseline 0?)

	* uniFB17 (U+FB17): X=300.0,Y=-0.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<402.5,227.0>-<406.0,208.0>-<407.0,194.0>>/B<<407.0,194.0>-<409.0,211.0>-<416.0,238.5>> = 10.79545358773178

	* eogonek (U+0119): B<<282.5,-58.0>-<309.0,-25.0>-<346.0,-9.0>>/B<<346.0,-9.0>-<340.0,-10.0>-<333.5,-10.0>> = 13.922898849188117

	* y (U+0079): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* yacute (U+00FD): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ycircumflex (U+0177): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ydieresis (U+00FF): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ygrave (U+1EF3): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>>

	* uniFB17 (U+FB17): L<<882.0,703.0>--<881.0,493.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSerifArmenian-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, tifinagh, coptic, math, canadian-aboriginal, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, lisu, coptic, kaithi, sundanese, kharoshthi, yi, sora-sompeng, cham, kayah-li
 * U+25CC DOTTED CIRCLE: try adding one of: tibetan, rejang, lepcha, duployan, kayah-li, pahawh-hmong, sinhala, coptic, mongolian, oriya, bengali, syriac, miao, tamil, limbu, sogdian, hanunoo, math, gujarati, symbols, batak, chakma, thaana, javanese, meetei-mayek, modi, elbasan, bassa-vah, khojki, siddham, sundanese, new-tai-lue, tirhuta, old-permic, khudawadi, manichaean, tagbanwa, kharoshthi, buginese, takri, yi, bhaiksuki, thai, gunjala-gondi, dogra, cham, buhid, ahom, masaram-gondi, hebrew, devanagari, soyombo, kannada, marchen, tifinagh, khmer, gurmukhi, psalter-pahlavi, balinese, phags-pa, grantha, adlam, telugu, tai-viet, brahmi, music, tai-le, malayalam, newa, sharada, lao, kaithi, mahajani, nko, wancho, mandaic, mende-kikakui, caucasian-albanian, zanabazar-square, hanifi-rohingya, myanmar, syloti-nagri, osage, tagalog

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0536
	* uni0537
	* uni0540
	* uni0541
	* uni0543
	* uni0554
	* uni0556
	* uni0568
	* uni0569
	* uni0571
	* uni0572
	* uni0573
	* uni057B
	* uni0584
	* uni0586
	* uni0588
	* uni058F
	* uniFB13
	* uniFB14
	* uniFB15
	* uniFB16 and uniFB17
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0548 + uni0552

	- uni0574 + uni0565

	- uni0565 + uni056B

	- uni056B + uni056D

	- uni056D + uni0576

	- uni0578 + uni0582

	- uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=343.0,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=336.0,Y=2.0 (should be at baseline 0?)

	* J (U+004A): X=281.0,Y=-2.0 (should be at baseline 0?)

	* a (U+0061): X=265.0,Y=-1.5 (should be at baseline 0?)

	* f (U+0066): X=310.0,Y=712.0 (should be at cap-height 714?)

	* s (U+0073): X=356.5,Y=534.5 (should be at x-height 536?)

	* t (U+0074): X=332.5,Y=-1.0 (should be at baseline 0?)

	* agrave (U+00E0): X=265.0,Y=-1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=265.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=265.0,Y=-1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=265.0,Y=-1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=265.0,Y=-1.5 (should be at baseline 0?)

	* aring (U+00E5): X=265.0,Y=-1.5 (should be at baseline 0?)

	* amacron (U+0101): X=265.0,Y=-1.5 (should be at baseline 0?)

	* abreve (U+0103): X=265.0,Y=-1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=265.0,Y=-1.5 (should be at baseline 0?)

	* tcaron (U+0165): X=332.5,Y=-1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=332.5,Y=-1.0 (should be at baseline 0?)

	* uni0545 (U+0545): X=448.0,Y=2.0 (should be at baseline 0?)

	* uni0547 (U+0547): X=94.5,Y=713.0 (should be at cap-height 714?)

	* uni055C (U+055C): X=272.0,Y=714.5 (should be at cap-height 714?)

	* uni055E (U+055E): X=340.0,Y=713.0 (should be at cap-height 714?)

	* uni056E (U+056E): X=371.0,Y=715.0 (should be at cap-height 714?)

	* uni0574 (U+0574): X=605.0,Y=713.0 (should be at cap-height 714?)

	* uni057A (U+057A): X=673.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* y (U+0079): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* yacute (U+00FD): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ycircumflex (U+0177): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ydieresis (U+00FF): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ygrave (U+1EF3): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>>

	* sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSerifArmenian-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, tifinagh, coptic, math, canadian-aboriginal, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, lisu, coptic, kaithi, sundanese, kharoshthi, yi, sora-sompeng, cham, kayah-li
 * U+25CC DOTTED CIRCLE: try adding one of: tibetan, rejang, lepcha, duployan, kayah-li, pahawh-hmong, sinhala, coptic, mongolian, oriya, bengali, syriac, miao, tamil, limbu, sogdian, hanunoo, math, gujarati, symbols, batak, chakma, thaana, javanese, meetei-mayek, modi, elbasan, bassa-vah, khojki, siddham, sundanese, new-tai-lue, tirhuta, old-permic, khudawadi, manichaean, tagbanwa, kharoshthi, buginese, takri, yi, bhaiksuki, thai, gunjala-gondi, dogra, cham, buhid, ahom, masaram-gondi, hebrew, devanagari, soyombo, kannada, marchen, tifinagh, khmer, gurmukhi, psalter-pahlavi, balinese, phags-pa, grantha, adlam, telugu, tai-viet, brahmi, music, tai-le, malayalam, newa, sharada, lao, kaithi, mahajani, nko, wancho, mandaic, mende-kikakui, caucasian-albanian, zanabazar-square, hanifi-rohingya, myanmar, syloti-nagri, osage, tagalog

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0536
	* uni0537
	* uni053E
	* uni0540
	* uni0541
	* uni0543
	* uni0554
	* uni0556
	* uni0568
	* uni0569
	* uni0571
	* uni0572
	* uni0573
	* uni0579
	* uni057B
	* uni0584
	* uni0586
	* uni0588
	* uni058F
	* uniFB13
	* uniFB14
	* uniFB15
	* uniFB16 and uniFB17
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0548 + uni0552

	- uni0574 + uni0565

	- uni0565 + uni056B

	- uni056B + uni056D

	- uni056D + uni0576

	- uni0578 + uni0582

	- uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Armenian ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 564 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=351.5,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=120.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=319.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=509.0,Y=2.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=274.0,Y=1.0 (should be at baseline 0?)

	* bracketright (U+005D): X=162.0,Y=1.0 (should be at baseline 0?)

	* b (U+0062): X=269.5,Y=534.5 (should be at x-height 536?)

	* c (U+0063): X=417.0,Y=535.0 (should be at x-height 536?)

	* f (U+0066): X=157.5,Y=715.0 (should be at cap-height 714?)

	* p (U+0070): X=265.0,Y=-1.5 (should be at baseline 0?)

	* s (U+0073): X=367.0,Y=535.0 (should be at x-height 536?)

	* t (U+0074): X=86.5,Y=534.0 (should be at x-height 536?)

	* t (U+0074): X=351.0,Y=0.5 (should be at baseline 0?)

	* y (U+0079): X=353.0,Y=2.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=373.0,Y=712.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=394.0,Y=713.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=411.0,Y=713.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=395.0,Y=713.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=353.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=353.0,Y=2.0 (should be at baseline 0?)

	* dcaron (U+010F): X=651.5,Y=712.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=358.5,Y=712.0 (should be at cap-height 714?)

	* tcaron (U+0165): X=353.0,Y=0.5 (should be at baseline 0?)

	* tcaron (U+0165): X=359.5,Y=712.0 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=353.0,Y=2.0 (should be at baseline 0?)

	* uni021B (U+021B): X=351.0,Y=0.5 (should be at baseline 0?)

	* tilde (U+02DC): X=330.0,Y=713.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-234.0,Y=713.0 (should be at cap-height 714?)

	* uni0312 (U+0312): X=95.0,Y=713.0 (should be at cap-height 714?)

	* uni0545 (U+0545): X=455.5,Y=1.0 (should be at baseline 0?)

	* uni0547 (U+0547): X=116.5,Y=715.0 (should be at cap-height 714?)

	* uni055C (U+055C): X=118.0,Y=713.5 (should be at cap-height 714?)

	* uni055C (U+055C): X=278.5,Y=713.0 (should be at cap-height 714?)

	* uni0561 (U+0561): X=602.0,Y=0.5 (should be at baseline 0?)

	* uni0576 (U+0576): X=303.0,Y=1.5 (should be at baseline 0?)

	* uni057D (U+057D): X=303.5,Y=2.0 (should be at baseline 0?)

	* ygrave (U+1EF3): X=353.0,Y=2.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=241.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=454.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=241.0,Y=713.0 (should be at cap-height 714?)

	* uniFB13 (U+FB13): X=927.5,Y=1.5 (should be at baseline 0?)

	* uniFB16 (U+FB16): X=371.0,Y=-2.0 (should be at baseline 0?)

	* uniFB16 (U+FB16): X=919.5,Y=1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eogonek (U+0119): B<<270.5,-58.5>-<297.0,-26.0>-<333.0,-9.0>>/B<<333.0,-9.0>-<329.0,-10.0>-<324.0,-10.0>> = 11.24147876762648

	* y (U+0079): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* yacute (U+00FD): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ycircumflex (U+0177): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ydieresis (U+00FF): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ygrave (U+1EF3): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<442.0,340.0>--<284.0,341.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSerifArmenian-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, tifinagh, coptic, math, canadian-aboriginal, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, lisu, coptic, kaithi, sundanese, kharoshthi, yi, sora-sompeng, cham, kayah-li
 * U+25CC DOTTED CIRCLE: try adding one of: tibetan, rejang, lepcha, duployan, kayah-li, pahawh-hmong, sinhala, coptic, mongolian, oriya, bengali, syriac, miao, tamil, limbu, sogdian, hanunoo, math, gujarati, symbols, batak, chakma, thaana, javanese, meetei-mayek, modi, elbasan, bassa-vah, khojki, siddham, sundanese, new-tai-lue, tirhuta, old-permic, khudawadi, manichaean, tagbanwa, kharoshthi, buginese, takri, yi, bhaiksuki, thai, gunjala-gondi, dogra, cham, buhid, ahom, masaram-gondi, hebrew, devanagari, soyombo, kannada, marchen, tifinagh, khmer, gurmukhi, psalter-pahlavi, balinese, phags-pa, grantha, adlam, telugu, tai-viet, brahmi, music, tai-le, malayalam, newa, sharada, lao, kaithi, mahajani, nko, wancho, mandaic, mende-kikakui, caucasian-albanian, zanabazar-square, hanifi-rohingya, myanmar, syloti-nagri, osage, tagalog

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0536
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0548 + uni0552

	- uni0574 + uni0565

	- uni0565 + uni056B

	- uni056B + uni056D

	- uni056D + uni0576

	- uni0578 + uni0582

	- uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Armenian ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=486.5,Y=-1.0 (should be at baseline 0?)

	* W (U+0057): X=496.0,Y=713.0 (should be at cap-height 714?)

	* W (U+0057): X=533.0,Y=713.0 (should be at cap-height 714?)

	* f (U+0066): X=349.0,Y=716.0 (should be at cap-height 714?)

	* w (U+0077): X=411.0,Y=535.0 (should be at x-height 536?)

	* w (U+0077): X=452.0,Y=535.0 (should be at x-height 536?)

	* sterling (U+00A3): X=359.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=91.0,Y=2.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=486.5,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=486.5,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=486.5,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=569.0,Y=1.0 (should be at baseline 0?)

	* Wcircumflex (U+0174): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wcircumflex (U+0174): X=533.0,Y=713.0 (should be at cap-height 714?)

	* uni055C (U+055C): X=146.0,Y=716.0 (should be at cap-height 714?)

	* uni055E (U+055E): X=191.0,Y=713.0 (should be at cap-height 714?)

	* uni0565 (U+0565): X=83.5,Y=713.5 (should be at cap-height 714?)

	* uni056B (U+056B): X=94.0,Y=713.0 (should be at cap-height 714?)

	* uni056D (U+056D): X=94.0,Y=713.0 (should be at cap-height 714?)

	* uni056F (U+056F): X=83.5,Y=713.5 (should be at cap-height 714?)

	* uni0570 (U+0570): X=244.5,Y=715.5 (should be at cap-height 714?)

	* uni0574 (U+0574): X=500.5,Y=715.5 (should be at cap-height 714?)

	* uni0587 (U+0587): X=83.5,Y=713.5 (should be at cap-height 714?)

	* Wgrave (U+1E80): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wgrave (U+1E80): X=533.0,Y=713.0 (should be at cap-height 714?)

	* Wacute (U+1E82): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wacute (U+1E82): X=533.0,Y=713.0 (should be at cap-height 714?)

	* Wdieresis (U+1E84): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wdieresis (U+1E84): X=533.0,Y=713.0 (should be at cap-height 714?)

	* Euro (U+20AC): X=417.0,Y=1.5 (should be at baseline 0?)

	* uniFB14 (U+FB14): X=654.0,Y=713.0 (should be at cap-height 714?)

	* uniFB15 (U+FB15): X=655.0,Y=713.0 (should be at cap-height 714?)

	* uniFB17 (U+FB17): X=655.0,Y=713.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSerifArmenian-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, tifinagh, coptic, math, canadian-aboriginal, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, lisu, coptic, kaithi, sundanese, kharoshthi, yi, sora-sompeng, cham, kayah-li
 * U+25CC DOTTED CIRCLE: try adding one of: tibetan, rejang, lepcha, duployan, kayah-li, pahawh-hmong, sinhala, coptic, mongolian, oriya, bengali, syriac, miao, tamil, limbu, sogdian, hanunoo, math, gujarati, symbols, batak, chakma, thaana, javanese, meetei-mayek, modi, elbasan, bassa-vah, khojki, siddham, sundanese, new-tai-lue, tirhuta, old-permic, khudawadi, manichaean, tagbanwa, kharoshthi, buginese, takri, yi, bhaiksuki, thai, gunjala-gondi, dogra, cham, buhid, ahom, masaram-gondi, hebrew, devanagari, soyombo, kannada, marchen, tifinagh, khmer, gurmukhi, psalter-pahlavi, balinese, phags-pa, grantha, adlam, telugu, tai-viet, brahmi, music, tai-le, malayalam, newa, sharada, lao, kaithi, mahajani, nko, wancho, mandaic, mende-kikakui, caucasian-albanian, zanabazar-square, hanifi-rohingya, myanmar, syloti-nagri, osage, tagalog

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0536
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0548 + uni0552

	- uni0574 + uni0565

	- uni0565 + uni056B

	- uni056B + uni056D

	- uni056D + uni0576

	- uni0578 + uni0582

	- uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Armenian Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* nine (U+0039): X=147.0,Y=1.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=183.5,Y=714.5 (should be at cap-height 714?)

	* bracketright (U+005D): X=145.5,Y=714.5 (should be at cap-height 714?)

	* t (U+0074): X=297.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=412.0,Y=534.0 (should be at x-height 536?)

	* w (U+0077): X=462.0,Y=534.0 (should be at x-height 536?)

	* y (U+0079): X=269.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=354.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=79.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=460.5,Y=1.0 (should be at baseline 0?)

	* paragraph (U+00B6): X=496.0,Y=715.5 (should be at cap-height 714?)

	* Oslash (U+00D8): X=446.5,Y=714.5 (should be at cap-height 714?)

	* atilde (U+00E3): X=398.0,Y=712.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=432.0,Y=712.0 (should be at cap-height 714?)

	* eth (U+00F0): X=440.0,Y=715.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=455.0,Y=712.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=489.0,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=408.0,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=442.0,Y=712.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=269.0,Y=-1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=269.0,Y=-1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=222.5,Y=713.5 (should be at cap-height 714?)

	* ccaron (U+010D): X=318.0,Y=713.5 (should be at cap-height 714?)

	* dcroat (U+0111): X=402.5,Y=716.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=219.5,Y=713.5 (should be at cap-height 714?)

	* ecaron (U+011B): X=315.0,Y=713.5 (should be at cap-height 714?)

	* lslash (U+0142): X=98.0,Y=715.5 (should be at cap-height 714?)

	* ncaron (U+0148): X=279.5,Y=713.5 (should be at cap-height 714?)

	* ncaron (U+0148): X=375.0,Y=713.5 (should be at cap-height 714?)

	* rcaron (U+0159): X=176.5,Y=713.5 (should be at cap-height 714?)

	* rcaron (U+0159): X=272.0,Y=713.5 (should be at cap-height 714?)

	* scaron (U+0161): X=173.5,Y=713.5 (should be at cap-height 714?)

	* scaron (U+0161): X=269.0,Y=713.5 (should be at cap-height 714?)

	* tcaron (U+0165): X=297.0,Y=1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=269.0,Y=-1.0 (should be at baseline 0?)

	* zcaron (U+017E): X=212.5,Y=713.5 (should be at cap-height 714?)

	* zcaron (U+017E): X=308.0,Y=713.5 (should be at cap-height 714?)

	* uni021B (U+021B): X=297.0,Y=1.0 (should be at baseline 0?)

	* caron (U+02C7): X=122.5,Y=713.5 (should be at cap-height 714?)

	* caron (U+02C7): X=218.0,Y=713.5 (should be at cap-height 714?)

	* tilde (U+02DC): X=339.0,Y=712.0 (should be at cap-height 714?)

	* tilde (U+02DC): X=373.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-185.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-151.0,Y=712.0 (should be at cap-height 714?)

	* uni030C (U+030C): X=-327.5,Y=713.5 (should be at cap-height 714?)

	* uni030C (U+030C): X=-232.0,Y=713.5 (should be at cap-height 714?)

	* uni0312 (U+0312): X=56.0,Y=715.0 (should be at cap-height 714?)

	* uni0574 (U+0574): X=390.5,Y=712.5 (should be at cap-height 714?)

	* uni0581 (U+0581): X=386.0,Y=-1.0 (should be at baseline 0?)

	* ygrave (U+1EF3): X=269.0,Y=-1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=198.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=377.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=198.0,Y=715.0 (should be at cap-height 714?)

	* uniFB13 (U+FB13): X=391.0,Y=712.5 (should be at cap-height 714?)

	* uniFB14 (U+FB14): X=691.0,Y=712.0 (should be at cap-height 714?)

	* uniFB14 (U+FB14): X=391.0,Y=712.5 (should be at cap-height 714?)

	* uniFB15 (U+FB15): X=693.0,Y=712.0 (should be at cap-height 714?)

	* uniFB15 (U+FB15): X=393.0,Y=712.5 (should be at cap-height 714?)

	* uniFB17 (U+FB17): X=693.0,Y=712.0 (should be at cap-height 714?)

	* uniFB17 (U+FB17): X=394.5,Y=712.5 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSerifArmenian-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, tifinagh, coptic, math, canadian-aboriginal, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, lisu, coptic, kaithi, sundanese, kharoshthi, yi, sora-sompeng, cham, kayah-li
 * U+25CC DOTTED CIRCLE: try adding one of: tibetan, rejang, lepcha, duployan, kayah-li, pahawh-hmong, sinhala, coptic, mongolian, oriya, bengali, syriac, miao, tamil, limbu, sogdian, hanunoo, math, gujarati, symbols, batak, chakma, thaana, javanese, meetei-mayek, modi, elbasan, bassa-vah, khojki, siddham, sundanese, new-tai-lue, tirhuta, old-permic, khudawadi, manichaean, tagbanwa, kharoshthi, buginese, takri, yi, bhaiksuki, thai, gunjala-gondi, dogra, cham, buhid, ahom, masaram-gondi, hebrew, devanagari, soyombo, kannada, marchen, tifinagh, khmer, gurmukhi, psalter-pahlavi, balinese, phags-pa, grantha, adlam, telugu, tai-viet, brahmi, music, tai-le, malayalam, newa, sharada, lao, kaithi, mahajani, nko, wancho, mandaic, mende-kikakui, caucasian-albanian, zanabazar-square, hanifi-rohingya, myanmar, syloti-nagri, osage, tagalog

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0536
	* uni0556
	* uni0586
	* uni058F and uniFB16
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0548 + uni0552

	- uni0574 + uni0565

	- uni0565 + uni056B

	- uni056B + uni056D

	- uni056D + uni0576

	- uni0578 + uni0582

	- uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Armenian Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=329.0,Y=713.0 (should be at cap-height 714?)

	* parenright (U+0029): X=32.0,Y=713.0 (should be at cap-height 714?)

	* three (U+0033): X=337.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=2.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=338.0,Y=715.0 (should be at cap-height 714?)

	* bracketleft (U+005B): X=295.0,Y=715.0 (should be at cap-height 714?)

	* bracketright (U+005D): X=80.0,Y=715.0 (should be at cap-height 714?)

	* bracketright (U+005D): X=37.0,Y=715.0 (should be at cap-height 714?)

	* a (U+0061): X=183.5,Y=537.0 (should be at x-height 536?)

	* a (U+0061): X=271.0,Y=1.5 (should be at baseline 0?)

	* b (U+0062): X=25.0,Y=715.0 (should be at cap-height 714?)

	* b (U+0062): X=18.0,Y=715.0 (should be at cap-height 714?)

	* b (U+0062): X=215.0,Y=537.5 (should be at x-height 536?)

	* c (U+0063): X=371.0,Y=535.0 (should be at x-height 536?)

	* d (U+0064): X=326.0,Y=715.0 (should be at cap-height 714?)

	* d (U+0064): X=318.0,Y=715.0 (should be at cap-height 714?)

	* g (U+0067): X=324.5,Y=537.0 (should be at x-height 536?)

	* g (U+0067): X=316.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=213.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=27.0,Y=715.0 (should be at cap-height 714?)

	* h (U+0068): X=18.0,Y=715.0 (should be at cap-height 714?)

	* k (U+006B): X=27.0,Y=715.0 (should be at cap-height 714?)

	* k (U+006B): X=18.0,Y=715.0 (should be at cap-height 714?)

	* l (U+006C): X=27.0,Y=715.0 (should be at cap-height 714?)

	* l (U+006C): X=14.0,Y=715.0 (should be at cap-height 714?)

	* q (U+0071): X=408.5,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=259.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=78.0,Y=2.0 (should be at baseline 0?)

	* paragraph (U+00B6): X=579.0,Y=715.0 (should be at cap-height 714?)

	* paragraph (U+00B6): X=566.0,Y=715.0 (should be at cap-height 714?)

	* Aring (U+00C5): X=465.0,Y=713.0 (should be at cap-height 714?)

	* Oslash (U+00D8): X=459.5,Y=716.0 (should be at cap-height 714?)

	* agrave (U+00E0): X=271.0,Y=1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=271.0,Y=1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=271.0,Y=1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=271.0,Y=1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=271.0,Y=1.5 (should be at baseline 0?)

	* aring (U+00E5): X=271.0,Y=1.5 (should be at baseline 0?)

	* yacute (U+00FD): X=259.0,Y=2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=27.0,Y=715.0 (should be at cap-height 714?)

	* thorn (U+00FE): X=19.0,Y=715.0 (should be at cap-height 714?)

	* ydieresis (U+00FF): X=259.0,Y=2.0 (should be at baseline 0?)

	* amacron (U+0101): X=271.0,Y=1.5 (should be at baseline 0?)

	* abreve (U+0103): X=271.0,Y=1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=271.0,Y=1.5 (should be at baseline 0?)

	* dcaron (U+010F): X=326.0,Y=715.0 (should be at cap-height 714?)

	* dcaron (U+010F): X=318.0,Y=715.0 (should be at cap-height 714?)

	* dcroat (U+0111): X=326.0,Y=715.0 (should be at cap-height 714?)

	* dcroat (U+0111): X=318.0,Y=715.0 (should be at cap-height 714?)

	* Gbreve (U+011E): X=527.5,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=316.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=213.0,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=527.5,Y=2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=316.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=213.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=527.5,Y=2.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=316.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=213.0,Y=-1.0 (should be at baseline 0?)

	* hbar (U+0127): X=27.0,Y=715.0 (should be at cap-height 714?)

	* hbar (U+0127): X=18.0,Y=715.0 (should be at cap-height 714?)

	* uni0137 (U+0137): X=27.0,Y=715.0 (should be at cap-height 714?)

	* uni0137 (U+0137): X=18.0,Y=715.0 (should be at cap-height 714?)

	* lacute (U+013A): X=27.0,Y=715.0 (should be at cap-height 714?)

	* lacute (U+013A): X=14.0,Y=715.0 (should be at cap-height 714?)

	* uni013C (U+013C): X=27.0,Y=715.0 (should be at cap-height 714?)

	* uni013C (U+013C): X=14.0,Y=715.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=27.0,Y=715.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=14.0,Y=715.0 (should be at cap-height 714?)

	* lslash (U+0142): X=38.0,Y=715.0 (should be at cap-height 714?)

	* lslash (U+0142): X=25.0,Y=715.0 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=259.0,Y=2.0 (should be at baseline 0?)

	* uni0312 (U+0312): X=84.0,Y=715.0 (should be at cap-height 714?)

	* uni0547 (U+0547): X=97.0,Y=714.5 (should be at cap-height 714?)

	* uni0565 (U+0565): X=60.5,Y=713.0 (should be at cap-height 714?)

	* uni056F (U+056F): X=60.5,Y=713.0 (should be at cap-height 714?)

	* uni0576 (U+0576): X=278.0,Y=712.0 (should be at cap-height 714?)

	* uni0586 (U+0586): X=269.0,Y=716.0 (should be at cap-height 714?)

	* uni0587 (U+0587): X=60.5,Y=713.0 (should be at cap-height 714?)

	* ygrave (U+1EF3): X=259.0,Y=2.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=224.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=427.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=224.0,Y=715.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<408.0,339.0>--<251.0,340.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[10] NotoSerifArmenian-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, tifinagh, coptic, math, canadian-aboriginal, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, lisu, coptic, kaithi, sundanese, kharoshthi, yi, sora-sompeng, cham, kayah-li
 * U+25CC DOTTED CIRCLE: try adding one of: tibetan, rejang, lepcha, duployan, kayah-li, pahawh-hmong, sinhala, coptic, mongolian, oriya, bengali, syriac, miao, tamil, limbu, sogdian, hanunoo, math, gujarati, symbols, batak, chakma, thaana, javanese, meetei-mayek, modi, elbasan, bassa-vah, khojki, siddham, sundanese, new-tai-lue, tirhuta, old-permic, khudawadi, manichaean, tagbanwa, kharoshthi, buginese, takri, yi, bhaiksuki, thai, gunjala-gondi, dogra, cham, buhid, ahom, masaram-gondi, hebrew, devanagari, soyombo, kannada, marchen, tifinagh, khmer, gurmukhi, psalter-pahlavi, balinese, phags-pa, grantha, adlam, telugu, tai-viet, brahmi, music, tai-le, malayalam, newa, sharada, lao, kaithi, mahajani, nko, wancho, mandaic, mende-kikakui, caucasian-albanian, zanabazar-square, hanifi-rohingya, myanmar, syloti-nagri, osage, tagalog

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0536
	* uni0556
	* uni0586 and uni058F
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0548 + uni0552

	- uni0574 + uni0565

	- uni0565 + uni056B

	- uni056B + uni056D

	- uni056D + uni0576

	- uni0578 + uni0582

	- uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=314.0,Y=715.0 (should be at cap-height 714?)

	* parenright (U+0029): X=32.0,Y=715.0 (should be at cap-height 714?)

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

	* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=454.5,Y=715.5 (should be at cap-height 714?)

	* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0312 (U+0312): X=82.0,Y=715.0 (should be at cap-height 714?)

	* uni0547 (U+0547): X=98.0,Y=715.5 (should be at cap-height 714?)

	* uni0567 (U+0567): X=74.5,Y=713.5 (should be at cap-height 714?)

	* quoteleft (U+2018): X=220.0,Y=715.0 (should be at cap-height 714?)

	* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

	* quotedblleft (U+201C): X=420.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=220.0,Y=715.0 (should be at cap-height 714?)

	* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

	* uniFB14 (U+FB14): X=548.0,Y=713.5 (should be at cap-height 714?)

	* uniFB15 (U+FB15): X=549.0,Y=713.5 (should be at cap-height 714?)

	* uniFB17 (U+FB17): X=551.5,Y=713.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSerifArmenian-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, tifinagh, coptic, math, canadian-aboriginal, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, lisu, coptic, kaithi, sundanese, kharoshthi, yi, sora-sompeng, cham, kayah-li
 * U+25CC DOTTED CIRCLE: try adding one of: tibetan, rejang, lepcha, duployan, kayah-li, pahawh-hmong, sinhala, coptic, mongolian, oriya, bengali, syriac, miao, tamil, limbu, sogdian, hanunoo, math, gujarati, symbols, batak, chakma, thaana, javanese, meetei-mayek, modi, elbasan, bassa-vah, khojki, siddham, sundanese, new-tai-lue, tirhuta, old-permic, khudawadi, manichaean, tagbanwa, kharoshthi, buginese, takri, yi, bhaiksuki, thai, gunjala-gondi, dogra, cham, buhid, ahom, masaram-gondi, hebrew, devanagari, soyombo, kannada, marchen, tifinagh, khmer, gurmukhi, psalter-pahlavi, balinese, phags-pa, grantha, adlam, telugu, tai-viet, brahmi, music, tai-le, malayalam, newa, sharada, lao, kaithi, mahajani, nko, wancho, mandaic, mende-kikakui, caucasian-albanian, zanabazar-square, hanifi-rohingya, myanmar, syloti-nagri, osage, tagalog

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0536
	* uni0537
	* uni0554
	* uni0556
	* uni0571
	* uni0573
	* uni0584
	* uni0586
	* uni0588
	* uni058F
	* uniFB13
	* uniFB14 and uniFB16
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0548 + uni0552

	- uni0574 + uni0565

	- uni0565 + uni056B

	- uni056B + uni056D

	- uni056D + uni0576

	- uni0578 + uni0582

	- uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Armenian SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=119.0,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=340.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=470.0,Y=-2.0 (should be at baseline 0?)

	* a (U+0061): X=186.5,Y=538.0 (should be at x-height 536?)

	* y (U+0079): X=254.0,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=343.0,Y=-2.0 (should be at baseline 0?)

	* Aring (U+00C5): X=477.0,Y=715.5 (should be at cap-height 714?)

	* germandbls (U+00DF): X=352.0,Y=716.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=135.5,Y=712.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=170.5,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=139.5,Y=712.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=254.0,Y=-2.0 (should be at baseline 0?)

	* yacute (U+00FD): X=343.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=343.0,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=343.0,Y=-2.0 (should be at baseline 0?)

	* tilde (U+02DC): X=73.5,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-474.5,Y=712.0 (should be at cap-height 714?)

	* uni0547 (U+0547): X=96.0,Y=713.5 (should be at cap-height 714?)

	* uni055C (U+055C): X=264.0,Y=716.0 (should be at cap-height 714?)

	* uni055E (U+055E): X=109.0,Y=712.5 (should be at cap-height 714?)

	* uni055E (U+055E): X=438.0,Y=713.0 (should be at cap-height 714?)

	* uni0565 (U+0565): X=25.0,Y=712.0 (should be at cap-height 714?)

	* uni056B (U+056B): X=31.0,Y=712.0 (should be at cap-height 714?)

	* uni056D (U+056D): X=31.0,Y=712.0 (should be at cap-height 714?)

	* uni056F (U+056F): X=25.0,Y=712.0 (should be at cap-height 714?)

	* uni0573 (U+0573): X=407.0,Y=712.0 (should be at cap-height 714?)

	* uni0574 (U+0574): X=594.5,Y=715.0 (should be at cap-height 714?)

	* uni0574 (U+0574): X=438.0,Y=712.0 (should be at cap-height 714?)

	* uni057A (U+057A): X=668.0,Y=1.0 (should be at baseline 0?)

	* uni057E (U+057E): X=328.0,Y=712.0 (should be at cap-height 714?)

	* uni0583 (U+0583): X=328.0,Y=712.0 (should be at cap-height 714?)

	* uni0587 (U+0587): X=25.0,Y=712.0 (should be at cap-height 714?)

	* ygrave (U+1EF3): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ygrave (U+1EF3): X=343.0,Y=-2.0 (should be at baseline 0?)

	* quotesinglbase (U+201A): X=119.0,Y=-1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=324.5,Y=-1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=119.0,Y=-1.0 (should be at baseline 0?)

	* uniFB13 (U+FB13): X=456.0,Y=712.0 (should be at cap-height 714?)

	* uniFB14 (U+FB14): X=456.0,Y=712.0 (should be at cap-height 714?)

	* uniFB15 (U+FB15): X=457.0,Y=712.0 (should be at cap-height 714?)

	* uniFB16 (U+FB16): X=556.0,Y=712.0 (should be at cap-height 714?)

	* uniFB17 (U+FB17): X=457.0,Y=712.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<104.0,119.0>--<103.0,648.0>>

	* h (U+0068): L<<233.0,313.0>--<234.0,115.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSerifArmenian-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, tifinagh, coptic, math, canadian-aboriginal, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, lisu, coptic, kaithi, sundanese, kharoshthi, yi, sora-sompeng, cham, kayah-li
 * U+25CC DOTTED CIRCLE: try adding one of: tibetan, rejang, lepcha, duployan, kayah-li, pahawh-hmong, sinhala, coptic, mongolian, oriya, bengali, syriac, miao, tamil, limbu, sogdian, hanunoo, math, gujarati, symbols, batak, chakma, thaana, javanese, meetei-mayek, modi, elbasan, bassa-vah, khojki, siddham, sundanese, new-tai-lue, tirhuta, old-permic, khudawadi, manichaean, tagbanwa, kharoshthi, buginese, takri, yi, bhaiksuki, thai, gunjala-gondi, dogra, cham, buhid, ahom, masaram-gondi, hebrew, devanagari, soyombo, kannada, marchen, tifinagh, khmer, gurmukhi, psalter-pahlavi, balinese, phags-pa, grantha, adlam, telugu, tai-viet, brahmi, music, tai-le, malayalam, newa, sharada, lao, kaithi, mahajani, nko, wancho, mandaic, mende-kikakui, caucasian-albanian, zanabazar-square, hanifi-rohingya, myanmar, syloti-nagri, osage, tagalog

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0548 + uni0552

	- uni0574 + uni0565

	- uni0565 + uni056B

	- uni056B + uni056D

	- uni056D + uni0576

	- uni0578 + uni0582

	- uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Armenian Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=99.5,Y=-1.5 (should be at baseline 0?)

	* semicolon (U+003B): X=111.5,Y=-1.5 (should be at baseline 0?)

	* C (U+0043): X=407.0,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=477.5,Y=-1.5 (should be at baseline 0?)

	* b (U+0062): X=114.0,Y=715.5 (should be at cap-height 714?)

	* d (U+0064): X=428.0,Y=715.5 (should be at cap-height 714?)

	* g (U+0067): X=394.0,Y=537.5 (should be at x-height 536?)

	* h (U+0068): X=114.0,Y=715.5 (should be at cap-height 714?)

	* k (U+006B): X=114.0,Y=715.5 (should be at cap-height 714?)

	* l (U+006C): X=110.0,Y=715.5 (should be at cap-height 714?)

	* t (U+0074): X=53.5,Y=536.5 (should be at x-height 536?)

	* sterling (U+00A3): X=362.5,Y=-1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=464.5,Y=-0.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=407.0,Y=1.5 (should be at baseline 0?)

	* Oslash (U+00D8): X=437.5,Y=713.5 (should be at cap-height 714?)

	* thorn (U+00FE): X=117.5,Y=716.0 (should be at cap-height 714?)

	* Cacute (U+0106): X=407.0,Y=1.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=407.0,Y=1.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=407.0,Y=1.5 (should be at baseline 0?)

	* dcaron (U+010F): X=428.0,Y=715.5 (should be at cap-height 714?)

	* dcroat (U+0111): X=427.5,Y=715.5 (should be at cap-height 714?)

	* Gbreve (U+011E): X=477.5,Y=-1.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=477.5,Y=-1.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=477.5,Y=-1.5 (should be at baseline 0?)

	* hbar (U+0127): X=113.5,Y=715.5 (should be at cap-height 714?)

	* uni0137 (U+0137): X=114.0,Y=715.5 (should be at cap-height 714?)

	* lacute (U+013A): X=110.0,Y=715.5 (should be at cap-height 714?)

	* uni013C (U+013C): X=110.0,Y=715.5 (should be at cap-height 714?)

	* lcaron (U+013E): X=110.0,Y=715.5 (should be at cap-height 714?)

	* Eng (U+014A): X=566.0,Y=1.0 (should be at baseline 0?)

	* uni0547 (U+0547): X=220.5,Y=714.5 (should be at cap-height 714?)

	* uni055A (U+055A): X=90.5,Y=715.5 (should be at cap-height 714?)

	* uni055C (U+055C): X=135.0,Y=712.0 (should be at cap-height 714?)

	* uni055E (U+055E): X=193.0,Y=714.5 (should be at cap-height 714?)

	* uni055E (U+055E): X=210.0,Y=713.0 (should be at cap-height 714?)

	* uni0576 (U+0576): X=279.5,Y=-2.0 (should be at baseline 0?)

	* uni2019 (U+2019): X=90.5,Y=715.5 (should be at cap-height 714?)

	* Euro (U+20AC): X=406.0,Y=0.5 (should be at baseline 0?)

	* uniFB13 (U+FB13): X=807.5,Y=-2.0 (should be at baseline 0?)

	* uniFB16 (U+FB16): X=385.0,Y=712.0 (should be at cap-height 714?)

	* uniFB16 (U+FB16): X=619.0,Y=712.0 (should be at cap-height 714?)

	* uniFB16 (U+FB16): X=777.5,Y=-2.0 (should be at baseline 0?)

	* uniFB16 (U+FB16): X=413.0,Y=712.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<385.5,450.5>-<412.0,431.0>-<428.0,400.0>>/B<<428.0,400.0>-<403.0,480.0>-<371.5,537.5>> = 9.945547575071476

	* sterling (U+00A3): B<<192.0,89.0>-<173.0,58.0>-<145.0,40.0>>/L<<145.0,40.0>--<149.0,42.0>> = 6.170175095029526 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<123.0,167.0>--<120.0,714.0>>

	* exclam (U+0021): L<<149.0,714.0>--<148.0,167.0>>

	* exclamdown (U+00A1): L<<123.0,-177.0>--<124.0,370.0>>

	* exclamdown (U+00A1): L<<149.0,370.0>--<152.0,-177.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 9 | 98 | 1046 | 55 | 897 | 0 |
| 0% | 0% | 5% | 50% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
