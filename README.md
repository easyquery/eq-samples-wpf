# EasyQuery samples for WPF

[![NuGet](https://img.shields.io/nuget/v/Korzh.EasyQuery.Wpf)](https://www.nuget.org/packages/Korzh.EasyQuery.Wpf) [![Build](https://github.com/easyquery/eq-samples-wpf/actions/workflows/build.yml/badge.svg)](https://github.com/easyquery/eq-samples-wpf/actions/workflows/build.yml) [![License: MIT](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

[EasyQuery](https://korzh.com/easyquery) adds a query builder, ad-hoc reporting and data filtering
to .NET applications. The samples in this repository show it on WPF.

## Samples

| Sample | Scenario | Stack |
|---|---|---|
| [Query builder (.NET)](EqDemoWpfNet6) | Query builder | .NET 6 · WPF · C# |
| [Query builder (.NET Framework)](EqDemoWpfNet4) | Query builder | .NET Framework 4.7.2 · WPF · C# |

* **Query builder.** A desktop query builder: users pick the columns and conditions in the EasyQuery controls, and the app builds the query and shows the result.

## Quick start

1. Get the code: [download the ZIP](https://github.com/easyquery/eq-samples-wpf/archive/refs/heads/main.zip),
   or `git clone https://github.com/easyquery/eq-samples-wpf.git`.
2. Open `Samples.Wpf.sln` in Visual Studio 2022 (17.2 or later).
3. Set the sample you want as the startup project and run it.

Every sample creates and fills its own demo database on the first start. That can take a minute
or two; later starts take a few seconds.

## Package versions

All NuGet package versions of this repository, EasyQuery and EasyData included, are set in one
file: [`Directory.Packages.props`](Directory.Packages.props) (NuGet central package
management, which needs Visual Studio 2022 17.2+ or the .NET 6.0.300+ SDK). To try another
EasyQuery version, change it there.

## License key

You don't need one to try the samples. Without a key they show a short reminder that EasyQuery is in trial mode. A purchased license key removes it; set it in code, before the EasyQuery controls are created (see `EasyQueryPage`):

```csharp
Korzh.EasyQuery.Wpf.License.Key = "your key goes here";
```

Ready to buy? See the [licensing options on korzh.com](https://korzh.com/easyquery?utm_source=github&utm_medium=sample&utm_campaign=eq-samples-wpf#wpf-edition).

## Other platforms

* [ASP.NET Core Razor Pages and MVC](https://github.com/easyquery/eq-samples-aspnetcore-razor-mvc) — 6 samples
* [ASP.NET Core + Angular](https://github.com/easyquery/eq-samples-aspnetcore-angular) — 2 samples
* [ASP.NET Core + Blazor](https://github.com/easyquery/eq-samples-aspnetcore-blazor) — 2 samples
* [ASP.NET Core + React](https://github.com/easyquery/eq-samples-aspnetcore-react) — 1 sample
* [ASP.NET Core + Vue](https://github.com/easyquery/eq-samples-aspnetcore-vue) — 2 samples
* [ASP.NET Core + Stencil](https://github.com/easyquery/eq-samples-aspnetcore-stencil) — 1 sample
* [ASP.NET MVC 5 (.NET Framework)](https://github.com/easyquery/eq-samples-aspnet4-mvc) — 5 samples
* [ASP.NET Web Forms (.NET Framework)](https://github.com/easyquery/eq-samples-aspnet4-webforms) — 2 samples
* [Windows Forms](https://github.com/easyquery/eq-samples-winforms) — 3 samples

## Links

* [EasyQuery home page](https://korzh.com/easyquery)
* [Documentation](https://korzh.com/easyquery/docs)
* [Live demo](https://korzh.com/demo)
* [All EasyQuery samples](https://github.com/easyquery/DotNetSamples)
