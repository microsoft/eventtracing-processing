# Issues-Only Repository

This repository is currently an issues-only repository for the `Microsoft.Windows.EventTracing.*`
NuGet packages.

These packages currently include the following groups on nuget.org:

- **1.x (stable):** the `Microsoft.Windows.EventTracing.Processing.*` packages and the related
  per-domain packages (for example, `Microsoft.Windows.EventTracing.Processing.All`,
  `Microsoft.Windows.EventTracing.Processing`, `Microsoft.Windows.EventTracing.Cpu`).
- **2.x (preview):** the newer `Microsoft.Windows.EventTracing` and
  `Microsoft.Windows.EventTracing.Core` packages, currently published as prerelease only.
- **MCP tool (preview):** the `Microsoft.Windows.EventTracing.MCP` packages (including the
  `win-x64` and `win-arm64` runtime variants) — a .NET tool that provides a Model Context
  Protocol (MCP) server for analyzing Windows Event Tracing (`.etl`) performance data.

For more information on these packages, see the [trace processing documentation](https://aka.ms/traceprocessing).

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
