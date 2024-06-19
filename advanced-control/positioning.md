# Positioning

### Positioning Consonants

Use a `SyllableGenerator` to control which consonants appear before or after a vowel of the same syllable: &#x20;

```csharp
var syllables = new SyllableGenerator()
    .WithVowels("ou")
    .WithLeadingConsonants("st")
    .WithTrailingConsonants("mn");

var names = new NameGenerator(syllables);
```

Every call to `Next()` on the `NameGenerator` above produces names like:

```
Toto
Sontu
Sumsum
```

### Consonant Position Terminology

Within a syllable, consonants that must only occur before vowels are called **leading consonants**. Similarly, consonants that must only occur after vowels are called **trailing consonants.**
