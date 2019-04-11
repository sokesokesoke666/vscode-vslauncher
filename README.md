# Visual Studio Launcher - Open a projects and files in VS via context menu

[![Version](https://vsmarketplacebadge.apphb.com/version-short/spmeesseman.vscode-vslauncher.svg)](https://marketplace.visualstudio.com/items?itemName=spmeesseman.vscode-vslauncher)
[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/spmeesseman.vscode-vslauncher.svg)](https://marketplace.visualstudio.com/items?itemName=spmeesseman.vscode-vslauncher)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads-short/spmeesseman.vscode-vslauncher.svg)](https://marketplace.visualstudio.com/items?itemName=spmeesseman.vscode-vslauncher)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/spmeesseman.vscode-vslauncher.svg)](https://marketplace.visualstudio.com/items?itemName=spmeesseman.vscode-vslauncher)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![Build Status](https://dev.azure.com/spmeesseman/vscode-vslauncher/_apis/build/status/spmeesseman.vscode-vslauncher?branchName=master)](https://dev.azure.com/spmeesseman/vscode-vslauncher/_build/latest?definitionId=10&branchName=master)
[![codecov](https://codecov.io/gh/spmeesseman/vscode-vslauncher/branch/master/graph/badge.svg)](https://codecov.io/gh/spmeesseman/vscode-vslauncher)

[![Dependencies Status](https://david-dm.org/spmeesseman/vscode-vslauncher/status.svg)](https://david-dm.org/spmeesseman/vscode-vslauncher)
[![DevDependencies Status](https://david-dm.org/spmeesseman/vscode-vslauncher/dev-status.svg)](https://david-dm.org/spmeesseman/vscode-vslauncher?type=dev)
[![Known Vulnerabilities](https://snyk.io/test/github/spmeesseman/vscode-vslauncher/badge.svg)](https://snyk.io/test/github/spmeesseman/vscode-vslauncher)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/spmeesseman/vscode-vslauncher.svg)](https://isitmaintained.com/project/spmeesseman/vscode-vslauncher "Average time to resolve an issue")
[![Percentage of issues still open](https://isitmaintained.com/badge/open/spmeesseman/vscode-vslauncher.svg)](https://isitmaintained.com/project/spmeesseman/vscode-vslauncher "Percentage of issues still open") [![Greenkeeper badge](https://badges.greenkeeper.io/spmeesseman/vscode-vslauncher.svg)](https://greenkeeper.io/)

## Description

> Provides a command in the context menu of both the file explorer and file editor to open that file in Visual Studio.  If the file is a `project` or `solution` file (vcproj, vcproj, vbproj, sln), the Visual Studio `project` or `solution` will be opened as opposed to the file itself (unlike other similar extensions on the marketplace).

## Usage

The location of your Visual Studio installation and the IDE executable is attemtped to be found automatically.  In most cases, if you have only a single VS installation, and you installed to the default installation directory,this works fine.  If you have more than one version of VS installed, the file is opened with the first version located.  If you did not install to a default location, the installation directory will not be found.  In either case, you can explicity set the location of your VS IDE executable in Settings.

## Feedback & Contributing

* Please report any bugs, suggestions or documentation requests via the
  [Issues](https://github.com/spmeesseman/vscode-vslauncher/issues)
* Feel free to submit [pull requests](https://github.com/spmeesseman/vscode-vslauncher/pulls)
* [Contributors](https://github.com/spmeesseman/vscode-vslauncher/graphs/contributors)

## Settings

|Config|Description|Default|
|-|-|-|
|`vslauncher.debug`|Turn on logging|`false`|
|`vslauncher.pathToVS`|The path to the Visual Studio program (devenv.exe)||
