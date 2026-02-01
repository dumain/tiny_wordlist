# Two, three and four word diceware wordlists

The EFF has published a [great set of diceware wordlists](https://www.eff.org/deeplinks/2016/07/new-wordlists-random-passphrases) and an [informative diceware page](https://www.eff.org/dice).  The wordlist can also be found in the EFF's [eff_diceware repo on GitHub](https://github.com/EFForg/eff_diceware).
This repository contains a couple of wordlists derived from truncated versions of Phil Thompson's 
revised version of the EFF's 5-die "large" list.

PhilThompson replaced 3,609 words, including:
  - words of 8 or more characters,
  - hard-to-spell words,
  - words with homophones,
  - words that could make for unpleasant, unsavory, or politically insensitive passphrases,
  - some compound words that might be difficult to remember as a single "word,"
  - words with common alternative spellings,
  - words containing non-alphabetic characters, and
  - other words that seem out of place in a wordlist.

He replaced most of the removed words with 3-6 character words from [hermitdave's FrequencyWords repo](https://github.com/hermitdave/FrequencyWords/).

I have extracted the three and four letter words, removed some and added some more words from hermitdave's FrequencyWords repo.

There are two wordlists created this way: a 3 dice list of three letter words and a 4 dice list of four letter words.

I have also created a 2 dice wordlist of two letter words by just writing down the 36 two letter words and exclamations
that seemed most familiar.

These wordlists  provide nearly 2.6 bits of entropy per letter when used with
a really good source of improbability (say a Brambleweeny 57 Sub-Meson
Brain connected to an atomic vector plotter suspended in a nice hot cup
of tea or some fair dice)

These are intended for creating a passphrase where the length of passwords
is unnecessarily restricted.

To get to the equivalent of 80 bits of entropy (currently considered
strong) using these methods would need a 31 character password: 7
words from the four word list plus 1 word from the three word list.

However if you are subject to excessive  restrictions on password 
length you are probably also required to insert some non-alphabetic
characters that will provide more entropy at the expense of 
memorability.

## License

The wordlist file is distributed by the EFF under the [Creative Commons Attribution License](https://creativecommons.org/licenses/by/3.0/us/).

The word's in hermitdave's FrequencyWords are distributed under the [Creative Commons Attribution Sharealike License](https://creativecommons.org/licenses/by-sa/4.0/)

Therefore the resultant work is also under the CC-BY-SA-4.0 license a copy of which can be found in LICENSE.txt in this repository.
