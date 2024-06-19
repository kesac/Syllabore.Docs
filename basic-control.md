# Basic Control

### Simple Vowels and Consonants

For simple generators, specify the vowels and consonants you'd like to use in the constructor of `NameGenerator` like so:

```csharp
var g = new NameGenerator("ae", "srnl");
Console.WriteLine(g.Next());
```

Then each call to `Next()` will return names like:

```
Lena
Salna
Rasse
```

For advanced control of vowels of consonants, you'll want to access a `SyllableGenerator` directly. This is covered in the next section.
