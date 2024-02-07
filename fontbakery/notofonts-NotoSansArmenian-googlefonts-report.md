## FontBakery report

fontbakery version: 0.11.1

<h2>Check results</h2><details><summary><b>[13] NotoSansArmenian[wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 💔 **ERROR** Failed with AttributeError: 'Vharfbuzz' object has no attribute 'ttfont'
```
  File "/home/runner/work/armenian/armenian/venv/lib/python3.11/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
                   ^^^^^^^^^^^^
  File "/home/runner/work/armenian/armenian/venv/lib/python3.11/site-packages/fontbakery/profiles/googlefonts.py", line 3537, in com_google_fonts_check_glyphsets_shape_languages
    shaperglot_checker = Checker(ttFont.reader.file.name)
                         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/runner/work/armenian/armenian/venv/lib/python3.11/site-packages/shaperglot/checker.py", line 23, in __init__
    self.ttfont = self.vharfbuzz.ttfont
                  ^^^^^^^^^^^^^^^^^^^^^

``` [code: failed-check]
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with AttributeError: 'Vharfbuzz' object has no attribute 'ttfont'
```
  File "/home/runner/work/armenian/armenian/venv/lib/python3.11/site-packages/fontbakery/checkrunner.py", line 170, in _exec_check
    results.extend(list(result))
                   ^^^^^^^^^^^^
  File "/home/runner/work/armenian/armenian/venv/lib/python3.11/site-packages/fontbakery/profiles/shaping.py", line 726, in com_google_fonts_check_soft_dotted
    checker = Checker(ttFont.reader.file.name)
              ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/runner/work/armenian/armenian/venv/lib/python3.11/site-packages/shaperglot/checker.py", line 23, in __init__
    self.ttfont = self.vharfbuzz.ttfont
                  ^^^^^^^^^^^^^^^^^^^^^

``` [code: failed-check]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 2.008 is equal to version on **Google Fonts**.
* 🔥 **FAIL** Version number 2.008 is equal to version on google/fonts **GitHub repo**.
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0326

	- uni0327

	- uni0328 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, syriac, tifinagh, math, canadian-aboriginal, tai-le, old-permic, malayalam
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `armenian`, `cyrillic-ext`, `greek-ext`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider updating the url from 'https://scripts.sil.org/OFL' to 'https://openfontlicense.org'. [code: old-url]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* A
	* AE
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Cdotaccent
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Eth
	* Euro
	* F
	* G
	* Gbreve
	* Gdotaccent
	* H
	* Hbar
	* I
	* Iacute
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* J
	* K
	* L
	* Lacute
	* Lcaron
	* Lslash
	* M
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* O
	* OE
	* Oacute
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohungarumlaut
	* Omacron
	* Oslash
	* Otilde
	* P
	* Q
	* R
	* Racute
	* Rcaron
	* S
	* Sacute
	* Scaron
	* Scedilla
	* T
	* Tcaron
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Uring
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* a
	* aacute
	* abreve
	* acircumflex
	* acute
	* acutecomb
	* adieresis
	* ae
	* agrave
	* amacron
	* ampersand
	* aogonek
	* aring
	* asciicircum
	* asciitilde
	* asterisk
	* at
	* atilde
	* b
	* backslash
	* bar
	* braceleft
	* braceright
	* bracketleft
	* bracketright
	* breve
	* bullet
	* c
	* cacute
	* caron
	* ccaron
	* ccedilla
	* cdotaccent
	* cedilla
	* cent
	* circumflex
	* colon
	* comma
	* copyright
	* d
	* dcaron
	* dcroat
	* degree
	* dieresis
	* divide
	* dollar
	* dotaccent
	* dotlessi
	* e
	* eacute
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* ellipsis
	* emacron
	* emdash
	* endash
	* eng
	* eogonek
	* equal
	* eth
	* exclam
	* exclamdown
	* f
	* five
	* four
	* g
	* gbreve
	* gdotaccent
	* germandbls
	* grave
	* gravecomb
	* greater
	* guillemotleft
	* guillemotright
	* guilsinglleft
	* guilsinglright
	* h
	* hbar
	* hungarumlaut
	* i
	* iacute
	* icircumflex
	* idieresis
	* igrave
	* imacron
	* iogonek
	* j
	* k
	* l
	* lacute
	* lcaron
	* less
	* lslash
	* m
	* macronmod
	* multiply
	* n
	* nacute
	* ncaron
	* nine
	* ntilde
	* numbersign
	* o
	* oacute
	* ocircumflex
	* odieresis
	* oe
	* ogonek
	* ograve
	* ohungarumlaut
	* omacron
	* one
	* onedotenleader
	* ordfeminine
	* ordmasculine
	* oslash
	* otilde
	* overscore
	* p
	* paragraph
	* parenleft
	* parenright
	* percent
	* period
	* periodcentered
	* plus
	* q
	* question
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* quoteleft
	* quoteright
	* quotesinglbase
	* quotesingle
	* r
	* racute
	* rcaron
	* registered
	* ring
	* s
	* sacute
	* scaron
	* scedilla
	* section
	* semicolon
	* seven
	* six
	* slash
	* sterling
	* t
	* tcaron
	* thorn
	* three
	* tilde
	* tildecomb
	* two
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhungarumlaut
	* umacron
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni0302
	* uni0304
	* uni0306
	* uni0307
	* uni030A
	* uni030B
	* uni030C
	* uni0312
	* uni0327
	* uni0328
	* uni1E9E
	* uogonek
	* uring
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent and zero
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
</div></details><details><summary>⚠ <b>WARN:</b> Check that legacy accents aren't used in composite glyphs. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* ⚠ **WARN** Glyph "Aacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Abreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Acircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Agrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Aogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Aring" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Atilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Cacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ccaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ccedilla" has a legacy accent component  (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Cdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Dcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Eacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ecaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ecircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Edotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Egrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Eogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Gbreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Gdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Iacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Icircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Idotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Igrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Iogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Lacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Nacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ncaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ntilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Oacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ocircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ograve" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ohungarumlaut" has a legacy accent component  (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Otilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Racute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Rcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Sacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Scaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Scedilla" has a legacy accent component  (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Tcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Uacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ubreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ucircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ugrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Uhungarumlaut" has a legacy accent component  (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Uring" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Wacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Wcircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Wgrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Yacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ycircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ygrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Zacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Zcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Zdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "aacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "abreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "acircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "acutecomb" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "agrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "aogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "aring" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "atilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0306" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "cacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni030C" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ccaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ccedilla" has a legacy accent component  (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "cdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0327" has a legacy accent component  (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0302" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0307" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "eacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ecaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ecircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "edotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "egrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "gbreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "gdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "gravecomb" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni030B" has a legacy accent component  (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "iacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "icircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "igrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "iogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "lacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "nacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ncaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ntilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "oacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ocircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0328" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ograve" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ohungarumlaut" has a legacy accent component  (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "otilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "racute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "rcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni030A" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "sacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "scaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "scedilla" has a legacy accent component  (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "tildecomb" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ubreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ucircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ugrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uhungarumlaut" has a legacy accent component  (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uring" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "wacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "wcircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "wgrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "yacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ycircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ygrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "zacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "zcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "zdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 2 | 0 | 3 | 8 | 101 | 8 | 138 | 0 |
| 1% | 0% | 1% | 3% | 39% | 3% | 53% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
