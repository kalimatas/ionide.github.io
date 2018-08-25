---
title: "Getting Started"
bg: purple
color: white
style: left
fa-icon: plug
---

# Requirements

* F# (Windows) - Easiest way to install latest versions of F# on Windows is using [VS Build Tools 2017](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=button+cta&utm_content=download+vs2017#build-tools-for-visual-studio-2017). If you use VS 2017, make sure that you've installed workload adding F# support.

* F# (Linux/MacOS) - F# on non-Windows platform is distributed as part of the `mono`. Installation guide and recent version of `mono` can be found on the [project webpage](https://www.mono-project.com/download/stable/) and on the F# Software Foundation ["Use on Linux" page](https://fsharp.org/use/linux/)

* .Net Core SDK - .Net Core is modern, cross platform implementation of .Net Framework. Ionide is requiring it for set of features such as project modifications or debugging. The core part of SDK is `dotnet` CLI tool that provides easy way to create, build and run F# projects. What's important - the `dotnet` tool can be used also to create applications targeting also Full Framewok (like `net461`). For detailed instructions on installing .Net Core visit [official step-by-step installation guide](https://www.microsoft.com/net/core)

* VSCode C# plugin (optional) - Ionide's debugging capabilities relies on the debugger provided by Omnisharp team. To get it install [C# extension from VSCode marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)

* MsBuild 2015 (Windows only, optional) - For old, verbose `.fsproj` files on Windows MsBuild 2015 (14.0) needs to be additionally installed. You can download it [here](https://www.microsoft.com/en-us/download/details.aspx?id=48159). However, we highly recommend using new, SDK-based project files.
