---
title: Device logs
---

Run `mos console` to attach to the device's UART and see device logs.
Reboot a device if you don't see any logs. Note that other mos
commands will not work when `mos console` is active, because they all
use the UART.
