<!-- https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/images/dd_logo_h_white.svg?raw=true" width="100%" height="100" alt="Datadog Logo">
  <img src=".github/images/dd_logo_h_rgb.svg?raw=true" width="100%" height="100" alt="Datadog Logo">
</picture>

# Datadog for the IntelliJ Platform

The [Datadog](https://plugins.jetbrains.com/plugin/19495-datadog) plugin helps improve software performance by providing
meaningful code-level insights in the IDE
based on real-time observability data. It helps reduce application latency and lower cloud costs by highlighting
specific code lines that consume the most CPU, allocate the most memory and spend the most time on locks, disk I/O,
socket I/O, and more.

> DISCLAIMER  
> This is a **Public Beta** version of the Datadog plugin intended for developers that use Datadog products such as
> the [Log Explorer](https://docs.datadoghq.com/logs/explorer/) and
> the [Continuous Profiler](https://docs.datadoghq.com/profiler/#pagetitle) for their Java or Go Services.

### Plugin Features

The **Code Insights** view keeps you informed about:

- Issues from [Error Tracking](https://docs.datadoghq.com/tracing/error_tracking/)
- [Vulnerability](https://docs.datadoghq.com/security/application_security/vulnerability_management/) reports by Application Security Management
- [Flaky tests](https://docs.datadoghq.com/continuous_integration/guides/flaky_test_management/) detected by CI Visibility
- Profiling insights from [Watchdog Insights](https://docs.datadoghq.com/watchdog/insights/)

The **Continuous Profiler** helps you to reduce latency and lower cloud costs by highlighting code lines that:

- Consume the most CPU
- Allocate the most memory
- Spend the most time on locks, disk I/O, and socket I/O

The **Logs Navigation** support opens the Datadog Log Explorer with a view matching the context in which you are
working.

### Help and Feedback
Checkout the [documentation](https://docs.datadoghq.com/developers/ide_integrations/idea/) to see more information about the
Datadog plugin. For any feedback reach out to us via the [issue tracker](https://github.com/DataDog/datadog-for-intellij-platform/issues) or send an email to team-ide-integration@datadoghq.com
