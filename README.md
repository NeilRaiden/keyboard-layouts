# Keyboard Layouts

What problems does this project aim to solve?

## 1. Keyboard Layouts — for writers, authors, editors, publishers, students.

### Problem:

All the novels, essays, newspaper articles, etc — anything that is published — must follow specific rules outlined in the writing guides such as the famous “Chicago Manual of Style”.

For example, those writing guides require writers, authors, publishers to use:  
 · 66-99 quotation marks and 6-9 marks for quotations inside quotations  
 · En-dash, Em-dash, several types of hyphens — not the hyphen-minus  
 · ellipsis, footnotes, end-notes, etc.  

None of those symbols is available on the standard English QWERTY keyboard layout. Neither on Dvorak and Colemak.

Instead, writers must either:  
 • memorize a list of **Alt codes**  
 • laboriously copy the symbols from the **CharacterMap** or a similar app  
 • or use an expensive software dedicated for writers that auto-magically replaces typed symbols with the correct ones.  

Unfortunately "smart quotes" are not implemented in every text editor — **that is THE PROBLEM**.

### Solution:

The **Writer** and **Writer+** keyboard layouts allow you to type those most commonly used symbols with **AltGr** (right Alt key) and **AltGr+Shift** in a way easier to memorize than _Alt codes_.
And you may also easily enter some other useful symbols: “«©℗®™√÷×≠±≈⟨¹²⁹⁰₁₂₉₀⟩⟮·○•◦⟯°πµ☐☑☒☺»”, and more.

Now you can write your novel even in a Notepad.

* Keyboard layout [Writer (QWERTY)](Windows/Writer/README.md) for Windows
* Keyboard layout [Writer (QWERTY)](Linux/docs/Writer.md) for Linux

Occasionally some English teachers may need to type **English IPA phonemes**. 

**/ðɪs sɪmpəl kibɔrd leɪaʊt meɪ hɛlp ðəm tə duː dʒʌst ðæt/**

* Keyboard layout [Writer+ (QWERTY)](Windows/Writer+/README.md) for Windows
* Keyboard layout [Writer+ (QWERTY)](Linux/docs/WriterPlus.md) for Linux

-----

## 2. Keyboard layout (English Phonemic) - for learners of spoken English.

### Problem:

The whole range of symbols for English phonemes that used by most English dictionaries is already supported by Unicode.
Some symbols are “obsoleted” and new ones recommended in their place. Not everyone is up to date with that "standard".
The symbols for English IPA phonemes are scattered across the several Unicode charsets:

 * Only the _thorn_ ⟨θ⟩ is in a Greek charset,  
 * all other IPA symbols are located in various Latin _supplement_ and _extension_ charsets.  

So if you use the _CharacterMap_ to find those symbols, unknowingly you may be using similar, but the wrong ones.

There seem to be no keyboard layout that would let you enter those codes to write in _fully phonemic English_ — and **that is THE PROBLEM**.
Although it may seem to be a borderline problem, **it is not**.

### Solution:

The best learning tool invented by humans is **writing**.  

Reading, listening — these only help you to acquire knowledge, **memorize** (encode).

Writing (especially in your own words) helps you to **apply** your knowledge, and the first step of applying is to **recall** from memory (decode).

The two processes involved in learning or acquiring a new language (like English):  

1. Spoken  
    - **listening** (memorizing — building an _audio vocabulary_)  
    - **speaking** and/or **reading aloud** (recalling and applying)  
2. Written  
    - **reading** (memorizing written words — building a _written/visual vocabulary_)  
    - **writing** (recalling and applying)  
 
Because of huge discrepancy between _written_ and _spoken_ English, the size of _audio_ and _visual_ vocabularies (that English learners build in their heads) are of **different sizes**. 

Because of that, many people, especially non‑native speakers and some dyslectics, are unable to fully express their thoughts in writing. And because most non-native speakers acquire their vocabulary primarily through reading, they end up 

Practicing (even only occasionally) a _phonetic_ or _phonemic_ writing may help you in closing the gap between your _written_ and _spoken_ English vocabularies.

The **English Phonemic** keyboard layout may help you with that.

 * Keyboard layout [English (Phonemic)](Windows/Phonemic/README.md) for Windows
 * Keyboard layout [English (Phonemic)](Linux/docs/Phonemic.md) for Linux

-----

## 3. Keyboard layout (Writer+ ASERTH)

### Problem:

The popular keyboard layout **QWERTY** was designed in 1870s, for the first typewriting machines.
The keys in those typewriter machines were moving type-bars which were placed very close to each other and their trajectories crossed with others. This caused jamming when a user pressed two keys one after another too quickly. To prevent jamming the keys were arranged in a way to slow down the user.  
In summary: QWERTY is highly inefficient.

In the 1930-ties [Dr August Dvorak](https://en.wikipedia.org/wiki/Dvorak_keyboard_layout) re-arranged the keys to create a more ergonomic layout with focus on writing speed and mimimizing strain. It was most likely designed for electric typewriting machines that started being popular in 1920s. His layout is known as **Dvorak** layout. But probably because the mechanical typewriters were still widely used the adoption of Dvorak failed.  
In summary: Dvorak is efficient, but hard to learn (retains only 2 keys from QWERTY layout)

In 2006 [Shai Coleman](https://colemak.com/) released his Colemak layout as a compromise between QWERTY and typing speed (17 keys moved and 10 retained). Colemak is the result of a very thorough analysis of English text, finger distances for most common letter pairs, etc. For more info visit [Colemak.com](https://colemak.com/) (official Shai Coleman website), [Colemak.org](https://colemak.org/) and [CarpalX](https://mk.bcgsc.ca/carpalx/?colemak).  
In summary: Colemak is one of the best designed layouts, easier to learn than Dvorak. But if you're typing at more than 50 wpm speeds it may take you 3 months to achieve that speed with new layout. However, the reduction in fatigue is noticeable almost immediately.

In recent decade multiple new layouts were designed that are slightly more efficient than Colemak.
But they are not much faster than Colemak, and their focus is on various types of optimization and not reduction of learning curve. Examples:

* [Three Layout - 3l](https://github.com/jackrosenthal/threelayout)
* [Workman](https://en.wikipedia.org/wiki/Keyboard_layout#Workman)

The difficulty of having to completely re-learn the layout is what keeps most people from even trying it. 
That is **the problem**.

### Solution:

Several good solutions already exist that are a middle-ground between QWERTY and Colemak.
Three most notable examples:
 
1. [Minimak](http://www.minimak.org/) layout. With Minimak you can gradually swap 12 keys:

    * **Minimak-4**: swap 4 keys for 60% improvement ⟮rotation: D → E → K → T → D⟯. 
    * **Minimak-8**: after few weeks, swap another 4 keys ⟮swap N with J, and L with O⟯
    * **Minimak-12**: after another few weeks, swap another 4 keys to achieve 83% of the benefits of Dvorak ⟮swap R with F, and P with ;⟯

2. [ASERT](https://github.com/AlternateKeyboard/ASERT) layout (15 keys relocated):

    * swap ERT with DFG
    * swap IOP with KL;
    * rotate: J → Y → N → J

3. [QWERTY-Flip](https://nick-gravgaard.com/qwerty-flip/) — the **Writer+ (ASERTH)** layout presented here is based on one of the QWERTY-Flip layouts by Nick Gravgaard. See his project page: ([GitHub](https://github.com/nick-gravgaard/qwerty-flip)). Total of 14 keys relocated according to scheme:

    * flip ERT with DFG
    * flip N with J, K with I
    * twist: L → ; → P → O → L


Both ASERT and Minimak focus on **reducing the learning curve** while being almost as efficient as Colemak.

### Writer+ (ASERTH):

 * Keyboard layout [Writer+ (ASERTH)](Windows/) for Windows
 * Keyboard layout [Writer+ (ASERTH)](Linux/docs/WriterASERT.md) for Linux

-----

## 4. Keyboard layouts for Shavian Alphabet.

### Problem:

If you've already tried the **English Phonemic** keyboard layout, you might have noticed that a lot of English phonemes take 2 or even 3 IPA symbols. What a waste of space. That's where the Doom music—, əhɛm, that's where the **Shavian Alphabet** kicks in.

The learning curve of Shavian Alphabet is definitely much steeper (in comparison to learning the English IPA symbols), but the benefits may outweigh that.  
Here are some of them:

1. Every English phoneme is represented by **a single symbol**.
>That feature of the Shavian Alphabet makes English **fully phonemic** (symbol to phoneme ratio is 1 to 1).

2. The Shavian Alphabet was designed for **fast** writing, all letters are **single‐stroke** symbols.
> In this aspect it is also one of the **simplest shorthand systems**, unlike Gregg or Pitmann (both also phonemic). Please note here that Gregg and Pitmann symbols are NOT implemented in Unicode — they are for handwriting only. 
> This single‑stroke feature may result in about **20% increase in writing speed**. 

3. English words written in Shavian Alphabet take about **20% less space**.
> This feature can give you another 20% boost in writing speed.

There are already solutions for writing in Shavian Alphabet — most notable one is [Keyman](https://www.keyman.com).

However, Keyman on Windows takes over 200MB of space, and sometimes acts very strangely. For example, it switches keyboard layouts intermittently without any warning when you're busy doing other things. This makes it a bit irritating.
There is also a number of websites with a kind of on‐screen keyboards, which allow you to write in Shavian, but then you have to copy the text and paste where you actually need it. It's only a partial solution, and it's a bit cumbersome to use.

Practically there is no other solution — and that is **THE PROBLEM** this project aims to solve.

### Solution:

The best solution is a Shavian keyboard layout designed **specifically for your operating system**.

* Keyboard layout [Shavian (QWERTY)](Windows/ShavianQWERTY/README.md) for Windows
* Keyboard layout [Shavian+ (QWERTY+)](Windows/ShavianQWERTY+/README.md) for Windows
* Keyboard layout [Shavian (Imperial)](Windows/ShavianImperial/README.md) for Windows
* Keyboard layout [Shavian (QWERTY)](Linux/docs/ShawQ.md) for Linux
* Keyboard layout [Shavian+ (QWERTY)](Linux/docs/ShawPlus.md) for Linux
* Keyboard layout [Shavian (Imperial)](Linux/docs/ShawImp.md) for Linux

-----
Copyright (R) 2024 Neil Raiden (AGPL v3)