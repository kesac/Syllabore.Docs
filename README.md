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

## Next Steps

* [Installation](installation.md)
* [Basic Control](basic-control.md)
* [Advanced Control](broken-reference)
  * [Positioning](advanced-control/positioning.md)
  * [Probabilities](advanced-control/probabilities.md)
  * [Weights](advanced-control/weights.md)
  * [Filtering](advanced-control/filtering.md)
  * [Transforms](advanced-control/transforms.md)
* [Fluent Methods](advanced-techniques/fluent-methods.md)
* [Advanced Techniques](broken-reference)
  * [Controlling Seeds](advanced-techniques/controlling-seeds.md)
  * [Combining Generators](advanced-techniques/combining-generators.md)
  * [Using SyllableSets](advanced-techniques/using-syllablesets.md)
* [Examples](broken-reference)
  * [Planet Names](examples/planet-names.md)
  * [Spaceship Names](examples/spaceship-names.md)
  * [Random Text](examples/random-text.md)

