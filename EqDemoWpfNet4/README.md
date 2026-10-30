# Query builder (.NET Framework) — EasyQuery on WPF

**Query builder.** A desktop query builder: users pick the columns and conditions in the EasyQuery controls, and the app builds the query and shows the result.

Part of [EasyQuery samples for WPF](../README.md).

## Tech stack

| | |
|---|---|
| Host | .NET Framework 4.7.2 |
| UI | WPF |
| Language | C# |
| EasyQuery | 7.5.0 — `Korzh.EasyQuery.Db`, `Korzh.EasyQuery.Wpf`, `Korzh.EasyQuery.SqlServerGate`, `Korzh.EasyQuery.DataExport`, `Korzh.EasyQuery.EntityFramework6` |
| EasyData | 1.6.0 — `EasyData.Exporters.ClosedXML` |
| Database | SQL Server Express LocalDB |

## Prerequisites

* Windows with .NET Framework 4.7.2 (Developer Pack) and Visual Studio 2022 17.2 or later
* SQL Server Express LocalDB (installed with Visual Studio)

## Run it

### Visual Studio

1. Open `Samples.Wpf.sln` from the repository root.
2. Set `EqDemoWpfNet4` as the startup project.
3. Press F5.

## License key

You don't need one to try the samples. Without a key they show a short reminder that EasyQuery is in trial mode. A purchased license key removes it; set it in code, before the EasyQuery controls are created (see `EasyQueryPage`):

```csharp
Korzh.EasyQuery.Wpf.License.Key = "your key goes here";
```

Ready to buy? See the [licensing options on korzh.com](https://korzh.com/easyquery?utm_source=github&utm_medium=sample&utm_campaign=eq-samples-wpf&utm_content=EqDemoWpfNet4#wpf-edition).

## Sample database

The demo database is created and filled automatically on the first start (about a minute or
two). It uses SQL Server Express LocalDB; the connection string is in the app's configuration file.

## Related samples

* [Query builder (.NET) — Windows Forms](https://github.com/easyquery/eq-samples-winforms/tree/main/EqDemoWinFormsNet6)
* [Query builder (.NET Framework) — Windows Forms](https://github.com/easyquery/eq-samples-winforms/tree/main/EqDemoWinFormsNet4)
* [Query builder (.NET Framework, Visual Basic) — Windows Forms](https://github.com/easyquery/eq-samples-winforms/tree/main/EqDemoWinFormsNet4VB)
* [Query builder (.NET) — WPF](https://github.com/easyquery/eq-samples-wpf/tree/main/EqDemoWpfNet6)
