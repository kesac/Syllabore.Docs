# Overview

### What is this?

[**Syllabore**](https://github.com/kesac/Syllabore) is a procedural name generator that does not use pre-made lists of names. It can be embedded into a .NET program or game, and used 100% offline.

### Quick Start

Instantiate a `NameGenerator` class and make calls to `Next()` to get new names.

```csharp
var g = new NameGenerator();
Console.WriteLine(g.Next());
```

The generator above will return names like:

```
Pheras
Domar
Teso
```
