# Word funnel

A word funnel is a series of words formed by removing one letter at a time from a starting word, keeping the remaining letters in order. For the purpose of this challenge, a word is defined as an entry in the enable1 word list. An example of a word funnel is:

``` gnash => gash => ash => ah```

This word funnel has length 4, because there are 4 words in it.

Given a word, determine the length of the longest word funnel that it starts. You may optionally also return the funnel itself (or any funnel tied for the longest, in the case of a tie).

Examples
```
funnel2("gnash") => 4
funnel2("princesses") => 9
funnel2("turntables") => 5
funnel2("implosive") => 1
funnel2("programmer") => 2
```
