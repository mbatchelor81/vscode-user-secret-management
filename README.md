# Fork Notice
This repository is an unmodified fork of [nanny07/vscode-user-secret-management](https://github.com/nanny07/vscode-user-secret-management).
<br><br>All authorship, copyright, and ownership remain with the original authors.
<br><br>Modifications are limited to packaging and publication on the OpenVSX Marketplace.

# User Secrets Management

View and manages user secretes for .NET Core/.NET5+ projects just like in Visual Studio.

## Features

Right click on your `.csproj`, `.fsproj` or `.vbproj` file and select `Manage User Secrets`.

It will open or create the `secret.json` file and update your project file if necessary.

![example](images/example.jpg)

## Requirements

This extension has the following dependencies:

* `uuid`: to generate a new GUID.

## Future improvement

In the future, this extension will directly use the `dotnet user-secrets init` command to generate the new GUID and update the project file. For now, it's not possible to wait until the end of a terminal run using Terminal.API on vscode ([see the issue on vscode's repository](https://github.com/microsoft/vscode/issues/145234))

## Release Notes

### 1.0.0

Initial release

---
