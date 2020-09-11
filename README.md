# Welcome to Campr Amps
Here you'll find the primary repositorie I'm working on, monthly iteration plans with key changes I plan to make, 
and issues containing discussions around new features and changes to this app. 

<img src="./images/google_pixel_3a_xl_3x.png" alt="drawing" width="256"/>

:zap: **Campr Amps** is a mobile app to calculate self-sufficient outdoor time for camper users and to get insights in power usage, based on available battery (Ah), an optional converter and solar panels. Source code is managed privately in Microsoft DevOps. Project is publicly managed in this repository. 

Available on App Store and Google Play when released.

## Project:
- Have an issue or suggestion? [Let me know!](https://github.com/Sw1ma/campr-amps/issues/new/choose)  
- Do you want to contribute as [beta tester](https://github.com/Sw1ma/campr-amps/blob/master/.github/CONTRIBUTING.md)?
- I encourage you to read [this wiki](https://github.com/Sw1ma/campr-amps/wiki) to get more insights.
- Get project [progress](https://github.com/Sw1ma/campr-amps/projects/1) insights.

## Build Status:
| Build Server | Type | Platform | Target | Status |
|--|--|--|--|--|
| App Center | Build, Launch | MacOS | Andriod | [![Build status](https://build.appcenter.ms/v0.1/apps/7b6c6208-b4fe-4556-a34f-cf3be94fd4f2/branches/master/badge)](https://appcenter.ms) |
| App Center | Build, Launch | MacOS | iOS  | [![Build status](https://build.appcenter.ms/v0.1/apps/852f753a-ee3c-4b81-b49f-aa86812d6b19/branches/master/badge)](https://appcenter.ms) |


## NuGet Packages:
| Package | Build Server| Type | Release |
|--|--|--|--|
| Campr.Forms | DevOps | Build | [![Campr.Forms Package](https://feeds.dev.azure.com/XlpinaDevOps/98af739c-52c4-42b2-8293-178c575c8c80/_apis/public/Packaging/Feeds/6d95a25d-d3a3-41de-9034-351b19e1d03a/Packages/01ba22b8-fc38-42d6-84b3-c589a3cfae34/Badge)](https://dev.azure.com/XlpinaDevOps/Campr.Artifacts) |
| Campr.Core | DevOps | Build |[![Campr.Core Package](https://feeds.dev.azure.com/XlpinaDevOps/98af739c-52c4-42b2-8293-178c575c8c80/_apis/public/Packaging/Feeds/6d95a25d-d3a3-41de-9034-351b19e1d03a/Packages/06b61ad0-bc67-4e6a-86fe-0de87b451dc6/Badge)](https://dev.azure.com/XlpinaDevOps/Campr.Artifacts/_packaging?_a=package&feed=6d95a25d-d3a3-41de-9034-351b19e1d03a&package=06b61ad0-bc67-4e6a-86fe-0de87b451dc6&preferRelease=true) | 
| Campr.Platform | DevOps | Buid | [![Campr.Platform Package](https://feeds.dev.azure.com/XlpinaDevOps/98af739c-52c4-42b2-8293-178c575c8c80/_apis/public/Packaging/Feeds/6d95a25d-d3a3-41de-9034-351b19e1d03a/Packages/344777fc-7e97-4c04-bfb1-e6bafaefdd54/Badge)](https://dev.azure.com/XlpinaDevOps/Campr.Artifacts) | 

## Release notes
See [changelog](./CHANGELOG.md) for overall release notes.

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
- [Xamarin.Essentials](https://docs.microsoft.com/xamarin/essentials)
- [Xamarin.Forms](https://xamarin.com/forms)
- [Xamarin.Forms.Visual.Material](https://docs.microsoft.com/xamarin/xamarin-forms/user-interface/visual/)
- [MVVM Helpers, James Montemagno](https://github.com/jamesmontemagno/mvvm-helpers)
- [Android Asset Studio, Roman Nurik](https://romannurik.github.io/AndroidAssetStudio/index.html)

## License & Copyright
Copyright (c) 2020, Xlpina Mobile Apps by Martin Swinkels  
See [license](./LICENSE) file.

<sub>Apple, iPhone, and iPad are trademarks of Apple Inc., registered in the U.S. and other countries and regions. App Store is a service mark of Apple Inc.</sub>  
<sub>Google Play and the Google Play logo are trademarks of Google LLC.</sub>
