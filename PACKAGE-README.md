# Hantsch.CSharp.StyleCop

`Hantsch.CSharp.StyleCop` is a NuGet package that bundles the StyleCop setup I use in my own C# projects and makes it easy to reuse elsewhere.

It depends on [`StyleCop.Analyzers`](https://www.nuget.org/packages/StyleCop.Analyzers/) and ships shared analyzer configuration transitively, so consuming projects automatically receive the same rules and settings.

## What the package includes

- `stylecop.json`
- `hantsch.stylecop.ruleset`
- `config/Hantsch.CSharp.StyleCop.globalconfig`
- `buildTransitive/hantsch.csharp.stylecop.props`

## Who this is for

This package is primarily maintained for my own projects, but anyone is free to use it if the included rules fit their preferred C# style.

## License

This project is available under the MIT License. See `LICENSE` for details.
