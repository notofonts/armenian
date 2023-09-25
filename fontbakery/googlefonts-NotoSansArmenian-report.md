## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[14] NotoSansArmenian-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** fsSelection bit 7 needs to be enabled because the family on Google Fonts has it enabled. [code: bad-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, syriac, tai-le, tifinagh, old-permic, math, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: coptic, yi, kaithi, cham, sora-sompeng, kharoshthi, lisu, sundanese, kayah-li, syloti-nagri
 * U+25CC DOTTED CIRCLE: try adding one of: coptic, music, yi, sinhala, syloti-nagri, khudawadi, devanagari, wancho, old-permic, malayalam, modi, tagbanwa, pahawh-hmong, kayah-li, chakma, manichaean, sogdian, sharada, gujarati, meetei-mayek, tai-viet, lao, mandaic, hanifi-rohingya, balinese, telugu, takri, kaithi, nko, rejang, marchen, tamil, bengali, elbasan, myanmar, lepcha, duployan, psalter-pahlavi, tagalog, tai-le, grantha, tifinagh, thai, dogra, osage, hanunoo, limbu, soyombo, newa, sundanese, tirhuta, kannada, khojki, phags-pa, bhaiksuki, tibetan, masaram-gondi, mahajani, kharoshthi, ahom, gurmukhi, cham, syriac, gunjala-gondi, symbols, siddham, batak, miao, khmer, zanabazar-square, hebrew, mongolian, thaana, brahmi, bassa-vah, javanese, caucasian-albanian, math, buhid, new-tai-lue, adlam, oriya, mende-kikakui, buginese

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0533
	* uni0536
	* uni0539
	* uni053A
	* uni053D
	* uni053E
	* uni053F
	* uni0540
	* uni0541
	* uni0543
	* uni0546
	* uni0547
	* uni0549
	* uni054A
	* uni054E
	* uni0551
	* uni0554
	* uni0562
	* uni0565
	* uni0567
	* uni0568
	* uni0569
	* uni056A
	* uni056E
	* uni0571
	* uni0573
	* uni0579
	* uni0588
	* uni058F
	* uniFB13
	* uniFB14
	* uniFB15 and uniFB16
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
 FONT_FAMILY_NAME = 'Noto Sans Armenian Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 586 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 318:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=129.0,Y=0.5 (should be at baseline 0?)

	* six (U+0036): X=510.0,Y=716.0 (should be at cap-height 714?)

	* C (U+0043): X=490.5,Y=-0.5 (should be at baseline 0?)

	* C (U+0043): X=506.0,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=545.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=282.0,Y=-1.5 (should be at baseline 0?)

	* f (U+0066): X=143.0,Y=716.0 (should be at cap-height 714?)

	* g (U+0067): X=577.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=386.0,Y=1.0 (should be at baseline 0?)

	* r (U+0072): X=311.5,Y=534.5 (should be at x-height 536?)

	* t (U+0074): X=363.0,Y=-1.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=506.0,Y=712.0 (should be at cap-height 714?)

	* agrave (U+00E0): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=282.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=282.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=447.5,Y=715.5 (should be at cap-height 714?)

	* acircumflex (U+00E2): X=179.5,Y=716.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=282.0,Y=-1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aring (U+00E5): X=282.0,Y=-1.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=-1.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=444.5,Y=715.5 (should be at cap-height 714?)

	* ecircumflex (U+00EA): X=176.5,Y=716.0 (should be at cap-height 714?)

	* icircumflex (U+00EE): X=298.5,Y=715.5 (should be at cap-height 714?)

	* icircumflex (U+00EE): X=30.5,Y=716.0 (should be at cap-height 714?)

	* ocircumflex (U+00F4): X=454.5,Y=715.5 (should be at cap-height 714?)

	* ocircumflex (U+00F4): X=186.5,Y=716.0 (should be at cap-height 714?)

	* ucircumflex (U+00FB): X=470.5,Y=715.5 (should be at cap-height 714?)

	* ucircumflex (U+00FB): X=202.5,Y=716.0 (should be at cap-height 714?)

	* amacron (U+0101): X=282.0,Y=-1.5 (should be at baseline 0?)

	* abreve (U+0103): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=282.0,Y=-1.5 (should be at baseline 0?)

	* Cacute (U+0106): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Cacute (U+0106): X=506.0,Y=712.0 (should be at cap-height 714?)

	* Cdotaccent (U+010A): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=506.0,Y=712.0 (should be at cap-height 714?)

	* Ccaron (U+010C): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=506.0,Y=712.0 (should be at cap-height 714?)

	* Gbreve (U+011E): X=545.5,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=386.0,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=545.5,Y=2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=386.0,Y=1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=545.5,Y=2.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=577.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=386.0,Y=1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=363.0,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=590.5,Y=715.5 (should be at cap-height 714?)

	* wcircumflex (U+0175): X=322.5,Y=716.0 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=440.5,Y=715.5 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=172.5,Y=716.0 (should be at cap-height 714?)

	* uni021B (U+021B): X=363.0,Y=-1.0 (should be at baseline 0?)

	* circumflex (U+02C6): X=396.5,Y=715.5 (should be at cap-height 714?)

	* circumflex (U+02C6): X=128.5,Y=716.0 (should be at cap-height 714?)

	* uni0302 (U+0302): X=129.5,Y=715.5 (should be at cap-height 714?)

	* uni0302 (U+0302): X=-138.5,Y=716.0 (should be at cap-height 714?)

	* uni0312 (U+0312): X=-23.0,Y=713.0 (should be at cap-height 714?)

	* uni0312 (U+0312): X=113.0,Y=713.0 (should be at cap-height 714?)

	* uni0545 (U+0545): X=162.5,Y=-0.5 (should be at baseline 0?)

	* uni0549 (U+0549): X=569.0,Y=-1.0 (should be at baseline 0?)

	* uni054E (U+054E): X=481.0,Y=715.0 (should be at cap-height 714?)

	* uni054E (U+054E): X=672.0,Y=715.0 (should be at cap-height 714?)

	* uni055B (U+055B): X=233.5,Y=715.0 (should be at cap-height 714?)

	* uni055C (U+055C): X=275.0,Y=712.5 (should be at cap-height 714?)

	* uni055D (U+055D): X=97.5,Y=713.5 (should be at cap-height 714?)

	* uni056F (U+056F): X=395.0,Y=1.0 (should be at baseline 0?)

	* uni057E (U+057E): X=395.0,Y=1.0 (should be at baseline 0?)

	* uni0583 (U+0583): X=395.0,Y=1.0 (should be at baseline 0?)

	* uni0584 (U+0584): X=266.5,Y=1.5 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=401.0,Y=-1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=96.0,Y=713.0 (should be at cap-height 714?)

	* quoteleft (U+2018): X=232.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=481.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=345.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=232.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=96.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=315.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=482.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=66.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=233.0,Y=713.0 (should be at cap-height 714?)

	* uniFB16 (U+FB16): X=395.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wdieresis (U+1E84): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wdieresis (U+1E84): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wdieresis (U+1E84): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wgrave (U+1E80): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wgrave (U+1E80): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wgrave (U+1E80): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[17] NotoSansArmenian-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Noto Sans Armenian Bold | Noto Sans Armenian |
| Subfamily Name | Regular | Bold |
| Full Name | Noto Sans Armenian Bold | Noto Sans Armenian Bold |
| Poscript Name | NotoSansArmenian-Bold | NotoSansArmenian-Bold |
| Typographic Family Name | Noto Sans Armenian | N/A |
| Typographic Subfamily Name | Bold | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** fsSelection bit 7 needs to be enabled because the family on Google Fonts has it enabled. [code: bad-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, syriac, tai-le, tifinagh, old-permic, math, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: coptic, yi, kaithi, cham, sora-sompeng, kharoshthi, lisu, sundanese, kayah-li, syloti-nagri
 * U+25CC DOTTED CIRCLE: try adding one of: coptic, music, yi, sinhala, syloti-nagri, khudawadi, devanagari, wancho, old-permic, malayalam, modi, tagbanwa, pahawh-hmong, kayah-li, chakma, manichaean, sogdian, sharada, gujarati, meetei-mayek, tai-viet, lao, mandaic, hanifi-rohingya, balinese, telugu, takri, kaithi, nko, rejang, marchen, tamil, bengali, elbasan, myanmar, lepcha, duployan, psalter-pahlavi, tagalog, tai-le, grantha, tifinagh, thai, dogra, osage, hanunoo, limbu, soyombo, newa, sundanese, tirhuta, kannada, khojki, phags-pa, bhaiksuki, tibetan, masaram-gondi, mahajani, kharoshthi, ahom, gurmukhi, cham, syriac, gunjala-gondi, symbols, siddham, batak, miao, khmer, zanabazar-square, hebrew, mongolian, thaana, brahmi, bassa-vah, javanese, caucasian-albanian, math, buhid, new-tai-lue, adlam, oriya, mende-kikakui, buginese

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0533
	* uni0536
	* uni0539
	* uni053A
	* uni053D
	* uni053E
	* uni053F
	* uni0540
	* uni0541
	* uni0543
	* uni054E
	* uni0551
	* uni0554
	* uni0562
	* uni0565
	* uni0567
	* uni0568
	* uni0569
	* uni056A
	* uni056E
	* uni0571
	* uni0573
	* uni0579
	* uni0588
	* uni058F
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
 FONT_FAMILY_NAME = 'Noto Sans Armenian Bold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=236.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=343.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=440.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=545.0,Y=713.0 (should be at cap-height 714?)

	* six (U+0036): X=489.0,Y=715.0 (should be at cap-height 714?)

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=543.0,Y=712.0 (should be at cap-height 714?)

	* c (U+0063): X=394.5,Y=-0.5 (should be at baseline 0?)

	* e (U+0065): X=432.5,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=555.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=295.0,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=288.5,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=481.0,Y=536.5 (should be at x-height 536?)

	* m (U+006D): X=627.5,Y=537.0 (should be at x-height 536?)

	* n (U+006E): X=291.5,Y=537.0 (should be at x-height 536?)

	* sterling (U+00A3): X=444.5,Y=712.5 (should be at cap-height 714?)

	* Ccedilla (U+00C7): X=482.0,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=758.0,Y=-0.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=0.5 (should be at baseline 0?)

	* ccedilla (U+00E7): X=394.5,Y=-0.5 (should be at baseline 0?)

	* egrave (U+00E8): X=432.5,Y=-0.5 (should be at baseline 0?)

	* eacute (U+00E9): X=432.5,Y=-0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=432.5,Y=-0.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=432.5,Y=-0.5 (should be at baseline 0?)

	* abreve (U+0103): X=249.0,Y=713.5 (should be at cap-height 714?)

	* abreve (U+0103): X=348.5,Y=714.5 (should be at cap-height 714?)

	* Cacute (U+0106): X=482.0,Y=-1.0 (should be at baseline 0?)

	* cacute (U+0107): X=394.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=482.0,Y=-1.0 (should be at baseline 0?)

	* cdotaccent (U+010B): X=394.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=482.0,Y=-1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=394.5,Y=-0.5 (should be at baseline 0?)

	* emacron (U+0113): X=432.5,Y=-0.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=432.5,Y=-0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=432.5,Y=-0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=527.5,Y=1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=543.0,Y=712.0 (should be at cap-height 714?)

	* gbreve (U+011F): X=555.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=261.0,Y=713.5 (should be at cap-height 714?)

	* gbreve (U+011F): X=360.5,Y=714.5 (should be at cap-height 714?)

	* Gdotaccent (U+0120): X=527.5,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=543.0,Y=712.0 (should be at cap-height 714?)

	* gdotaccent (U+0121): X=555.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=527.5,Y=1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=543.0,Y=712.0 (should be at cap-height 714?)

	* uni0123 (U+0123): X=555.0,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=591.0,Y=2.0 (should be at baseline 0?)

	* oe (U+0153): X=816.5,Y=-0.5 (should be at baseline 0?)

	* ubreve (U+016D): X=276.0,Y=713.5 (should be at cap-height 714?)

	* ubreve (U+016D): X=375.5,Y=714.5 (should be at cap-height 714?)

	* breve (U+02D8): X=179.0,Y=713.5 (should be at cap-height 714?)

	* breve (U+02D8): X=278.5,Y=714.5 (should be at cap-height 714?)

	* uni0306 (U+0306): X=-50.0,Y=713.5 (should be at cap-height 714?)

	* uni0306 (U+0306): X=49.5,Y=714.5 (should be at cap-height 714?)

	* uni0549 (U+0549): X=555.0,Y=-1.0 (should be at baseline 0?)

	* uni054F (U+054F): X=418.5,Y=712.0 (should be at cap-height 714?)

	* uni055C (U+055C): X=249.0,Y=715.5 (should be at cap-height 714?)

	* uni055E (U+055E): X=80.5,Y=714.5 (should be at cap-height 714?)

	* uni055E (U+055E): X=394.0,Y=712.0 (should be at cap-height 714?)

	* uni056F (U+056F): X=416.0,Y=1.0 (should be at baseline 0?)

	* uni0570 (U+0570): X=213.5,Y=713.5 (should be at cap-height 714?)

	* uni057E (U+057E): X=416.0,Y=1.0 (should be at baseline 0?)

	* uni0583 (U+0583): X=416.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=371.5,Y=-1.0 (should be at baseline 0?)

	* uniFB16 (U+FB16): X=416.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wdieresis (U+1E84): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wgrave (U+1E80): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** fsSelection bit 7 needs to be enabled because the family on Google Fonts has it enabled. [code: bad-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, syriac, tai-le, tifinagh, old-permic, math, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: coptic, yi, kaithi, cham, sora-sompeng, kharoshthi, lisu, sundanese, kayah-li, syloti-nagri
 * U+25CC DOTTED CIRCLE: try adding one of: coptic, music, yi, sinhala, syloti-nagri, khudawadi, devanagari, wancho, old-permic, malayalam, modi, tagbanwa, pahawh-hmong, kayah-li, chakma, manichaean, sogdian, sharada, gujarati, meetei-mayek, tai-viet, lao, mandaic, hanifi-rohingya, balinese, telugu, takri, kaithi, nko, rejang, marchen, tamil, bengali, elbasan, myanmar, lepcha, duployan, psalter-pahlavi, tagalog, tai-le, grantha, tifinagh, thai, dogra, osage, hanunoo, limbu, soyombo, newa, sundanese, tirhuta, kannada, khojki, phags-pa, bhaiksuki, tibetan, masaram-gondi, mahajani, kharoshthi, ahom, gurmukhi, cham, syriac, gunjala-gondi, symbols, siddham, batak, miao, khmer, zanabazar-square, hebrew, mongolian, thaana, brahmi, bassa-vah, javanese, caucasian-albanian, math, buhid, new-tai-lue, adlam, oriya, mende-kikakui, buginese

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0533
	* uni0536
	* uni0539
	* uni053A
	* uni053D
	* uni053E
	* uni053F
	* uni0540
	* uni0541
	* uni0543
	* uni0546
	* uni0549
	* uni054A
	* uni054E
	* uni0551
	* uni0554
	* uni0562
	* uni0565
	* uni0567
	* uni0568
	* uni0569
	* uni056A
	* uni056E
	* uni0571
	* uni0573
	* uni0579
	* uni0588
	* uni058F
	* uniFB13
	* uniFB14
	* uniFB15 and uniFB16
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
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 578 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 320:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni053B (U+053B): L<<241.0,414.0>--<249.0,414.0>> -> L<<249.0,414.0>--<249.0,414.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,209.5>-<333.0,177.0>-<335.0,156.0>>/B<<335.0,156.0>-<338.0,177.0>-<344.5,209.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wgrave (U+1E80): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** fsSelection bit 7 needs to be enabled because the family on Google Fonts has it enabled. [code: bad-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, syriac, tai-le, tifinagh, old-permic, math, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: coptic, yi, kaithi, cham, sora-sompeng, kharoshthi, lisu, sundanese, kayah-li, syloti-nagri
 * U+25CC DOTTED CIRCLE: try adding one of: coptic, music, yi, sinhala, syloti-nagri, khudawadi, devanagari, wancho, old-permic, malayalam, modi, tagbanwa, pahawh-hmong, kayah-li, chakma, manichaean, sogdian, sharada, gujarati, meetei-mayek, tai-viet, lao, mandaic, hanifi-rohingya, balinese, telugu, takri, kaithi, nko, rejang, marchen, tamil, bengali, elbasan, myanmar, lepcha, duployan, psalter-pahlavi, tagalog, tai-le, grantha, tifinagh, thai, dogra, osage, hanunoo, limbu, soyombo, newa, sundanese, tirhuta, kannada, khojki, phags-pa, bhaiksuki, tibetan, masaram-gondi, mahajani, kharoshthi, ahom, gurmukhi, cham, syriac, gunjala-gondi, symbols, siddham, batak, miao, khmer, zanabazar-square, hebrew, mongolian, thaana, brahmi, bassa-vah, javanese, caucasian-albanian, math, buhid, new-tai-lue, adlam, oriya, mende-kikakui, buginese

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
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0571 (U+0571): L<<426.0,0.0>--<426.0,0.0>> -> L<<426.0,0.0>--<426.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** fsSelection bit 7 needs to be enabled because the family on Google Fonts has it enabled. [code: bad-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, syriac, tai-le, tifinagh, old-permic, math, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: coptic, yi, kaithi, cham, sora-sompeng, kharoshthi, lisu, sundanese, kayah-li, syloti-nagri
 * U+25CC DOTTED CIRCLE: try adding one of: coptic, music, yi, sinhala, syloti-nagri, khudawadi, devanagari, wancho, old-permic, malayalam, modi, tagbanwa, pahawh-hmong, kayah-li, chakma, manichaean, sogdian, sharada, gujarati, meetei-mayek, tai-viet, lao, mandaic, hanifi-rohingya, balinese, telugu, takri, kaithi, nko, rejang, marchen, tamil, bengali, elbasan, myanmar, lepcha, duployan, psalter-pahlavi, tagalog, tai-le, grantha, tifinagh, thai, dogra, osage, hanunoo, limbu, soyombo, newa, sundanese, tirhuta, kannada, khojki, phags-pa, bhaiksuki, tibetan, masaram-gondi, mahajani, kharoshthi, ahom, gurmukhi, cham, syriac, gunjala-gondi, symbols, siddham, batak, miao, khmer, zanabazar-square, hebrew, mongolian, thaana, brahmi, bassa-vah, javanese, caucasian-albanian, math, buhid, new-tai-lue, adlam, oriya, mende-kikakui, buginese

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
 FONT_FAMILY_NAME = 'Noto Sans Armenian Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 571 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0543 (U+0543): L<<260.0,558.0>--<260.0,558.0>>/L<<260.0,558.0>--<70.0,590.0>> = 9.560096480886276 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** fsSelection bit 7 needs to be enabled because the family on Google Fonts has it enabled. [code: bad-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, syriac, tai-le, tifinagh, old-permic, math, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: coptic, yi, kaithi, cham, sora-sompeng, kharoshthi, lisu, sundanese, kayah-li, syloti-nagri
 * U+25CC DOTTED CIRCLE: try adding one of: coptic, music, yi, sinhala, syloti-nagri, khudawadi, devanagari, wancho, old-permic, malayalam, modi, tagbanwa, pahawh-hmong, kayah-li, chakma, manichaean, sogdian, sharada, gujarati, meetei-mayek, tai-viet, lao, mandaic, hanifi-rohingya, balinese, telugu, takri, kaithi, nko, rejang, marchen, tamil, bengali, elbasan, myanmar, lepcha, duployan, psalter-pahlavi, tagalog, tai-le, grantha, tifinagh, thai, dogra, osage, hanunoo, limbu, soyombo, newa, sundanese, tirhuta, kannada, khojki, phags-pa, bhaiksuki, tibetan, masaram-gondi, mahajani, kharoshthi, ahom, gurmukhi, cham, syriac, gunjala-gondi, symbols, siddham, batak, miao, khmer, zanabazar-square, hebrew, mongolian, thaana, brahmi, bassa-vah, javanese, caucasian-albanian, math, buhid, new-tai-lue, adlam, oriya, mende-kikakui, buginese

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0533
	* uni0536
	* uni053A
	* uni053D
	* uni053E
	* uni053F
	* uni0540
	* uni0541
	* uni0543
	* uni054E
	* uni0551
	* uni0554
	* uni0567
	* uni0569
	* uni056A
	* uni056E
	* uni0571
	* uni0573
	* uni0588
	* uni058F
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
 FONT_FAMILY_NAME = 'Noto Sans Armenian Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=136.0,Y=-1.0 (should be at baseline 0?)

	* six (U+0036): X=476.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=96.0,Y=-1.0 (should be at baseline 0?)

	* at (U+0040): X=552.5,Y=-0.5 (should be at baseline 0?)

	* C (U+0043): X=506.5,Y=712.5 (should be at cap-height 714?)

	* G (U+0047): X=534.5,Y=-0.5 (should be at baseline 0?)

	* G (U+0047): X=544.0,Y=712.5 (should be at cap-height 714?)

	* S (U+0053): X=137.5,Y=-0.5 (should be at baseline 0?)

	* S (U+0053): X=397.5,Y=712.5 (should be at cap-height 714?)

	* a (U+0061): X=188.5,Y=535.5 (should be at x-height 536?)

	* c (U+0063): X=383.0,Y=-2.0 (should be at baseline 0?)

	* e (U+0065): X=415.0,Y=-1.0 (should be at baseline 0?)

	* s (U+0073): X=124.5,Y=-1.5 (should be at baseline 0?)

	* w (U+0077): X=278.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=160.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=645.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=524.0,Y=1.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=111.0,Y=712.5 (should be at cap-height 714?)

	* Ccedilla (U+00C7): X=506.5,Y=712.5 (should be at cap-height 714?)

	* germandbls (U+00DF): X=332.0,Y=-1.5 (should be at baseline 0?)

	* aring (U+00E5): X=173.0,Y=715.0 (should be at cap-height 714?)

	* aring (U+00E5): X=400.0,Y=716.0 (should be at cap-height 714?)

	* aring (U+00E5): X=339.0,Y=715.0 (should be at cap-height 714?)

	* aring (U+00E5): X=232.0,Y=715.0 (should be at cap-height 714?)

	* ae (U+00E6): X=724.5,Y=-1.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=383.0,Y=-2.0 (should be at baseline 0?)

	* egrave (U+00E8): X=415.0,Y=-1.0 (should be at baseline 0?)

	* eacute (U+00E9): X=415.0,Y=-1.0 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=415.0,Y=-1.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=415.0,Y=-1.0 (should be at baseline 0?)

	* Cacute (U+0106): X=506.5,Y=712.5 (should be at cap-height 714?)

	* cacute (U+0107): X=383.0,Y=-2.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=506.5,Y=712.5 (should be at cap-height 714?)

	* cdotaccent (U+010B): X=383.0,Y=-2.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=506.5,Y=712.5 (should be at cap-height 714?)

	* ccaron (U+010D): X=383.0,Y=-2.0 (should be at baseline 0?)

	* emacron (U+0113): X=415.0,Y=-1.0 (should be at baseline 0?)

	* edotaccent (U+0117): X=415.0,Y=-1.0 (should be at baseline 0?)

	* ecaron (U+011B): X=415.0,Y=-1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=534.5,Y=-0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=544.0,Y=712.5 (should be at cap-height 714?)

	* Gdotaccent (U+0120): X=534.5,Y=-0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=544.0,Y=712.5 (should be at cap-height 714?)

	* uni0122 (U+0122): X=534.5,Y=-0.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=544.0,Y=712.5 (should be at cap-height 714?)

	* Eng (U+014A): X=583.0,Y=1.0 (should be at baseline 0?)

	* oe (U+0153): X=798.5,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=137.5,Y=-0.5 (should be at baseline 0?)

	* Sacute (U+015A): X=397.5,Y=712.5 (should be at cap-height 714?)

	* sacute (U+015B): X=124.5,Y=-1.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=137.5,Y=-0.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=397.5,Y=712.5 (should be at cap-height 714?)

	* scedilla (U+015F): X=124.5,Y=-1.5 (should be at baseline 0?)

	* Scaron (U+0160): X=137.5,Y=-0.5 (should be at baseline 0?)

	* Scaron (U+0160): X=397.5,Y=712.5 (should be at cap-height 714?)

	* scaron (U+0161): X=124.5,Y=-1.5 (should be at baseline 0?)

	* uring (U+016F): X=201.0,Y=715.0 (should be at cap-height 714?)

	* uring (U+016F): X=428.0,Y=716.0 (should be at cap-height 714?)

	* uring (U+016F): X=367.0,Y=715.0 (should be at cap-height 714?)

	* uring (U+016F): X=260.0,Y=715.0 (should be at cap-height 714?)

	* wcircumflex (U+0175): X=278.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=160.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=645.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=524.0,Y=1.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=137.5,Y=-0.5 (should be at baseline 0?)

	* uni0218 (U+0218): X=397.5,Y=712.5 (should be at cap-height 714?)

	* uni0219 (U+0219): X=124.5,Y=-1.5 (should be at baseline 0?)

	* ring (U+02DA): X=40.0,Y=715.0 (should be at cap-height 714?)

	* ring (U+02DA): X=267.0,Y=716.0 (should be at cap-height 714?)

	* ring (U+02DA): X=206.0,Y=715.0 (should be at cap-height 714?)

	* ring (U+02DA): X=99.0,Y=715.0 (should be at cap-height 714?)

	* uni030A (U+030A): X=-111.0,Y=715.0 (should be at cap-height 714?)

	* uni030A (U+030A): X=116.0,Y=716.0 (should be at cap-height 714?)

	* uni030A (U+030A): X=55.0,Y=715.0 (should be at cap-height 714?)

	* uni030A (U+030A): X=-52.0,Y=715.0 (should be at cap-height 714?)

	* uni0545 (U+0545): X=181.5,Y=0.5 (should be at baseline 0?)

	* uni0549 (U+0549): X=542.0,Y=-1.0 (should be at baseline 0?)

	* uni056F (U+056F): X=419.0,Y=1.0 (should be at baseline 0?)

	* uni0570 (U+0570): X=206.0,Y=713.5 (should be at cap-height 714?)

	* uni0573 (U+0573): X=540.0,Y=716.0 (should be at cap-height 714?)

	* uni057E (U+057E): X=419.0,Y=1.0 (should be at baseline 0?)

	* uni0583 (U+0583): X=419.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=278.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=160.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=645.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=524.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=278.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=160.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=645.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=524.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=278.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=160.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=645.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=524.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=339.0,Y=-1.5 (should be at baseline 0?)

	* Euro (U+20AC): X=470.0,Y=-1.5 (should be at baseline 0?)

	* uniFB16 (U+FB16): X=419.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0571 (U+0571): L<<441.0,0.0>--<441.0,0.0>> -> L<<441.0,0.0>--<441.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansArmenian-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** fsSelection bit 7 needs to be enabled because the family on Google Fonts has it enabled. [code: bad-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, syriac, tai-le, tifinagh, old-permic, math, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: coptic, yi, kaithi, cham, sora-sompeng, kharoshthi, lisu, sundanese, kayah-li, syloti-nagri
 * U+25CC DOTTED CIRCLE: try adding one of: coptic, music, yi, sinhala, syloti-nagri, khudawadi, devanagari, wancho, old-permic, malayalam, modi, tagbanwa, pahawh-hmong, kayah-li, chakma, manichaean, sogdian, sharada, gujarati, meetei-mayek, tai-viet, lao, mandaic, hanifi-rohingya, balinese, telugu, takri, kaithi, nko, rejang, marchen, tamil, bengali, elbasan, myanmar, lepcha, duployan, psalter-pahlavi, tagalog, tai-le, grantha, tifinagh, thai, dogra, osage, hanunoo, limbu, soyombo, newa, sundanese, tirhuta, kannada, khojki, phags-pa, bhaiksuki, tibetan, masaram-gondi, mahajani, kharoshthi, ahom, gurmukhi, cham, syriac, gunjala-gondi, symbols, siddham, batak, miao, khmer, zanabazar-square, hebrew, mongolian, thaana, brahmi, bassa-vah, javanese, caucasian-albanian, math, buhid, new-tai-lue, adlam, oriya, mende-kikakui, buginese

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0536
	* uni053D
	* uni053E
	* uni0541
	* uni0543
	* uni054E
	* uni0567
	* uni056E
	* uni0571
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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** fsSelection bit 7 needs to be enabled because the family on Google Fonts has it enabled. [code: bad-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, syriac, tai-le, tifinagh, old-permic, math, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: coptic, yi, kaithi, cham, sora-sompeng, kharoshthi, lisu, sundanese, kayah-li, syloti-nagri
 * U+25CC DOTTED CIRCLE: try adding one of: coptic, music, yi, sinhala, syloti-nagri, khudawadi, devanagari, wancho, old-permic, malayalam, modi, tagbanwa, pahawh-hmong, kayah-li, chakma, manichaean, sogdian, sharada, gujarati, meetei-mayek, tai-viet, lao, mandaic, hanifi-rohingya, balinese, telugu, takri, kaithi, nko, rejang, marchen, tamil, bengali, elbasan, myanmar, lepcha, duployan, psalter-pahlavi, tagalog, tai-le, grantha, tifinagh, thai, dogra, osage, hanunoo, limbu, soyombo, newa, sundanese, tirhuta, kannada, khojki, phags-pa, bhaiksuki, tibetan, masaram-gondi, mahajani, kharoshthi, ahom, gurmukhi, cham, syriac, gunjala-gondi, symbols, siddham, batak, miao, khmer, zanabazar-square, hebrew, mongolian, thaana, brahmi, bassa-vah, javanese, caucasian-albanian, math, buhid, new-tai-lue, adlam, oriya, mende-kikakui, buginese

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0533
	* uni0536
	* uni0539
	* uni053A
	* uni053D
	* uni053E
	* uni053F
	* uni0540
	* uni0541
	* uni0543
	* uni054E
	* uni0551
	* uni0554
	* uni0567
	* uni0569
	* uni056A
	* uni056E
	* uni0571
	* uni0573
	* uni0588
	* uni058F
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
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=241.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=334.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=449.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=540.0,Y=713.0 (should be at cap-height 714?)

	* three (U+0033): X=135.0,Y=-0.5 (should be at baseline 0?)

	* four (U+0034): X=340.0,Y=716.0 (should be at cap-height 714?)

	* four (U+0034): X=461.0,Y=716.0 (should be at cap-height 714?)

	* six (U+0036): X=482.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=90.0,Y=-2.0 (should be at baseline 0?)

	* C (U+0043): X=485.5,Y=-2.0 (should be at baseline 0?)

	* G (U+0047): X=531.0,Y=0.5 (should be at baseline 0?)

	* G (U+0047): X=543.5,Y=712.0 (should be at cap-height 714?)

	* S (U+0053): X=399.5,Y=712.0 (should be at cap-height 714?)

	* c (U+0063): X=388.5,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=423.0,Y=-1.0 (should be at baseline 0?)

	* s (U+0073): X=126.5,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=217.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=440.0,Y=712.0 (should be at cap-height 714?)

	* section (U+00A7): X=129.0,Y=1.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=485.5,Y=-2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=490.0,Y=715.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=139.0,Y=712.0 (should be at cap-height 714?)

	* ae (U+00E6): X=740.0,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=308.5,Y=2.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=388.5,Y=-1.0 (should be at baseline 0?)

	* egrave (U+00E8): X=423.0,Y=-1.0 (should be at baseline 0?)

	* eacute (U+00E9): X=423.0,Y=-1.0 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=423.0,Y=-1.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=423.0,Y=-1.0 (should be at baseline 0?)

	* ntilde (U+00F1): X=167.0,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=153.0,Y=712.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=217.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=217.0,Y=2.0 (should be at baseline 0?)

	* Cacute (U+0106): X=485.5,Y=-2.0 (should be at baseline 0?)

	* cacute (U+0107): X=388.5,Y=-1.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=485.5,Y=-2.0 (should be at baseline 0?)

	* cdotaccent (U+010B): X=388.5,Y=-1.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=485.5,Y=-2.0 (should be at baseline 0?)

	* ccaron (U+010D): X=388.5,Y=-1.0 (should be at baseline 0?)

	* emacron (U+0113): X=423.0,Y=-1.0 (should be at baseline 0?)

	* edotaccent (U+0117): X=423.0,Y=-1.0 (should be at baseline 0?)

	* ecaron (U+011B): X=423.0,Y=-1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=531.0,Y=0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=543.5,Y=712.0 (should be at cap-height 714?)

	* Gdotaccent (U+0120): X=531.0,Y=0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=543.5,Y=712.0 (should be at cap-height 714?)

	* uni0122 (U+0122): X=531.0,Y=0.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=543.5,Y=712.0 (should be at cap-height 714?)

	* Eng (U+014A): X=586.0,Y=1.0 (should be at baseline 0?)

	* Eng (U+014A): X=700.0,Y=2.0 (should be at baseline 0?)

	* oe (U+0153): X=807.0,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=399.5,Y=712.0 (should be at cap-height 714?)

	* sacute (U+015B): X=126.5,Y=-2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=399.5,Y=712.0 (should be at cap-height 714?)

	* scedilla (U+015F): X=126.5,Y=-2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=399.5,Y=712.0 (should be at cap-height 714?)

	* scaron (U+0161): X=126.5,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=217.0,Y=2.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=399.5,Y=712.0 (should be at cap-height 714?)

	* uni0219 (U+0219): X=126.5,Y=-2.0 (should be at baseline 0?)

	* tilde (U+02DC): X=80.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-467.0,Y=712.0 (should be at cap-height 714?)

	* uni0545 (U+0545): X=178.0,Y=0.5 (should be at baseline 0?)

	* uni0549 (U+0549): X=548.0,Y=-1.0 (should be at baseline 0?)

	* uni055C (U+055C): X=238.5,Y=716.0 (should be at cap-height 714?)

	* uni055E (U+055E): X=300.0,Y=715.0 (should be at cap-height 714?)

	* uni055E (U+055E): X=181.0,Y=713.5 (should be at cap-height 714?)

	* uni056F (U+056F): X=418.0,Y=1.0 (should be at baseline 0?)

	* uni0573 (U+0573): X=554.0,Y=713.0 (should be at cap-height 714?)

	* uni057E (U+057E): X=418.0,Y=1.0 (should be at baseline 0?)

	* uni0583 (U+0583): X=418.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=354.5,Y=-1.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=217.0,Y=2.0 (should be at baseline 0?)

	* Euro (U+20AC): X=471.5,Y=-2.0 (should be at baseline 0?)

	* uniFB16 (U+FB16): X=418.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** fsSelection bit 7 needs to be enabled because the family on Google Fonts has it enabled. [code: bad-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, syriac, tai-le, tifinagh, old-permic, math, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: coptic, yi, kaithi, cham, sora-sompeng, kharoshthi, lisu, sundanese, kayah-li, syloti-nagri
 * U+25CC DOTTED CIRCLE: try adding one of: coptic, music, yi, sinhala, syloti-nagri, khudawadi, devanagari, wancho, old-permic, malayalam, modi, tagbanwa, pahawh-hmong, kayah-li, chakma, manichaean, sogdian, sharada, gujarati, meetei-mayek, tai-viet, lao, mandaic, hanifi-rohingya, balinese, telugu, takri, kaithi, nko, rejang, marchen, tamil, bengali, elbasan, myanmar, lepcha, duployan, psalter-pahlavi, tagalog, tai-le, grantha, tifinagh, thai, dogra, osage, hanunoo, limbu, soyombo, newa, sundanese, tirhuta, kannada, khojki, phags-pa, bhaiksuki, tibetan, masaram-gondi, mahajani, kharoshthi, ahom, gurmukhi, cham, syriac, gunjala-gondi, symbols, siddham, batak, miao, khmer, zanabazar-square, hebrew, mongolian, thaana, brahmi, bassa-vah, javanese, caucasian-albanian, math, buhid, new-tai-lue, adlam, oriya, mende-kikakui, buginese

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
 FONT_FAMILY_NAME = 'Noto Sans Armenian Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>>

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 30 | 92 | 1046 | 55 | 882 | 0 |
| 0% | 1% | 4% | 50% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
