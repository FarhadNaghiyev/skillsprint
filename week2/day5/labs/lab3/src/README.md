# Shell Scripting Ops Toolkit - Lab Submission

## Overview
In this lab, I built a comprehensive toolkit for system administration and operations using Shell Scripting. The toolkit automates critical day-to-day tasks.

## Tools Created
1. **fm_tool.sh**: Automates file management by finding, archiving, rotating, and cleaning up old log files.
2. **proc_watch.sh**: Monitors specific background processes (like CPU and Memory usage) with built-in action triggers.
3. **backup.sh**: Creates reliable, timestamped backups of designated directories while enforcing retention policies to save disk space.
4. **log_parse.sh**: Parses system logs (`syslog`) to extract top programs and error timestamps using powerful text processing tools like `awk` and `sort`.

## Challenges & Observations
- **Regex Compatibility**: I encountered an issue where the default `awk` utility did not recognize the `\b` (word boundary) regex flag during process monitoring. I resolved this by adjusting the search pattern to ensure the script accurately captured the target processes.

