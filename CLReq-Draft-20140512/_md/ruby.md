<section class='informative'>
# Usage of Chinese Ruby

Chinese Ruby, also known as interlinear annotation, is a small-sized,
supplementary text attached to certain characters in the main text. Chinese
Ruby is usually set in the interlinear space, aligned to the corresponding
annotated text. In Chinese typesetting, Chinese Ruby is mainly used to give
pronunciation or meaning.

<section>
## Indicate the Pronunciation for Chinese characters

In Chinese, interlinear annotation is most commonly used in this way.
Presenting the pronunciation alongside the characters is a great help to
beginners, especially to children who are native speakers or to foreigners
intending to study Chinese. Therefore, it's a rare situation to annotate
certain individual Hanzi. Instead, we do use phonetic annotation to mark the
full text. Also, there is no such custom or practice to provide Hanzi
pronunciation in Chinese layout, not even for the pronunciation of rarely used
characters, although sometimes their pronunciation is provided within inline
brackets.

There are two methods, Zhuyin and Romanization, to indicate the pronunciation
in Chinese phonetic systems:

<section>
### Zhuyin

Mandarin Phonetic Symbols (國語注音符號) and Taiwanese Dialect Phonetic Symbols
(台灣方言音符號), hereinafter referred to as ‘Zhuyin’, are the systems of phonetic
annotation mainly used in Taiwan, while other areas may also include Zhuyin in
certain dictionaries or textbooks. In most cases, Zhuyin appears on the right
side of the base characters, exceptions are very rare.
</section><!--/###-->

<section>
### Romanization

Hanyu Pinyin, which is being carried out in Mainland China nowadays, uses the
Latin alphabet to transcribe Modern Standard Chinese (Mandarin) pronunciations
of Chinese characters. Indicating the pronunciation for all characters of the
full text with Hanyu Pinyin is the most common use case in Mainland China. In
Taiwan and Hong Kong, Taiwanese Romanization System for Min Nan (台灣閩南語羅馬字),
the romanization system of the Hong Kong Education and Manpower Bureau
(教育學院拼音方案) or Romanization systems of other Chinese dialects own similar ruby
annotation use cases with Hanyu Pinyin.

Due to the feature of Latin alphabet, the text in such phonetic annotation
appear only in horizontal writing mode. The text for young children who are
native speakers usually provides reading aid for each individual character,
while the text for those who are learning Chinese as a second language mainly
indicates the pronunciation for each words, but occasionally both of them will
have almost the same typesetting. In the latter situation, there will be space
between base characters and ruby characters will have their unique
requirements such as sentence case, or punctuation marks corresponding to the
base characters. The publication for Pinyin in the early stage are very varied
and lack of consistency, both character-based and word-based annotation can be
found, so we don't intend to provide detailed discussion about them in this
document.
</section><!--/###-->
</section><!--/##-->

<section>
## Indicate the Meaning or Other Additional Information

<section>
### Bilingual Annotation

Bilingual annotation aims to provide Chinese translation of the text in
foreign languages and acronyms, or to offer original text to the translated
word. This is mainly used for proper nouns, titles or words difficult to be
translated. It is commonly found in translation, especially in light novels.
</section><!--/###-->

<section>
### Interlinear Comments

Interlinear comments are methods to annotate the meaning of a piece of text
fragments or a single word, which is named for its interlinear positioning. It
usually lies in the interlinear space and co-exists with the body text.
Compared to other annotation methods, e.g. headnotes or footnotes, interlinear
comments are more compact and stickier to the body. These kinds of comments
are often found in ancient books, e.g. Rouge Inkstone, an early commentator of
the novel Dream of the Red Chamber.
</section><!--/###-->
</section><!--/##-->

<section>
## Qu Notation

Qu Notation contains many tradition methods to represent musical notes and
lyrics in ancient China, e.g. Gongche notation (工尺譜). In modern prints,
similar methods like numbered musical notation can also be found.
</section><!--/##-->
</section><!--/#-->

<section>
# Positioning of Chinese Ruby

<section>
## Overview

In vertical writing mode, Zhuyin, Romanization or bilingual annotations are
usually placed at the right side of the base characters (Hanzi), while
interlinear comments are often set at the left side. In horizontal writing
mode, Zhuyin can be placed on top of the base characters, but in most cases
they are still set to the right side of the base characters, while
Romanization and bilingual annotations can be placed at both the top or the
bottom of the base characters, and the interlinear comments are usually placed
at the bottom of the base characters.

In principle, the Zhuyin symbols are of the same size and the number of Zhuyin
symbols for a character is never more than three, which is rather
controllable. The letters of Romanization alphabet can have different sizes
and be composed to different length, and there should also be space between
the Romanization for each word. Thus, these two kinds of phonetic annotations
differ greatly in positioning.
</section><!--/##-->

<section>
## Zhuyin

<section>
### Positioning of Zhuyin

According to Manual of Mandarin Phonetic Symbols (國語注音符號手冊) released by
Ministry of Education in Taiwan, there are two standard ways placing Zhuyin to
the top (horizontal Zhuyin) or the right side (vertical Zhuyin) of the
corresponding Hanzi, the use cases of putting Zhuyin on the top are still
rarely found in today's textbooks or other prints, and not accepted by the
public. Therefore, it's always a better practice to place Zhuyin annotation on
the right side no matter in horizontal or vertical writing mode.
</section><!--/###-->

<section>
### Choice of Size and Ratio for Zhuyin

If a Hanzi character is considered as a square with an aspect ratio of 30:30,
its Zhuyin should set the ratio of width to height as 15:30 in vertical
writing mode and of 30:15 in horizontal writing mode, and stay sticky to the
base character. Among these Zhuyin (initials, medials and finals) have an
aspect ratio of 9:9, while Mandarin non-neutral tones and dialect non-checked
tones have an aspect ratio of 5:5, and the aspect ratio of Mandarin neutral
tones is 9:2, the aspect ratio of dialect checked tones is 5:5.

When the font size of the body is small, it's possible to provide larger font
size only for the MPS, and the other methods, e.g. providing Zhuyin in the
parentheses within the body, are workable. More details can be found in 2.2.4
The Positioning of Different Composition for the Tones.
</section><!--/###-->

<section>
### Positioning of the Tones in Mandarin Phonetic Symbols

  * To Mandarin non-neutral tones and dialect non-checked tones, in either horizontal or vertical writing mode, they are placed to the upper right corner of the last phonetic symbol.
  * The Mandarin neutral tones come first to the phonetic symbols, which is the top in vertical writing mode and the left side in the horizontal writing mode.
  * The dialect checked tones are set to the lower right corner to the phonetic symbols.
</section><!--/###-->

<section>
### The Positioning of Different Composition for the Tones

  * Composition of one single symbol: initial, medial or final.
  * Composition of two symbols: initial-medial, initial-final or medial-final.
  * Composition of three symbols: initial-medial-final,
    1. Mandarin non-neutral tones and dialect non-checked tones
    2. Mandarin neutral tones
  * The dialect checked tones
</section><!--/###-->

<section>
### Rule to Zhuyin Typesetting

Similar to the case that putting certain punctuation marks in the beginning of
the line is forbidden, in principle, Zhuyin should stay sticky to the base
character in horizontal writing mode, they must not appear in the beginning of
the line, and must always place on the right side of its corresponding base
character.
</section><!--/###-->
</section><!--/##-->

<section>
## Romanization

<section>
### Basic Requirements

  * Romanization is more commonly available in horizontal writing mode only. These Ruby characters are usually placed on top of its base characters. In general, Ruby characters and their base characters are sticky to each other regardless of space, and both of them are aligned centered.
  * In special cases when Romanization is needed in vertical writing mode, the annotation is usually set to the right side of its corresponding base character, but it is difficult to read anyway.
  * If Ruby characters is longer than its base character and is at the start of a line, both the Ruby characters and the base character can be aligned to the beginning of the line.
  * The space between two adjacent Ruby characters should not be smaller than the size of normal Western-language space, which is about 1/4 em. Due to the limitation of typesetting, there's no space between the Ruby characters which are longer than their base characters in many prints. Luckily, this is not likely to lead to ambiguity because every Hanzi character is just one syllable and most Pinyin fragments are easy to tell, but sometimes these connected Ruby characters can cause misunderstanding that the two base characters come from the same word, also make it hard to understand the meaning of words.

**Note**: This layout requirement relies on the way HTML Ruby Markup Extensions supports  and the way CSS Ruby Module Level 1 deals with space. 双窗shuāng chuāng

The end of the bottom line and the beginner of the head line usually contains
a space.

  * The Ruby characters are allowed to be extended to the top of adjacent base characters as long as the minimum space is insured.
  * As most target readers are beginners to Chinese, the body text has larger font size than usual prints.
  * As the width of most Latin letters are different from each other, and the letters can vary in visual size according to the typefaces even in the same font size, there's no special requirement for the ratio of from the font size of phonetic annotations to the font size of their base characters. Despite of this, the Ruby characters usually use 1/2 the font size of the base characters under the impact of Japanese Ruby Typesetting.
  * Phonetic annotations usually use sans-serif typeface which is rather thin and round. It's a general opinion in publishing and in education that Pinyin must use those typefaces in which ‘a’ and ‘g’ are single story and the second-tone mark is thick on the lower part and thin on the upper as of its handwriting style of the stroke. Actually there have never been any national standard which can specify the typefaces and the glyphs for Pinyin. The General Association of Chinese Culture in Taiwan once wrote to the Ministry of Education in Mainland China about the rules of the glyph issues of Pinyin, and was responded that the letter ‘a’ and ‘g’ should only follow the corresponding Latin letters, and there are no any strict requirements for their glyphs.

    1. [audreyt/moedict webkit#83](https://github.com/audreyt/moedict-webkit/issues/83#issuecomment-26715350)
    2. [twitter.com/audreyt/status/392509080582885376](https://twitter.com/audreyt/status/392509080582885376)

Below detailed the description of the difference between two typical use
cases.
</section><!--/###-->

<section>
### Character-based Phonetic Annotation

  * The base character is a single Hanzi. Only the Hanzi is annotated, but not Arabic numerals, punctuation marks nor other characters.
  * The ruby characters are always on the top.
  * As the ruby characters are often longer than their base character, the space between each base character should be set larger to avoid too much irregular adjustment within the base characters.
  * The ruby characters are all in lower case. Sentence case is rare.
</section><!--/###-->

<section>
### Word-based Phonetic Annotation

  * The base characters are one or more words consist of Hanzi characters. Rules for the making of words can refer to GB/T 16159—2012 Basic Requirements for Words in Hanyu Pinyin.
  * Ruby characters sometimes appear at the bottom.
  * Both the Ruby characters and the base characters are separated by words. The adjacent Ruby characters should be separated by a space of 1/2 em, but the spacing between each base characters is normal.
  * Many Ruby characters for words can indicate the logic of the whole sentence, rather than merely indicating the pronunciation — these Ruby characters have sentence case, as well as punctuation marks which follow the annotations in front of it.
</section><!--/###-->
</section><!--/##-->

<section>
## Annotating Both Pinyin and Zhuyin

Annotating both Pinyin and Zhuyin is a practical method to indicate the
pronunciation to the readers who know only one of these phonetic systems, as
well as to help study or enquiry the other phonetic system. Normally, when
Pinyin and Zhuyin are both provided, the Zhuyin are placed on the right side
of the Hanzi character, while Romanization are set to the bottom of Hanzi in
horizontal writing mode and the left side in vertical writing mode.
</section><!--/##-->

<section>
## Atypical Use Cases for Hanzi Phonetic Annotations

<section>
### Erhuayin

Erhuayin is one special phonetic phenomenon of Modern Standard Chinese, which
needs extra description in the body text or note with Zhuyin annotation system
because Zhuyin corresponds to only one base character and fails to indicate
the continuity of erhuayin and the change of the final, while Romanization
shows the features of erhuayin very well.
</section><!--/###-->

<section>
### Ligature

Ligature is special for its many syllables, thus its Ruby annotation may fail
to typeset nicely. The pronunciation of ligature should be given by note
instead, in parentheses or even inside the body. Ligature is rare in modern
writing system of Chinese nowadays.
</section><!--/###-->
</section><!--/##-->

<section>
## Bilingual Annotation

The typesetting of bilingual annotation is actually quite similar to that of
Romanization. It is usually placed in the start of the annotated text, i.e.
the right side of the base text in vertical writing mode and the top of the
base text in horizontal writing mode.

<section>
### Word Alignment

In order to maintain the unity of the text, when the ruby text have different
length from the base text, it is necessary to adjust the spacing between words
to avoid misunderstanding.

When the ruby text is shorter than its base text, the ruby text can be aligned
centered if it's in Western, or it can leave larger spacing between each
character if it's in Hanzi. There are two methods to satisfy the latter, one
is to equally distribute the spacing, the other is to align justified.

When the ruby text is longer than its base text, the base text can be aligned
centered if it's in Western, or it can leave more spacing between each
character if it's in Hanzi.

**Note:** More detail can be referred to the section, [Positioning of Group-ruby with Respect to Base Characters](http://www.w3.org/TR/jlreq/#positioning_of_groupruby_with_respect_to_base_characters) in Requirements for Japanese Text Layout.
</section><!--/###-->
</section><!--/##-->

<section>
## Interlinear Comments

Interlinear comments can have very varied layouts and different length. They
are usually placed at the end of the annotated text, the left side of the base
text in vertical writing mode and the bottom of the base text in horizontal
writing mode. Sometimes the interlinear comments are in other color to help
readers tell the difference from the body text.

Interlinear comments are also used to explain the context and detail for a
rather long text fragment. In this case, due to the ambiguity of the base
text, the ruby text can find itself a suitable place as an anchor and flow
down. There's no strict requirement for its length, and sometimes it can be
longer than one line.
</section><!--/##-->
</section><!--/#-->
