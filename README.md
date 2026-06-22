<!-- https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to -->
[![Version](https://img.shields.io/jetbrains/plugin/v/19495)](https://plugins.jetbrains.com/plugin/19495-datadog) [![Downloads](https://img.shields.io/jetbrains/plugin/d/19495)](https://plugins.jetbrains.com/plugin/19495-datadog) [![Rating](https://img.shields.io/jetbrains/plugin/r/rating/19495)](https://plugins.jetbrains.com/plugin/19495-datadog)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/images/dd_logo_h_white.svg?raw=true" width="100%" height="100" alt="Datadog Logo">
  <img src=".github/images/dd_logo_h_rgb.svg?raw=true" width="100%" height="100" alt="Datadog Logo">
</picture>

# Datadog for JetBrains IDEs

The [Datadog](https://www.datadoghq.com/) plugin helps developers debug problems faster by providing runtime context based on real-time observability data from Datadog.

### Plugin Features

Write secure code with **[Code Security](https://docs.datadoghq.com/ide_plugins/idea/code_security/)**:

* Library and runtime code vulnerabilities are reported inline in your source files and summarized in the Code Insights tab.
* Code quality and security rules are detected by Datadog's static analysis engine, running locally, and reported to you immediately.

> The following features are in limited support.

**[Error Tracking](https://docs.datadoghq.com/ide_plugins/idea/error_tracking/)** helps you find and fix runtime errors from production without leaving your IDE.

See event counts from **[Logs](https://docs.datadoghq.com/ide_plugins/idea/logs/)** directly in your source code editor and easily navigate to the [Log Explorer](https://docs.datadoghq.com/logs/explorer/) for further analysis.

### Help and Feedback
Checkout the [documentation](https://docs.datadoghq.com/ide_plugins/idea/) to see more information about the
Datadog plugin. For any feedback reach out to us via the [issue tracker](https://github.com/DataDog/datadog-for-intellij-platform/issues) or send an email to team-ide-integration@datadoghq.com

### Data and Telemetry
Datadog collects information about your usage of this IDE, including how you interact with it, whether errors occurred while using it, and what caused those errors, in accordance with the [Datadog Privacy Policy](https://www.datadoghq.com/legal/privacy/) and [Datadog's EULA](https://www.datadoghq.com/legal/eula/).

If you don't wish to send this data to Datadog, you can opt out at any time in the settings: `Settings > Tools > Datadog > Data Sharing` and disable the `Send usage statistics` option.
