# ABC - POJ variants keyboard layout

This is a modification of the “ABC - Extended” keyboard layout for Mac OS X, to include diacritics and special characters used in Pe̍h-ōe-jī and related romanization systems for Southern Chinese languages. 

This layout was created in [Ukelele](https://software.sil.org/ukelele/) v3.5.5. 

## FAQ

1. How to install this keyboard layout?

   > Please refer to the Ukelele documentation for instruct ions on installing a keyboard layout. This keyboard layout is for Mac OS X only.

2. What keyboard is this compatible with?

   > This was developed and tested on a QWERTY ANSI MacBook Pro keyboard. Your mileage may vary.... 

3. Why is a special keyboard layout necessary?

   > Romanized Chinesee languages are usually typed with Latin alphabet keyboard layouts designed for other languages, typically English or Western European languages. However, historical romanization systems used several special characters and diacritics that are not implemented in most default keyboard layouts, a well known example being [o͘](https://en.wikipedia.org/wiki/O͘) (O with combining dot above right) in Pe̍h-ōe-jī. This layout replaces some key combinations in the “ABC - Extended” layout with others required for POJ and romanized Southern Chinese languages.

4. Why is it so complicated?

   > The keyboard layout is intended to support writing in as many different romanization systems as possible. The original motivation was to be able to transcribe romanized texts written in different systems without switching keyboard layouts or looking up special characters.

5. What fonts support these special characters and diacritics?

   > Most modern system fonts should support these diacritics. For a consistently designed font that supports a wide set of characters, consider one of the [SIL fonts](https://software.sil.org/fonts/) such as Doulos SIL or Andika. 

6. How can we add tone marks to characters that already have diacritics?

   > To add tone marks on characters that already have diacritics, use `alt-shift-` instead of `alt-` with the key combination for tones, after typing the character with diacritic. For example, to type `ṳ̂`, first type `alt-y, u` to produce `ṳ`, then type `alt-shift-r` to add the circumflex accent on top: `ṳ̂`.

Below are listings of key combinations to produce characters and diacritics not in the basic Latin alphabet for each romanization system.

## Pe̍h-ōe-jī (Hokkien)

Wikipedia: [Pe̍h-ōe-jī](https://en.wikipedia.org/wiki/Pe̍h-ōe-jī)

| POJ  | Key combination      | Category     |
| ---- | -------------------- | ------------ |
| ⁿ    | alt-t                | Nasalization |
| o͘    | alt-o                | Vowel        |
| O͘    | shift-o, alt-shift-o | Vowel        |
| ◌́    | alt-e, ◌             | Tone 上      |
| ◌̀    | alt-`, ◌             | Tone 陰去    |
| ◌̂    | alt-r, ◌             | Tone 陽平    |
| ◌̄    | alt-a, ◌             | Tone 陽去    |
| ◌̍    | alt-\, ◌             | Tone 陽入    |

## Tâi-uân Lô-má-jī (Hokkien)

Derived from Pe̍h-ōe-jī, promoted by the Taiwan Ministry of Education to write Tâi-gí.

Wikipedia: [Tâi-uân Lô-má-jī](https://en.wikipedia.org/wiki/Tâi-uân_Lô-má-jī_Phing-im_Hong-àn)

Special characters and diacritics in Tâi-lô compared to Pe̍h-ōe-jī:

* Same set of tone markers
* **oo** instead of **o͘**
* **nn** instead of **ⁿ**

## Pe̍h-ūe-jī (Teochew)

Used in dictionaries and romanized Bibles published by Presbyterian missionaries in Swatow, inspired by Hokkien Pe̍h-ōe-jī.

Wikipedia: [Pe̍h-ūe-jī](https://en.wikipedia.org/wiki/Teochew_Romanization) 

| PUJ  | Key combination | Category     |
| ---- | --------------- | ------------ |
| ⁿ    | alt-t           | Nasalization |
| ṳ    | alt-y, u        | Vowel        |
| ◌́    | alt-e, ◌        | Tone 陰上    |
| ◌̀    | alt-`, ◌        | Tone 陰去    |
| ◌̂    | alt-r, ◌        | Tone 陽平    |
| ◌̃    | alt-n, ◌        | Tone 陽上    |
| ◌̄    | alt-a, ◌        | Tone 陽去    |
| ◌̍    | alt-\, ◌        | Tone 陽入    |

## Fielde dictionary (Teochew)

Used in a dictionary for the Swatow dialect of Teochew, published by Baptist missionaries.

Wikisource: [Dictionary of the Swatow Dialect](https://en.wikisource.org/wiki/Dictionary_of_the_Swatow_dialect/Introduction) 

| Fielde | Key combination | Category |
| ------ | --------------- | -------- |
| ṳ      | alt-y, u        | Vowel    |
| o̤      | alt-y, o        | Vowel    |
| ◌́      | alt-e, ◌        | Tone     |
| ◌̀      | alt-`, ◌        | Tone     |
| ◌̂      | alt-r, ◌        | Tone     |
| ◌̆      | alt-b, ◌        | Tone     |
| ◌̄      | alt-a, ◌        | Tone     |
|        |                 |          |

## Tiê-tsiu Tsiánn-im Tsiánn-zi tshok-tsìn-huĕ (Teochew)

Modern system inspired by the Tâi-lô system for Taiwanese Hokkien, used primarily in online communities.

Website: [Tiê-tsiu Tsiánn-im Tsiánn-zi tshok-tsìn-huĕ](http://teochew.pw/)

Same set of tone diacritics as the Fielde system; all other characters are basic Latin.

## Diê⁵ziu¹ Pêng¹im¹

Published by the Guangdong Provincial education department in 1960, used in modern Teochew dictionaries and publications from mainland China, primarily to indicate pronunciation, rather than as a full writing system.

| Pêng¹im¹ | Key combination | Category |
| -------- | --------------- | -------- |
| ê        | alt-r, e        | Vowel    |
| ¹        | alt-r, 1        | Tone     |
| ²        | alt-r, 2 (etc.) | Tone     |

Tones in Pêng¹im¹ are indicated with numerals, which can be formatted as superscript for aesthetic reasons.

## Bàng-ûa-cê (Foochow)

Wikipedia: [Bàng-uâ-cê](https://en.wikipedia.org/wiki/Foochow_Romanized) 

| BUC  | Key combination | Category |
| ---- | --------------- | -------- |
| a̤    | alt-y, a        | Vowel    |
| o̤    | alt-y, o        | Vowel    |
| e̤    | alt-y, e        | Vowel    |
| ṳ    | alt-y, u        | Vowel    |
| ◌̆    | alt-b, ◌        | Tone     |
| ◌̄    | alt-a, ◌        | Tone     |
| ◌́    | alt-e, ◌        | Tone     |
| ◌̀    | alt-`, ◌        | Tone     |
| ◌̂    | alt-r, ◌        | Tone     |
|      |                 |          |

## Bǽh-oe-tu (Hainanese)

Wikipedia: [Bǽh-oe-tu](https://en.wikipedia.org/wiki/Hainan_Romanized) 

| BOT  | Key combination | Category |
| ---- | --------------- | -------- |
| æ    | alt-'           | Vowel    |
| o͘    | alt-o           | Vowel    |
| ◌̂    | alt-r, ◌        | Tone     |
| ◌́    | alt-e, ◌        | Tone     |
| ◌̀    | alt-`, ◌        | Tone     |
| ◌̄    | alt-a, ◌        | Tone     |
|      |                 |          |

## Gṳ̿ing-nǎing Lô̤-mǎ-cī (Kienning)

Wikipedia: [Gṳ̿ing-nǎing Lô̤-mǎ-cī](https://en.wikipedia.org/wiki/Kienning_Colloquial_Romanized)

| GNLMC | Key combination | Category |
| ----- | --------------- | -------- |
| e̤     | alt-y, e        | Vowel    |
| ṳ     | alt-y, u        | Vowel    |
| o̤     | alt-y, o        | Vowel    |
| a̤     | alt-y, a        | Vowel    |
| ◌́     | alt-e, ◌        | Tone     |
| ◌̂     | alt-r, ◌        | Tone     |
| ◌̌     | alt-v, ◌        | Tone     |
| ◌̿     | alt-d, ◌        | Tone     |
| ◌̄     | alt-a, ◌        | Tone     |
| ◌̆     | alt-b, ◌        | Tone     |
| ◌̀     | alt-`, ◌        | Tone     |

## Pha̍k-fa-sṳ (Hakka)

[Pha̍k-fa-sṳ](https://en.wikipedia.org/wiki/Pha̍k-fa-sṳ)

| PFS  | Key combination | Category |
| ---- | --------------- | -------- |
| ṳ    | alt-y, u        | Vowel    |
| ◌̂    | alt-r, ◌        | Tone     |
| ◌̀    | alt-`, ◌        | Tone     |
| ◌́    | alt-e, ◌        | Tone     |
| ◌̊    | alt-k, ◌        | Tone     |
| ◌̍    | alt-\, ◌        | Tone     |

## Báⁿ-uā-ci̍ (Hinghwa)

Wikipedia: [Báⁿ-uā-ci̍](https://en.wikipedia.org/wiki/Hinghwa_Romanized) 

| BUC  | Key combination | Category     |
| ---- | --------------- | ------------ |
| o̤    | alt-y, o        | Vowel        |
| a̤    | alt-y, a        | Vowel        |
| e̤    | alt-y, e        | Vowel        |
| ṳ    | alt-y, u        | Vowel        |
| ⁿ    | alt-t           | Nasalization |
| ◌̂    | alt-r, ◌        | Tone         |
| ◌̍    | alt-\, ◌        | Tone         |
| ◌́    | alt-e, ◌        | Tone         |
| ◌̄    | alt-a, ◌        | Tone         |
|      |                 |              |

## Pha̍k-oa-chhi (Nanchang Gan)

Wikipedia: [Pha̍k-oa-chhi](https://en.wikipedia.org/wiki/Pha̍k-oa-chhi_romanization) 

| POC  | Key combination | Category |
| ---- | --------------- | -------- |
| e̤    | alt-y, e        | Vowel    |
| ṳ    | alt-y, u        | Vowel    |
| ◌́    | alt-e, ◌        | Tone     |
| ◌̂    | alt-r, ◌        | Tone     |
| ◌̄    | alt-a, ◌        | Tone     |
| ◌̀    | alt-`, ◌        | Tone     |
| ◌̍    | alt-\, ◌        | Tone     |
|      |                 |          |

## Alternative input methods

[PhahTaigi POJ Keyboard](https://keyman.com/keyboards/taigi_poj) - Implemented in [Keyman](https://keyman.com), supported on multiple operating systems, but supports Hokkien/Taigi only, diacritics for other romanization systems not available.

[建寧府羅馬字輸入法](https://github.com/triehhoo/svnihua) - Implemented in [RIME](https://rime.im), supported on multiple operating systems, for Kienning/Min Bei romanization.