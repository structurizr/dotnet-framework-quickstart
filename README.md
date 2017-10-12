# Structurizr for .NET Framework quickstart

This is a simple starting point for using [Structurizr for .NET](https://github.com/structurizr/dotnet). To use it:

## 1. Clone the repo

```
git clone https://github.com/structurizr/dotnet-framework-quickstart.git
```

## 2. Set your workspace ID, API key and secret

Modify the constants at the top of [structurizr/Program.cs](https://github.com/structurizr/dotnet-framework-quickstart/blob/master/structurizr/Program.cs) to reflect your own Structurizr workspace (this information is available on your dashboard, after signing in).

```c#
private const long WorkspaceId = 1234;
private const string ApiKey = "key";
private const string ApiSecret = "secret";
```

## 3. Run the program

Finally, run the program, using your IDE.

For more information, please see [Structurizr for .NET - Getting Started](https://github.com/structurizr/dotnet/blob/master/docs/getting-started.md).