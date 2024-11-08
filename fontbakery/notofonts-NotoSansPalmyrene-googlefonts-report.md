## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[9] NotoSansPalmyrene-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach acutecomb to uni0237</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansPalmyrene/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, todhri, malayalam, canadian-aboriginal, math, duployan, hebrew, tai-le, coptic, tifinagh, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>palmyrene</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ma’di (Latn, 584,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), South Central Banda (Latn, 244,000 speakers), Basaa (Latn, 332,940 speakers), Ngbaka (Latn, 1,020,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kaska (Latn, 125 speakers), Ekpeye (Latn, 226,000 speakers), Lugbara (Latn, 2,200,000 speakers), Dii (Latn, 71,000 speakers), Fur (Latn, 1,230,163 speakers), Zapotec (Latn, 490,000 speakers), Gulay (Latn, 250,478 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Southern Kisi (Latn, 360,000 speakers), Sar (Latn, 500,000 speakers), Koonzime (Latn, 40,000 speakers), Cicipu (Latn, 44,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Bafut (Latn, 158,146 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Dutch (Latn, 31,709,104 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers), Teke-Ebo (Latn, 260,000 speakers), Mango (Latn, 77,000 speakers), Heiltsuk (Latn, 300 speakers), Nzakara (Latn, 50,000 speakers), Yala (Latn, 200,000 speakers), Ejagham (Latn, 120,000 speakers), Avokaya (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Han (Latn, 6 speakers), Vute (Latn, 21,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* u10863 (U+10863): X=562.5,Y=-2.0 (should be at baseline 0?)

* u10864 (U+10864): X=248.0,Y=-2.0 (should be at baseline 0?)

* u10864 (U+10864): X=192.5,Y=1.0 (should be at baseline 0?)

* u10864 (U+10864): X=625.5,Y=-2.0 (should be at baseline 0?)

* u10865 (U+10865): X=456.0,Y=1.5 (should be at baseline 0?)

* u10866 (U+10866): X=213.5,Y=-1.5 (should be at baseline 0?)

* u1086A (U+1086A): X=184.5,Y=1.0 (should be at baseline 0?)

* u1086B (U+1086B): X=216.0,Y=-0.5 (should be at baseline 0?)

* u1086C (U+1086C): X=30.5,Y=2.0 (should be at baseline 0?)

* u1086F (U+1086F): X=173.5,Y=2.0 (should be at baseline 0?)

* u10870 (U+10870): X=44.5,Y=-1.5 (should be at baseline 0?)

* u10870 (U+10870): X=107.5,Y=0.5 (should be at baseline 0?)

* u10871 (U+10871): X=270.0,Y=-2.0 (should be at baseline 0?)

* u10871 (U+10871): X=209.5,Y=-1.0 (should be at baseline 0?)

* u10871 (U+10871): X=137.0,Y=1.5 (should be at baseline 0?)

* u10871 (U+10871): X=270.0,Y=-2.0 (should be at baseline 0?)

* u10873 (U+10873): X=509.0,Y=0.5 (should be at baseline 0?)

* u10874 (U+10874): X=562.5,Y=-2.0 (should be at baseline 0?)

* u1086E10864: X=248.0,Y=-2.0 (should be at baseline 0?)

* u1086E10864: X=192.5,Y=1.0 (should be at baseline 0?)

* u108711086B: X=216.0,Y=-0.5 (should be at baseline 0?)

* u108711086B: X=630.0,Y=-2.0 (should be at baseline 0?)

* u108711086B: X=569.5,Y=-1.5 (should be at baseline 0?)

* u108711086B: X=497.0,Y=0.5 (should be at baseline 0?)

* u1086C10876: X=585.0,Y=2.0 (should be at baseline 0?)

* u1087310863: X=1029.0,Y=0.5 (should be at baseline 0?)

* u1087310874: X=1029.0,Y=0.5 (should be at baseline 0?)

* G (U+0047): X=537.0,Y=-1.0 (should be at baseline 0?)

* Gbreve (U+011E): X=537.0,Y=-1.0 (should be at baseline 0?)

* uni0122 (U+0122): X=537.0,Y=-1.0 (should be at baseline 0?)

* Gdotaccent (U+0120): X=537.0,Y=-1.0 (should be at baseline 0?)

* uni1E9E (U+1E9E): X=326.5,Y=-1.5 (should be at baseline 0?)

* S (U+0053): X=136.0,Y=-1.0 (should be at baseline 0?)

* Sacute (U+015A): X=136.0,Y=-1.0 (should be at baseline 0?)

* Scaron (U+0160): X=136.0,Y=-1.0 (should be at baseline 0?)

* Scedilla (U+015E): X=136.0,Y=-1.0 (should be at baseline 0?)

* uni0218 (U+0218): X=136.0,Y=-1.0 (should be at baseline 0?)

* Uogonek (U+0172): X=447.0,Y=-1.0 (should be at baseline 0?)

* ae (U+00E6): X=710.5,Y=-1.5 (should be at baseline 0?)

* braceleft (U+007B): X=150.0,Y=1.0 (should be at baseline 0?)

* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

* e (U+0065): X=408.0,Y=-1.5 (should be at baseline 0?)

* eacute (U+00E9): X=408.0,Y=-1.5 (should be at baseline 0?)

* ecaron (U+011B): X=408.0,Y=-1.5 (should be at baseline 0?)

* ecircumflex (U+00EA): X=408.0,Y=-1.5 (should be at baseline 0?)

* edieresis (U+00EB): X=408.0,Y=-1.5 (should be at baseline 0?)

* edotaccent (U+0117): X=408.0,Y=-1.5 (should be at baseline 0?)

* egrave (U+00E8): X=408.0,Y=-1.5 (should be at baseline 0?)

* ellipsis (U+2026): X=177.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=90.0,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=439.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=352.0,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=700.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=613.0,Y=2.0 (should be at baseline 0?)

* emacron (U+0113): X=408.0,Y=-1.5 (should be at baseline 0?)

* Euro (U+20AC): X=468.5,Y=-0.5 (should be at baseline 0?)

* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

* germandbls (U+00DF): X=317.0,Y=-1.0 (should be at baseline 0?)

* i (U+0069): X=165.5,Y=639.0 (should be at x-height 640?)

* i (U+0069): X=93.0,Y=639.0 (should be at x-height 640?)

* j (U+006A): X=165.5,Y=639.0 (should be at x-height 640?)

* j (U+006A): X=93.0,Y=639.0 (should be at x-height 640?)

* oe (U+0153): X=791.0,Y=-1.5 (should be at baseline 0?)

* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?)

* question (U+003F): X=134.5,Y=2.0 (should be at baseline 0?)

* s (U+0073): X=123.5,Y=-1.0 (should be at baseline 0?)

* sacute (U+015B): X=123.5,Y=-1.0 (should be at baseline 0?)

* scaron (U+0161): X=123.5,Y=-1.0 (should be at baseline 0?)

* scedilla (U+015F): X=123.5,Y=-1.0 (should be at baseline 0?)

* uni0219 (U+0219): X=123.5,Y=-1.0 (should be at baseline 0?)

* three (U+0033): X=137.0,Y=-1.5 (should be at baseline 0?)

* w (U+0077): X=258.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=158.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=626.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=523.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=258.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=158.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=626.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=523.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=258.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=158.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=626.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=523.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=258.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=158.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=626.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=523.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=258.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=158.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=626.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=523.0,Y=1.0 (should be at baseline 0?)

* y (U+0079): X=217.0,Y=-2.0 (should be at baseline 0?)

* yacute (U+00FD): X=217.0,Y=-2.0 (should be at baseline 0?)

* ycircumflex (U+0177): X=217.0,Y=-2.0 (should be at baseline 0?)

* ydieresis (U+00FF): X=217.0,Y=-2.0 (should be at baseline 0?)

* ygrave (U+1EF3): X=217.0,Y=-2.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 2 | 7 | 118 | 6 | 118 | 0 | 
| 0% | 0% | 1% | 3% | 47% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
