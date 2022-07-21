# Changelog

## 2022-07-21, version 0.9.1

- Added single guillemets.
- Added inverted exclamation mark.
- Added inverted question mark.
- Breaking change: renamed Wd (Wide) to sWd (Semi Wide) for consistency with Martian Grotesk.
- Added `®`—registered trademark symbol.
- Added `™`—trademark symbol.
- Added `°`—degree symbol.
- Added metadata (License, License URL, Copyright, etc).
- Added `Ãã` (Atilde, atilde).
- Added `Ññ` (Ntilde, ntilde).
- Added `Õõ` (Otilde, otilde).
- Added `Áá` (Aacute, aacute).
- Added `Ćć` (Cacute, cacute).
- Added `Éé` (Eacute, eacute).
- Added `Íí` (Iacute, iacute).
- Added `Óó` (Oacute, oacute).
- Added `Úú` (Uacute, uacute).
- Added `Ýý` (Yacute, yacute).
- Fixed weight classes. Fixes #2.
- `Axis Mappings` on the font’s level → `Axis Location` on every instance.
- Added `Ää` (Adieresis, adieresis).
- Added `Ëë` (Edieresis, edieresis).
- Added `Ïï` (Idieresis, idieresis).
- Added `Öö` (Odieresis, odieresis).
- Added `Üü` (Udieresis, udieresis).
- Added `Ÿÿ` (Ydieresis, ydieresis).
- Added `Áá` (Agrave, agrave).
- Added `Éé` (Egrave, egrave).
- Added `Íí` (Igrave, igrave).
- Added `Óó` (Ograve, ograve).
- Added `Úú` (Ugrave, ugrave).
- Added `Ââ` (Acircumflex, acircumflex).
- Added `Êê` (Ecircumflex, ecircumflex).
- Added `Îî` (Icircumflex, icircumflex).
- Added `Ôô` (Ocircumflex, ocircumflex).
- Added `Ûû` (Ucircumflex, ucircumflex).
- Added `Čč` (Ccaron, ccaron).
- Added `Šš` (Scaron, scaron).
- Added `Çç` (Ccedilla, ccedilla).
- Added `Åå` (Aring, aring).
- Added `Øø` (Oslash, oslash).
- Added `Ææ` (AE, ae).
- Added `Œœ` (OE, oe).
- Added `ẞß` (Germandbls, germandbls).
- Removed Reserved Font Name (RFN) from the license. RFN requires any font derivative made by non-authors to be renamed. Removing RFN enables creating font subsets (removing unnecessary glyphs, in other words) for web purposes.
- Fixed the acute position for `Á` (Aacute).
- Fixed the grave position for `À` (Agrave).
- Added superscript numbers: `⁰¹²³⁴⁵⁶⁷⁸⁹`.
- Added ordinal indicators: `ª` and `º`.
- Added `Žž` (Zcaron, zcaron).
- Added `†` and `‡` (dagger and daggerdbl).
- Added `·` (periodcentered, also known as an interpunct, interpoint, and middle dot).
- Added nonbreakinghyphen.
- Martian Mono is available on Homebrew. Thanks to @y-nk and @miccal for this.
- Added detached diacritical marks: dieresis, acute, circumflex, cedilla, macron.
- Added non-breaking space (nbspace).
- Added soft hyphen (softhyphen).
- Added `¦` broken bar (brokenbar).
- Added `±` plus–minus sign (plusminus) and its case-sensitive version (plusminus.case).
- Added `¬` negation aka logical not sign (logicalnot).
- Added `‰` per mille aka per thousand sign (perthousand).
- Added `Āā` (Amacron, amacron).
- Added `Ēē` (Emacron, emacron).
- Added `Īī` (Imacron, imacron).
- Added `Ōō` (Omacron, omacron).
- Added `Ūū` (Umacron, umacron).
- Added `Ðð` (Eth, eth).  Special thanks to Siggi Odds, Sveinn Davíðsson, and Jökull Solberg.
- Added `Þþ` (Thorn, thorn).
- Added paragraph sign.
- Added `ƒ` aka florin sign (florin).
- Added `μ` aka micro sign aka mu (micro).
- Added fraction sign.
- Added denominators and numerators from 0 to 9.
- Added fractions: onehalf, onequarter, threequarters.
- Added scientific inferiors (`sinf`).

## 2022-03-28, version 0.9.0

- [Ampersands redesign](https://twitter.com/romanshamin_en/status/1477687473669091328): right leg ending, more natural contrast distribution.
- [New look of guillemets](https://twitter.com/romanshamin_en/status/1478044084782735367) that now look like goldfishes.
- [New look of section signs](https://twitter.com/romanshamin_en/status/1479523955081945089).
- [New look of copyright signs](https://twitter.com/romanshamin_en/status/1479884106410479623): more balanced.
- [New look of pound sterling](https://twitter.com/romanshamin_en/status/1480600396330643456).
- [Similarly thick strikethroughs](https://twitter.com/romanshamin_en/status/1480982576840187904) in all currencies.
- Rebalanced ALL glyphs with diagonals, e. g. `Kk`, `Vv`, and `Xx`.
- Revised the weight of `N`, and `E`.
- Revised proportions of `Kk`, `N`, `v` and `y`.
- [Implemented axis mapping](https://twitter.com/romanshamin_en/status/1489629883789713412). the weight coordinates now more correctly correspond to the 100—800 range, and likewise, the width coordinates to the 75—112.5% range. New coordinates comply with the `font-width` and `font-stretch` property specifications. Among other things, this update allows the use of keywords like `bold` or `condensed` in CSS.
- Expanded [braces, parens, and brackets](https://twitter.com/romanshamin_en/status/1489371033706668034).
- Decreased contrast for qoute-based signs: `,“”‘’`.
- Revised terminals’ thickness for `£CGS2356?§cegst`.
- Made math symbols (`+−×÷`) bigger.
- Rebalanced `<` and `>` according to new math symbols (`+−×÷`).
- Deleted Bk (Book) style.

## 2021-09-01, version 0.8.5

- New proportions and ink traps for `M` and `N`.
- New widths for hyphen, en dash, and em dash.
- Synced vertical positions for hyphens, dashes, and all current math operators: `<>+−×÷=≠~≈`.
- Added case-sensitive versions of hyphens, dashes, and math operators;
- Added an OpenType feature (calt): a hyphen, any dash, or any math operator would automatically rise to optical center when surrounded by numbers or uppercase;
- Made a case-sensitive version of a colon. Included it to the same automatic adapting feature. Added a special case for double colon, which occurs in  IPv6 addresses.
- Fixed switching cent and dollar signs to their torn versions in bold weights.
- Made bullets bigger.

## 2021-08-23, version 0.8.4

- Fixed bug with `Z`.

## 2021-08-19, version 0.8.3

- Revisited weights of all Latin lower and upper case glyphs.

## 2021-08-11, version 0.8.2

- Set percent variants as cv01 and cv02 features.
- Set weight class for Book as 350.


## 2021-08-04, version 0.8.1

- Added Bk (Book) and Lt (Light) styles.
- Added (`) — backtick / grave accent glyph.


## 2021-07-19, version 0.8.0

Early adopters release.