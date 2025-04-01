## FontBakery report

fontbakery version: 0.13.2





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Fedorovsk-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- uni04860300 (U+E003)</p>
<pre><code>- uni04860301 (U+E001)

- uni04860311 (U+E005)

- uni20DD (U+20DD)

- uni2DE00487 (U+F4E0)

- uni2DE10487 (U+F4E1)

- uni2DE20487 (U+F4E2)

- uni2DE60487 (U+F4E6)

- uni2DE70487 (U+F4E7)

- uni2DE90487 (U+F4E9)

- uni2DEA0487 (U+F4EA)

- uni2DEB0487 (U+F4EB)

- uni2DEC0487 (U+F4EC)

- uni2DED0487 (U+F4ED)

- uni2DF00487 (U+F4EF)

- uni2DF10487 (U+F4F1)

- uni2DF20487 (U+F4F2)

- uni2DF30487 (U+F4F3)

- uni2DFD0487 (U+F4FD)

- uniA671 (U+A671)
</code></pre>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[19] Fedorovsk-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1115, but got 1055 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 517, but got 385 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ҁ, ꙃ, Ҁ, Ꙃ</td>
<td align="left">cu_Cyrl (Church Slavic)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00A1 (INVERTED EXCLAMATION MARK)


- 0x00A2 (CENT SIGN)


- 0x00A3 (POUND SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A8 (DIAERESIS)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AE (REGISTERED SIGN)


- 0x00AF (MACRON)


- 0x00B8 (CEDILLA)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x00BF (INVERTED QUESTION MARK)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F7 (DIVISION SIGN)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0304 (COMBINING MACRON)


- 0x030A (COMBINING RING ABOVE)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x201A (SINGLE LOW-9 QUOTATION MARK)


- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


- 0x2026 (HORIZONTAL ELLIPSIS)


- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni0303 (U+0303), uniFE00 (U+FE00), uniFE01 (U+FE01), uniFE02 (U+FE02) and uniFE03 (U+FE03)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-spacing-marks">opentype/gdef_spacing_marks</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs seem to be spacing (because they have width &gt; 0 on the hmtx table) so they may be in the GDEF mark glyph class by mistake, or they should have zero width instead:
uni0488 (U+0488), uni0489 (U+0489), uni2DE3A675 (U+F0023), uni2DE42DF7 (U+F0030), uni2DEEA675 (U+F00AF), uniA670 (U+A670) and uniA672 (U+A672)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni002A	Contours detected: 2	Expected: 1 or 4

- Glyph name: uni0435	Contours detected: 1	Expected: 2

- Glyph name: uni0436	Contours detected: 2	Expected: 1

- Glyph name: uni043A	Contours detected: 2	Expected: 1

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 3	Expected: 4

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: uni045C	Contours detected: 3	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni0473	Contours detected: 2	Expected: 3

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

- Glyph name: uni0435	Contours detected: 1	Expected: 2

- Glyph name: uni0436	Contours detected: 2	Expected: 1

- Glyph name: uni043A	Contours detected: 2	Expected: 1

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 3	Expected: 4

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: uni045C	Contours detected: 3	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni0473	Contours detected: 2	Expected: 3

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 887 among a set of 4 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 406:
uni002B</p>
<p>Width = 690:
uni003E, uni003C</p>
<p>Width = 394:
uni003D</p>
<p>Width = 575:
uni00AC</p>
<p>Width = 390:
uni2214, uni2213</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* uni0026 (U+0026): L&lt;&lt;108.0,487.0&gt;--&lt;108.0,488.0&gt;&gt; has the same coordinates as a previous segment.

* uni0026 (U+0026): B&lt;&lt;108.0,488.0&gt;-&lt;108.0,488.0&gt;-&lt;108.0,488.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#stylisticset-description">stylisticset_description</a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss02 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, canadian-aboriginal, tai-le, todhri, duployan, hebrew, coptic, tifinagh, syriac, malayalam, old-permic</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: coptic, todhri</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+0358 COMBINING DOT ABOVE RIGHT: try adding osage</li>
<li>U+10FB GEORGIAN PARAGRAPH SEPARATOR: try adding one of: georgian, glagolitic</li>
<li>U+1DF6 COMBINING KAVYKA ABOVE RIGHT: not included in any glyphset definition</li>
<li>U+1DF7 COMBINING KAVYKA ABOVE LEFT: not included in any glyphset definition</li>
<li>U+1DF8 COMBINING DOT ABOVE LEFT: try adding syriac</li>
<li>U+1DF9 COMBINING WIDE INVERTED BRIDGE BELOW: not included in any glyphset definition</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: chakma, khudawadi, tibetan, gunjala-gondi, oriya, duployan, cham, hebrew, rejang, syloti-nagri, kharoshthi, yi, masaram-gondi, meetei-mayek, telugu, psalter-pahlavi, warang-citi, dogra, manichaean, gurmukhi, tai-viet, avestan, limbu, mandaic, saurashtra, lepcha, hatran, mongolian, newa, hanifi-rohingya, grantha, buhid, modi, arabic, tifinagh, batak, kayah-li, tai-le, tai-tham, thaana, bengali, tagbanwa, thai, devanagari, sharada, tirhuta, balinese, hanunoo, javanese, khmer, myanmar, siddham, syriac, brahmi, takri, bhaiksuki, sundanese, gujarati, buginese, kannada, khojki, sinhala, tagalog, kaithi, phags-pa, nko, tamil, mahajani, zanabazar-square, lao, new-tai-lue, sogdian, malayalam, pahawh-hmong</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: chakma, khudawadi, tibetan, gunjala-gondi, oriya, duployan, cham, hebrew, rejang, syloti-nagri, kharoshthi, yi, masaram-gondi, meetei-mayek, telugu, psalter-pahlavi, warang-citi, dogra, manichaean, gurmukhi, tai-viet, avestan, limbu, mandaic, saurashtra, lepcha, mongolian, newa, hanifi-rohingya, grantha, buhid, modi, old-hungarian, arabic, tifinagh, batak, kayah-li, tai-le, tai-tham, thaana, bengali, tagbanwa, thai, devanagari, sharada, tirhuta, balinese, hanunoo, javanese, khmer, myanmar, siddham, syriac, brahmi, takri, bhaiksuki, sundanese, gujarati, buginese, kannada, khojki, sinhala, tagalog, kaithi, phags-pa, nko, tamil, mahajani, zanabazar-square, lao, new-tai-lue, sogdian, malayalam, pahawh-hmong</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: thaana, hebrew, phags-pa, nko, syriac, arabic</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: thaana, hebrew, phags-pa, nko, syriac</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: yi, syloti-nagri, arabic</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2053 SWUNG DASH: try adding coptic</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205C DOTTED CROSS: not included in any glyphset definition</li>
<li>U+205D TRICOLON: try adding one of: carian, meroitic, old-hungarian, meroitic-hieroglyphs</li>
<li>U+205E VERTICAL FOUR DOTS: try adding old-hungarian</li>
<li>U+20DD COMBINING ENCLOSING CIRCLE: try adding symbols</li>
<li>U+2213 MINUS-OR-PLUS SIGN: try adding math</li>
<li>U+2214 DOT PLUS: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: math, yi, symbols, tai-tham</li>
<li>U+223B HOMOTHETIC: try adding math</li>
<li>U+223C TILDE OPERATOR: try adding math</li>
<li>U+223D REVERSED TILDE: try adding math</li>
<li>U+2241 NOT TILDE: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: khudawadi, tibetan, hebrew, miao, meetei-mayek, gurmukhi, coptic, wancho, mongolian, buhid, math, batak, thaana, tirhuta, tagbanwa, devanagari, balinese, hanunoo, takri, tifinagh, siddham, yi, sundanese, gujarati, buginese, sinhala, kaithi, phags-pa, mahajani, psalter-pahlavi, pahawh-hmong, oriya, cham, syloti-nagri, caucasian-albanian, mandaic, symbols, grantha, thai, myanmar, brahmi, bhaiksuki, tagalog, nko, tamil, armenian, sogdian, malayalam, chakma, duployan, ahom, telugu, old-permic, warang-citi, manichaean, tai-viet, limbu, music, saurashtra, lepcha, hanifi-rohingya, modi, osage, kayah-li, soyombo, tai-le, tai-tham, bengali, javanese, khmer, kannada, canadian-aboriginal, khojki, syriac, gunjala-gondi, rejang, mende-kikakui, kharoshthi, adlam, dogra, marchen, newa, elbasan, sharada, bassa-vah, zanabazar-square, lao, new-tai-lue, masaram-gondi</li>
<li>U+2626 ORTHODOX CROSS: try adding symbols</li>
<li>U+271A HEAVY GREEK CROSS: try adding symbols</li>
<li>U+2720 MALTESE CROSS: try adding symbols</li>
<li>U+2734 EIGHT POINTED BLACK STAR: try adding symbols</li>
<li>U+29DF DOUBLE-ENDED MULTIMAP: try adding math</li>
<li>U+2E2A TWO DOTS OVER ONE DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2B ONE DOT OVER TWO DOTS PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2C SQUARED FOUR DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2D FIVE DOT MARK: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E34 RAISED COMMA: try adding coptic</li>
<li>U+2E43 DASH WITH LEFT UPTURN: try adding glagolitic</li>
<li>U+2E45 INVERTED LOW KAVYKA: not included in any glyphset definition</li>
<li>U+2E46 INVERTED LOW KAVYKA WITH KAVYKA ABOVE: not included in any glyphset definition</li>
<li>U+2E47 LOW KAVYKA: not included in any glyphset definition</li>
<li>U+2E48 LOW KAVYKA WITH DOT: not included in any glyphset definition</li>
<li>U+2E49 DOUBLE STACKED COMMA: not included in any glyphset definition</li>
<li>U+E001 : not included in any glyphset definition</li>
<li>U+E003 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
<li>U+E0E0 : not included in any glyphset definition</li>
<li>U+E0E1 : not included in any glyphset definition</li>
<li>U+E0E2 : not included in any glyphset definition</li>
<li>U+E0E3 : not included in any glyphset definition</li>
<li>U+E0E4 : not included in any glyphset definition</li>
<li>U+E0E5 : not included in any glyphset definition</li>
<li>U+E0E6 : not included in any glyphset definition</li>
<li>U+E0E7 : not included in any glyphset definition</li>
<li>U+E0E8 : not included in any glyphset definition</li>
<li>U+E0E9 : not included in any glyphset definition</li>
<li>U+E0EA : not included in any glyphset definition</li>
<li>U+E0EB : not included in any glyphset definition</li>
<li>U+E0EC : not included in any glyphset definition</li>
<li>U+E0ED : not included in any glyphset definition</li>
<li>U+E0EE : not included in any glyphset definition</li>
<li>U+E0EF : not included in any glyphset definition</li>
<li>U+E16E : not included in any glyphset definition</li>
<li>U+E1A5 : not included in any glyphset definition</li>
<li>U+E3F0 : not included in any glyphset definition</li>
<li>U+E3F1 : not included in any glyphset definition</li>
<li>U+E407 : not included in any glyphset definition</li>
<li>U+E540 : not included in any glyphset definition</li>
<li>U+E5B1 : not included in any glyphset definition</li>
<li>U+E5D0 : not included in any glyphset definition</li>
<li>U+E5D1 : not included in any glyphset definition</li>
<li>U+E5D2 : not included in any glyphset definition</li>
<li>U+E5D3 : not included in any glyphset definition</li>
<li>U+E5D6 : not included in any glyphset definition</li>
<li>U+E5D7 : not included in any glyphset definition</li>
<li>U+E5D8 : not included in any glyphset definition</li>
<li>U+E612 : not included in any glyphset definition</li>
<li>U+E613 : not included in any glyphset definition</li>
<li>U+E714 : not included in any glyphset definition</li>
<li>U+E715 : not included in any glyphset definition</li>
<li>U+E7B4 : not included in any glyphset definition</li>
<li>U+E800 : not included in any glyphset definition</li>
<li>U+E8E0 : not included in any glyphset definition</li>
<li>U+E8E1 : not included in any glyphset definition</li>
<li>U+E8E2 : not included in any glyphset definition</li>
<li>U+E8E3 : not included in any glyphset definition</li>
<li>U+E8E4 : not included in any glyphset definition</li>
<li>U+E8E5 : not included in any glyphset definition</li>
<li>U+E8E6 : not included in any glyphset definition</li>
<li>U+E8E7 : not included in any glyphset definition</li>
<li>U+E8E8 : not included in any glyphset definition</li>
<li>U+E8E9 : not included in any glyphset definition</li>
<li>U+E8EA : not included in any glyphset definition</li>
<li>U+E8EB : not included in any glyphset definition</li>
<li>U+E8EC : not included in any glyphset definition</li>
<li>U+E8ED : not included in any glyphset definition</li>
<li>U+E8EE : not included in any glyphset definition</li>
<li>U+E8EF : not included in any glyphset definition</li>
<li>U+E8F0 : not included in any glyphset definition</li>
<li>U+E900 : not included in any glyphset definition</li>
<li>U+E901 : not included in any glyphset definition</li>
<li>U+E902 : not included in any glyphset definition</li>
<li>U+E903 : not included in any glyphset definition</li>
<li>U+E904 : not included in any glyphset definition</li>
<li>U+E905 : not included in any glyphset definition</li>
<li>U+E906 : not included in any glyphset definition</li>
<li>U+E907 : not included in any glyphset definition</li>
<li>U+E909 : not included in any glyphset definition</li>
<li>U+E90A : not included in any glyphset definition</li>
<li>U+E90B : not included in any glyphset definition</li>
<li>U+E90C : not included in any glyphset definition</li>
<li>U+E90D : not included in any glyphset definition</li>
<li>U+E92A : not included in any glyphset definition</li>
<li>U+E92B : not included in any glyphset definition</li>
<li>U+E930 : not included in any glyphset definition</li>
<li>U+E931 : not included in any glyphset definition</li>
<li>U+EC45 : not included in any glyphset definition</li>
<li>U+EC46 : not included in any glyphset definition</li>
<li>U+EC47 : not included in any glyphset definition</li>
<li>U+EC48 : not included in any glyphset definition</li>
<li>U+EC49 : not included in any glyphset definition</li>
<li>U+EC4A : not included in any glyphset definition</li>
<li>U+EC4B : not included in any glyphset definition</li>
<li>U+EC50 : not included in any glyphset definition</li>
<li>U+ED17 : not included in any glyphset definition</li>
<li>U+F4E0 : not included in any glyphset definition</li>
<li>U+F4E1 : not included in any glyphset definition</li>
<li>U+F4E2 : not included in any glyphset definition</li>
<li>U+F4E6 : not included in any glyphset definition</li>
<li>U+F4E7 : not included in any glyphset definition</li>
<li>U+F4E9 : not included in any glyphset definition</li>
<li>U+F4EA : not included in any glyphset definition</li>
<li>U+F4EB : not included in any glyphset definition</li>
<li>U+F4EC : not included in any glyphset definition</li>
<li>U+F4ED : not included in any glyphset definition</li>
<li>U+F4EF : not included in any glyphset definition</li>
<li>U+F4F1 : not included in any glyphset definition</li>
<li>U+F4F2 : not included in any glyphset definition</li>
<li>U+F4F3 : not included in any glyphset definition</li>
<li>U+F4FD : not included in any glyphset definition</li>
<li>U+FE00 VARIATION SELECTOR-1: try adding one of: yi, manichaean, phags-pa</li>
<li>U+FE01 VARIATION SELECTOR-2: not included in any glyphset definition</li>
<li>U+FE02 VARIATION SELECTOR-3: not included in any glyphset definition</li>
<li>U+FE03 VARIATION SELECTOR-4: not included in any glyphset definition</li>
<li>U+FE26 COMBINING CONJOINING MACRON: try adding one of: coptic, caucasian-albanian</li>
<li>U+1F540 CIRCLED CROSS POMMEE: try adding symbols</li>
<li>U+1F541 CROSS POMMEE WITH HALF-CIRCLE BELOW: try adding symbols</li>
<li>U+1F542 CROSS POMMEE: try adding symbols</li>
<li>U+1F543 NOTCHED LEFT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F544 NOTCHED RIGHT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F545 SYMBOL FOR MARKS CHAPTER: try adding symbols</li>
<li>U+1F908 DOWNWARD FACING HOOK: try adding symbols</li>
<li>U+1F909 DOWNWARD FACING NOTCHED HOOK: try adding symbols</li>
<li>U+1F90A DOWNWARD FACING HOOK WITH DOT: try adding symbols</li>
<li>U+1F90B DOWNWARD FACING NOTCHED HOOK WITH DOT: try adding symbols</li>
<li>U+F0023 : not included in any glyphset definition</li>
<li>U+F0030 : not included in any glyphset definition</li>
<li>U+F00AF : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̋ j̀ j́ j̃ j̈ j̑ і́</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ì í î ĩ ĭ i̇ ȉ ȋ i̾ i҃ i҄ i҅ i҆ i҇ iⷠ iⷡ iⷢ iⷣ iⷤ iⷥ</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* u1f545.alt1 (U+E5D0): L&lt;&lt;510.0,802.0&gt;--&lt;485.0,778.0&gt;&gt; -&gt; L&lt;&lt;485.0,778.0&gt;--&lt;465.0,761.0&gt;&gt;

* u1f545.alt2 (U+E5D1): L&lt;&lt;269.0,462.0&gt;--&lt;271.0,653.0&gt;&gt; -&gt; L&lt;&lt;271.0,653.0&gt;--&lt;271.0,659.0&gt;&gt;

* uni005A (U+005A): L&lt;&lt;187.0,38.0&gt;--&lt;189.0,38.0&gt;&gt; -&gt; L&lt;&lt;189.0,38.0&gt;--&lt;382.0,42.0&gt;&gt;

* uni0414 (U+0414): L&lt;&lt;365.0,-35.0&gt;--&lt;353.0,9.0&gt;&gt; -&gt; L&lt;&lt;353.0,9.0&gt;--&lt;341.0,59.0&gt;&gt;

* uni0458 (U+0458): L&lt;&lt;-45.0,-248.0&gt;--&lt;-89.0,-244.0&gt;&gt; -&gt; L&lt;&lt;-89.0,-244.0&gt;--&lt;-100.0,-244.0&gt;&gt;

* uni0458 (U+0458): L&lt;&lt;122.0,388.0&gt;--&lt;148.0,388.0&gt;&gt; -&gt; L&lt;&lt;148.0,388.0&gt;--&lt;191.0,390.0&gt;&gt;

* uni0458 (U+0458): L&lt;&lt;148.0,388.0&gt;--&lt;191.0,390.0&gt;&gt; -&gt; L&lt;&lt;191.0,390.0&gt;--&lt;202.0,390.0&gt;&gt;

* uni0458 (U+0458): L&lt;&lt;43.0,-258.0&gt;--&lt;-45.0,-248.0&gt;&gt; -&gt; L&lt;&lt;-45.0,-248.0&gt;--&lt;-89.0,-244.0&gt;&gt;

* uni045F (U+045F): L&lt;&lt;287.0,175.0&gt;--&lt;288.0,194.0&gt;&gt; -&gt; L&lt;&lt;288.0,194.0&gt;--&lt;288.0,259.0&gt;&gt;

* uni0471 (U+0471): L&lt;&lt;216.0,-306.0&gt;--&lt;216.0,-150.0&gt;&gt; -&gt; L&lt;&lt;216.0,-150.0&gt;--&lt;222.0,15.0&gt;&gt;

* uni0471 (U+0471): L&lt;&lt;287.0,14.0&gt;--&lt;284.0,-164.0&gt;&gt; -&gt; L&lt;&lt;284.0,-164.0&gt;--&lt;280.0,-245.0&gt;&gt;

* uni0471.short (U+E0ED): L&lt;&lt;216.0,-306.0&gt;--&lt;216.0,-150.0&gt;&gt; -&gt; L&lt;&lt;216.0,-150.0&gt;--&lt;222.0,15.0&gt;&gt;

* uni0471.short (U+E0ED): L&lt;&lt;287.0,14.0&gt;--&lt;284.0,-164.0&gt;&gt; -&gt; L&lt;&lt;284.0,-164.0&gt;--&lt;280.0,-245.0&gt;&gt;

* uni0491.alt (U+E16E): L&lt;&lt;173.0,585.0&gt;--&lt;261.0,575.0&gt;&gt; -&gt; L&lt;&lt;261.0,575.0&gt;--&lt;305.0,571.0&gt;&gt;

* uni0491.alt (U+E16E): L&lt;&lt;261.0,575.0&gt;--&lt;305.0,571.0&gt;&gt; -&gt; L&lt;&lt;305.0,571.0&gt;--&lt;316.0,571.0&gt;&gt;

* uni0491.alt (U+E16E): L&lt;&lt;94.0,-61.0&gt;--&lt;93.0,-61.0&gt;&gt; -&gt; L&lt;&lt;93.0,-61.0&gt;--&lt;68.0,-60.0&gt;&gt;

* uni1C86 (U+1C86): L&lt;&lt;-202.0,553.0&gt;--&lt;-226.0,557.0&gt;&gt; -&gt; L&lt;&lt;-226.0,557.0&gt;--&lt;-245.0,562.0&gt;&gt;

* uni2DE4 (U+2DE4): L&lt;&lt;-84.0,672.0&gt;--&lt;-100.0,676.0&gt;&gt; -&gt; L&lt;&lt;-100.0,676.0&gt;--&lt;-134.0,686.0&gt;&gt;

* uni2DE42DF7 (U+F0030): L&lt;&lt;-16.0,598.0&gt;--&lt;0.0,606.0&gt;&gt; -&gt; L&lt;&lt;0.0,606.0&gt;--&lt;13.0,614.0&gt;&gt;

* uni2DF7 (U+2DF7): L&lt;&lt;-91.0,527.0&gt;--&lt;-77.0,536.0&gt;&gt; -&gt; L&lt;&lt;-77.0,536.0&gt;--&lt;-67.0,543.0&gt;&gt;

* uniA641.trunc (U+E0E0): L&lt;&lt;276.0,302.0&gt;--&lt;297.0,311.0&gt;&gt; -&gt; L&lt;&lt;297.0,311.0&gt;--&lt;313.0,319.0&gt;&gt;

* uniFE2E (U+FE2E): L&lt;&lt;-155.0,723.0&gt;--&lt;-151.0,698.0&gt;&gt; -&gt; L&lt;&lt;-151.0,698.0&gt;--&lt;-147.0,672.0&gt;&gt;

* uniFE2F (U+FE2F): L&lt;&lt;-398.0,662.0&gt;--&lt;-397.0,682.0&gt;&gt; -&gt; L&lt;&lt;-397.0,682.0&gt;--&lt;-397.0,713.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni0405 (U+0405): B&lt;&lt;563.5,165.0&gt;-&lt;560.0,188.0&gt;-&lt;551.0,202.0&gt;&gt;/B&lt;&lt;551.0,202.0&gt;-&lt;552.0,200.0&gt;-&lt;551.5,200.5&gt;&gt; = 6.170175095029526

* uni1C84 (U+1C84): B&lt;&lt;215.5,16.5&gt;-&lt;220.0,5.0&gt;-&lt;224.0,0.0&gt;&gt;/B&lt;&lt;224.0,0.0&gt;-&lt;219.0,4.0&gt;-&lt;203.0,4.0&gt;&gt; = 12.680383491819796
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u1f545.alt2 (U+E5D1): L&lt;&lt;172.0,761.0&gt;--&lt;173.0,450.0&gt;&gt;

* u1f545.alt2 (U+E5D1): L&lt;&lt;173.0,404.0&gt;--&lt;175.0,0.0&gt;&gt;

* u1f545.alt2 (U+E5D1): L&lt;&lt;690.0,761.0&gt;--&lt;691.0,438.0&gt;&gt;

* u1f545.alt2 (U+E5D1): L&lt;&lt;691.0,341.0&gt;--&lt;692.0,0.0&gt;&gt;

* uni004E (U+004E): L&lt;&lt;556.0,185.0&gt;--&lt;554.0,514.0&gt;&gt;

* uni0054 (U+0054): L&lt;&lt;350.0,504.0&gt;--&lt;352.0,124.0&gt;&gt;

* uni0065 (U+0065): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* uni00D1 (U+00D1): L&lt;&lt;556.0,185.0&gt;--&lt;554.0,514.0&gt;&gt;

* uni00E8 (U+00E8): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* uni00E9 (U+00E9): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* uni00EA (U+00EA): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* uni00EB (U+00EB): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID is 'PfEd', a font editor default. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: bad]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 5 | 15 | 109 | 7 | 100 | 0 | 
| 0% | 0% | 2% | 6% | 46% | 3% | 42% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
