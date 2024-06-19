# Sequences

### Sequences

**Sequences** are multicharacter units used in the generation of syllables.&#x20;

For example, to use `ui` and `ea` in addition to normal vowels, declare them as **vowel sequences** in your `SyllableGenerator`:

```csharp
var syllables = new SyllableGenerator()
    .WithVowels("ou")
    .WithVowelSequences("ui", "ea") // Multicharacter units
    .WithLeadingConsonants("st")
    .WithTrailingConsonants("mn");

var names = new NameGenerator(syllables);
```

Calling `Next()` on the `NameGenerator` above will produce names like:

```
Suinto
Toseas
Susui
```

### Types of Sequences

* VowelSequences
* ConsonantSequences
* LeadingConsonantSequences
* TrailingConsonantSequences

### Terminology

* A syllable's _nucleus_ or vowel can be a _cluster_ of more than character (eg. "team", "rain", "look")
* Similarly, an _onset_ or _leading consonant_ can be a cluster (eg. "chat", "wheel", "shot")
* Finally, a _coda_ or _trailing consonant_ can be a cluster (eg. "beach", "mark", "tell")
