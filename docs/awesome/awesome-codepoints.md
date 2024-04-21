<div class="github-widget" data-repo="Codepoints/awesome-codepoints"></div>
## Awesome Code Points [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a curated list of characters in Unicode, that have interesting (and
maybe not widely known) features or are awesome in some other way.



## Standalone Code Points

* The code points of the Unicode blocks [Box
    Drawing](https://codepoints.net/box_drawing) (U+2500 to U+257F) and [Block
    Elements](https://codepoints.net/block_elements) (U+2580 to U+259F) cover
    most of your monospace command-line visualization needs.

        ╭───────╮
        │Unicode│
        │rules! │
        ╰┬─────┬╯
* [U+2E2E](https://codepoints.net/U+2E2E) REVERSED QUESTION MARK - the “irony
    mark” to express irony/sarcasm. A useful character&#x2E2E;
* [U+D800](https://codepoints.net/U+D800) to
    [U+DFFF](https://codepoints.net/U+DFFF) - surrogate code points. They are
    only reserved to ease [UTF-16
    encoding](https://en.wikipedia.org/wiki/UTF-16).
* [U+FEFF](https://codepoints.net/U+FEFF) ZERO WIDTH NO-BREAK SPACE - it’s name
    suggests, that it can be used like U+2060 WORD JOINER. And in fact the
    latter was introduced to inherit its semantics. This is because U+FEFF had
    become a special beacon called the [byte order
    mark](https://en.wikipedia.org/wiki/Byte_order_mark), that was placed on
    the beginning of some UTF-8 files. In complying software (including many
    text editors) this character is stripped from the start of a file and
    handled as metadata. In non-complying software (like the PHP interpreter)
    this leads to all sorts of fun behaviour.
* [U+FFFD](https://codepoints.net/U+FFFD) REPLACEMENT CHARACTER - when a
    character cannot be displayed (e.g., decoding an erroneous UTF-8 sequency),
    this code point steps into the breach.
* [U+1D455](https://codepoints.net/U+1D455) is missing. It would be an italic
    small “h”. It was not encoded, because it would be identical to the Planck
    constant ℎ ([U+210E](https://codepoints.net/U+210E)).
* [U+FF03](https://codepoints.net/U+FF03) FULLWIDTH NUMBER SIGN - it is the 
    "Japanese Hashtag" `＃`. Sites like Twitter accept it as equivalent to the 
    regular `#` ([U+0023](https://codepoints.net/U+0023)).

## Code Points that Affect Others

* [U+202D](https://codepoints.net/U+202D) and
    [U+202E](https://codepoints.net/U+202E) - change the text direction.
    Relevant XKCD:

    [![](http://imgs.xkcd.com/comics/rtl.png )](https://xkcd.com/1137/)
* [U+FE0E](https://codepoints.net/U+FE0E) VARIATION SELECTOR-15 - force
    black-_&_-white emoji. If this code point follows an emoji, an explicit
    monochrome rendering of the emoji is requested (if the client supports it).
* [U+FE0F](https://codepoints.net/U+FE0F) VARIATION SELECTOR-16 - force
    colorful emoji. If this code point follows an emoji, an explicit colorful
    rendering of the emoji is requested (if the client supports it).
* Diacritics and combining marks: There is a [host of
    characters](https://codepoints.net/search?gc=Mn), that add
    to the characters before. Those are called Combining Marks. Unicode
    provides a [handy FAQ](http://unicode.org/faq/char_combmark.html) on the
    details, but in a nutshell: If you add one after a character, it is placed
    on top of that previous one. So, `a + ̊ = å`. This _may_ lead to all kinds
    of funny problems, because for some combinations there are pre-composed
    characters. Our little `å` here can also be encoded as U+00E5. You might
    note, that while this has a length of one character, the combination of `a`
    and combining ring has a length of two characters.

    Of course, one can also do fun things with those characters like
    [this answer](http://stackoverflow.com/a/1732454/113195) on StackOverflow.
* The [Regional Indicator Symbols](https://codepoints.net/U+1F1E6..U+1F1FF)
    U+1F1E6 to U+1F1FF resemble the 26 latin characters. They are used to
    create flag emoji. Since the Unicode consortium didn’t feel like getting on
    board with international politics, the solution to flags is to combine
    these 26 characters to the respective ISO code for a country. Examples:

    Country | ISO Code | Code Points       | Emoji (if supported)
    --------|----------|-------------------|---------------------
    USA     | US       | U+1F1FA + U+1F1F8 | &#x1F1FA;&#x1F1F8;
    Germany | DE       | U+1F1E9 + U+1F1EA | &#x1F1E9;&#x1F1EA;
    China   | CN       | U+1F1E8 + U+1F1F3 | &#x1F1E8;&#x1F1F3;
* Skin color of emoji: There are five code points, that control the skin color
    of emoji, [U+1F3FB to U+1F3FF](https://codepoints.net/U+1F3FB..U+1F3FF).
    They are called “Emoji Modifier Fitzpatrick Type” 1 to 6, with 1 the palest
    and 6 the darkest. If one of these characters follows an emoji, that emoji
    is meant to be rendered in the appropriate skin color of [the Fitzpatrick
    scale](https://en.wikipedia.org/wiki/Fitzpatrick_scale). If no such
    modifier is added, the skin tone should be unnatural, e. g., bright yellow.
    Fun fact: Since the Fitzpatrick modifiers are normal code points, emoji
    with such skin colors have the length 2, which Twitter users noticed first.
    Here is a comparison chart [directly from the
    specification](http://www.unicode.org/reports/tr51/tr51-2.html#Diversity):

    Code    | Name                                | Samples
    --------|-------------------------------------|---------
    U+1F3FB | EMOJI MODIFIER FITZPATRICK TYPE-1-2 | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-1-2.png" alt="" height="20" width="auto"> <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-1-2-bw.png" alt="" height="20" width="auto">
    U+1F3FC | EMOJI MODIFIER FITZPATRICK TYPE-3   | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-3.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-3-bw.png" alt="" height="20" width="auto">
    U+1F3FD | EMOJI MODIFIER FITZPATRICK TYPE-4   | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-4.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-4-bw.png" alt="" height="20" width="auto">
    U+1F3FE | EMOJI MODIFIER FITZPATRICK TYPE-5   | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-5.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-5-bw.png" alt="" height="20" width="auto">
    U+1F3FF | EMOJI MODIFIER FITZPATRICK TYPE-6   | <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-6.png" alt="" height="20" width="auto">   <img src="http://www.unicode.org/reports/tr51/images/other/swatch-type-6-bw.png" alt="" height="20" width="auto">

### Breaking and Gluing other characters

* [U+00A0](https://codepoints.net/U+00A0) NO-BREAK SPACE - force adjacent
    characters to stick together. Well known as `&nbsp;` in HTML.
* [U+00AD](https://codepoints.net/U+00AD) SOFT HYPHEN - (in HTML: `&shy;`)
    like ZERO WIDTH SPACE, but show a hyphen if (and only if) a break occurs.
* [U+200B](https://codepoints.net/U+200B) ZERO WIDTH SPACE - the inverse to
    U+00A0: create no space, but allow word breaking.
* [U+200D](https://codepoints.net/U+200D) ZERO WIDTH JOINER - force adjacent
    characters to be joined together (e.g., arabic characters or supported
    emoji). Apple uses this to compose some emoji like different families.
* [U+2060](https://codepoints.net/U+2060) WORD JOINER - the same as
    U+00A0, but completely invisible. Good for writing `@font-face` on Twitter.

For better comparison of which code point has which effect, consult this
table:

               | U+00A0 | U+00AD | U+200B | U+200D | U+2060
---------------|--------|--------|--------|--------|--------
create space   |   ✓    |   ✗    |   ✗    |   ✗    |   ✗
allow breaking |   ✗    |   ✓    |   ✓    |   ✗    |   ✗
possible change|   ✗    |   ✓    |   ✗    |   ✓    |   ✗

Smashing Magazine featured [a comprehensive
article](http://www.smashingmagazine.com/2015/10/space-yourself/) on the
different types of whitespace.

## Record Holders and Extremes

* [U+0000](https://codepoints.net/U+0000) &lt;control> - first code point.
* [U+10FFFF](https://codepoints.net/U+10FFFF) (_non-character_) - last code
    point. The whole rest of its plane apart from U+10FFFE, the code points
    in the 0x10000-0x10FFFD range, are private use characters, guaranteed to
    be never filled by a future Unicode standard.
* [U+1F402](https://codepoints.net/U+1F402) OX - shortest name.
* U+1FBA8 BOX DRAWINGS LIGHT DIAGONAL UPPER CENTRE TO MIDDLE LEFT AND MIDDLE RIGHT TO LOWER CENTRE
    and
    U+1FBA9 BOX DRAWINGS LIGHT DIAGONAL UPPER CENTRE TO MIDDLE RIGHT AND MIDDLE LEFT TO LOWER CENTRE - longest name: 88
    characters each.
* [U+FDFA](https://codepoints.net/U+FDFA) ARABIC LIGATURE SALLALLAHOU ALAYHE
    WASALLAM - longest decomposition form: 18 characters.
* [U+5146](https://codepoints.net/U+5146) and
    [U+16B61](https://codepoints.net/U+16B61) - code points that represent the
    highest “single-digit” number. In both cases that’s 1,000,000,000,000, a
    trillion.
* [U+0F33](https://codepoints.net/U+0F33) TIBETAN DIGIT HALF ZERO - code point that
    represents the _lowest_ “single-digit” number and at the same time the
    only negative one, -½.
* The trophy for most useless code points goes to
    [U+0080](https://codepoints.net/U+0080),
    [U+0081](https://codepoints.net/U+0081) and
    [U+0099](https://codepoints.net/U+0099). These so-called C1 control
    characters are more or less unspecified. They got into Unicode, because
    they were present in the very first version of what should later become ISO
    10646, the ISO-standardized version of Unicode. They [were meant to be part
    of an upgrade to ISO
    2022](http://unicode.org/mail-arch/unicode-ml/y2015-m10/0050.html), that
    never came to be.
* A close second place in this regard goes to the CJK unified ideographs
    [妛](https://codepoints.net/U+599B),
    [挧](https://codepoints.net/U+6327),
    [暃](https://codepoints.net/U+6683),
    [椦](https://codepoints.net/U+6926),
    [槞](https://codepoints.net/U+69DE),
    [蟐](https://codepoints.net/U+87D0),
    [袮](https://codepoints.net/U+88AE),
    [閠](https://codepoints.net/U+95A0),
    [駲](https://codepoints.net/U+99F2),
    [墸](https://codepoints.net/U+58B8),
    [壥](https://codepoints.net/U+58E5), and
    [彁](https://codepoints.net/U+5F41). These so-called [“ghost characters”](https://www.dampfkraft.com/ghost-characters.html)
    came to Unicode via the Japanese JIS standard, where they were added, because
    they were mis-read or misinterpreted from other signs, when JIS was compiled
    from original printed text sources.
* [U+006F](https://codepoints.net/U+006F) LATIN SMALL LETTER O - leads the list
    of characters with confusable shapes. Of all the possible mappings in the
    [list of confusable
    characters](http://www.unicode.org/reports/tr39/#Data_Files), the small “o”
    leads with a whopping 73 entries of similar looking glyphs, followed by
    [U+006C](https://codepoints.net/U+006C) LATIN SMALL LETTER L with 70
    entries.
* [U+1F4C0](https://codepoints.net/U+1F4C0) DVD - only code point name without any vowel ([source](https://twitter.com/ken_lunde/status/960188623390846976))
* [U+3106C](https://codepoints.net/U+3106C) CJK UNIFIED IDEOGRAPH 3106C - the
    character with the most
    [strokes](https://en.wikipedia.org/wiki/Chinese_character_strokes): 84.
    Take your time to write this one!

## For Funsies

* [U+1680](https://codepoints.net/U+1680) OGHAM SPACE MARK - a space that looks
    like a dash. Great to bring programmers close to madness: `1 +  2 === 3`.
* [U+037E](https://codepoints.net/U+037E) GREEK QUESTION MARK - a look-alike to
    the semicolon. Also a fun way to annoy developers.
* [U+1DD2](https://codepoints.net/U+1DD2) COMBINING US ABOVE - this is the most
    romantic code point.
* [U+F8FF](https://codepoints.net/U+F8FF) PRIVATE USE CODEPOINT - this private
    use code point is rendered as Apple logo on many Apple devices.
* [U+1F574](https://codepoints.net/U+1F574) MAN IN BUSINESS SUIT LEVITATING -
    A rather curious character, that only made it into Unicode for its
    appearance in the Webdings font (for reasons of backwards compatibility).
* [U+1F596](https://codepoints.net/U+1F596) RAISED HAND WITH PART BETWEEN
    MIDDLE AND RING FINGERS - the Vulcan salute. Live long and prosper!
    &#x1F596;
* [U+1F918](https://codepoints.net/U+1F918) SIGN OF THE HORNS - Rock on!
    &#x1F918;
* [U+2800](https://codepoints.net/U+2800) BRAILLE PATTERN BLANK - A Braille pattern that has zero of its six or eight dots filled in. According to the standard: “* while this character is imaged as a fixed-width blank in many fonts, it does not act as a space” Essentially it is rendered as white-space, but since it is designated as *not* white-space it isn't matched by white-space-validating regular expressions. This can be used to bypass all kinds of validation that disallows or trims white-space.


### Games

For plain-text gaming, Unicode is well equipped with several complete sets:

* [Chess figures](https://codepoints.net/U+2654..U+265F).
* [Card suits](https://codepoints.net/U+2660..U+2667) and even a whole [deck of
    cards](https://codepoints.net/playing_cards) complete with joker and back
    of card.
* [Die faces](https://codepoints.net/U+2680..U+2685) and a nice [die
    emoji](https://codepoints.net/U+1F3B2).
* [Go pieces](https://codepoints.net/U+2686..U+2689).
* [Draughts (or checkers) pieces](https://codepoints.net/U+26C0..U+26C3).
* [Shogi pieces](https://codepoints.net/U+2616,U+2617,U+26C9,U+26CA), a
    [Japanese variant of chess](https://en.wikipedia.org/wiki/Shogi).
* [Domino tiles](https://codepoints.net/domino_tiles)
* [Mahjong tiles](https://codepoints.net/mahjong_tiles)

## Other Lists of Code Points

* [Cross-platform terminal characters](https://github.com/ehmicky/cross-platform-terminal-characters) - a list of characters that work on most terminals.

## Contributing Your Code Points

See [the contribution guide](https://github.com/Codepoints/awesome-codepoints/blob/master/CONTRIBUTING.md) for details.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [the
contributors](https://github.com/Codepoints/awesome-codepoints/graphs/contributors)
have waived all copyright and related or neighboring rights to this work. See
[the license file](https://github.com/Codepoints/awesome-codepoints/blob/master/LICENSE) for details.
