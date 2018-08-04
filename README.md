# Project Templates for LiterateCS Tool

This repository contains currently a single project template for [LiterateCS] tool.
The template creates a new .NET Standard class library with additional files needed by
LiterateCS. To install the template type in the command line.

    dotnet new -i LiterateCS.Templates.LiterateLib.CSharp

After that you can create a new literate class library with:

    dotnet new literatelib

## Options

There are two options in the template:

* `-f|--footer`

  The footer text used in the documentation pages.

* `-g|--github`

  The address of the GitHub repository for the project.

Both options can be changed easily later on by editing the `defaults.yml` file.

## Uninstalling

To uninstall the template enter on the command line:

    dotnet new -u LiterateCS.Templates.LiterateLib.CSharp

For more information see the [LiterateCS] repository.

[LiterateCS]: https://github.com/johtela/LiterateCS