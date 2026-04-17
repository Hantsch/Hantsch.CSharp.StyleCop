# Introduction

Welcome travelers! So this package define some StyleCop rules i use for my projects.<br/>

This repository contains the little bundle of C# style choices that keeps my projects in line and my eyeballs reasonably calm.<br/>

This package uses the StyleCop.Analyzers NuGet package for code analyses and distributes the shared Roslyn analyzer configuration transitively.<br/>
See: https://www.nuget.org/packages/stylecop.analyzers/

The package distributes the following shared analyzer assets:
* stylecop.json
* hantsch.stylecop.ruleset
* config/Hantsch.CSharp.StyleCop.globalconfig
* buildTransitive/hantsch.csharp.stylecop.props

Mostly i use this for myself, but if these rules spark joy for your C# projects too, feel free to use it.

## License

Everyone can use it under the MIT License. The license file is here: [`LICENSE`](LICENSE)

## Updating the NuGet API key

If the publish workflow fails with a `403` from nuget.org, create or rotate the nuget.org API key first, then update the GitHub Actions secret `NUGETORGAPIKEY` in this repository:

1. Sign in to `https://www.nuget.org/`.
2. Open your account menu and go to `API Keys` (`https://www.nuget.org/account/apikeys`).
3. Create a new API key for package push, copy it when shown, and keep it secure because nuget.org only shows it once.
4. Open this repository on GitHub.
5. Go to `Settings` -> `Secrets and variables` -> `Actions`.
6. Update the repository secret named `NUGETORGAPIKEY` with the current nuget.org API key.
