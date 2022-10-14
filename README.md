<!-- https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/images/dd_logo_h_white.svg?raw=true" width="100%" height="100" alt="Datadog Logo">
  <img src=".github/images/dd_logo_h_rgb.svg?raw=true" width="100%" height="100" alt="Datadog Logo">
</picture>

# Datadog for IntelliJ IDEA

The [Datadog](https://www.datadoghq.com/) plugin helps improve software performance by providing
meaningful code-level insights in the IDE
based on real-time observability data. It helps reduce application latency and lower cloud costs by highlighting
specific code lines that consume the most CPU, allocate the most memory and spend the most time on locks, disk I/O,
socket I/O, and more.

> DISCLAIMER
> 
> This is a **Public Beta** version of the Datadog plugin, intended for Datadog customers that use the [Continuous Profiler](https://docs.datadoghq.com/profiler/#pagetitle) for their Java Services.

### Features

- Top List to identify the methods that consume the most resources
- Flame Graph visualizes the aggregated profile data
- Find resource consumption broken down by method name and line number
- Insights available from various staging and production environments


[Documentation](https://docs.datadoghq.com/developers/ide_integrations/idea/) | [Marketplace](https://plugins.jetbrains.com/plugin/19495-datadog)
