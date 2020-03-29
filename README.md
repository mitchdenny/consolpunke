# Consolpunke (for .NET Developers)

![build](https://github.com/consolpunke/consolpunke-dotnet/workflows/build/badge.svg)

Consolpunke is a text-based social platform for software developers. This
repository hosts the .NET implementation of Consolpunke. For more information
about Consolpunk read the [project homepage](https://consolpunke.io).

## Installation

Consolpunke for .NET developers is implemented as a .NET Core global tool
which can be downloaded from NuGet using the .NET Core command-line tooling.

```
dotnet tool install -g Consolpunke
consolpunke --version
```

For more information on installing the .NET Core command-line tooling visit
the [.NET homepage](https://dotnet.microsoft.com/).

If you would like to see if there is an alternative implementation of
Consolpunke for your favorite language/runtime check out the
[project homepage](https://consolpunke.io) or perhaps start building your own
using the [specs repository](https://github.com/consolpunke/consolpunke-specs)
as a guide.

## Usage

Once installed, launching into Consolpunke is done using the following command:

```
consolpunke
```

Consolpunke will launch a private server on your local machine in the
background and connect to it. By default your avatar will be visible
in a room with a door. Follow the on-screen instructions to start
exploring the Consolpunke world.

## Contributing

Consolpunke is very early in its development cycle where ideas and concepts
are still being explored. If you want to get involved start by creating an
issue with your ideas and how you can contribute.

## License
[MIT](https://choosealicense.com/licenses/mit/)