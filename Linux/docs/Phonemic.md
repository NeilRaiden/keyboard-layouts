# Keyboard layout: English (Phonemic)

This keyboard layout is designed to write in English phonemically using IPA symbols.

_If you are trying to build reflexes to learn Shavian QWERTY, but you feel intimidated by Shavian yet, then you may want to try this layout first._

**Important**: this layout (for Linux) requires you to copy the [XCompose](../XCompose) file and save it in your home directory as `$HOME/.XCompose`.  
Or, see the **XCompose** section at the bottom of this page.
This is because XKB does not allow to map more than a single Unicode code point to a key.

Notes:  

 * this layout lets you type 14 phonemes up to 3 Unicode code points per keystroke
 * the single-symbol code points are produced by layout defined in `/usr/share/X11/xkb/symbols/phonem`
 * and for the 2-3 symbols sequences this layout sends out Unicode points from unassigned range **U+FDD0-U+FDEF** (aka non-characters)
 * those non-characters are then converted by `~/.XCompose` to proper phoneme sequences
 * the XCompose file on some Linux distros does not convert 2-byte Unicode points (like U+FDD0) — in that case try [English (Phonemic2)](Phonemic2.md)

Phonemic (uses `/phonemes/`):  

 - text or words usually enclosed with forward slash `/brakets/`,  
 - single phonemes are usually enclosed in angle brackets: ⟨e⟩.  

This keyboard layout is based on **Shavian (QWERTY)** — the key layout is very similar, which may be helpful in learning the same typing reflexes for writing in both English IPA and Shavian.

 * The **Unshifted** and **Shifted** layers: English Phonemes are arranged in the same way as [Shavian (QWERTY)](ShawQ.md)
 * The **AltGR** and **AltGr+Shift** layers: similar but not identical to [Writer+ (QWERTY)](Writerp.md)

Notes:  
 - the colon ⟨:⟩ is replaced by the vowel‑length mark ⟨ː⟩, and the symbol of traditional colon is available on the AltGr layer  
 - the RP and GA pronunciation differs, also almost every dictionary is using their own notation — this layout was designed specifically for GA pronunciation.  

>Writing phonemically builds phonemic awareness.  


### Unshifted:
```
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬──────┐
│ ` │ 1 │ 2 │ 3 │ 4 │ 5 │ 6 │ 7 │ 8 │ 9 │ 0 │ - │ = │ bksp │
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬────┤
│ tab │ɔɪ │ w │ ɛ │ r │ t │ ɑ │ ʌ │ ɪ │ ɒ │ p │ [ │ ] │  \ │
├─────┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴────┤
│ caps  │ ə │ s │ d │ f │ g │ h │ j │ k │ l │ ; │ ' │  ent │
├───────┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴──────┤
│ shift   │ z │ɜːr│tʃ │ v │ b │ n │ m │ , │ . │ / │  shift │
└─────────┴───┴───┴───┴───┴───┴───┴───┴───┴───┴───┴────────┘
```

### Shifted:
```
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬──────┐
│ ~ │ ! │ @ │ # │ $ │ % │ ^ │ & │ * │ ( │ ) │ _ │ + │ bksp │
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬────┤
│ tab │aʊ │ɪə │eɪ │ɑːr│ θ │ ɔ │ ʊ │ i │əʊ │ɔːr│ ⟨ │ ⟩ │  | │
├─────┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴────┤
│ caps  │ æ │ ʃ │ər │aɪ │ · │ ð │dʒ │ « │ » │ ː │ " │  ent │
├───────┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴──────┤
│ shift   │ ʒ │ɛər│ɪər│ju │ ⸰ │ ŋ │ u │ ‹ │ › │ ? │  shift │
└─────────┴───┴───┴───┴───┴───┴───┴───┴───┴───┴───┴────────┘
```

### AltGr (RightAlt or LeftAlt+Ctrl):
```
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬──────┐
│ ´ │ ¹ │ ² │ ³ │ ⁴ │ ⁵ │ ⁶ │ ⁷ │ ⁸ │ ⁹ │ ⁰ │ → │ ≠ │ bksp │
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬────┤
│ tab │ … │ ʍ │ ɜ │ ɹ │   │   │ ↑ │ ˈ │   │   │ { │ } │  • │
├─────┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴────┤
│ caps  │ “ │ ” │ ↓ │ ° │   │ ‐ │ ʤ │ ˌ │ ɫ │ : │ × │  ent │
├───────┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴──────┤
│ shift   │ ‘ │ ’ │ ʧ │ ⁃ │ · │ – │ — │ < │ > │ ÷ │  shift │
└─────────┴───┴───┴───┴───┴───┴───┴───┴───┴───┴───┴────────┘
```

### AltGr+Shift (RightAlt+Shift or LeftAlt+Ctrl+Shift):
```
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬──────┐
│ ≈ │ ₁ │ ₂ │ ₃ │ ₄ │ ₅ │ ₆ │ ₇ │ ₈ │ ₉ │ ₀ │ ← │ ± │ bksp │
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬────┤
│ tab │ ⌜ │ ⌝ │ ⌞ │ ⌟ │   │   │   │   │   │ π │ ⟮ │ ⟯ │  ◦ │
├─────┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴────┤
│ caps  │   │   │   │   │   │ ‑ │   │   │   │ § │ ☒ │  ent │
├───────┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴──────┤
│ shift   │   │   │   │   │ ○ │   │ µ │ ☺ │ ☐ │ ☑ │  shift │
└─────────┴───┴───┴───┴───┴───┴───┴───┴───┴───┴───┴────────┘
```

### Spaces

| Layer | Unicode | Whitespace name |
|:----- |:------- |:--------------- |
| Unshifted | U+0020 | regular space |
| Shifted | U+0020 | regular space |
| AltGr | U+2003 | Em-space - width equal to font height |
| AltGr+Shift | U+200b | zero-width space |

### XCompose

Add the following section to your `$HOME/.XCompose` file:
```
<UFDD0> : "ɔɪ"  # q U0254 U026A
<UFDD1> : "aʊ"  # Q U0061 U028A
<UFDD2> : "ɪə"  # W U026A U0259
<UFDD3> : "eɪ"  # E U0065 U026A
<UFDD4> : "ɑːr" # R U0251 U02D0 U0072
<UFDD5> : "əʊ"  # O U0259 U028A
<UFDD6> : "ɔːr" # P U0254 U0072
<UFDD7> : "ər"  # D U0259 U0072
<UFDD8> : "aɪ"  # F U0061 U026A
<UFDD9> : "dʒ"  # J U0064 U0292
<UFDDA> : "ɜːr" # x U025C U02D0 U0072
<UFDDB> : "ɛər" # X U025B U0259 U0072 
<UFDDC> : "tʃ"  # c U0074 U0283
<UFDDD> : "ɪər" # C U026A U0259 U0072
<UFDDE> : "ju"  # V U006A U0075
```
-----
Copyright (c) 2024 Neil Raiden (AGPL v3)