# Hantsch.CSharp.StyleCop

`Hantsch.CSharp.StyleCop` is a NuGet package that bundles the StyleCop setup I use in my own C# projects, so I can outsource some arguing to analyzers and get back to writing code.

It depends on [`StyleCop.Analyzers`](https://www.nuget.org/packages/StyleCop.Analyzers/) and ships shared analyzer configuration transitively, so consuming projects automatically receive the same rules and settings without every repository inventing its own tiny bureaucracy.

## What the package includes

- `stylecop.json`
- `hantsch.stylecop.ruleset`
- `config/Hantsch.CSharp.StyleCop.globalconfig`
- `buildTransitive/hantsch.csharp.stylecop.props`

In other words: the package arrives with opinions, luggage, and receipts.

## Who this is for

This package is primarily maintained for my own projects, but anyone is free to use it if the included rules match their preferred C# style and tolerance for a mildly bossy robot.

## License

This project is available under the MIT License. See `LICENSE` for details, which is the nice license that mostly says “have fun, just do not blame me if the code gets weird.”
