# Introduction

Welcome travelers! So this package define some StyleCop rules i use for my projects.<br/>

This package uses the StyleCop.Analyzers NuGet package for code analyses and distributes the shared Roslyn analyzer configuration transitively.<br/>
See: https://www.nuget.org/packages/stylecop.analyzers/

The package distributes the following shared analyzer assets:
* stylecop.json
* hantsch.stylecop.ruleset
* config/Hantsch.CSharp.StyleCop.globalconfig

## Updating the NuGet API key

If the publish workflow fails with a `403` from nuget.org, update the GitHub Actions secret `NUGETORGAPIKEY` in this repository:

1. Open `https://github.com/Hantsch/Hantsch.CSharp.StyleCop`.
2. Go to `Settings` -> `Secrets and variables` -> `Actions`.
3. Update the repository secret named `NUGETORGAPIKEY` with the current nuget.org API key.
