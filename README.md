# Welcome to Campr Amps
Here you'll find the primary repositorie I'm working on, monthly iteration plans with key changes I plan to make, 
and issues containing discussions around new features and changes to this app. 

:zap: **Campr Amps** is a mobile app to calculate self-sufficient outdoor time for campers and to get insights in power usage. 
Based on the available battery (Ah), an optional converter or solar panels.

## Build Status:
| Build Server | Type | Platform | Target | Status |
|--|--|--|--|--|
| App Center | Build | MacOS | Andriod | [![Build status](https://build.appcenter.ms/v0.1/apps/edba7a7c-fdaf-4762-a420-f8983f88921f/branches/master/badge)](https://appcenter.ms) |
| App Center | Build | MacOS | iOS  | n/a |

## NuGet Packages:
| Package | Build Server| Type | Release |
|--|--|--|--|
| Campr.Forms | DevOps | Build | [![Campr.Forms Package](https://feeds.dev.azure.com/XlpinaDev/98af739c-52c4-42b2-8293-178c575c8c80/_apis/public/Packaging/Feeds/6d95a25d-d3a3-41de-9034-351b19e1d03a/Packages/01ba22b8-fc38-42d6-84b3-c589a3cfae34/Badge)](https://dev.azure.com/XlpinaDev/Campr.Artifacts/_packaging?_a=package&feed=6d95a25d-d3a3-41de-9034-351b19e1d03a&package=01ba22b8-fc38-42d6-84b3-c589a3cfae34&preferRelease=true) |
| Campr.Shared | DevOps | Build | [![Campr.Shared Package](https://feeds.dev.azure.com/XlpinaDev/98af739c-52c4-42b2-8293-178c575c8c80/_apis/public/Packaging/Feeds/6d95a25d-d3a3-41de-9034-351b19e1d03a/Packages/21d07268-c74d-4040-9e9e-45a9b2888373/Badge)](https://dev.azure.com/XlpinaDev/Campr.Artifacts/_packaging?_a=package&feed=6d95a25d-d3a3-41de-9034-351b19e1d03a&package=21d07268-c74d-4040-9e9e-45a9b2888373&preferRelease=true) | 
| Campr.Platform | DevOps | Buid | [![Campr.Platform Package](https://feeds.dev.azure.com/XlpinaDev/98af739c-52c4-42b2-8293-178c575c8c80/_apis/public/Packaging/Feeds/6d95a25d-d3a3-41de-9034-351b19e1d03a/Packages/344777fc-7e97-4c04-bfb1-e6bafaefdd54/Badge)](https://dev.azure.com/XlpinaDev/Campr.Artifacts/_packaging?_a=package&feed=6d95a25d-d3a3-41de-9034-351b19e1d03a&package=344777fc-7e97-4c04-bfb1-e6bafaefdd54&preferRelease=true) | 

## Release notes
See [changelog](./CHANGELOG) for release notes for all versions.

## Tools and technologies
* Visual Studio Community Edition 2019
* App Center (CI, Build, Test, Distribute)
* Azure DevOps (CI, Build Pipelines, Source Control)
* GitHub (Project Management)

## Design guidelines
- Following Microsoft [Framework Design Guidelines](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/)  

## Color guidelines
- Using Android [material color scheme](https://material.io/resources/color/#!/?view.left=0&view.right=0&primary.color=344955&secondary.color=F9AA33)

## Basic coding guidelines:
- No leading "this."
- Single type per file
- Member variables are camelCased with _prefix
- Local variables are camelCased with no prefix 
- Types, properties, methods, events are PascalCased
- Use new C# features (e.g nameof) where possible, but keep the code readable (e.g. don't var everything)

## Third-Party Resources
- [Material Design Icons v3.8.95](https://cdn.materialdesignicons.com/3.8.95/)

## Made Possible By
* [MVVM Helpers, James Montemagno](https://github.com/jamesmontemagno/mvvm-helpers)
* [Android Asset Studio, Roman Nurik](https://romannurik.github.io/AndroidAssetStudio/index.html)

## License & Copyright
Copyright (c) 2020, Xlpina Mobile Apps by Martin Swinkels  
See [license](./LICENSE) file.
