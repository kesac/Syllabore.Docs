# Syllabore

### What is this?

* **Syllabore** is a procedural name generator that does not use pre-made lists of names
* It can be embedded into a .NET program or game, and used 100% offline

### Quick Start

* Instantiate a `NameGenerator` class and make calls to `Next()` to get new names

```csharp
var g = new NameGenerator();
Console.WriteLine(g.Next());
```

* The generator above will return names like:

```
Pheras
Domar
Teso
```

## Next Steps

* Installation
* Basic Control
* Advanced Control
  * Positioning
  * Probabilities
  * Weights
  * Filtering
  * Transforms
* Fluent Methods
* Advanced Techniques
  * Controlling Seeds
  * Combining Generators
  * Using SyllableSets
* Examples
  * Planet Names
  * Spaceship Names
  * Random Text

