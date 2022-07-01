## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[3] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf', 'fonts/NotoSansArmenian/googlefonts/ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSansArmenian[wght].ttf' must be renamed to 'NotoSansArmenian[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Check variable font instances have correct names (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/varfont_instance_names">com.google.fonts/check/varfont_instance_names</a>)</summary><div>


* 🔥 **FAIL** Following instances are not supported: 
	- Condensed ExtraLight
	- Condensed Light
	- Condensed
	- Condensed Medium
	- Condensed SemiBold
	- Condensed Bold
	- SemiCondensed ExtraLight
	- SemiCondensed Light
	- SemiCondensed
	- SemiCondensed Medium
	- SemiCondensed SemiBold
	- SemiCondensed Bold
	- ExtraCondensed ExtraLight
	- ExtraCondensed Light
	- ExtraCondensed
	- ExtraCondensed Medium
	- ExtraCondensed SemiBold
	- ExtraCondensed Bold

Further info can be found in our spec https://github.com/googlefonts/gf-docs/tree/main/Spec#fvar-instances [code: bad-instance-names]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 261. [code: invalid-default-instance-subfamily-nameid:261]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its postScriptNameID should be 6, instead of 297. [code: invalid-default-instance-postscript-nameid:297]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni053E
	* uniFB16
	* uni0536
	* uni0562
	* uni058F
	* uni054E
	* uni0547
	* uniFB13
	* uni0569
	* uni0568 and 23 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 77 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
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

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni053E
	* uniFB16
	* uni0536
	* uni0562
	* uni058F
	* uni054E
	* uni0569
	* uni0568
	* uni0565
	* uni0551 and 17 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
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

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-Condensed.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Condensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni056E (U+056E): L<<146.0,661.0>--<151.0,665.0>> -> L<<151.0,665.0>--<272.0,769.0>> 

	* And uniFB13 (U+FB13): L<<366.0,760.0>--<571.0,760.0>> -> L<<571.0,760.0>--<571.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<206.0,179.5>-<214.0,134.0>-<217.0,100.0>>/B<<217.0,100.0>-<223.0,142.0>-<231.5,188.5>> = 13.172553423326871

	* W (U+0057): B<<401.5,521.5>-<395.0,559.0>-<390.0,599.0>>/B<<390.0,599.0>-<387.0,573.0>-<381.0,534.5>> = 13.70696100407981

	* W (U+0057): B<<550.0,191.0>-<558.0,147.0>-<564.0,100.0>>/B<<564.0,100.0>-<569.0,145.0>-<577.0,190.5>> = 13.615196703799155

	* Wacute (U+1E82): B<<206.0,179.5>-<214.0,134.0>-<217.0,100.0>>/B<<217.0,100.0>-<223.0,142.0>-<231.5,188.5>> = 13.172553423326871

	* Wacute (U+1E82): B<<401.5,521.5>-<395.0,559.0>-<390.0,599.0>>/B<<390.0,599.0>-<387.0,573.0>-<381.0,534.5>> = 13.70696100407981

	* Wacute (U+1E82): B<<550.0,191.0>-<558.0,147.0>-<564.0,100.0>>/B<<564.0,100.0>-<569.0,145.0>-<577.0,190.5>> = 13.615196703799155

	* Wcircumflex (U+0174): B<<206.0,179.5>-<214.0,134.0>-<217.0,100.0>>/B<<217.0,100.0>-<223.0,142.0>-<231.5,188.5>> = 13.172553423326871

	* Wcircumflex (U+0174): B<<401.5,521.5>-<395.0,559.0>-<390.0,599.0>>/B<<390.0,599.0>-<387.0,573.0>-<381.0,534.5>> = 13.70696100407981

	* Wcircumflex (U+0174): B<<550.0,191.0>-<558.0,147.0>-<564.0,100.0>>/B<<564.0,100.0>-<569.0,145.0>-<577.0,190.5>> = 13.615196703799155

	* Wdieresis (U+1E84): B<<206.0,179.5>-<214.0,134.0>-<217.0,100.0>>/B<<217.0,100.0>-<223.0,142.0>-<231.5,188.5>> = 13.172553423326871 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-CondensedBlack.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Condensed Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=121.0,Y=-1.5 (should be at baseline 0?)

	* six (U+0036): X=454.0,Y=716.0 (should be at cap-height 714?)

	* nine (U+0039): X=69.0,Y=-2.0 (should be at baseline 0?)

	* A (U+0041): X=192.0,Y=715.0 (should be at cap-height 714?)

	* A (U+0041): X=426.0,Y=715.0 (should be at cap-height 714?)

	* C (U+0043): X=429.0,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=465.5,Y=1.0 (should be at baseline 0?)

	* asciicircum (U+005E): X=222.0,Y=715.0 (should be at cap-height 714?)

	* asciicircum (U+005E): X=305.0,Y=715.0 (should be at cap-height 714?)

	* t (U+0074): X=304.5,Y=-2.0 (should be at baseline 0?) 

	* And 48 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0531 (U+0531): L<<569.0,714.0>--<569.0,245.0>> -> L<<569.0,245.0>--<569.0,242.0>>

	* uni053B (U+053B): L<<233.0,421.0>--<239.0,421.0>> -> L<<239.0,421.0>--<239.0,421.0>> 

	* And uni0571 (U+0571): L<<404.0,0.0>--<404.0,0.0>> -> L<<404.0,0.0>--<404.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<292.5,236.0>-<298.0,203.0>-<299.0,182.0>>/B<<299.0,182.0>-<302.0,203.0>-<307.0,236.0>> = 10.8564133480622

	* W (U+0057): B<<256.0,258.0>-<261.0,220.0>-<265.0,189.0>>/B<<265.0,189.0>-<269.0,227.0>-<276.0,269.5>> = 13.361385317386862

	* W (U+0057): B<<452.0,370.5>-<444.0,424.0>-<440.0,469.0>>/B<<440.0,469.0>-<438.0,443.0>-<433.0,408.0>> = 9.478313215010054

	* W (U+0057): B<<599.5,266.0>-<606.0,224.0>-<610.0,189.0>>/B<<610.0,189.0>-<612.0,216.0>-<617.0,251.0>> = 10.756196550715789

	* Wacute (U+1E82): B<<256.0,258.0>-<261.0,220.0>-<265.0,189.0>>/B<<265.0,189.0>-<269.0,227.0>-<276.0,269.5>> = 13.361385317386862

	* Wacute (U+1E82): B<<452.0,370.5>-<444.0,424.0>-<440.0,469.0>>/B<<440.0,469.0>-<438.0,443.0>-<433.0,408.0>> = 9.478313215010054

	* Wacute (U+1E82): B<<599.5,266.0>-<606.0,224.0>-<610.0,189.0>>/B<<610.0,189.0>-<612.0,216.0>-<617.0,251.0>> = 10.756196550715789

	* Wcircumflex (U+0174): B<<256.0,258.0>-<261.0,220.0>-<265.0,189.0>>/B<<265.0,189.0>-<269.0,227.0>-<276.0,269.5>> = 13.361385317386862

	* Wcircumflex (U+0174): B<<452.0,370.5>-<444.0,424.0>-<440.0,469.0>>/B<<440.0,469.0>-<438.0,443.0>-<433.0,408.0>> = 9.478313215010054

	* Wcircumflex (U+0174): B<<599.5,266.0>-<606.0,224.0>-<610.0,189.0>>/B<<610.0,189.0>-<612.0,216.0>-<617.0,251.0>> = 10.756196550715789 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-CondensedBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Condensed' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=119.5,Y=-2.0 (should be at baseline 0?)

	* four (U+0034): X=275.0,Y=715.0 (should be at cap-height 714?)

	* four (U+0034): X=410.0,Y=715.0 (should be at cap-height 714?)

	* six (U+0036): X=427.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=72.0,Y=-1.0 (should be at baseline 0?)

	* A (U+0041): X=197.0,Y=715.0 (should be at cap-height 714?)

	* A (U+0041): X=376.0,Y=715.0 (should be at cap-height 714?)

	* G (U+0047): X=451.5,Y=0.5 (should be at baseline 0?)

	* S (U+0053): X=121.5,Y=-0.5 (should be at baseline 0?)

	* S (U+0053): X=348.5,Y=712.0 (should be at cap-height 714?) 

	* And 84 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0579 (U+0579): L<<237.0,344.0>--<292.0,310.0>> -> L<<292.0,310.0>--<294.0,309.0>>

	* uni0588 (U+0588): L<<98.0,176.0>--<98.0,182.0>> -> L<<98.0,182.0>--<98.0,501.0>> 

	* And uniFB13 (U+FB13): L<<782.0,556.0>--<782.0,555.0>> -> L<<782.0,555.0>--<782.0,541.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<268.5,195.5>-<274.0,165.0>-<277.0,143.0>>/B<<277.0,143.0>-<279.0,165.0>-<284.5,195.0>> = 12.959594926160113

	* W (U+0057): B<<233.0,214.5>-<238.0,180.0>-<241.0,152.0>>/B<<241.0,152.0>-<245.0,183.0>-<250.5,218.0>> = 13.46788292617776

	* W (U+0057): B<<428.0,430.5>-<420.0,479.0>-<416.0,522.0>>/B<<416.0,522.0>-<413.0,500.0>-<409.0,468.5>> = 13.07971168837008

	* W (U+0057): B<<579.0,217.5>-<584.0,183.0>-<588.0,152.0>>/B<<588.0,152.0>-<592.0,194.0>-<600.5,248.0>> = 12.79271139089786

	* Wacute (U+1E82): B<<233.0,214.5>-<238.0,180.0>-<241.0,152.0>>/B<<241.0,152.0>-<245.0,183.0>-<250.5,218.0>> = 13.46788292617776

	* Wacute (U+1E82): B<<428.0,430.5>-<420.0,479.0>-<416.0,522.0>>/B<<416.0,522.0>-<413.0,500.0>-<409.0,468.5>> = 13.07971168837008

	* Wacute (U+1E82): B<<579.0,217.5>-<584.0,183.0>-<588.0,152.0>>/B<<588.0,152.0>-<592.0,194.0>-<600.5,248.0>> = 12.79271139089786

	* Wcircumflex (U+0174): B<<233.0,214.5>-<238.0,180.0>-<241.0,152.0>>/B<<241.0,152.0>-<245.0,183.0>-<250.5,218.0>> = 13.46788292617776

	* Wcircumflex (U+0174): B<<428.0,430.5>-<420.0,479.0>-<416.0,522.0>>/B<<416.0,522.0>-<413.0,500.0>-<409.0,468.5>> = 13.07971168837008

	* Wcircumflex (U+0174): B<<579.0,217.5>-<584.0,183.0>-<588.0,152.0>>/B<<588.0,152.0>-<592.0,194.0>-<600.5,248.0>> = 12.79271139089786 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-CondensedExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Condensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=120.0,Y=-2.0 (should be at baseline 0?)

	* four (U+0034): X=273.0,Y=715.0 (should be at cap-height 714?)

	* four (U+0034): X=422.0,Y=715.0 (should be at cap-height 714?)

	* six (U+0036): X=439.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=70.0,Y=-2.0 (should be at baseline 0?)

	* A (U+0041): X=194.0,Y=715.0 (should be at cap-height 714?)

	* A (U+0041): X=399.0,Y=715.0 (should be at cap-height 714?)

	* G (U+0047): X=458.0,Y=0.5 (should be at baseline 0?)

	* S (U+0053): X=122.5,Y=-0.5 (should be at baseline 0?)

	* asciicircum (U+005E): X=222.0,Y=715.0 (should be at cap-height 714?) 

	* And 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0571 (U+0571): L<<395.0,0.0>--<395.0,0.0>> -> L<<395.0,0.0>--<395.0,0.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<279.5,214.0>-<285.0,182.0>-<287.0,161.0>>/B<<287.0,161.0>-<290.0,182.0>-<295.5,213.5>> = 13.570434385161475

	* W (U+0057): B<<244.0,235.0>-<249.0,199.0>-<252.0,169.0>>/B<<252.0,169.0>-<256.0,203.0>-<262.0,242.0>> = 12.420429945256531

	* W (U+0057): B<<439.0,402.5>-<431.0,453.0>-<427.0,498.0>>/B<<427.0,498.0>-<425.0,473.0>-<420.5,440.5>> = 9.653529119915403

	* W (U+0057): B<<588.5,240.0>-<594.0,202.0>-<598.0,169.0>>/B<<598.0,169.0>-<600.0,197.0>-<605.0,231.5>> = 10.996843898999522

	* Wacute (U+1E82): B<<244.0,235.0>-<249.0,199.0>-<252.0,169.0>>/B<<252.0,169.0>-<256.0,203.0>-<262.0,242.0>> = 12.420429945256531

	* Wacute (U+1E82): B<<439.0,402.5>-<431.0,453.0>-<427.0,498.0>>/B<<427.0,498.0>-<425.0,473.0>-<420.5,440.5>> = 9.653529119915403

	* Wacute (U+1E82): B<<588.5,240.0>-<594.0,202.0>-<598.0,169.0>>/B<<598.0,169.0>-<600.0,197.0>-<605.0,231.5>> = 10.996843898999522

	* Wcircumflex (U+0174): B<<244.0,235.0>-<249.0,199.0>-<252.0,169.0>>/B<<252.0,169.0>-<256.0,203.0>-<262.0,242.0>> = 12.420429945256531

	* Wcircumflex (U+0174): B<<439.0,402.5>-<431.0,453.0>-<427.0,498.0>>/B<<427.0,498.0>-<425.0,473.0>-<420.5,440.5>> = 9.653529119915403

	* Wcircumflex (U+0174): B<<588.5,240.0>-<594.0,202.0>-<598.0,169.0>>/B<<598.0,169.0>-<600.0,197.0>-<605.0,231.5>> = 10.996843898999522 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian-CondensedExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Condensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uniFB13 (U+FB13): L<<321.0,760.0>--<522.0,760.0>> -> L<<522.0,760.0>--<522.0,760.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-CondensedLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Condensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0543 (U+0543): L<<57.0,641.0>--<231.0,604.0>> -> L<<231.0,604.0>--<235.0,603.0>>

	* uni056E (U+056E): L<<134.0,676.0>--<136.0,678.0>> -> L<<136.0,678.0>--<234.0,767.0>> 

	* And uniFB13 (U+FB13): L<<338.0,760.0>--<540.0,760.0>> -> L<<540.0,760.0>--<540.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<382.5,568.0>-<377.0,596.0>-<373.0,632.0>>/B<<373.0,632.0>-<369.0,603.0>-<364.0,575.0>> = 14.193505047888126

	* Wacute (U+1E82): B<<382.5,568.0>-<377.0,596.0>-<373.0,632.0>>/B<<373.0,632.0>-<369.0,603.0>-<364.0,575.0>> = 14.193505047888126

	* Wcircumflex (U+0174): B<<382.5,568.0>-<377.0,596.0>-<373.0,632.0>>/B<<373.0,632.0>-<369.0,603.0>-<364.0,575.0>> = 14.193505047888126

	* Wdieresis (U+1E84): B<<382.5,568.0>-<377.0,596.0>-<373.0,632.0>>/B<<373.0,632.0>-<369.0,603.0>-<364.0,575.0>> = 14.193505047888126 

	* And Wgrave (U+1E80): B<<382.5,568.0>-<377.0,596.0>-<373.0,632.0>>/B<<373.0,632.0>-<369.0,603.0>-<364.0,575.0>> = 14.193505047888126 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-CondensedMedium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Condensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni056E (U+056E): L<<152.0,653.0>--<157.0,657.0>> -> L<<157.0,657.0>--<291.0,769.0>> 

	* And uniFB13 (U+FB13): L<<381.0,760.0>--<585.0,760.0>> -> L<<585.0,760.0>--<585.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<212.5,200.5>-<221.0,152.0>-<224.0,116.0>>/B<<224.0,116.0>-<230.0,159.0>-<238.5,207.5>> = 12.707113501316583

	* W (U+0057): B<<409.5,495.0>-<402.0,536.0>-<398.0,577.0>>/B<<398.0,577.0>-<394.0,548.0>-<387.5,506.0>> = 13.42551110594199

	* W (U+0057): B<<557.0,209.0>-<565.0,162.0>-<571.0,116.0>>/B<<571.0,116.0>-<576.0,160.0>-<584.0,207.5>> = 13.914481664069719

	* Wacute (U+1E82): B<<212.5,200.5>-<221.0,152.0>-<224.0,116.0>>/B<<224.0,116.0>-<230.0,159.0>-<238.5,207.5>> = 12.707113501316583

	* Wacute (U+1E82): B<<409.5,495.0>-<402.0,536.0>-<398.0,577.0>>/B<<398.0,577.0>-<394.0,548.0>-<387.5,506.0>> = 13.42551110594199

	* Wacute (U+1E82): B<<557.0,209.0>-<565.0,162.0>-<571.0,116.0>>/B<<571.0,116.0>-<576.0,160.0>-<584.0,207.5>> = 13.914481664069719

	* Wcircumflex (U+0174): B<<212.5,200.5>-<221.0,152.0>-<224.0,116.0>>/B<<224.0,116.0>-<230.0,159.0>-<238.5,207.5>> = 12.707113501316583

	* Wcircumflex (U+0174): B<<409.5,495.0>-<402.0,536.0>-<398.0,577.0>>/B<<398.0,577.0>-<394.0,548.0>-<387.5,506.0>> = 13.42551110594199

	* Wcircumflex (U+0174): B<<557.0,209.0>-<565.0,162.0>-<571.0,116.0>>/B<<571.0,116.0>-<576.0,160.0>-<584.0,207.5>> = 13.914481664069719

	* Wdieresis (U+1E84): B<<212.5,200.5>-<221.0,152.0>-<224.0,116.0>>/B<<224.0,116.0>-<230.0,159.0>-<238.5,207.5>> = 12.707113501316583 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-CondensedSemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Condensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=118.0,Y=-2.0 (should be at baseline 0?)

	* six (U+0036): X=412.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=74.0,Y=-1.0 (should be at baseline 0?)

	* A (U+0041): X=200.0,Y=715.0 (should be at cap-height 714?)

	* A (U+0041): X=347.0,Y=715.0 (should be at cap-height 714?)

	* G (U+0047): X=459.0,Y=712.0 (should be at cap-height 714?)

	* S (U+0053): X=119.0,Y=-1.0 (should be at baseline 0?)

	* S (U+0053): X=342.0,Y=712.5 (should be at cap-height 714?)

	* asciicircum (U+005E): X=219.0,Y=715.0 (should be at cap-height 714?)

	* asciicircum (U+005E): X=280.0,Y=715.0 (should be at cap-height 714?) 

	* And 87 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni056E (U+056E): L<<159.0,644.0>--<163.0,647.0>> -> L<<163.0,647.0>--<313.0,769.0>> 

	* And uniFB13 (U+FB13): L<<398.0,760.0>--<601.0,760.0>> -> L<<601.0,760.0>--<601.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<220.0,222.5>-<228.0,171.0>-<232.0,133.0>>/B<<232.0,133.0>-<238.0,178.0>-<247.0,229.0>> = 13.60364932608595

	* W (U+0057): B<<418.5,464.5>-<411.0,509.0>-<406.0,551.0>>/B<<406.0,551.0>-<403.0,520.0>-<396.0,474.0>> = 12.316514726094919

	* W (U+0057): B<<564.5,229.0>-<573.0,179.0>-<579.0,133.0>>/B<<579.0,133.0>-<583.0,176.0>-<591.5,226.5>> = 12.745953641117218

	* Wacute (U+1E82): B<<220.0,222.5>-<228.0,171.0>-<232.0,133.0>>/B<<232.0,133.0>-<238.0,178.0>-<247.0,229.0>> = 13.60364932608595

	* Wacute (U+1E82): B<<418.5,464.5>-<411.0,509.0>-<406.0,551.0>>/B<<406.0,551.0>-<403.0,520.0>-<396.0,474.0>> = 12.316514726094919

	* Wacute (U+1E82): B<<564.5,229.0>-<573.0,179.0>-<579.0,133.0>>/B<<579.0,133.0>-<583.0,176.0>-<591.5,226.5>> = 12.745953641117218

	* Wcircumflex (U+0174): B<<220.0,222.5>-<228.0,171.0>-<232.0,133.0>>/B<<232.0,133.0>-<238.0,178.0>-<247.0,229.0>> = 13.60364932608595

	* Wcircumflex (U+0174): B<<418.5,464.5>-<411.0,509.0>-<406.0,551.0>>/B<<406.0,551.0>-<403.0,520.0>-<396.0,474.0>> = 12.316514726094919

	* Wcircumflex (U+0174): B<<564.5,229.0>-<573.0,179.0>-<579.0,133.0>>/B<<579.0,133.0>-<583.0,176.0>-<591.5,226.5>> = 12.745953641117218

	* Wdieresis (U+1E84): B<<220.0,222.5>-<228.0,171.0>-<232.0,133.0>>/B<<232.0,133.0>-<238.0,178.0>-<247.0,229.0>> = 13.60364932608595 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian-CondensedThin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Condensed Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<118.0,714.0>--<114.0,171.0>>

	* exclam (U+0021): L<<90.0,171.0>--<87.0,714.0>>

	* exclamdown (U+00A1): L<<112.0,351.0>--<116.0,-192.0>>

	* exclamdown (U+00A1): L<<86.0,-192.0>--<88.0,351.0>> 

	* And p (U+0070): L<<97.0,527.0>--<98.0,403.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni053E
	* uniFB16
	* uni0536
	* uni0562
	* uni058F
	* uni054E
	* uniFB13
	* uni0569
	* uni0568
	* uni0546 and 22 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And Wgrave (U+1E80): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-ExtraCondensed.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraCondensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni053B (U+053B): L<<147.0,436.0>--<152.0,436.0>> -> L<<152.0,436.0>--<152.0,436.0>>

	* uni056E (U+056E): L<<124.0,664.0>--<130.0,669.0>> -> L<<130.0,669.0>--<246.0,768.0>> 

	* And uniFB13 (U+FB13): L<<337.0,760.0>--<510.0,760.0>> -> L<<510.0,760.0>--<510.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* A (U+0041): B<<230.5,589.0>-<226.0,615.0>-<223.0,638.0>>/B<<223.0,638.0>-<218.0,590.0>-<206.0,536.0>> = 13.37827102514601

	* Aacute (U+00C1): B<<230.5,589.0>-<226.0,615.0>-<223.0,638.0>>/B<<223.0,638.0>-<218.0,590.0>-<206.0,536.0>> = 13.37827102514601

	* Abreve (U+0102): B<<230.5,589.0>-<226.0,615.0>-<223.0,638.0>>/B<<223.0,638.0>-<218.0,590.0>-<206.0,536.0>> = 13.37827102514601

	* Acircumflex (U+00C2): B<<230.5,589.0>-<226.0,615.0>-<223.0,638.0>>/B<<223.0,638.0>-<218.0,590.0>-<206.0,536.0>> = 13.37827102514601

	* Adieresis (U+00C4): B<<230.5,589.0>-<226.0,615.0>-<223.0,638.0>>/B<<223.0,638.0>-<218.0,590.0>-<206.0,536.0>> = 13.37827102514601

	* Agrave (U+00C0): B<<230.5,589.0>-<226.0,615.0>-<223.0,638.0>>/B<<223.0,638.0>-<218.0,590.0>-<206.0,536.0>> = 13.37827102514601

	* Amacron (U+0100): B<<230.5,589.0>-<226.0,615.0>-<223.0,638.0>>/B<<223.0,638.0>-<218.0,590.0>-<206.0,536.0>> = 13.37827102514601

	* Aogonek (U+0104): B<<230.5,589.0>-<226.0,615.0>-<223.0,638.0>>/B<<223.0,638.0>-<218.0,590.0>-<206.0,536.0>> = 13.37827102514601

	* Aring (U+00C5): B<<230.5,589.0>-<226.0,615.0>-<223.0,638.0>>/B<<223.0,638.0>-<218.0,590.0>-<206.0,536.0>> = 13.37827102514601

	* Atilde (U+00C3): B<<230.5,589.0>-<226.0,615.0>-<223.0,638.0>>/B<<223.0,638.0>-<218.0,590.0>-<206.0,536.0>> = 13.37827102514601 

	* And 16 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-ExtraCondensedBlack.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraCondensed Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* six (U+0036): X=430.0,Y=716.0 (should be at cap-height 714?)

	* nine (U+0039): X=65.0,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=350.0,Y=-0.5 (should be at baseline 0?)

	* t (U+0074): X=279.5,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=166.0,Y=-2.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=108.0,Y=712.0 (should be at cap-height 714?)

	* acute (U+00B4): X=262.5,Y=712.5 (should be at cap-height 714?)

	* Aring (U+00C5): X=288.0,Y=716.0 (should be at cap-height 714?)

	* Aring (U+00C5): X=288.0,Y=716.0 (should be at cap-height 714?)

	* aacute (U+00E1): X=379.5,Y=712.5 (should be at cap-height 714?) 

	* And 33 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* A (U+0041): B<<297.5,522.0>-<292.0,559.0>-<288.0,589.0>>/B<<288.0,589.0>-<285.0,561.0>-<279.5,524.0>> = 13.71014693487685

	* Aacute (U+00C1): B<<297.5,522.0>-<292.0,559.0>-<288.0,589.0>>/B<<288.0,589.0>-<285.0,561.0>-<279.5,524.0>> = 13.71014693487685

	* Abreve (U+0102): B<<297.5,522.0>-<292.0,559.0>-<288.0,589.0>>/B<<288.0,589.0>-<285.0,561.0>-<279.5,524.0>> = 13.71014693487685

	* Acircumflex (U+00C2): B<<297.5,522.0>-<292.0,559.0>-<288.0,589.0>>/B<<288.0,589.0>-<285.0,561.0>-<279.5,524.0>> = 13.71014693487685

	* Adieresis (U+00C4): B<<297.5,522.0>-<292.0,559.0>-<288.0,589.0>>/B<<288.0,589.0>-<285.0,561.0>-<279.5,524.0>> = 13.71014693487685

	* Agrave (U+00C0): B<<297.5,522.0>-<292.0,559.0>-<288.0,589.0>>/B<<288.0,589.0>-<285.0,561.0>-<279.5,524.0>> = 13.71014693487685

	* Amacron (U+0100): B<<297.5,522.0>-<292.0,559.0>-<288.0,589.0>>/B<<288.0,589.0>-<285.0,561.0>-<279.5,524.0>> = 13.71014693487685

	* Aogonek (U+0104): B<<297.5,522.0>-<292.0,559.0>-<288.0,589.0>>/B<<288.0,589.0>-<285.0,561.0>-<279.5,524.0>> = 13.71014693487685

	* Aring (U+00C5): B<<297.5,522.0>-<292.0,559.0>-<288.0,589.0>>/B<<288.0,589.0>-<285.0,561.0>-<279.5,524.0>> = 13.71014693487685

	* Atilde (U+00C3): B<<297.5,522.0>-<292.0,559.0>-<288.0,589.0>>/B<<288.0,589.0>-<285.0,561.0>-<279.5,524.0>> = 13.71014693487685 

	* And 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-ExtraCondensedBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraCondensed' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* four (U+0034): X=252.0,Y=716.0 (should be at cap-height 714?)

	* four (U+0034): X=385.0,Y=716.0 (should be at cap-height 714?)

	* six (U+0036): X=400.0,Y=715.0 (should be at cap-height 714?)

	* S (U+0053): X=113.0,Y=-1.5 (should be at baseline 0?)

	* S (U+0053): X=325.5,Y=712.5 (should be at cap-height 714?)

	* b (U+0062): X=239.0,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=383.0,Y=535.0 (should be at x-height 536?)

	* m (U+006D): X=480.5,Y=537.0 (should be at x-height 536?)

	* braceleft (U+007B): X=125.0,Y=-1.0 (should be at baseline 0?)

	* braceright (U+007D): X=239.0,Y=-1.0 (should be at baseline 0?) 

	* And 59 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0531 (U+0531): L<<506.0,714.0>--<506.0,236.0>> -> L<<506.0,236.0>--<506.0,234.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* A (U+0041): B<<283.0,480.0>-<271.0,551.0>-<263.0,608.0>>/B<<263.0,608.0>-<258.0,552.0>-<243.0,482.0>> = 13.091492018755051

	* Aacute (U+00C1): B<<283.0,480.0>-<271.0,551.0>-<263.0,608.0>>/B<<263.0,608.0>-<258.0,552.0>-<243.0,482.0>> = 13.091492018755051

	* Abreve (U+0102): B<<283.0,480.0>-<271.0,551.0>-<263.0,608.0>>/B<<263.0,608.0>-<258.0,552.0>-<243.0,482.0>> = 13.091492018755051

	* Acircumflex (U+00C2): B<<283.0,480.0>-<271.0,551.0>-<263.0,608.0>>/B<<263.0,608.0>-<258.0,552.0>-<243.0,482.0>> = 13.091492018755051

	* Adieresis (U+00C4): B<<283.0,480.0>-<271.0,551.0>-<263.0,608.0>>/B<<263.0,608.0>-<258.0,552.0>-<243.0,482.0>> = 13.091492018755051

	* Agrave (U+00C0): B<<283.0,480.0>-<271.0,551.0>-<263.0,608.0>>/B<<263.0,608.0>-<258.0,552.0>-<243.0,482.0>> = 13.091492018755051

	* Amacron (U+0100): B<<283.0,480.0>-<271.0,551.0>-<263.0,608.0>>/B<<263.0,608.0>-<258.0,552.0>-<243.0,482.0>> = 13.091492018755051

	* Aogonek (U+0104): B<<283.0,480.0>-<271.0,551.0>-<263.0,608.0>>/B<<263.0,608.0>-<258.0,552.0>-<243.0,482.0>> = 13.091492018755051

	* Aring (U+00C5): B<<283.0,480.0>-<271.0,551.0>-<263.0,608.0>>/B<<263.0,608.0>-<258.0,552.0>-<243.0,482.0>> = 13.091492018755051

	* Atilde (U+00C3): B<<283.0,480.0>-<271.0,551.0>-<263.0,608.0>>/B<<263.0,608.0>-<258.0,552.0>-<243.0,482.0>> = 13.091492018755051 

	* And 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-ExtraCondensedExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraCondensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* four (U+0034): X=252.0,Y=715.0 (should be at cap-height 714?)

	* four (U+0034): X=397.0,Y=715.0 (should be at cap-height 714?)

	* six (U+0036): X=414.0,Y=715.0 (should be at cap-height 714?)

	* S (U+0053): X=114.5,Y=-1.0 (should be at baseline 0?)

	* c (U+0063): X=318.0,Y=1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=120.0,Y=-1.0 (should be at baseline 0?)

	* braceright (U+007D): X=245.0,Y=-1.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=106.0,Y=712.5 (should be at cap-height 714?)

	* Aring (U+00C5): X=274.0,Y=716.0 (should be at cap-height 714?)

	* Aring (U+00C5): X=274.0,Y=716.0 (should be at cap-height 714?) 

	* And 38 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0531 (U+0531): L<<518.0,714.0>--<518.0,239.0>> -> L<<518.0,239.0>--<518.0,237.0>> 

	* And uniFB13 (U+FB13): L<<757.0,559.0>--<757.0,558.0>> -> L<<757.0,558.0>--<757.0,544.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* A (U+0041): B<<283.5,536.0>-<278.0,571.0>-<275.0,599.0>>/B<<275.0,599.0>-<269.0,542.0>-<254.0,466.0>> = 12.12450952377988

	* Aacute (U+00C1): B<<283.5,536.0>-<278.0,571.0>-<275.0,599.0>>/B<<275.0,599.0>-<269.0,542.0>-<254.0,466.0>> = 12.12450952377988

	* Abreve (U+0102): B<<283.5,536.0>-<278.0,571.0>-<275.0,599.0>>/B<<275.0,599.0>-<269.0,542.0>-<254.0,466.0>> = 12.12450952377988

	* Acircumflex (U+00C2): B<<283.5,536.0>-<278.0,571.0>-<275.0,599.0>>/B<<275.0,599.0>-<269.0,542.0>-<254.0,466.0>> = 12.12450952377988

	* Adieresis (U+00C4): B<<283.5,536.0>-<278.0,571.0>-<275.0,599.0>>/B<<275.0,599.0>-<269.0,542.0>-<254.0,466.0>> = 12.12450952377988

	* Agrave (U+00C0): B<<283.5,536.0>-<278.0,571.0>-<275.0,599.0>>/B<<275.0,599.0>-<269.0,542.0>-<254.0,466.0>> = 12.12450952377988

	* Amacron (U+0100): B<<283.5,536.0>-<278.0,571.0>-<275.0,599.0>>/B<<275.0,599.0>-<269.0,542.0>-<254.0,466.0>> = 12.12450952377988

	* Aogonek (U+0104): B<<283.5,536.0>-<278.0,571.0>-<275.0,599.0>>/B<<275.0,599.0>-<269.0,542.0>-<254.0,466.0>> = 12.12450952377988

	* Aring (U+00C5): B<<283.5,536.0>-<278.0,571.0>-<275.0,599.0>>/B<<275.0,599.0>-<269.0,542.0>-<254.0,466.0>> = 12.12450952377988

	* Atilde (U+00C3): B<<283.5,536.0>-<278.0,571.0>-<275.0,599.0>>/B<<275.0,599.0>-<269.0,542.0>-<254.0,466.0>> = 12.12450952377988 

	* And 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-ExtraCondensedExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraCondensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni056E (U+056E): L<<104.0,690.0>--<105.0,691.0>> -> L<<105.0,691.0>--<184.0,766.0>> 

	* And uniFB13 (U+FB13): L<<295.0,760.0>--<461.0,760.0>> -> L<<461.0,760.0>--<461.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<338.5,587.5>-<335.0,610.0>-<330.0,648.0>>/B<<330.0,648.0>-<326.0,614.0>-<322.0,591.0>> = 14.205694447486762

	* Wacute (U+1E82): B<<338.5,587.5>-<335.0,610.0>-<330.0,648.0>>/B<<330.0,648.0>-<326.0,614.0>-<322.0,591.0>> = 14.205694447486762

	* Wcircumflex (U+0174): B<<338.5,587.5>-<335.0,610.0>-<330.0,648.0>>/B<<330.0,648.0>-<326.0,614.0>-<322.0,591.0>> = 14.205694447486762

	* Wdieresis (U+1E84): B<<338.5,587.5>-<335.0,610.0>-<330.0,648.0>>/B<<330.0,648.0>-<326.0,614.0>-<322.0,591.0>> = 14.205694447486762 

	* And Wgrave (U+1E80): B<<338.5,587.5>-<335.0,610.0>-<330.0,648.0>>/B<<330.0,648.0>-<326.0,614.0>-<322.0,591.0>> = 14.205694447486762 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-ExtraCondensedLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraCondensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0531 (U+0531): L<<438.0,714.0>--<438.0,222.0>> -> L<<438.0,222.0>--<438.0,215.0>> 

	* And uniFB13 (U+FB13): L<<311.0,760.0>--<480.0,760.0>> -> L<<480.0,760.0>--<480.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<350.0,558.5>-<346.0,586.0>-<341.0,628.0>>/B<<341.0,628.0>-<337.0,595.0>-<333.0,567.0>> = 13.700201693463454

	* Wacute (U+1E82): B<<350.0,558.5>-<346.0,586.0>-<341.0,628.0>>/B<<341.0,628.0>-<337.0,595.0>-<333.0,567.0>> = 13.700201693463454

	* Wcircumflex (U+0174): B<<350.0,558.5>-<346.0,586.0>-<341.0,628.0>>/B<<341.0,628.0>-<337.0,595.0>-<333.0,567.0>> = 13.700201693463454

	* Wdieresis (U+1E84): B<<350.0,558.5>-<346.0,586.0>-<341.0,628.0>>/B<<341.0,628.0>-<337.0,595.0>-<333.0,567.0>> = 13.700201693463454 

	* And Wgrave (U+1E80): B<<350.0,558.5>-<346.0,586.0>-<341.0,628.0>>/B<<341.0,628.0>-<337.0,595.0>-<333.0,567.0>> = 13.700201693463454 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-ExtraCondensedMedium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraCondensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uniFB13 (U+FB13): L<<352.0,760.0>--<528.0,760.0>> -> L<<528.0,760.0>--<528.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* A (U+0041): B<<242.5,577.0>-<238.0,605.0>-<235.0,629.0>>/B<<235.0,629.0>-<230.0,579.0>-<217.0,520.0>> = 12.835609486401424

	* Aacute (U+00C1): B<<242.5,577.0>-<238.0,605.0>-<235.0,629.0>>/B<<235.0,629.0>-<230.0,579.0>-<217.0,520.0>> = 12.835609486401424

	* Abreve (U+0102): B<<242.5,577.0>-<238.0,605.0>-<235.0,629.0>>/B<<235.0,629.0>-<230.0,579.0>-<217.0,520.0>> = 12.835609486401424

	* Acircumflex (U+00C2): B<<242.5,577.0>-<238.0,605.0>-<235.0,629.0>>/B<<235.0,629.0>-<230.0,579.0>-<217.0,520.0>> = 12.835609486401424

	* Adieresis (U+00C4): B<<242.5,577.0>-<238.0,605.0>-<235.0,629.0>>/B<<235.0,629.0>-<230.0,579.0>-<217.0,520.0>> = 12.835609486401424

	* Agrave (U+00C0): B<<242.5,577.0>-<238.0,605.0>-<235.0,629.0>>/B<<235.0,629.0>-<230.0,579.0>-<217.0,520.0>> = 12.835609486401424

	* Amacron (U+0100): B<<242.5,577.0>-<238.0,605.0>-<235.0,629.0>>/B<<235.0,629.0>-<230.0,579.0>-<217.0,520.0>> = 12.835609486401424

	* Aogonek (U+0104): B<<242.5,577.0>-<238.0,605.0>-<235.0,629.0>>/B<<235.0,629.0>-<230.0,579.0>-<217.0,520.0>> = 12.835609486401424

	* Aring (U+00C5): B<<242.5,577.0>-<238.0,605.0>-<235.0,629.0>>/B<<235.0,629.0>-<230.0,579.0>-<217.0,520.0>> = 12.835609486401424

	* Atilde (U+00C3): B<<242.5,577.0>-<238.0,605.0>-<235.0,629.0>>/B<<235.0,629.0>-<230.0,579.0>-<217.0,520.0>> = 12.835609486401424 

	* And 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-ExtraCondensedSemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraCondensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* six (U+0036): X=382.0,Y=715.0 (should be at cap-height 714?)

	* G (U+0047): X=422.5,Y=712.0 (should be at cap-height 714?)

	* S (U+0053): X=110.0,Y=-2.0 (should be at baseline 0?)

	* S (U+0053): X=317.0,Y=713.0 (should be at cap-height 714?)

	* grave (U+0060): X=194.5,Y=716.0 (should be at cap-height 714?)

	* c (U+0063): X=293.5,Y=-1.0 (should be at baseline 0?)

	* f (U+0066): X=102.0,Y=715.5 (should be at cap-height 714?)

	* g (U+0067): X=264.5,Y=535.0 (should be at x-height 536?)

	* p (U+0070): X=223.0,Y=535.0 (should be at x-height 536?)

	* q (U+0071): X=264.5,Y=535.0 (should be at x-height 536?) 

	* And 71 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0531 (U+0531): L<<489.0,714.0>--<489.0,233.0>> -> L<<489.0,233.0>--<489.0,229.0>>

	* uni056E (U+056E): L<<140.0,645.0>--<144.0,648.0>> -> L<<144.0,648.0>--<291.0,769.0>>

	* uni0579 (U+0579): L<<213.0,330.0>--<246.0,301.0>> -> L<<246.0,301.0>--<247.0,300.0>>

	* uni0588 (U+0588): L<<206.0,498.0>--<206.0,172.0>> -> L<<206.0,172.0>--<206.0,169.0>>

	* uni0588 (U+0588): L<<94.0,169.0>--<94.0,172.0>> -> L<<94.0,172.0>--<94.0,498.0>> 

	* And uniFB13 (U+FB13): L<<368.0,760.0>--<548.0,760.0>> -> L<<548.0,760.0>--<548.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* A (U+0041): B<<256.0,563.5>-<251.0,594.0>-<248.0,619.0>>/B<<248.0,619.0>-<243.0,566.0>-<229.0,502.0>> = 12.232085172604307

	* Aacute (U+00C1): B<<256.0,563.5>-<251.0,594.0>-<248.0,619.0>>/B<<248.0,619.0>-<243.0,566.0>-<229.0,502.0>> = 12.232085172604307

	* Abreve (U+0102): B<<256.0,563.5>-<251.0,594.0>-<248.0,619.0>>/B<<248.0,619.0>-<243.0,566.0>-<229.0,502.0>> = 12.232085172604307

	* Acircumflex (U+00C2): B<<256.0,563.5>-<251.0,594.0>-<248.0,619.0>>/B<<248.0,619.0>-<243.0,566.0>-<229.0,502.0>> = 12.232085172604307

	* Adieresis (U+00C4): B<<256.0,563.5>-<251.0,594.0>-<248.0,619.0>>/B<<248.0,619.0>-<243.0,566.0>-<229.0,502.0>> = 12.232085172604307

	* Agrave (U+00C0): B<<256.0,563.5>-<251.0,594.0>-<248.0,619.0>>/B<<248.0,619.0>-<243.0,566.0>-<229.0,502.0>> = 12.232085172604307

	* Amacron (U+0100): B<<256.0,563.5>-<251.0,594.0>-<248.0,619.0>>/B<<248.0,619.0>-<243.0,566.0>-<229.0,502.0>> = 12.232085172604307

	* Aogonek (U+0104): B<<256.0,563.5>-<251.0,594.0>-<248.0,619.0>>/B<<248.0,619.0>-<243.0,566.0>-<229.0,502.0>> = 12.232085172604307

	* Aring (U+00C5): B<<256.0,563.5>-<251.0,594.0>-<248.0,619.0>>/B<<248.0,619.0>-<243.0,566.0>-<229.0,502.0>> = 12.232085172604307

	* Atilde (U+00C3): B<<256.0,563.5>-<251.0,594.0>-<248.0,619.0>>/B<<248.0,619.0>-<243.0,566.0>-<229.0,502.0>> = 12.232085172604307 

	* And 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian-ExtraCondensedThin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraCondensed Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<85.0,170.0>--<82.0,714.0>>

	* exclamdown (U+00A1): L<<81.0,-194.0>--<84.0,350.0>> 

	* And p (U+0070): L<<90.0,527.0>--<91.0,404.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0571 (U+0571): L<<426.0,0.0>--<426.0,0.0>> -> L<<426.0,0.0>--<426.0,0.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0543 (U+0543): L<<260.0,558.0>--<260.0,558.0>>/L<<260.0,558.0>--<70.0,590.0>> = 9.560096480886276 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni053E
	* uniFB16
	* uni0536
	* uni058F
	* uni054E
	* uni0569
	* uni0551
	* uniFB14
	* uni0588
	* uni056E and 12 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 87 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0571 (U+0571): L<<441.0,0.0>--<441.0,0.0>> -> L<<441.0,0.0>--<441.0,0.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[10] NotoSansArmenian-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni053E
	* uniFB16
	* uni0536
	* uni058F
	* uni054E
	* uni056E
	* uni0541
	* uni0567
	* uni0571
	* uni0543 and uni053D
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni053E
	* uniFB16
	* uni0536
	* uni058F
	* uni054E
	* uni0569
	* uni0551
	* uniFB14
	* uni0588
	* uni056E and 13 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
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

	* And 65 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
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

	* And Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-SemiCondensed.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiCondensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni056E (U+056E): L<<170.0,658.0>--<173.0,661.0>> -> L<<173.0,661.0>--<300.0,769.0>>

	* uni0571 (U+0571): L<<395.0,0.0>--<395.0,0.0>> -> L<<395.0,0.0>--<395.0,0.0>> 

	* And uniFB13 (U+FB13): L<<399.0,760.0>--<638.0,760.0>> -> L<<638.0,760.0>--<638.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<604.0,189.5>-<613.0,145.0>-<618.0,104.0>>/B<<618.0,104.0>-<623.0,145.0>-<631.5,189.5>> = 13.9059149363478

	* Wacute (U+1E82): B<<604.0,189.5>-<613.0,145.0>-<618.0,104.0>>/B<<618.0,104.0>-<623.0,145.0>-<631.5,189.5>> = 13.9059149363478

	* Wcircumflex (U+0174): B<<604.0,189.5>-<613.0,145.0>-<618.0,104.0>>/B<<618.0,104.0>-<623.0,145.0>-<631.5,189.5>> = 13.9059149363478

	* Wdieresis (U+1E84): B<<604.0,189.5>-<613.0,145.0>-<618.0,104.0>>/B<<618.0,104.0>-<623.0,145.0>-<631.5,189.5>> = 13.9059149363478 

	* And Wgrave (U+1E80): B<<604.0,189.5>-<613.0,145.0>-<618.0,104.0>>/B<<618.0,104.0>-<623.0,145.0>-<631.5,189.5>> = 13.9059149363478 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-SemiCondensedBlack.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiCondensed Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=124.5,Y=-0.5 (should be at baseline 0?)

	* six (U+0036): X=481.0,Y=716.0 (should be at cap-height 714?)

	* A (U+0041): X=211.0,Y=716.0 (should be at cap-height 714?)

	* A (U+0041): X=456.0,Y=716.0 (should be at cap-height 714?)

	* C (U+0043): X=451.5,Y=-0.5 (should be at baseline 0?)

	* C (U+0043): X=465.5,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=503.5,Y=1.5 (should be at baseline 0?)

	* asciicircum (U+005E): X=215.0,Y=716.0 (should be at cap-height 714?)

	* asciicircum (U+005E): X=298.0,Y=716.0 (should be at cap-height 714?)

	* b (U+0062): X=239.0,Y=537.0 (should be at x-height 536?) 

	* And 73 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0588 (U+0588): L<<114.0,190.0>--<114.0,195.0>> -> L<<114.0,195.0>--<114.0,508.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<314.5,235.5>-<320.0,203.0>-<322.0,183.0>>/B<<322.0,183.0>-<324.0,203.0>-<329.5,235.5>> = 11.42118627499929

	* W (U+0057): B<<279.0,244.0>-<285.0,206.0>-<289.0,179.0>>/B<<289.0,179.0>-<293.0,218.0>-<301.5,266.0>> = 14.282982606909593

	* W (U+0057): B<<486.5,414.0>-<481.0,450.0>-<478.0,477.0>>/B<<478.0,477.0>-<476.0,452.0>-<470.5,416.0>> = 10.914113005810767

	* W (U+0057): B<<652.0,263.0>-<660.0,215.0>-<664.0,179.0>>/B<<664.0,179.0>-<667.0,204.0>-<673.0,240.5>> = 13.182965158540823

	* Wacute (U+1E82): B<<279.0,244.0>-<285.0,206.0>-<289.0,179.0>>/B<<289.0,179.0>-<293.0,218.0>-<301.5,266.0>> = 14.282982606909593

	* Wacute (U+1E82): B<<486.5,414.0>-<481.0,450.0>-<478.0,477.0>>/B<<478.0,477.0>-<476.0,452.0>-<470.5,416.0>> = 10.914113005810767

	* Wacute (U+1E82): B<<652.0,263.0>-<660.0,215.0>-<664.0,179.0>>/B<<664.0,179.0>-<667.0,204.0>-<673.0,240.5>> = 13.182965158540823

	* Wcircumflex (U+0174): B<<279.0,244.0>-<285.0,206.0>-<289.0,179.0>>/B<<289.0,179.0>-<293.0,218.0>-<301.5,266.0>> = 14.282982606909593

	* Wcircumflex (U+0174): B<<486.5,414.0>-<481.0,450.0>-<478.0,477.0>>/B<<478.0,477.0>-<476.0,452.0>-<470.5,416.0>> = 10.914113005810767

	* Wcircumflex (U+0174): B<<652.0,263.0>-<660.0,215.0>-<664.0,179.0>>/B<<664.0,179.0>-<667.0,204.0>-<673.0,240.5>> = 13.182965158540823 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSansArmenian-SemiCondensedBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiCondensed' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign (U+0023): X=213.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=316.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=405.0,Y=713.0 (should be at cap-height 714?)

	* numbersign (U+0023): X=506.0,Y=713.0 (should be at cap-height 714?)

	* three (U+0033): X=126.5,Y=-1.0 (should be at baseline 0?)

	* four (U+0034): X=301.0,Y=715.0 (should be at cap-height 714?)

	* four (U+0034): X=438.0,Y=715.0 (should be at cap-height 714?)

	* five (U+0035): X=128.0,Y=-1.0 (should be at baseline 0?)

	* six (U+0036): X=456.0,Y=715.0 (should be at cap-height 714?)

	* nine (U+0039): X=77.0,Y=-2.0 (should be at baseline 0?) 

	* And 66 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0579 (U+0579): L<<241.0,360.0>--<325.0,313.0>> -> L<<325.0,313.0>--<327.0,312.0>>

	* uni0588 (U+0588): L<<101.0,174.0>--<101.0,175.0>> -> L<<101.0,175.0>--<101.0,501.0>> 

	* And uni0588 (U+0588): L<<237.0,501.0>--<237.0,175.0>> -> L<<237.0,175.0>--<237.0,174.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<455.5,475.0>-<450.0,508.0>-<448.0,532.0>>/B<<448.0,532.0>-<446.0,511.0>-<440.5,478.5>> = 10.203973721731666

	* W (U+0057): B<<628.5,207.0>-<634.0,172.0>-<637.0,145.0>>/B<<637.0,145.0>-<640.0,171.0>-<645.5,205.5>> = 12.922136401087942

	* Wacute (U+1E82): B<<455.5,475.0>-<450.0,508.0>-<448.0,532.0>>/B<<448.0,532.0>-<446.0,511.0>-<440.5,478.5>> = 10.203973721731666

	* Wacute (U+1E82): B<<628.5,207.0>-<634.0,172.0>-<637.0,145.0>>/B<<637.0,145.0>-<640.0,171.0>-<645.5,205.5>> = 12.922136401087942

	* Wcircumflex (U+0174): B<<455.5,475.0>-<450.0,508.0>-<448.0,532.0>>/B<<448.0,532.0>-<446.0,511.0>-<440.5,478.5>> = 10.203973721731666

	* Wcircumflex (U+0174): B<<628.5,207.0>-<634.0,172.0>-<637.0,145.0>>/B<<637.0,145.0>-<640.0,171.0>-<645.5,205.5>> = 12.922136401087942

	* Wdieresis (U+1E84): B<<455.5,475.0>-<450.0,508.0>-<448.0,532.0>>/B<<448.0,532.0>-<446.0,511.0>-<440.5,478.5>> = 10.203973721731666

	* Wdieresis (U+1E84): B<<628.5,207.0>-<634.0,172.0>-<637.0,145.0>>/B<<637.0,145.0>-<640.0,171.0>-<645.5,205.5>> = 12.922136401087942

	* Wgrave (U+1E80): B<<455.5,475.0>-<450.0,508.0>-<448.0,532.0>>/B<<448.0,532.0>-<446.0,511.0>-<440.5,478.5>> = 10.203973721731666 

	* And Wgrave (U+1E80): B<<628.5,207.0>-<634.0,172.0>-<637.0,145.0>>/B<<637.0,145.0>-<640.0,171.0>-<645.5,205.5>> = 12.922136401087942 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni053F (U+053F): L<<453.0,0.0>--<452.0,185.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSansArmenian-SemiCondensedExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiCondensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=126.0,Y=-1.0 (should be at baseline 0?)

	* six (U+0036): X=468.0,Y=715.0 (should be at cap-height 714?)

	* A (U+0041): X=218.0,Y=716.0 (should be at cap-height 714?)

	* A (U+0041): X=429.0,Y=716.0 (should be at cap-height 714?)

	* G (U+0047): X=495.0,Y=1.0 (should be at baseline 0?)

	* asciicircum (U+005E): X=223.0,Y=716.0 (should be at cap-height 714?)

	* asciicircum (U+005E): X=299.0,Y=716.0 (should be at cap-height 714?)

	* b (U+0062): X=281.0,Y=537.0 (should be at x-height 536?)

	* c (U+0063): X=373.5,Y=1.0 (should be at baseline 0?)

	* d (U+0064): X=313.0,Y=537.5 (should be at x-height 536?) 

	* And 72 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni053B (U+053B): L<<228.0,417.0>--<235.0,417.0>> -> L<<235.0,417.0>--<235.0,417.0>>

	* uni0571 (U+0571): L<<421.0,0.0>--<421.0,0.0>> -> L<<421.0,0.0>--<421.0,0.0>>

	* uni0588 (U+0588): L<<107.0,181.0>--<107.0,184.0>> -> L<<107.0,184.0>--<107.0,504.0>> 

	* And uni0588 (U+0588): L<<263.0,504.0>--<263.0,184.0>> -> L<<263.0,184.0>--<263.0,181.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<301.5,212.0>-<308.0,180.0>-<310.0,159.0>>/B<<310.0,159.0>-<313.0,180.0>-<318.5,211.5>> = 13.570434385161475

	* W (U+0057): B<<263.0,223.5>-<269.0,187.0>-<272.0,161.0>>/B<<272.0,161.0>-<276.0,194.0>-<283.0,235.0>> = 13.493171774202695

	* W (U+0057): B<<470.0,447.0>-<464.0,481.0>-<462.0,507.0>>/B<<462.0,507.0>-<460.0,484.0>-<454.5,450.0>> = 9.368446083105818

	* W (U+0057): B<<639.0,233.0>-<646.0,192.0>-<650.0,161.0>>/B<<650.0,161.0>-<652.0,187.0>-<658.0,222.0>> = 11.751084714887869

	* Wacute (U+1E82): B<<263.0,223.5>-<269.0,187.0>-<272.0,161.0>>/B<<272.0,161.0>-<276.0,194.0>-<283.0,235.0>> = 13.493171774202695

	* Wacute (U+1E82): B<<470.0,447.0>-<464.0,481.0>-<462.0,507.0>>/B<<462.0,507.0>-<460.0,484.0>-<454.5,450.0>> = 9.368446083105818

	* Wacute (U+1E82): B<<639.0,233.0>-<646.0,192.0>-<650.0,161.0>>/B<<650.0,161.0>-<652.0,187.0>-<658.0,222.0>> = 11.751084714887869

	* Wcircumflex (U+0174): B<<263.0,223.5>-<269.0,187.0>-<272.0,161.0>>/B<<272.0,161.0>-<276.0,194.0>-<283.0,235.0>> = 13.493171774202695

	* Wcircumflex (U+0174): B<<470.0,447.0>-<464.0,481.0>-<462.0,507.0>>/B<<462.0,507.0>-<460.0,484.0>-<454.5,450.0>> = 9.368446083105818

	* Wcircumflex (U+0174): B<<639.0,233.0>-<646.0,192.0>-<650.0,161.0>>/B<<650.0,161.0>-<652.0,187.0>-<658.0,222.0>> = 11.751084714887869 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian-SemiCondensedExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiCondensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0543 (U+0543): L<<232.0,568.0>--<228.0,569.0>> -> L<<228.0,569.0>--<65.0,598.0>> 

	* And uniFB13 (U+FB13): L<<350.0,760.0>--<588.0,760.0>> -> L<<588.0,760.0>--<588.0,760.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian-SemiCondensedLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiCondensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni056E (U+056E): L<<160.0,672.0>--<161.0,673.0>> -> L<<161.0,673.0>--<265.0,768.0>>

	* uni0571 (U+0571): L<<383.0,0.0>--<383.0,0.0>> -> L<<383.0,0.0>--<383.0,0.0>> 

	* And uniFB13 (U+FB13): L<<368.0,760.0>--<607.0,760.0>> -> L<<607.0,760.0>--<607.0,760.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-SemiCondensedMedium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiCondensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0571 (U+0571): L<<401.0,0.0>--<401.0,0.0>> -> L<<401.0,0.0>--<401.0,0.0>>

	* uniFB13 (U+FB13): L<<414.0,760.0>--<648.0,760.0>> -> L<<648.0,760.0>--<648.0,760.0>> 

	* And uniFB13 (U+FB13): L<<798.0,550.0>--<798.0,549.0>> -> L<<798.0,549.0>--<798.0,536.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<438.0,536.0>-<433.0,563.0>-<431.0,583.0>>/B<<431.0,583.0>-<429.0,567.0>-<424.5,541.0>> = 12.835609486401424

	* Wacute (U+1E82): B<<438.0,536.0>-<433.0,563.0>-<431.0,583.0>>/B<<431.0,583.0>-<429.0,567.0>-<424.5,541.0>> = 12.835609486401424

	* Wcircumflex (U+0174): B<<438.0,536.0>-<433.0,563.0>-<431.0,583.0>>/B<<431.0,583.0>-<429.0,567.0>-<424.5,541.0>> = 12.835609486401424

	* Wdieresis (U+1E84): B<<438.0,536.0>-<433.0,563.0>-<431.0,583.0>>/B<<431.0,583.0>-<429.0,567.0>-<424.5,541.0>> = 12.835609486401424 

	* And Wgrave (U+1E80): B<<438.0,536.0>-<433.0,563.0>-<431.0,583.0>>/B<<431.0,583.0>-<429.0,567.0>-<424.5,541.0>> = 12.835609486401424 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansArmenian-SemiCondensedSemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiCondensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni053B (U+053B): L<<196.0,411.0>--<202.0,411.0>> -> L<<202.0,411.0>--<202.0,411.0>>

	* uni056E (U+056E): L<<180.0,644.0>--<183.0,646.0>> -> L<<183.0,646.0>--<337.0,770.0>>

	* uni0571 (U+0571): L<<408.0,0.0>--<408.0,0.0>> -> L<<408.0,0.0>--<408.0,0.0>> 

	* And uniFB13 (U+FB13): L<<431.0,760.0>--<660.0,760.0>> -> L<<660.0,760.0>--<660.0,760.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<446.5,507.5>-<441.0,537.0>-<439.0,559.0>>/B<<439.0,559.0>-<437.0,541.0>-<432.0,512.0>> = 11.534620653644708

	* W (U+0057): B<<615.5,221.5>-<625.0,170.0>-<630.0,130.0>>/B<<630.0,130.0>-<635.0,170.0>-<644.0,221.0>> = 14.25003269780357

	* Wacute (U+1E82): B<<446.5,507.5>-<441.0,537.0>-<439.0,559.0>>/B<<439.0,559.0>-<437.0,541.0>-<432.0,512.0>> = 11.534620653644708

	* Wacute (U+1E82): B<<615.5,221.5>-<625.0,170.0>-<630.0,130.0>>/B<<630.0,130.0>-<635.0,170.0>-<644.0,221.0>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<446.5,507.5>-<441.0,537.0>-<439.0,559.0>>/B<<439.0,559.0>-<437.0,541.0>-<432.0,512.0>> = 11.534620653644708

	* Wcircumflex (U+0174): B<<615.5,221.5>-<625.0,170.0>-<630.0,130.0>>/B<<630.0,130.0>-<635.0,170.0>-<644.0,221.0>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<446.5,507.5>-<441.0,537.0>-<439.0,559.0>>/B<<439.0,559.0>-<437.0,541.0>-<432.0,512.0>> = 11.534620653644708

	* Wdieresis (U+1E84): B<<615.5,221.5>-<625.0,170.0>-<630.0,130.0>>/B<<630.0,130.0>-<635.0,170.0>-<644.0,221.0>> = 14.25003269780357

	* Wgrave (U+1E80): B<<446.5,507.5>-<441.0,537.0>-<439.0,559.0>>/B<<439.0,559.0>-<437.0,541.0>-<432.0,512.0>> = 11.534620653644708 

	* And Wgrave (U+1E80): B<<615.5,221.5>-<625.0,170.0>-<630.0,130.0>>/B<<630.0,130.0>-<635.0,170.0>-<644.0,221.0>> = 14.25003269780357 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian-SemiCondensedThin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian SemiCondensed Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<122.0,714.0>--<119.0,173.0>>

	* exclam (U+0021): L<<95.0,173.0>--<92.0,714.0>>

	* exclamdown (U+00A1): L<<117.0,353.0>--<120.0,-189.0>>

	* exclamdown (U+00A1): L<<91.0,-189.0>--<93.0,353.0>> 

	* And p (U+0070): L<<105.0,528.0>--<106.0,403.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NotoSansArmenian-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Armenian Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>> 

	* And exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansArmenian[wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>💔 <b>ERROR:</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT/gf-axisregistry">com.google.fonts/check/STAT/gf-axisregistry</a>)</summary><div>


* 💔 **ERROR** Failed with AttributeError: 'NoneType' object has no attribute 'toUnicode'
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansArmenian/googlefonts/slim-variable-ttf/NotoSansArmenian[wght].ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Black.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Bold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Condensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-CondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-ExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Light.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Medium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Regular.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensed.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBlack.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedExtraLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedLight.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedMedium.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedSemiBold.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-SemiCondensedThin.ttf', 'fonts/NotoSansArmenian/googlefonts/ttf/NotoSansArmenian-Thin.ttf', 'fonts/NotoSansArmenian/googlefonts/variable-ttf/NotoSansArmenian[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx-roundtrip">com.google.fonts/check/ttx-roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 288 missing from name table
* 🔥 **FAIL** name id 270 missing from name table
* 🔥 **FAIL** name id 279 missing from name table
* 🔥 **FAIL** name id 258 missing from name table
* 🔥 **FAIL** name id 259 missing from name table
* 🔥 **FAIL** name id 260 missing from name table
* 🔥 **FAIL** name id 261 missing from name table
* 🔥 **FAIL** name id 262 missing from name table
* 🔥 **FAIL** name id 263 missing from name table
* 🔥 **FAIL** name id 264 missing from name table
* 🔥 **FAIL** name id 265 missing from name table
* 🔥 **FAIL** name id 266 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 334. [code: invalid-default-instance-subfamily-nameid:334]
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

	- And uni057E + uni0576 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Checking with ots-sanitize. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ots">com.google.fonts/check/ots</a>)</summary><div>


* ⚠ **WARN** ots-sanitize passed this file, however warnings were printed:

ERROR: STAT: Invalid nameID: 288
ERROR: Table discarded
 [code: ots-sanitize-warn]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 39 | 113 | 341 | 4478 | 255 | 3149 | 0 |
| 0% | 1% | 4% | 53% | 3% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
