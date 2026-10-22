Advanced Anti-Anti-Debug Plugin for x32dbg / x64dbg

Kernel Level
Anti-Debug
100% Free
Initiated 2025/07/09
Introduction
Initiated on July 9, 2025
A plugin built around the core capability of deeply hiding debugger traces, precisely fulfilling the critical requirement of evading detection in anti-anti-debugging scenarios.

Applicable scenarios: A dedicated plugin for debugger concealment and countering anti-debugging detection from packer protectors. By.Sound/ReTeam

Why plugin?
Satisfy my daily reverse engineering and debugging needs.
That’s why I decided to develop my own. just a casual toy project.
I've already met part of my needs, I'll slow down with the code..

• SYS not encrypted

• 100% free

• Full version will disable key verification

have fun. :)

Essential Technical
Leverages callback mechanisms offered by kernel tracing.
Dynamically seizes control during syscall execution.
Temporarily replaces hook function pointers on runtime stack.
R3-R0 Hooks, bypass PatchGuard & anti-debug mechanisms.
Supports latest VMProtect 3.x.x (x86/x64).
Works on VMware / Physical x86/x64.
Network access is solely for version updates, no malicious conduct included.
The plugin runs normally offline.

No promises. No explanations. No liabilities.

Good luck!

Supported Systems
Win10 1607~1909
Win10 2004+
Win11 21H2+ (≥22000)
Physical & Virtual Machines
Run as Administrator
Hook sensitive → VM/Win10 2004~22H2
Usage Instructions
Requires x96Dbg 2025_08_19 or later.
Place Void-Dbg.dp32 / dp64 into plugins folder.
Click "Anti" when debugging target.
When using this plugin, ensure other plugins of the same type are disabled.
Concurrent execution of multiple hooking‑based plugins may lead to hook‑chain conflicts and unexpected anomalies.
