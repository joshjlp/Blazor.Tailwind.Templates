# Blazor.Tailwind.Templates
[![Nuget version](https://img.shields.io/nuget/v/Blazor.Tailwind.Templates?color=ff4081&label=nuget%20version&logo=nuget&style=flat-square)](https://www.nuget.org/packages/Blazor.Tailwind.Templates/)
[![Nuget downloads](https://img.shields.io/nuget/dt/Blazor.Tailwind.Templates?color=ff4081&label=nuget%20downloads&logo=nuget&style=flat-square)](https://www.nuget.org/packages/Blazor.Tailwind.Templates/)
## Getting Started
### Installation
```
dotnet new install Blazor.Tailwind.Templates
```
### Usage
```
dotnet new blazortailwind --host webapp-wasm -o MyApplication
```
### Usage with Framework
To specify the framework, use the `--framework` option. You can use `.net8.0`, `net9.0`, or both `.net8.0;.net9.0`.

```
dotnet new blazortailwind --host webapp-wasm --framework net8.0 -o MyApplication
```

```
dotnet new blazortailwind --host webapp-wasm --framework net9.0 -o MyApplication
```

```
dotnet new blazortailwind --host webapp-wasm --framework "net8.0;net9.0" -o MyApplication
```
