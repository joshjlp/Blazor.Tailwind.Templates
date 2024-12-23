# Blazor.Tailwind.Templates

[![Nuget version](https://img.shields.io/nuget/v/Blazor.Tailwind.Templates?color=ff4081&label=nuget%20version&logo=nuget&style=flat-square)](https://www.nuget.org/packages/Blazor.Tailwind.Templates/)
[![Nuget downloads](https://img.shields.io/nuget/dt/Blazor.Tailwind.Templates?color=ff4081&label=nuget%20downloads&logo=nuget&style=flat-square)](https://www.nuget.org/packages/Blazor.Tailwind.Templates/)

## Getting Started

### Installation

```sh
dotnet new install Blazor.Tailwind.Templates
```

### Usage

You can specify different hosts using the `--host` option. The available hosts are `none`, `server`, `auto`, and `wasm`.

#### Host: none

```sh
dotnet new blazortailwind --host none -o MyApplication
```

#### Host: server

```sh
dotnet new blazortailwind --host server -o MyApplication
```

#### Host: auto

```sh
dotnet new blazortailwind --host auto -o MyApplication
```

#### Host: wasm

```sh
dotnet new blazortailwind --host wasm -o MyApplication
```

### Usage with Framework

To specify the framework, use the `--framework` option. You can use `net8.0`, `net9.0`, or both `net8.0;net9.0` (*Note that this is only applicable if the host is `wasm` for now*).

```sh
dotnet new blazortailwind --host wasm --framework net8.0 -o MyApplication
```

```sh
dotnet new blazortailwind --host wasm --framework net9.0 -o MyApplication
```

```sh
dotnet new blazortailwind --host wasm --framework "net8.0;net9.0" -o MyApplication
```

### Sample Site

You can view a sample site created with these templates [here](https://joshjlp.github.io/Blazor.Tailwind.Templates/).
