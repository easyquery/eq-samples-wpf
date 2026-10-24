# Query builder (.NET) — EasyQuery on WPF

**Query builder.** A desktop query builder: users pick the columns and conditions in the EasyQuery controls, and the app builds the query and shows the result.

Part of [EasyQuery samples for WPF](../README.md).

## Tech stack

| | |
|---|---|
| Host | .NET 6 |
| UI | WPF |
| Language | C# |
| EasyQuery | 7.5.0 — `Korzh.EasyQuery.Db`, `Korzh.EasyQuery.Wpf`, `Korzh.EasyQuery.SqlServerGate`, `Korzh.EasyQuery.DataExport`, `Korzh.EasyQuery.EntityFrameworkCore.Relational` |
| EasyData | 1.6.0 — `EasyData.Exporters.ClosedXML` |
| Database | SQL Server Express LocalDB |

## Prerequisites

* [.NET 6 SDK](https://dotnet.microsoft.com/download)
* Windows; Visual Studio 2022 17.2 or later is recommended
* SQL Server Express LocalDB (installed with Visual Studio)

## Run it

### Visual Studio

1. Open `Samples.Wpf.sln` from the repository root.
2. Set `EqDemoWpfNet6` as the startup project.
3. Press F5.

### Command line

```bash
cd EqDemoWpfNet6
dotnet run
```

## License key

EasyQuery needs a license key. Get a free 30-day trial key on
[korzh.com](https://korzh.com/easyquery?utm_source=github&utm_medium=sample&utm_campaign=eq-samples-wpf&utm_content=EqDemoWpfNet6#get-started).

Set it in code, before the EasyQuery controls are created (see `EasyQueryPage`):

```csharp
Korzh.EasyQuery.Wpf.License.Key = "your trial key goes here";
```

## Sample database

The demo database is created and filled automatically on the first start (about a minute or
two). It uses SQL Server Express LocalDB; the connection string is in the app's configuration file.

## Related samples

* [Query builder (.NET) — Windows Forms](https://github.com/easyquery/eq-samples-winforms/tree/main/EqDemoWinFormsNet6)
* [Query builder (.NET Framework) — Windows Forms](https://github.com/easyquery/eq-samples-winforms/tree/main/EqDemoWinFormsNet4)
* [Query builder (.NET Framework, Visual Basic) — Windows Forms](https://github.com/easyquery/eq-samples-winforms/tree/main/EqDemoWinFormsNet4VB)
* [Query builder (.NET Framework) — WPF](https://github.com/easyquery/eq-samples-wpf/tree/main/EqDemoWpfNet4)
